change directory to frontend to install packages
```shell
npm install
```
install hardhat and other dependancies.
```shell
npm install hardhat
npm install @nomicfoundation/hardhat-toolbox
npm install dotenv
```
setup your env file with api url and account key

Start the node and deploy
```shell
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
or
npx hardhat run scripts/deploy.js --network localhost 
```

Start the frontend 
```shell
npm start
```

this contract was deployed on Volta.
LOOM link for verification purpose: https://www.loom.com/share/0a2289e742ad4123962bc569a2bba349?sid=31117505-d730-4a2b-bb2e-797270043d51
