<h1 align="center">Hi there, I'm Jayesh Yadav</h1>
<h3 align="center">Protocol Architect</h3>
<p align="center">Open to new protocol engineering roles (remote)</p>

Two years designing and building in DeFi on EVM chains. Deep expertise in EIP-2535 Diamond proxy, ERC-4626 vaults, ERC-7579 modular accounts, and composable DeFi integration (DEXs, lending, yield, cross-chain). At [Blok Capital](https://github.com/BLOKCapital), architected a modular multichain wealth management protocol: Diamond proxy vaults with a CREATE2 factory, DAO-governed Facet Registry, multiple yield strategies, onchain indices with automated rebalancing, and CCTP + CCIP for cross-chain USDC transfers. Currently building in public and studying zero-knowledge proofs.

---

## What I'm building

**Coffer:** Self-custodial, modular smart-vault protocol on ERC-7579 + ERC-4337 v0.7. Every user gets their own programmable smart account that holds their funds and executes DeFi strategies (Aave V3, Uniswap V2/V3). Pluggable validator/executor/hook modules, deterministic CREATE2 deployment (up to 10 coffers per user), an ExecutorRegistry for clean DEX routing, and a funds-safe KillSwitch that blocks capital-deploying actions in emergencies while always leaving withdrawals open. → [repo](https://github.com/jayeshy14/coffer-contracts)

**Vault Router:** ERC-4626 compliant yield vault on the Diamond proxy pattern (EIP-2535), routing deposits across Morpho Blue, Aave V3, and Pendle PT strategy facets on Arbitrum. Curator-governed allocation with per-strategy caps, idle reserve enforcement, and a Facet Registry for strategy allow-listing. → [repo](https://github.com/jayeshy14/Vault-Router)

**Uniswap V4 Diamond Hook:** Upgradeable V4 hook framework using EIP-2535. Hook address stays permanent while logic is upgradeable via `diamondCut`, eliminating pool migration on upgrades. Solved V4's permission-bit address constraint by mining the CREATE2 salt once at deploy. → [repo](https://github.com/jayeshy14/uniswap-v4-hook-diamond)

**ZK proofs:** Working through the RareSkills ZK course (zero-knowledge proofs from first principles). Posting weekly progress on [Twitter](https://x.com/0xjayeshyadav). Notes in [zk-book-notes](https://github.com/jayeshy14/zk-book-notes).

---

## Selected work

| Repo | What it is |
|------|------------|
| [coffer-contracts](https://github.com/jayeshy14/coffer-contracts) | ERC-7579 modular smart accounts on ERC-4337 v0.7. Self-custodial vaults with executor registry, kill switch, and multi-protocol strategy execution |
| [Vault-Router](https://github.com/jayeshy14/Vault-Router) | ERC-4626 + EIP-2535 Diamond vault routing across Morpho, Aave, and Pendle on Arbitrum |
| [Diamond-Storage-Detector](https://github.com/jayeshy14/Diamond-Storage-Detector) | Static analysis tool detecting storage slot collisions across EIP-2535 Diamond facets |
| [uniswap-v4-hook-diamond](https://github.com/jayeshy14/uniswap-v4-hook-diamond) | Upgradeable Uniswap V4 hook framework. Permanent hook address, logic upgradeable via diamondCut |

---

## Stack

**Languages** &nbsp; Solidity · Rust · TypeScript · JavaScript  
**Frameworks** &nbsp; Foundry · Hardhat · OpenZeppelin  
**Standards** &nbsp; EIP-2535 · ERC-7579 · ERC-4626 · ERC-4337 · ERC-5484 · ERC-1967 · EIP-7201  
**DeFi protocols** &nbsp; Uniswap V4 · Morpho · Aave · Pendle · Camelot · Chainlink  
**Cross-chain** &nbsp; CCTP · CCIP  
**Infra** &nbsp; Dune · Tenderly · The Graph · IPFS  

---

## Certifications

Uniswap V4 Incubator (Atrium) · Smart Contract Security, Advanced Foundry, Advanced Uniswap V3 (Cyfrin Updraft) · Web3 Dev, Blockchain Security Expert, Fintech Expert, Solana Development (101 Blockchains)

---

## Reach me

- **X / Twitter:** [@0xjayeshyadav](https://x.com/0xjayeshyadav)
- **LinkedIn:** [linkedin.com/in/jayeshyadav](https://www.linkedin.com/in/jayeshyadav)
- **Email:** [jayeshnyadav497@gmail.com](mailto:jayeshnyadav497@gmail.com)

Open to conversations on protocol design, Diamond pattern at scale, vault architecture, and the EVM ↔ ZK boundary.
