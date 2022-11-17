# BlockChain-Voting-System
Build my first decentralized application, or Dapp, on the Ethereum Network.

Follow the steps below to download, install, and run this project.
## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.<ul>

  <li>NPM: https://nodejs.org</li>
  <li>Truffle: https://github.com/trufflesuite/truffle</li>
  <li>Ganache: http://truffleframework.com/ganache/</li>
  <li>Metamask: https://metamask.io/</li></ul>

  
## Step 1. Clone Project
    git clone https://github.com/tiwariji-mukund/BlockChain-Voting-System 
## Step 2. Install dependencies
    $ cd election
    $ npm install
    
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. 

## Step 4. Compile & Deploy Election Smart Contract
    $ truffle migrate --reset 
  You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
Now, follow the following steps<ul>

  <li>Unlock Metamask.</li>
  
  <li>Connect metamask to your local Etherum blockchain provided by Ganache.</li>
  
  <li>Import an account provided by ganache.</li></ul>

## Step 6. Run the Front End Application

    $ npm run dev 
Visit this URL in your browser: http://localhost:3000
