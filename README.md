
# **Real Estate Smart Contract**

This project demonstrates how to create, deploy, and test a smart contract for real estate management using RemixIDE, interact with it via MetaMask, and integrate a web interface using web3.js for seamless blockchain interactions.

## Prerequisites
1. **MetaMask** 
Install the [MetaMask](https://metamask.io/) browser extension and create an account.

2. **Sepolia Test Network** 
* Switch your MetaMask network to Sepolia (test network).
* Add free test ETH to your wallet using [Sepolia Faucet](https://www.sepoliafaucet.io/).

3. **Node.js**
Install [Node.js](https://nodejs.org/fr) if not already installed (for the HTTP server).

## Steps to Deploy the Contract

1. **Open RemixIDE** 
* Visit [RemixIDE](https://remix.ethereum.org/) in your browser.

2. **Create and Compile the Smart Contract** 
* Create a new `.sol` file in RemixIDE.
* Copy the contract code from` RemixIDE Code Sol File.txt` into the file.

* Compile the contract using the **Solidity Compiler** tab.

3. **Deploy the Smart Contract** 
* Go to the **Deploy & Run Transactions** tab in RemixIDE.

* Select **Injected Provider - MetaMask** as the environment.

* Deploy the smart contract and confirm the transaction in MetaMask.

4. **Retrieve Contract Details** 
* Note the **contract address**, your **MetaMask account address**, and **ABI** from the RemixIDE deployment logs..

## Running the Application

1. **Install HTTP Server** 
Install a simple HTTP server globally using the command below:
```bash
npm install -g http-server
```

2. **Run the Server** 
Install a simple HTTP server globally using the command below:
```bash
http-server
```
3. **Connect to the Contract**
Use the retrieved **contract address**, **account address**, and **ABI** in the frontend code to interact with the smart contract.

## Notes
* **What is Sepolia?**
Sepolia is an Ethereum test network for testing smart contracts without using real ETH.

## Support 
If you encounter any issues, feel free to contact:
**Montasser Benouirane**

Email: montasser.benouirane@esprit.tn

## Application Overview and Visuals

<div align="center">
  <img src="https://github.com/user-attachments/assets/5e97f27b-4c37-41a5-b759-545327207df5" alt="App Screenshot 1" width="30%" />
  <img src="https://github.com/user-attachments/assets/4391d22d-b39e-4f55-8722-a42dec31bec4" alt="App Screenshot 2" width="30%" />
  <img src="https://github.com/user-attachments/assets/e84f0466-b625-4ecd-bc60-04dad5da908d" alt="App Screenshot 3" width="30%" />
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/a9b20304-088f-40c1-b712-7c4a992067d0" alt="App Screenshot 4" width="30%" />
  <img src="https://github.com/user-attachments/assets/afccf69c-a333-4cea-8328-b30280d898b3" alt="App Screenshot 5" width="30%" />
  <img src="https://github.com/user-attachments/assets/8ad28181-8ca8-42ae-8042-c5f0d4e895d3" alt="App Screenshot 6" width="30%" />
</div>




