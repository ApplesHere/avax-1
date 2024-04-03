# avax-1

**Project: EVM Subnet Deployment and Integration Guide**

This guide will walk you through the process of deploying your EVM (Ethereum Virtual Machine) subnet using the Avalanche CLI, adding it to Metamask, connecting Remix to Metamask, deploying smart contracts, and testing your application.

### Step 1: Deploying EVM Subnet using Avalanche CLI

1. Install Avalanche CLI if you haven't already. You can find installation instructions [here](https://docs.avax.network/build/tools/avalanche-cli).
   
2. Use Avalanche CLI to deploy your EVM subnet. Follow the documentation or specific instructions provided by Avalanche to complete this step.

### Step 2: Adding Subnet to Metamask

1. Open Metamask and ensure you're logged in.
   
2. Click on the network selection button (typically labeled as "Main Ethereum Network" or the current network you're on).
   
3. Select "Custom RPC" and input the necessary details for your deployed EVM subnet (RPC URL, chain ID, etc.). Consult the documentation provided by Avalanche for these details.

### Step 3: Connecting Remix to Metamask

1. Open Remix IDE (https://remix.ethereum.org/) in your browser.
   
2. On the left sidebar, select the "Settings" tab.
   
3. Under the "Plugin" section, locate "Solidity" and enable "Metamask" as the provider.

### Step 4: Deploying Smart Contracts

1. Write or import your smart contracts into Remix IDE.
   
2. Compile your smart contracts using Remix's Solidity compiler.
   
3. Select the appropriate contract from the sidebar and deploy it using the "Deploy & Run Transactions" tab.
   
4. Ensure you're connected to the correct network (your deployed EVM subnet) via Metamask.

### Step 5: Testing Your Application

1. After deploying your contracts, you can interact with them using the Remix IDE.
   
2. Use the "Injected Web3" provider option in Remix to connect to Metamask.
   
3. Interact with your deployed contracts by calling their functions and testing various scenarios to ensure they function as expected.

### Additional Tips

- Remember to fund your accounts with the necessary tokens for gas fees and contract interactions on your deployed EVM subnet.
- Make sure to keep your private keys and sensitive information secure.
- Consult the official documentation of Avalanche, Metamask, and Remix for more detailed information and troubleshooting.

Congratulations! You've successfully deployed your EVM subnet, integrated it with Metamask, connected Remix IDE, deployed smart contracts, and tested your application. Feel free to customize and expand your project further as needed.
- - -
