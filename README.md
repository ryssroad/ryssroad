# road

Systems engineer, ~20 years in infrastructure. These days I build at the intersection of
crypto, privacy and agent systems, mostly in hackathons and protocol programs.

Almaty, KZ · [X @imtheryss](https://x.com/imtheryss) · [LinkedIn](https://www.linkedin.com/in/roadz)

## Recent builds

| Project | What it is | Stack | Context |
|---|---|---|---|
| [QVault](https://github.com/ryssroad/qvault) | A vault that a leaked ECDSA key cannot drain: every withdrawal also needs an ML-DSA-87 signature verified on-chain | Solidity · TypeScript | QoreChain *Build Before Q-Day*, Post-Quantum dApp track, 2026 |
| [Veil](https://github.com/ryssroad/veil) | Private invoices for public payments on an optimistic rollup, with an auditor watchtower and fast finality (~6 s from pay to final) | Node.js | QoreChain *Build Before Q-Day*, Protocol Builders track, 2026 |
| [ZECRET](https://github.com/ryssroad/zecret-dms-demo) | Private dead man's switch on Zcash: releases information, not funds | Rust · Zcash | WIP, offline protocol-core demo |

<!-- add a row once the contract-migration agent has a repo -->

## Protocol work

- **Post Fiat**: validator operator and Task Node contributor ([example PR](https://github.com/CorbanuCore/CorbanuTerminal/pull/2423))
- **Gensyn**: ~9 months on the testnet
- Long-running node and validator operations across several networks

## How I build

I treat agents as part of the infrastructure. I own architecture and decisions.
Claude Code and Codex do implementation and cross-review, and their work is labeled
in issues and PRs. Every build ships with a reproducible demo and a written spec.
