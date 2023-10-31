# Wonderland-Wanderers
## About the project
Wonderland Wanderers is my final project submission for the [Alchemy University](https://www.alchemy.com/university) Ethereum bootcamp. WW for short is a DynamicForge: Real-time NFT Crafting project where
users can build their prefered nft artwork from a preset amount of traits from the [mint site](https://wonderland-wanderers.vercel.app/mint).

My project features a live canvas for users to customize their NFT in real time. They can seamlessly mint it on three EVM-compatible test blockchains. Users receive detailed feedback during minting with robust error handling. Unique contract feature ensures no duplicate artwork on a chain, providing truly one-of-a-kind NFTs."

## Getting Started
1. Create a .env file in the root of the frontend folder and input your keys in this format without the ""

  ```javascript
  VITE_ALCHEMY_API_KEY="Your Alchemy API key"
  VITE_INFURA_API_KEY="Your Infura API key"
  VITE_NFTSTORAGE_API_KEY="Your NFT storage API key"
  VITE_PRIVATE_KEY="Your private Key"
  ```
You can get your keys from these sites:
* [Alchemy API key](https://www.alchemy.com/)
* [Infura API key](https://app.infura.io/register)
* [NFT storage API key](https://nft.storage/login/)
  
2. Install Packages
   ```bash
   npm install
   ```
3. Run the application
   ```bash
   npm run dev
   ```
Note: All commands should be executed in the root of the frontend folder.

And that's all; you are good to go.
