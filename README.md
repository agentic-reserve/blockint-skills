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
| `blockchain-spider-toolkit` | [BlockchainSpider](https://github.com/wuzhy1ng/BlockchainSpider) — Python/Scrapy on-chain **data collection** (EVM/Solana, subgraphs) |
| `mots-transaction-semantics` | [MoTS](https://github.com/wuzhy1ng/MoTS) — legacy **KYT / transaction semantics** Scrapy research code (merged upstream note → prefer BlockchainSpider for current work) |
| `impersonator-dapp-devtools` | [Impersonator](https://github.com/impersonator-eth/impersonator) / [Impersonator Solana](https://github.com/impersonator-eth/impersonator-solana) — dApp **read-only address** UX via WalletConnect (dev/testing; strong ethics guardrails) |
| `phalcon-compliance-documentation` | Pointer to **Phalcon Compliance** public docs portal (compliance investigation / monitoring product docs) |
| `chainalysis-sanctions-screening` | **Chainalysis** public **Sanctions API** + EVM **oracle** router (OFAC SDN–oriented checks; verify live docs; see `Chainalysis.md` excerpt) |
| `fatf-glossary-reference` | [FATF Glossary](https://www.fatf-gafi.org/en/pages/fatf-glossary.html) — official **AML/CFT** terminology (educational; not legal advice) |
| `arkham-leading-crypto-analysis-tools` | [Arkham research](https://info.arkm.com/research/leading-crypto-analysis-tools-for-traders-investors) — survey of **fundamental / technical / on-chain** tool landscape for traders (not investment advice) |
| `risk-exposure-screening-concepts` | Risk **indicator** taxonomies, exposure value/%, address vs tx screening templates (educational) |
| `behavioral-risk-screening-concepts` | Large-value / high-frequency / transit behavior, rapid-transit tx rules (educational) |
| `address-screening-workflow-concepts` | Tags/markers, bulk CSV import, address list/detail, blacklist/whitelist patterns (educational) |
| `transaction-screening-workflow-concepts` | Tx/transfer screening, deposit vs withdrawal, CSV, list/detail, STR-style exports (educational) |
| `on-chain-research-tokenomics` | On-chain metrics, tokenomics |
| `crypto-investigation-compliance` | Crime map, ethical investigation workflow |
| `bellingcat-investigation-toolkit` | Bellingcat OSINT toolkit pointer (GitBook + GitHub catalog) |
| `crypto-market-structures` | Max pain, ETFs, arbitrage, TA flags (educational) |
| `on-chain-investigator-agent` | On-chain forensics persona: tracing, contracts, scam patterns, evidence reports |
| `solana-tracing-specialist` | Solana-focused tracing: ATAs, SPL, indexers, fund-flow graphs |
| `solana-onchain-intelligence-resources` | Solana intel **resource router**: Helius, Range MCP, Tavily, PayAI x402, React Flow, Solana.com skills (`llms.txt` indexes), [Solana Policy Institute](https://www.solanapolicyinstitute.org/) (policy/education) |
| `range-ai-investigation-playbook` | **Range AI** MCP investigation workflow (risk, sanctions, flows, cross-chain) + one-shot prompt |
| `solana-clustering-advanced` | Advanced Solana clustering: graphs, bundles, launchpads, PDAs, ML |
| `solana-clustering-case-study-agent` | Solana clustering → public case studies, threads, evidence packs, reproducible exports |
| `defi-security-audit-agent` | DeFi audit/rug-risk triage: contracts, liquidity, governance, bridges, evidence reports |
| `defi-admin-takeover-mitigation-lessons` | Privileged-access failures (e.g. [Drift hack](https://www.chainalysis.com/blog/lessons-from-the-drift-hack/)): signers, nonces, oracles, monitoring |
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

## Discovery on [skills.sh](https://skills.sh/)

The [open agent skills ecosystem](https://www.npmjs.com/package/skills) discovers skills from public Git repositories. [skills.sh](https://skills.sh/) is the browseable directory; there is **no separate upload form**—visibility comes from **installing** skills with the CLI (telemetry drives the leaderboard). Keep this repo **public** and **up to date** on GitHub.

**Install all skills from this repo:**

`npx skills add agentic-reserve/blockint-skills`

**List skill names without installing:**

`npx skills add agentic-reserve/blockint-skills --list`

**Install specific skills (example):**

`npx skills add agentic-reserve/blockint-skills --skill blockchain-intelligence-playbook --skill crypto-investigation-compliance`
