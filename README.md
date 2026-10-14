# Awesome-Prediction-Market

## Top Prediction Market Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Event Contract Trading, Decentralized Forecasting & Real-Time Probability Pricing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Prediction Markets**. These platforms enable users to trade on the outcomes of future events — elections, economic indicators, sports, crypto prices, and more — using real money, play money, or reputation-based forecasting. Prices serve as real-time probability estimates that often outperform polls and expert panels.

**Examples** include Polymarket, Kalshi, PredictIt, Manifold Markets, Augur, Insight Prediction, Metaculus, Smarkets, Drift BET, and Hedgehog Markets (the category leaders).

**Open-source emphasis**: This section is expanded with every major active project for self-hosting, custom market creation, and transparent on-chain settlement — ideal for developers building prediction market platforms, researchers studying collective intelligence, and teams avoiding regulatory complexity.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Polymarket](https://polymarket.com/)**  
  The largest decentralized prediction market, running on Polygon with USDC. Zero trading fees with deep liquidity on political, crypto, sports, and cultural events. Blocks US users; global access with crypto wallet [citation:1][citation:5].

- **[Kalshi](https://kalshi.com/)**  
  The only CFTC-regulated prediction exchange in the US. Offers real-money event contracts on economics, politics, weather, and sports with fiat deposits (USD). Full US access with KYC [citation:1][citation:5].

- **[PredictIt](https://www.predictit.org/)**  
  Long-standing US political prediction market operating under a CFTC no-action letter. Real money (USD) with position limits and a political-only catalog [citation:1][citation:19].

- **[Manifold Markets](https://manifold.markets/)**  
  Play-money prediction market with virtual "Mana" currency. Free, open to all users globally, with user-created markets on virtually any topic. Popular for research, teaching, and risk-free practice [citation:1][citation:5].

- **[Augur](https://augur.net/)**  
  Fully decentralized, permissionless prediction market on Ethereum. No KYC, censorship-resistant market creation, on-chain resolution. Low liquidity and complex UX for non-crypto users [citation:1][citation:7].

- **[Insight Prediction](https://insightprediction.com/)**  
  Newer crypto-based prediction market focused on US political and economic markets. Competitive fees, real-money crypto trading, but significantly lower liquidity than Polymarket [citation:1].

- **[Metaculus](https://www.metaculus.com/)**  
  Reputation-based forecasting platform with no money involved. Long-range scientific, AI, and geopolitical questions scored by accuracy. Complementary research tool, not a trading venue [citation:1][citation:5].

- **[Smarkets](https://smarkets.com/)**  
  UK-licensed peer-to-peer betting exchange (back/lay model) covering politics and sports. Fiat currency (GBP), popular with UK/EU users wanting exchange-style odds [citation:1][citation:19].

- **[Drift BET](https://drift.trade/)**  
  Prediction module within the Drift Protocol DEX on Solana. Supports 30+ collateral types including yield-bearing assets [citation:5].

- **[Hedgehog Markets](https://hedgehog.markets/)**  
  Solana-native prediction market offering peer-to-peer markets, AMM pools, and parimutuel markets with pooled staking products [citation:5].

## Open-Source GitHub Projects

- **[SocialPredict](https://github.com/openpredictionmarkets/socialpredict)**  
  **Easy-to-deploy open-source prediction market platform** under MIT license. Go-based with 229 GitHub stars. Designed for quick self-hosting and community market creation [citation:2][citation:6].

- **[Kuest](https://github.com/kuestcom/prediction-market)**  
  **Full-stack Polymarket-inspired platform on Polygon** with shared liquidity, UMA oracle integration, and bot-ready SDKs. Next.js 16 frontend, Supabase backend, CLOB matching engine. MIT+Commons license. Includes market orders, limit orders, split/merge, portfolio tracking, and real-time activity feeds. Production status: approaching MVP readiness on Polygon Amoy testnet [citation:15].

- **[pyclob](https://pypi.org/project/pyclob/)**  
  **Pure-Python central limit order book (CLOB) matching engine for binary event contracts.** Implements price-time priority, price improvement, reserve escrow, and position accounting with weighted-average cost basis. Extracted from a live play-money World Cup prediction market. Ideal for simulation, backtesting, and education [citation:3].

- **[Prediction-Market-Solana (DecentraPredict)](https://github.com/solzarr/Prediction-Market-Solana)**  
  **Decentralized prediction market on Solana** with smart contracts (Anchor/Rust), Next.js frontend, Node.js backend, and Switchboard oracle integration. Features market creation, liquidity provision, betting, locking periods, and transparent payout distribution [citation:4].

- **[pancake-prediction-clone](https://github.com/codemenco/pancake-prediction-clone)**  
  **Multi-chain PancakeSwap-style UP/DOWN prediction market** for EVM networks. Configurable round lifecycle (default 5 minutes: Open → Lock → Close), Chainlink/Pyth oracle integration, auto round management, Next.js UI, and REST/WebSocket APIs. Supports BNB Chain, Ethereum, Polygon, Arbitrum, Optimism, Avalanche, and Base [citation:8].

- **[Zeitgeist](https://github.com/zeitgeistpm/zeitgeist)**  
  **Evolving blockchain for prediction markets and futarchy** on Polkadot/Substrate. Rust-based with GPL-3.0 license, 201 GitHub stars. Includes UI, SDK, and subsquid indexer for GraphQL data access [citation:2][citation:17].

- **[Prediction-Market-Web3](https://github.com/Sealva-Devs/Prediction-Market-Web3)**  
  **Production-ready crypto prediction market** with secure smart contracts, React frontend, peer-to-peer wagering, multi-sig escrow, automatic payouts, and comprehensive security measures. Solidity/Hardhat stack with wagmi/viem [citation:2].

- **[prediction-market (kuestcom fork)](https://github.com/openpredictionmarkets/prediction-market)**  
  **Launch your own Web3 decentralized prediction market in minutes** — Polymarket-like architecture with TypeScript frontend and smart contracts [citation:2].

- **[polymarket-clone](https://github.com/openpredictionmarkets/polymarket-clone)**  
  **Polygon prediction market clone** with Vue 3 and Solidity for on-chain USDT escrow, market trading, and automated settlement [citation:2].

- **[manifold (fork)](https://github.com/openpredictionmarkets/manifold)**  
  **Open-source fork of Manifold Markets** — a market for every question. TypeScript-based, MIT licensed [citation:2].

- **[PNPFUCIUS](https://www.npmjs.com/package/pnpfucius)**  
  **PNP Exchange CLI & SDK for Solana prediction markets.** Features full exchange integration, built-in LLM oracle for market resolution criteria, AMM and P2P market support, custom odds, market discovery, and trading tools. Interactive CLI with slash commands [citation:11].

- **[metaforecast](https://github.com/quantified-uncertainty/metaforecast)**  
  **Fetch forecasts from prediction markets and forecasting platforms** to make them searchable and integrate into other services. Aggregates across multiple platforms for research and analytics [citation:6][citation:12].

- **[hanson](https://github.com/ruuda/hanson)**  
  **Self-hosted prediction market app** implementing Robin Hanson's Logarithmic Market Scoring Rule (LMSR). Lightweight, open-source, suitable for private or community markets [citation:12][citation:14].

- **[prediction-market-agent-tooling](https://github.com/gnosis/prediction-market-agent-tooling)**  
  **Tools to benchmark, deploy, and monitor prediction market agents** from Gnosis. Supports Polymarket, Manifold, and Omen for building AI trading agents [citation:14][citation:18].

### Additional Strong Open-Source Options

- **[Gnosis pm-contracts](https://github.com/gnosis/pm-contracts)** — Smart contracts for the Gnosis prediction market platform. Solidity, 177 GitHub stars [citation:6][citation:12].
- **[Limitless Exchange](https://github.com/limitless-labs-group/Limitless-Exchange)** — Crypto-native, fast-resolving on-chain prediction market. TypeScript-based [citation:6][citation:14].
- **[PredictionMarket.sol (Arc Testnet)](https://github.com/Ivan-Dosev/CannesETH26)** — Contract deployed on Arc Testnet enabling 0.001 USDC minimum bets for AI agent micro-trading. Includes AI market generation via 0G Compute and on-chain provenance via 0G Storage [citation:10].
- **[Discord Prediction Market Bots](https://github.com/topics/prediction-market)** — Multiple community-built Discord bots for play-money prediction markets (io12, abcy73, ChassterTP, and others) [citation:14].

**Frameworks for building custom systems**: Combine **Kuest** for a full Polymarket-style platform with shared liquidity, **pyclob** for CLOB matching engine logic, **Prediction-Market-Solana** for Solana-based on-chain markets, **pancake-prediction-clone** for multi-chain UP/DOWN games, and **metaforecast** for aggregating data across venues to build a complete prediction market stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Prediction markets involve financial risk and are subject to complex and evolving regulations. **Legality varies significantly by jurisdiction** — real-money prediction markets are restricted or prohibited in many countries including the US (for crypto platforms like Polymarket) [citation:9]. Always verify local laws before participating. Play-money platforms like Manifold and Metaculus are legal virtually everywhere.
- Self-hosted open-source solutions require proper smart contract auditing, oracle reliability assessment, and legal counsel before deploying real-money markets.

---

**Made for prediction market enthusiasts, quantitative traders, forecasting researchers, and developers building decentralized market platforms.**  
Let's make prediction markets more open, accessible, and transparent.
