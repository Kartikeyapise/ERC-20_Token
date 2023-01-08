### create a dir, Initialise a project and then. install hardhat:

mkdir ERC-20_token
npm init
npm install --save-dev hardhat
npx hardhat

### Spin up a test hardhat network with nodes on localhost

### after this you can see all the network logs in the console

npx hardhat node

### Connect to this test network using any client/wallet like metamask using these credentials:

Network Name: Hardhat
Network URl: http://127.0.0.1:8545/
chain id: 31337
Currency Symbol: HardhatETH

### Deploy smart contracts using a script in hardhat:

npx hardhat node
npx hardhat run --network localhost scripts/deploy.js

### Run all test cases:

npx hardhat test
