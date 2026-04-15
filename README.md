# blockint-skills

Cursor **Agent Skills** for blockchain intelligence, on-chain research, investigation ethics, market-structure concepts, and **[Katana](https://github.com/projectdiscovery/katana)** web crawling.

Skills live under `.cursor/skills/`. The **`blockchain-intelligence-playbook`** skill is a short **index**; topical skills are split for clearer triggering:

| Directory | Topic |
|-----------|--------|
| `blockchain-intelligence-playbook` | **Index** — routes to other skills; “choosing a skill” guidance |
| `blockchain-intelligence-fundamentals` | BI basics, tool types, payment rails |
| `address-clustering-attribution` | **Clustering** heuristics, entity/label/tag, attribution |
| `cross-chain-clustering-techniques-agent` | Multi-chain clustering: bridges, wrapped assets, unified graphs, cross-chain heuristics |
| `blockchain-analytics-operations` | Analytics platforms, compliance/forensic use cases |
| `on-chain-research-tokenomics` | On-chain metrics, tokenomics |
| `crypto-investigation-compliance` | Crime map, ethical investigation workflow |
| `bellingcat-investigation-toolkit` | Bellingcat OSINT toolkit pointer (GitBook + GitHub catalog) |
| `crypto-market-structures` | Max pain, ETFs, arbitrage, TA flags (educational) |
| `on-chain-investigator-agent` | On-chain forensics persona: tracing, contracts, scam patterns, evidence reports |
| `solana-tracing-specialist` | Solana-focused tracing: ATAs, SPL, indexers, fund-flow graphs |
| `solana-clustering-advanced` | Advanced Solana clustering: graphs, bundles, launchpads, PDAs, ML |
| `solana-clustering-case-study-agent` | Solana clustering → public case studies, threads, evidence packs, reproducible exports |
| `defi-security-audit-agent` | DeFi audit/rug-risk triage: contracts, liquidity, governance, bridges, evidence reports |
| `evm-solidity-defi-triage-agent` | EVM Solidity DeFi triage: proxies, oracles, reentrancy, access control (Ethereum/L2) |
| `honeypot-detection-techniques` | Honeypot-style token checks: EVM transfer gates, SPL/Token-2022, safe validation |
| `rug-pull-pattern-detection-agent` | Launch rug-risk: LP/dev patterns, locks, coordinated exits, red-flag scoring (public data) |
| `mev-bot-rug-coordination-investigator-agent` | MEV × rug hypotheses: bundle overlap, timing, joint flows, confidence-scored case studies |
| `flash-loan-exploit-investigator-agent` | Flash-loan / atomic DeFi post-mortems: EVM + Solana traces, impact, mitigations, read-only sim |
| `sandwich-attack-investigator-agent` | DEX sandwich MEV post-mortems: EVM + Solana bundles, slippage/profit estimates, evidence packs |
| `mev-bot-infrastructure-analysis-agent` | MEV infrastructure: searchers, bundles/builders, strategy fingerprints, concentration, public data |
| `solana-defi-vulnerability-analyst-agent` | Solana DeFi program risks: Anchor/PDAs/CPIs, oracles, pools, SPL, historical tx reconstruction |
| `katana-web-crawling` | Crawling / spidering with Katana |

Copy `.cursor/skills/` into a project or symlink for global use, for example:

`ln -sf /path/to/blockint-skills/.cursor/skills ~/.cursor/skills`
