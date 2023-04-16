# avaxLinkFeeds
Using Chainlink Price Feeds on Avalanche. If you'd like to read the verbose version, check [out the blog.] (link is TBD)

## Quickstart
1. Head over to [`remix`](https://remix.ethereum.org/)
2. Create a new file
3. Paste the code from `AvaxLinkFeeds.sol` into a new file in remix. 
4. Compile using `0.8.0` version of solidity or above. 
5. Setup your Metamask to work with Avalanche:
```
Network Name: Avalanche FUJI C-Chain  
New RPC URL: https://api.avax-test.network/ext/bc/C/rpc  
ChainID: 43113  
Symbol: AVAX  
Explorer: https://cchain.explorer.avax-test.network  
```
5. Deploy the contract with "Injected Web3" environment
6. Run "getLatestPrice" to retrieve price data
