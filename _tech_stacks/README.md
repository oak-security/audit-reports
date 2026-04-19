# Oak Security Audit Reports — By Tech Stack

> **Note:** Reports are classified by primary tech stack but many span multiple categories. Cross-category listings are indicated where relevant.

---

## Tech Stack Index

| Category | Description |
|---|---|
| [EVM / Solidity](./evm.md) | Ethereum Virtual Machine smart contracts, EVM-compatible chains (Filecoin FEVM, L2s, etc.) |
| [CosmWasm](./cosmwasm.md) | Rust-based smart contracts for CosmWasm-compatible Cosmos chains |
| [Cosmos SDK](./cosmos-sdk.md) | Cosmos SDK blockchain core and modules (Go) |
| [Neutron](./neutron.md) | Neutron chain audits (dedicated section — one of the most audited chains) |
| [Cosmos Bridges & Cross-Chain](./bridges.md) | IBC bridges, cross-chain messaging, multi-chain protocols |
| [Polkadot / Substrate](./polkadot-substrate.md) | Polkadot ecosystem, Substrate chains, Parachains |
| [Soroban & Stellar](./soroban-stellar.md) | Soroban smart contracts and Stellar protocol core |
| [Gno](./gno.md) | Gnolang smart contracts (Gno.land) |
| [Rust (non-CosmWasm)](./rust.md) | Rust consensus engines, node libraries, protocol cores |
| [ZK Systems](./zk-systems.md) | Zero-knowledge provers, verifiers, privacy protocols |
| [Offchain / TypeScript](./offchain-typescript.md) | Backend services, APIs, indexers, wallets, frontends |

---

## Taxonomy Notes

The classification is intentionally **not strict** — many reports span multiple tech stacks:

- **CosmWasm + Cosmos SDK**: Most CosmWasm chain audits also involve Cosmos SDK modules
- **EVM + CosmWasm**: Projects like Router, Structured, and Evmos span both
- **ZK + Rust**: Dusk's Rusk is both a Rust project and a ZK consensus protocol
- **Cosmos + Polkadot**: Snowbridge bridges both ecosystems
- **Offchain + EVM**: Wallet audits often include both the app and the connected contracts

The primary tech stack is used for the main listing; cross-listings are indicated inline.

---

## Report Counts (Approximate)

| Tech Stack | # Reports |
|---|---|
| CosmWasm | ~180 |
| EVM / Solidity | ~80 |
| Cosmos SDK | ~30 |
| Bridges / Cross-chain | ~30 |
| Offchain / TypeScript | ~20 |
| ZK Systems | ~10 |
| Rust (non-CosmWasm) | ~10 |
| Polkadot / Substrate | ~8 |
| Soroban / Stellar | ~3 |
| Gno | ~4 |
| Neutron (dedicated) | ~4 |

---

*Maintained by Oak Security. Report issues or suggest corrections via GitHub.*
