# PancakeSwap (pancakeswap)

PancakeSwap is the largest decentralized exchange (DEX) on BNB Chain, operating across ten blockchains including Ethereum, Arbitrum, Base, Solana, zkSync, Linea, Polygon zkEVM, opBNB, and Aptos. It provides REST and GraphQL APIs for accessing token prices, liquidity pool data, swap routing, farm yields, trading pair statistics, NFT market data, and prediction markets. Developers can query on-chain data via hosted subgraphs on The Graph Protocol and NodeReal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pancakeswap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pancakeswap/refs/heads/main/apis.yml)

## Tags

- DeFi
- DEX
- BNB Chain
- Decentralized Exchange
- Blockchain
- Swap
- Liquidity
- Yield Farming
- NFT
- Web3

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### PancakeSwap Info API v2

REST API providing on-chain data for the top ~1000 PancakeSwap trading pairs, tokens, and market summaries sourced from underlying subgraphs. Used by market aggregators such as CoinMarketCap to surface liquidity and volume data. Responses are cached for 5 minutes.

- **Human URL:** [https://github.com/pancakeswap/pancake-info-api](https://github.com/pancakeswap/pancake-info-api)
- **Base URL:** `https://api.pancakeswap.info`

#### Tags

- Tokens
- Pairs
- Liquidity
- Prices
- Volume

#### Properties

- [Documentation](https://github.com/pancakeswap/pancake-info-api/blob/develop/v2-documentation.md)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/pancakeswap/refs/heads/main/openapi/openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Graph Q L](graphql/pancakeswap-graphql.md)

### PancakeSwap Exchange V2 Subgraph (BSC)

GraphQL subgraph for querying PancakeSwap V2 exchange data on BNB Smart Chain, including swaps, liquidity pools, trading pairs, volume, and price history. Hosted on NodeReal MegaNode API Marketplace.

- **Human URL:** [https://nodereal.io/meganode/api-marketplace/pancakeswap-graphql](https://nodereal.io/meganode/api-marketplace/pancakeswap-graphql)
- **Base URL:** `https://nodereal.io/meganode/api-marketplace/pancakeswap-graphql`

#### Tags

- GraphQL
- Subgraph
- BNB Chain
- Exchange V2
- Liquidity Pools

#### Properties

- [Documentation](https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph)
- [X- Subgraph](https://nodereal.io/meganode/api-marketplace/pancakeswap-graphql)

### PancakeSwap Exchange V2 Subgraph (Ethereum)

GraphQL subgraph for querying PancakeSwap V2 exchange data on Ethereum mainnet, including swaps, liquidity pools, pairs, and historical volume data hosted on The Graph decentralized network.

- **Human URL:** [https://api.thegraph.com/subgraphs/name/pancakeswap/exhange-eth](https://api.thegraph.com/subgraphs/name/pancakeswap/exhange-eth)
- **Base URL:** `https://api.thegraph.com/subgraphs/name/pancakeswap/exhange-eth`

#### Tags

- GraphQL
- Subgraph
- Ethereum
- Exchange V2

#### Properties

- [Documentation](https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph)

### PancakeSwap Exchange V3 Subgraph (BSC)

GraphQL subgraph for querying PancakeSwap V3 concentrated liquidity exchange data on BNB Smart Chain, including positions, pools, ticks, swaps, and fee tiers. Hosted on The Graph and NodeReal.

- **Human URL:** [https://thegraph.com/explorer/subgraphs/78EUqzJmEVJsAKvWghn7qotf9LVGqcTQxJhT5z84ZmgJ](https://thegraph.com/explorer/subgraphs/78EUqzJmEVJsAKvWghn7qotf9LVGqcTQxJhT5z84ZmgJ)
- **Base URL:** `https://thegraph.com/explorer/subgraphs/78EUqzJmEVJsAKvWghn7qotf9LVGqcTQxJhT5z84ZmgJ`

#### Tags

- GraphQL
- Subgraph
- BNB Chain
- Exchange V3
- Concentrated Liquidity

#### Properties

- [Documentation](https://developer.pancakeswap.finance/apis/subgraph)

### PancakeSwap Exchange V3 Subgraph (Ethereum)

GraphQL subgraph for querying PancakeSwap V3 concentrated liquidity exchange data on Ethereum mainnet, including positions, pools, swaps, and historical volume data hosted on The Graph decentralized network.

- **Human URL:** [https://thegraph.com/explorer/subgraphs/9opY17WnEPD4REcC43yHycQthSeUMQE26wyoeMjZTLEx](https://thegraph.com/explorer/subgraphs/9opY17WnEPD4REcC43yHycQthSeUMQE26wyoeMjZTLEx)
- **Base URL:** `https://thegraph.com/explorer/subgraphs/9opY17WnEPD4REcC43yHycQthSeUMQE26wyoeMjZTLEx`

#### Tags

- GraphQL
- Subgraph
- Ethereum
- Exchange V3
- Concentrated Liquidity

#### Properties

- [Documentation](https://developer.pancakeswap.finance/apis/subgraph)

### PancakeSwap StableSwap Subgraph (BSC)

GraphQL subgraph for querying PancakeSwap StableSwap pools on BNB Smart Chain, providing stable coin pair liquidity, swap volumes, and pool statistics for low-slippage stablecoin trading pairs.

- **Human URL:** [https://api.thegraph.com/subgraphs/name/pancakeswap/exchange-stableswap](https://api.thegraph.com/subgraphs/name/pancakeswap/exchange-stableswap)
- **Base URL:** `https://api.thegraph.com/subgraphs/name/pancakeswap/exchange-stableswap`

#### Tags

- GraphQL
- Subgraph
- BNB Chain
- StableSwap
- Stablecoins

#### Properties

- [Documentation](https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph)

### PancakeSwap Profile API

REST API for PancakeSwap user profile data including usernames, leaderboard rankings by trading volume, team competitions, and profile registration. Supports CORS for cross-origin access.

- **Human URL:** [https://github.com/pancakeswap/pancake-profile-api](https://github.com/pancakeswap/pancake-profile-api)
- **Base URL:** `https://profile.pancakeswap.com/api`

#### Tags

- Profiles
- Leaderboard
- Users
- Trading Volume

#### Properties

- [Documentation](https://github.com/pancakeswap/pancake-profile-api/blob/develop/docs/README.md)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/pancakeswap/refs/heads/main/openapi/profile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### PancakeSwap NFT Market Subgraph

GraphQL subgraph for querying PancakeSwap NFT Market data on BNB Smart Chain, including NFT collections, listings, sales, bids, and trading history for the PancakeSwap NFT marketplace.

- **Human URL:** [https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph](https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph)
- **Base URL:** `https://api.thegraph.com/subgraphs/name/pancakeswap/nft-market`

#### Tags

- GraphQL
- Subgraph
- NFT
- BNB Chain
- Marketplace

#### Properties

- [Documentation](https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph)

### PancakeSwap MasterChef V3 Subgraph

GraphQL subgraph for querying PancakeSwap yield farming data via MasterChef V3 on BNB Smart Chain, including active farms, CAKE emission rates, staking positions, and farm APR data for V3 concentrated liquidity farms.

- **Human URL:** [https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph](https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph)
- **Base URL:** `https://api.thegraph.com/subgraphs/name/pancakeswap/masterchef-v3`

#### Tags

- GraphQL
- Subgraph
- Yield Farming
- CAKE
- MasterChef
- BNB Chain

#### Properties

- [Documentation](https://docs.pancakeswap.finance/chinese/gei-kai-fa-zhe-men/api/subgraph)

## Common Properties

- [Website](https://pancakeswap.finance)
- [Documentation](https://docs.pancakeswap.finance)
- [Developer Documentation](https://developer.pancakeswap.finance)
- [Github Organization](https://github.com/pancakeswap)
- [Blog](https://blog.pancakeswap.finance)
- [Twitter](https://twitter.com/PancakeSwap)
- [Telegram](https://t.me/PancakeSwap)
- [Discord](https://discord.gg/pancakeswap)
- [Reddit](https://reddit.com/r/pancakeswap)
- [Terms of Service](https://pancakeswap.finance/terms-of-service)
- [Privacy Policy](https://pancakeswap.finance/privacy-policy)
- [Status Page](https://status.pancakeswap.finance)
- [GitHub Repository](https://github.com/pancakeswap/pancake-frontend)
- [Plans](https://raw.githubusercontent.com/api-evangelist/pancakeswap/refs/heads/main/plans/plans.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/pancakeswap/refs/heads/main/rate-limits/rate-limits.yml)
- [Financial Operations](https://raw.githubusercontent.com/api-evangelist/pancakeswap/refs/heads/main/finops/finops.yml)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
