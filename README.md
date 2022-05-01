# :desktop_computer: Quick Start
Install the dependencies
```
npm install
```
# :Docker:get permission
```
sudo chmod 666 /var/run/docker.sock
```
# :bring up the network by issuing the following command. 
cd /home/i45000/fyp-block/ouhk-FYP/app/first-network
```
./network.sh down
```
./network.sh up createChannel
# :the smart contract chaincode inside ’patient-asset-transfer’ and the wallet
```
./network.sh deployCC
```

# :Optioal: add another organization
```
cd addHosp3
./addHosp3.sh up
./addHosp3.sh deployCC
```

# : Angular CLI for runnig
```
npm install
ng serve -o
```
/home/i45000/fyp/blockchain-hyperledger-fabric-electronic-patient-records/app/server/node_modules


# ouhk-FYP
Role | Username | password
--- | --- | --- 
Admin | hosp1admin | hosp1lithium
Admin | hosp2admin | hosp2lithium
Patient | PID0 | PID0
Patient | PID1 | PID1
Patient | PID2 | PID2
Patient | PID3 | PID3
Patient | PID4 | PID4
Patient | PID5 | harryli1
Doctor | HOSP1-DOC0 | password
Doctor | HOSP2-DOC1 | password
Doctor | HOSP1-DOC2 | password
Doctor | HOSP2-DOC3 | password




# :scroll: Reference
https://hyperledger-fabric.readthedocs.io/en/release-2.2/
https://github.com/kshitijyelpale/blockchain-hyperledger-fabric-electronic-patient-records




