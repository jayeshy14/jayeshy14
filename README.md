<h1 align="center">Hi there, I'm Jayesh Yadav</h1>
<h3 align="center">Smart Contract / Protocol Engineer</h3>
<p align="center">Open to remote protocol engineering roles</p>

Two years designing and building in DeFi on EVM chains, with a focus on upgrade safety, vault architecture, and manipulation-resistant accounting. My depth is in EIP-2535 Diamonds and ERC-4626 vaults, with working knowledge of ERC-7579 / ERC-4337 modular accounts and composable DeFi integration across DEXs, lending, yield, and cross-chain. At [Blok Capital](https://github.com/BLOKCapital) I architected a modular multichain wealth-management protocol: Diamond proxy vaults with a CREATE2 factory, a DAO-governed Facet Registry, onchain indices with automated rebalancing, and cross-chain USDC via CCTP and CCIP. Currently building an autonomous, market-cap-weighted index vault, and studying zero-knowledge proofs on the side.

---

## Selected work

**Index Protocol** — a pooled, autonomous, market-cap-weighted index vault on Ethereum mainnet. An ERC-7540 async superset of ERC-4626 with two-lane liquidity, an on-chain methodology engine (iterative capping with exact invariants and free-float weighting), and a layered circulating-supply oracle (trustless on-chain derivation, multi-source median with divergence freeze, and rate-limited containment). Core vault, methodology, and oracle are implemented and tested; CoW-settled rebalancing is in progress. → [repo](https://github.com/jayeshy14/index-protocol)

**Diamond Storage Collision Detector** — a static-analysis tool that catches storage-slot collisions across EIP-2535 facets before deployment, where a collision silently corrupts shared state across facets. → [repo](https://github.com/jayeshy14/Diamond-Storage-Detector)

**Vault Router** — an ERC-4626 yield vault on the Diamond proxy pattern, routing deposits across Morpho Blue, Aave V3, and Pendle PT strategy facets on Arbitrum, with curator-governed allocation, per-strategy caps, and idle-reserve enforcement. → [repo](https://github.com/jayeshy14/Vault-Router)

**Uniswap V4 Diamond Hook** — an upgradeable V4 hook framework on EIP-2535. The hook address stays permanent via a once-mined CREATE2 salt while logic upgrades through `diamondCut`, eliminating pool migration on hook upgrades. → [repo](https://github.com/jayeshy14/uniswap-v4-hook-diamond)

---

## Stack

**Depth** &nbsp; EIP-2535 Diamonds · ERC-4626 vaults · storage layout and upgrade safety (EIP-1967, ERC-7201) · Foundry fuzz and invariant testing
**Working knowledge** &nbsp; ERC-7579 / ERC-4337 modular accounts · Chainlink oracles · CCTP / CCIP cross-chain
**Languages** &nbsp; Solidity · Rust · TypeScript · JavaScript
**Tooling** &nbsp; Foundry · Hardhat · OpenZeppelin · Dune · Tenderly
**DeFi** &nbsp; Uniswap V4 · Morpho · Aave · Pendle · Camelot · Chainlink

---

## Reach me

- **X / Twitter:** [@0xjayeshyadav](https://x.com/0xjayeshyadav)
- **LinkedIn:** [linkedin.com/in/jayeshyadav](https://www.linkedin.com/in/jayeshyadav)
- **Email:** [jayeshnyadav497@gmail.com](mailto:jayeshnyadav497@gmail.com)

Open to conversations on protocol design, the Diamond pattern at scale, and vault architecture.
