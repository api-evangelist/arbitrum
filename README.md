# Arbitrum (arbitrum)

Arbitrum is the Ethereum Layer 2 rollup ecosystem from Offchain Labs. It includes Arbitrum One (general-purpose rollup secured by Ethereum), Arbitrum Nova (AnyTrust chain for high-throughput, low-cost apps), Arbitrum Sepolia (testnet), and Arbitrum Orbit (settlement framework for custom L2 / L3 chains). Developers interact via standard Ethereum JSON-RPC, the Stylus SDK for Rust / C / C++ smart contracts, the Arbitrum SDK for cross-chain messaging and bridging, and the Arbitrum Bridge for canonical asset transfer between Ethereum and Arbitrum chains.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/arbitrum/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/arbitrum/refs/heads/main/apis.yml)

## Tags

- Layer 2
- Ethereum
- Rollup
- JSON-RPC
- Stylus
- Nitro
- Orbit
- Bridge

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### Arbitrum One JSON-RPC

Public Ethereum JSON-RPC endpoint for Arbitrum One mainnet (chain ID 42161), the flagship optimistic rollup secured directly by Ethereum L1. Supports standard eth_* methods plus Arbitrum-specific precompiles for L1 messaging, retryable tickets, and gas accounting. Public endpoint does not support WebSockets — production teams use Alchemy, QuickNode, Infura, Chainstack, or self-hosted Nitro nodes.

- **Human URL:** [https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers](https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers)
- **Base URL:** `https://arb1.arbitrum.io/rpc`

#### Tags

- JSON-RPC
- Mainnet
- Arbitrum One

#### Properties

- [Documentation](https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/arbitrum/refs/heads/main/asyncapi/arbitrum-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arbitrum Nova JSON-RPC

Public Ethereum JSON-RPC endpoint for Arbitrum Nova (chain ID 42170), an AnyTrust chain with a Data Availability Committee for high-throughput, low-cost transactions suited to gaming and social apps.

- **Human URL:** [https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers](https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers)
- **Base URL:** `https://nova.arbitrum.io/rpc`

#### Tags

- JSON-RPC
- Nova
- AnyTrust

#### Properties

- [Documentation](https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/arbitrum/refs/heads/main/asyncapi/arbitrum-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arbitrum Sepolia JSON-RPC

Public Ethereum JSON-RPC endpoint for the Arbitrum Sepolia testnet (chain ID 421614).

- **Human URL:** [https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers](https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers)
- **Base URL:** `https://sepolia-rollup.arbitrum.io/rpc`

#### Tags

- JSON-RPC
- Testnet
- Sepolia

#### Properties

- [Documentation](https://docs.arbitrum.io/build-decentralized-apps/reference/node-providers)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/arbitrum/refs/heads/main/asyncapi/arbitrum-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arbitrum Bridge

Canonical cross-chain bridge for transferring ETH and ERC-20 tokens between Ethereum L1, Arbitrum One, Arbitrum Nova, and connected Orbit chains. Bridge operations and underlying token-bridge contracts are open-source.

- **Human URL:** [https://bridge.arbitrum.io](https://bridge.arbitrum.io)
- **Base URL:** `https://bridge.arbitrum.io`

#### Tags

- Bridge
- Cross-Chain
- Canonical

#### Properties

- [Documentation](https://docs.arbitrum.io/arbitrum-bridge/quickstart)
- [App](https://bridge.arbitrum.io)
- [Repository](https://github.com/OffchainLabs/token-bridge-contracts)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arbitrum SDK

Official TypeScript SDK (@arbitrum/sdk) for cross-chain interactions — building L1-to-L2 and L2-to-L1 messages, deposit and withdrawal flows, retryable tickets, and gas estimation for Arbitrum chains.

- **Human URL:** [https://docs.arbitrum.io/sdk](https://docs.arbitrum.io/sdk)
- **Base URL:** `https://github.com/OffchainLabs/arbitrum-sdk`

#### Tags

- SDK
- TypeScript
- Cross-Chain

#### Properties

- [Documentation](https://docs.arbitrum.io/sdk)
- [Repository](https://github.com/OffchainLabs/arbitrum-sdk)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stylus SDK (Rust)

Stylus lets developers write EVM-compatible smart contracts in Rust, C, and C++ that compile to WASM and run alongside Solidity contracts. The Rust SDK provides storage primitives, host I/O, and macros for ABI compatibility.

- **Human URL:** [https://docs.arbitrum.io/stylus/gentle-introduction](https://docs.arbitrum.io/stylus/gentle-introduction)
- **Base URL:** `https://github.com/OffchainLabs/stylus-sdk-rs`

#### Tags

- Stylus
- SDK
- Rust
- WASM

#### Properties

- [Documentation](https://docs.arbitrum.io/stylus/gentle-introduction)
- [Repository](https://github.com/OffchainLabs/stylus-sdk-rs)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arbitrum Nitro

Open-source Nitro node implementation that runs Arbitrum One, Nova, and Orbit chains. Includes the sequencer, batch poster, validator, and a fork of go- ethereum patched for Arbitrum's execution layer.

- **Human URL:** [https://docs.arbitrum.io/how-arbitrum-works/inside-arbitrum-nitro](https://docs.arbitrum.io/how-arbitrum-works/inside-arbitrum-nitro)
- **Base URL:** `https://github.com/OffchainLabs/nitro`

#### Tags

- Node
- Nitro
- Sequencer
- Validator

#### Properties

- [Documentation](https://docs.arbitrum.io/how-arbitrum-works/inside-arbitrum-nitro)
- [Repository](https://github.com/OffchainLabs/nitro)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arbitrum Orbit SDK

TypeScript SDK and tooling for deploying and operating Orbit chains — custom Arbitrum L2 / L3 chains that settle to Arbitrum One, Nova, or other Orbit chains.

- **Human URL:** [https://docs.arbitrum.io/launch-orbit-chain/orbit-gentle-introduction](https://docs.arbitrum.io/launch-orbit-chain/orbit-gentle-introduction)
- **Base URL:** `https://github.com/OffchainLabs/arbitrum-orbit-sdk`

#### Tags

- Orbit
- SDK
- Appchains

#### Properties

- [Documentation](https://docs.arbitrum.io/launch-orbit-chain/orbit-gentle-introduction)
- [Repository](https://github.com/OffchainLabs/arbitrum-orbit-sdk)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arbiscan Block Explorer

Etherscan-family block explorer for Arbitrum One, Nova, and Sepolia with a public REST API for contracts, transactions, and addresses.

- **Human URL:** [https://arbiscan.io](https://arbiscan.io)
- **Base URL:** `https://api.arbiscan.io/api`

#### Tags

- Block Explorer
- Arbiscan
- API

#### Properties

- [Documentation](https://docs.arbiscan.io)
- [Website](https://arbiscan.io)
- [Postman Collection](collections/arbitrum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arbitrum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://arbitrum.io)
- [Foundation](https://arbitrum.foundation)
- [Documentation](https://docs.arbitrum.io)
- [Git Hub](https://github.com/OffchainLabs)
- [Portal](https://portal.arbitrum.io)
- [Bridge](https://bridge.arbitrum.io)
- [Status](https://status.arbitrum.io)
- [Twitter](https://x.com/arbitrum)
- [Discord](https://discord.gg/arbitrum)
- [Blog](https://medium.com/offchainlabs)
- [L L Ms Txt](https://docs.arbitrum.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
