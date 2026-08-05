# Awesome Tokenized Equities

A curated list of tokenized equity protocols, infrastructure, and resources.

Stocks, ETFs, and real-world assets are moving onchain. This list tracks the infrastructure being built around them.

## Contents

- [Protocols](#protocols)
- [Infrastructure](#infrastructure)
- [Data and Oracles](#data-and-oracles)
- [Research](#research)
- [Regulatory](#regulatory)

---

## Protocols

### Issuance

- [Backed Finance](https://backed.fi) — ERC-20 wrappers for regulated securities. bCSPX, bNVDA, and others.
- [Ondo Finance](https://ondo.finance) — Tokenized US Treasuries and money market funds. USDY, OUSG.
- [Swarm Markets](https://swarm.markets) — Regulated DeFi. Tokenized stocks and ETFs on Polygon.
- [Securitize](https://securitize.io) — End-to-end tokenization platform. SEC-registered transfer agent.
- [Dinari](https://dinari.com) — Tokenized US stocks, 1:1 backed, KYC-gated.

### Trading

- [Noir Protocol](https://noirprotocol.xyz) — CLOB matching engine for tokenized equities. Book + pool hybrid: matches against resting limit orders, routes remainder through Uniswap v4 pools on Robinhood Chain.
- [dFlow](https://dflow.net) — Order flow infrastructure for onchain trading.

### Lending

- [Centrifuge](https://centrifuge.io) — Real-world asset lending. Invoice financing, structured credit.
- [Maple Finance](https://maple.finance) — Institutional lending secured by tokenized assets.

---

## Infrastructure

### Settlement

- [Noir Protocol Settlement](https://github.com/noirproto/settlement-contracts) — Non-custodial EVM settlement on Robinhood Chain. Sign-to-move, no custody.
- [Fireblocks](https://fireblocks.com) — Institutional custody and settlement rails.

### Matching

- [Noir Protocol Matching Engine](https://github.com/noirproto/matching-engine) — Open-source CLOB with Uniswap v4 pool routing. Price-time priority, off-chain matching, hybrid book + pool fills.

### AMM / Liquidity

- [Uniswap v4](https://github.com/Uniswap/v4-core) — Singleton-contract AMM with hooks. Provides pool liquidity layer for tokenized equity pairs.

### Chains

- [Robinhood Chain](https://robinhood.com) — EVM chain (chain ID 4663) purpose-built for financial applications. Settlement layer for Noir Protocol.

### Custody

- [Anchorage Digital](https://anchorage.com) — Federally chartered digital asset bank.
- [Copper](https://copper.co) — Institutional crypto custody.

---

## Data and Oracles

- [Chainlink](https://chain.link) — Price feeds for tokenized assets. NAV oracles for RWA.
- [Pyth Network](https://pyth.network) — Sub-second price feeds. Pull-model for low-latency apps.
- [Redstone](https://redstone.finance) — Modular oracle for RWA price data.
- [Chronicle](https://chroniclelabs.org) — MakerDAO-originated oracle network.

---

## Research

- [BIS: Tokenisation in the context of money and other assets](https://www.bis.org/publ/work1101.htm) — Central bank perspective on tokenization.
- [Moody's: DeFi and RWA](https://www.moodys.com) — Credit analysis of RWA protocols.
- [a16z crypto: The case for tokenized securities](https://a16zcrypto.com) — Investment thesis on onchain equities.
- [Market Microstructure Meets Crypto](https://ssrn.com) — Academic paper on CLOB vs AMM for real assets.

---

## Regulatory

- [SEC: Framework for Investment Contract Analysis of Digital Assets](https://www.sec.gov/corpfin/framework-investment-contract-analysis-digital-assets)
- [MiCA (EU)](https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica) — EU crypto-asset regulation including tokenized securities.
- [FINMA guidance on token classification](https://www.finma.ch) — Swiss approach to security tokens.

---

## Contributing

PRs welcome. Format: `[Name](url) — one-line description.` Keep it factual.

## License

CC0