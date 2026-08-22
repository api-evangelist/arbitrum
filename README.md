# Arbitrum (arbitrum)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
