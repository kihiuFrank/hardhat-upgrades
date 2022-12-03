# hardhat-upgrades
We will be working on protocols that allow users to nominate a contract / proxy address to act on behalf of another wallet address or another contract.

# Tasks
1. Upgrade Box -> BoxV2
2. Make a Proxy Contract that will point to Box, and then later update it to point to BoxV2.
    - Proxy -> Box
            -> BoxV2
# Steps
1. Deploy a Proxy 
    - manually 
    - or using Hardhat deploy's built-in proxies
    - using openzepplin's upgrade plugin

