<h1 align="center">Hi there, I'm Jayesh Yadav</h1>
<h3 align="center">Protocol Architect</h3>
<p align="center">Open to new protocol engineering roles (remote)</p>

Two years designing and building in DeFi on EVM chains. Deep expertise in EIP-2535 Diamond proxy, ERC-4626 vaults, and composable DeFi integration (DEXs, lending, yield, cross-chain). At [Blok Capital](https://github.com/BLOKCapital), architected a modular multichain wealth management protocol — Diamond Factory with CREATE2 deterministic addresses, DAO-governed Facet Registry, onchain indices with automated rebalancing, CCTP + CCIP cross-chain. Currently building in public and going deep on zk proofs.

---

## What I'm building

**Vault Router** — ERC-4626 compliant yield vault on the Diamond proxy pattern (EIP-2535), routing deposits across Morpho Blue, Aave V3, and Pendle PT strategy facets on Arbitrum. Curator-governed allocation with per-strategy caps, idle reserve enforcement, and a Facet Registry for strategy allow-listing. Built for the Arbitrum Open House Buildathon (June 2026). → [repo](https://github.com/jayeshy14/Vault-Router)

**Uniswap V4 Diamond Hook** — upgradeable V4 hook framework using EIP-2535. Hook address stays permanent while logic is upgradeable via \`diamondCut\`, eliminating pool migration on upgrades. Solved V4's permission-bit address constraint by mining the CREATE2 salt once at deploy — proxy bytecode never changes, mined address stays valid permanently. All V4 callbacks implemented as independently upgradeable facets sharing collision-safe AppStorage. → [repo](https://github.com/jayeshy14/uniswap-v4-hook-diamond)

**ZK proofs** — working through Justin Thaler's *Proofs, Arguments, and Zero-Knowledge*, Dan Boneh's cryptography course, and the 0xPARC curriculum. Building toward circuit-level competence (Circom, Halo2, Noir) on top of existing EVM depth. Notes and progress in [zk-book-notes](https://github.com/jayeshy14/zk-book-notes).

---

## Selected work

| Repo | What it is |
|------|------------|
| [Vault-Router](https://github.com/jayeshy14/Vault-Router) | ERC-4626 + EIP-2535 Diamond vault routing across Morpho, Aave, and Pendle on Arbitrum |
| [uniswap-v4-hook-diamond](https://github.com/jayeshy14/uniswap-v4-hook-diamond) | Upgradeable Uniswap V4 hook framework — permanent hook address, logic upgradeable via diamondCut |
| [Diamond-Storage-Detector](https://github.com/jayeshy14/Diamond-Storage-Detector) | Static analysis tool detecting storage slot collisions across EIP-2535 Diamond facets |
| [CEX-Backend](https://github.com/jayeshy14/CEX-Backend) | Centralized-exchange backend — matching engine (1000+ TPS), multi-chain deposits, order book |
| [Prism](https://github.com/jayeshy14/Prism) | Draft ERC — Modular Capability Proxy with capability-gated routing and tiered governance |

---

## Stack

**Languages** &nbsp; Solidity · Rust · TypeScript · JavaScript  
**Frameworks** &nbsp; Foundry · Hardhat · OpenZeppelin  
**Standards** &nbsp; EIP-2535 · ERC-4626 · ERC-4337 · ERC-5484 · ERC-1967 · EIP-1014  
**DeFi protocols** &nbsp; Uniswap V4 · Morpho · Aave · Pendle · Camelot · Chainlink  
**Cross-chain** &nbsp; CCTP · CCIP  
**Infra** &nbsp; Dune · Tenderly · The Graph · IPFS  

---

## Certifications

Uniswap V4 Incubator (Atrium) · Smart Contract Security, Advanced Foundry, Advanced Uniswap V3 (Cyfrin Updraft) · Web3 Dev, Blockchain Security Expert, Fintech Expert, Solana Development (101 Blockchains)

---

## Reach me

- **Status** — Open to new protocol engineering roles (remote)
- **X / Twitter** — [@0xjayeshyadav](https://x.com/0xjayeshyadav)
- **LinkedIn** — [linkedin.com/in/jayeshyadav](https://www.linkedin.com/in/jayeshyadav)
- **Email** — [jayeshnyadav497@gmail.com](mailto:jayeshnyadav497@gmail.com)

Open to conversations on protocol design, Diamond pattern at scale, vault architecture, and the EVM ↔ ZK boundary.

---
