# PancakeSwap GraphQL API

PancakeSwap exposes on-chain DeFi data through GraphQL subgraphs hosted on The Graph Protocol and NodeReal. The primary subgraph is the Exchange V3 subgraph, which indexes concentrated liquidity pool data on BNB Smart Chain and Ethereum mainnet. It provides queryable entities covering tokens, liquidity pools, tick ranges, positions, swaps, mints, burns, fee collections, and flash loans, as well as aggregated time-series data at hourly and daily granularity for pools, tokens, and the overall protocol.

Authentication is not required for public subgraph endpoints on The Graph's hosted service or via The Graph's decentralized network, though API keys are needed for high-volume production access through The Graph's gateway. The NodeReal MegaNode marketplace endpoint for PancakeSwap V2 data requires a NodeReal API key passed as a path segment or header. All endpoints accept HTTP POST requests with a JSON body containing a `query` field conforming to the GraphQL specification.

The canonical V3 subgraph on The Graph's decentralized network is identified by subgraph ID `78EUqzJmEVJsAKvWghn7qotf9LVGqcTQxJhT5z84ZmgJ` for BNB Smart Chain. The V2 BSC exchange subgraph is also available via NodeReal. The schema is maintained in the open-source `pancakeswap/pancake-subgraph` repository on GitHub under the `v3` branch.

**Endpoint:** https://gateway.thegraph.com/api/subgraphs/id/78EUqzJmEVJsAKvWghn7qotf9LVGqcTQxJhT5z84ZmgJ

**Documentation:** https://developer.pancakeswap.finance/apis/subgraph

**References:**
- Documentation: https://developer.pancakeswap.finance/apis/subgraph
- GettingStarted: https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph
