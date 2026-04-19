# Oak Security — Public Audit Reports

This repository hosts the public audit reports produced by Oak Security, an independent blockchain and smart contract security firm.

Oak Security has completed **600+ security audits** across the Web3 ecosystem, working with protocols across DeFi, Layer 2 infrastructure, cross-chain bridges, privacy systems, and more. Our researchers include experts with PhDs in Computer Science, Cryptography, Economics, Engineering, and Finance.

Reports are published here as PDFs after both the project team and Oak Security mutually agree that the audit is complete and all findings have been addressed.

> **Note:** Audit reports in this repository represent a subset of Oak Security's total audit output. Non-public reports and early-stage pre-disclosure reports are not included.

---

## Browse Reports by Tech Stack

| Category | Description |
|---|---|
| [EVM / Solidity](./_tech_stacks/evm.md) | Ethereum Virtual Machine smart contracts, EVM-compatible chains (Filecoin FEVM, L2s, rollups, etc.) |
| [CosmWasm](./_tech_stacks/cosmwasm.md) | Rust-based smart contracts for CosmWasm-compatible Cosmos chains |
| [Cosmos SDK](./_tech_stacks/cosmos-sdk.md) | Cosmos SDK blockchain core modules and application-specific chains (Go) |
| [Neutron](./_tech_stacks/neutron.md) | Neutron chain — dedicated section for one of the most-audited Cosmos chains |
| [Cosmos Bridges & Cross-Chain](./_tech_stacks/bridges.md) | IBC bridges, cross-chain messaging, multi-chain protocols (Wormhole, Hyperlane, Snowbridge, etc.) |
| [Polkadot / Substrate](./_tech_stacks/polkadot-substrate.md) | Polkadot ecosystem, Substrate frameworks, Parachains |
| [Soroban & Stellar](./_tech_stacks/soroban-stellar.md) | Soroban smart contracts and Stellar protocol core |
| [Gno](./_tech_stacks/gno.md) | Gnolang smart contracts (Gno.land) |
| [Rust (non-CosmWasm)](./_tech_stacks/rust.md) | Rust consensus engines, node libraries, protocol cores outside CosmWasm |
| [ZK Systems](./_tech_stacks/zk-systems.md) | Zero-knowledge provers, verifiers, privacy protocols, ZK-based consensus |
| [Offchain / TypeScript](./_tech_stacks/offchain-typescript.md) | Backend services, APIs, indexers, wallet integrations, frontend security |

---

## Taxonomy Notes

Reports are classified by **primary tech stack** but many span multiple categories. Cross-category listings are noted inline within each stack file:

- **CosmWasm + Cosmos SDK**: Most CosmWasm chain audits also involve Cosmos SDK modules
- **EVM + CosmWasm**: Projects like Router, Structured, and Evmos span both
- **ZK + Rust**: Dusk's Rusk is both a Rust project and a ZK consensus protocol
- **Cosmos + Polkadot**: Snowbridge bridges both ecosystems
- **Offchain + EVM**: Wallet audits often cover both the application and connected contracts

---

## About Oak Security

- **Website:** https://oaksecurity.io
- **Audit Reports:** https://github.com/oak-security/audit-reports
- **Public Resources:** https://github.com/oak-security/resources
- Featured in CoinTelegraph, Barron's, Newsweek, Yahoo Finance, Crypto News

---

*Maintained by Oak Security. Report issues or suggest corrections via GitHub.*
