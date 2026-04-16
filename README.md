# blockint-skills

Public **Cursor Agent Skills** for **blockchain intelligence**, on-chain research, **compliance / screening** concepts, **DeFi and MEV** investigation patterns, **Solana** resources, **[Dune](https://docs.sim.dune.com/llms.txt) Sim** / **Dune Analytics API** doc routing, **OSINT** pointers, **[Katana](https://github.com/projectdiscovery/katana)** web crawling, selected **security-research** references (e.g. classic **AFL** docs), and a pointer to the **[Agent Skills](https://github.com/agentskills/agentskills)** open-format **specification** ([agentskills.io](https://agentskills.io)).

**Repository:** [github.com/agentic-reserve/blockint-skills](https://github.com/agentic-reserve/blockint-skills)

Skills live under `.cursor/skills/`. The **`blockchain-intelligence-playbook`** skill is the **index** (routing + “choosing a skill”); the table below lists **45** skill directories (**1** index + **44** topical).

| Directory | Topic |
|-----------|--------|
| `address-clustering-attribution` | **Clustering** heuristics, entity/label/tag, attribution |
| `address-screening-workflow-concepts` | Tags/markers, bulk CSV import, address list/detail, blacklist/whitelist patterns (educational) |
| `agentskills-specification` | [agentskills/agentskills](https://github.com/agentskills/agentskills) + [agentskills.io/llms.txt](https://agentskills.io/llms.txt) — **Agent Skills** format ([spec](https://agentskills.io/specification.md), [integrate](https://agentskills.io/integrate-skills.md)) |
| `arkham-leading-crypto-analysis-tools` | [Arkham research](https://info.arkm.com/research/leading-crypto-analysis-tools-for-traders-investors) — survey of **fundamental / technical / on-chain** tool landscape for traders (not investment advice) |
| `armaniferrante-x-status-solana-reference` | [@armaniferrante X post](https://x.com/armaniferrante/status/1411589629384355840) — **citation bookmark** (open URL for verbatim text) |
| `behavioral-risk-screening-concepts` | Large-value / high-frequency / transit behavior, rapid-transit tx rules (educational) |
| `bellingcat-investigation-toolkit` | Bellingcat OSINT toolkit pointer (GitBook + GitHub catalog) |
| `blockchain-analytics-operations` | Analytics platforms, compliance/forensic use cases |
| `blockchain-intelligence-fundamentals` | BI basics, tool types, payment rails |
| `blockchain-intelligence-playbook` | **Index** — routes to other skills; “choosing a skill” guidance |
| `blockchain-spider-toolkit` | [BlockchainSpider](https://github.com/wuzhy1ng/BlockchainSpider) — Python/Scrapy on-chain **data collection** (EVM/Solana, subgraphs) |
| `chainalysis-sanctions-screening` | **Chainalysis** public **Sanctions API** + EVM **oracle** router (OFAC SDN–oriented checks; verify live docs; see `Chainalysis.md` excerpt) |
| `cmichel-smart-contract-auditor-guide` | [cmichel.io](https://cmichel.io/how-to-become-a-smart-contract-auditor/) — **EVM** smart contract **auditor** learning path & FAQ (educational; article dated 2021) |
| `cross-chain-clustering-techniques-agent` | Multi-chain clustering: bridges, wrapped assets, unified graphs, cross-chain heuristics |
| `crypto-investigation-compliance` | Crime map, ethical investigation workflow |
| `crypto-market-structures` | Max pain, ETFs, arbitrage, TA flags (educational) |
| `defi-admin-takeover-mitigation-lessons` | Privileged-access failures (e.g. [Drift hack](https://www.chainalysis.com/blog/lessons-from-the-drift-hack/)): signers, nonces, oracles, monitoring |
| `defi-security-audit-agent` | DeFi audit/rug-risk triage: contracts, liquidity, governance, bridges, evidence reports |
| `dune-sim-onchain-analytics` | [Dune Sim](https://docs.sim.dune.com/llms.txt) + [Dune Analytics API](https://docs.sim.dune.com/dune-analytics-api.md) — realtime **EVM/SVM** analytics, subscriptions, historical SQL; [OpenAPI](https://docs.sim.dune.com/openapi.json) |
| `evm-solidity-defi-triage-agent` | EVM Solidity DeFi triage: proxies, oracles, reentrancy, access control (Ethereum/L2) |
| `fatf-glossary-reference` | [FATF Glossary](https://www.fatf-gafi.org/en/pages/fatf-glossary.html) — official **AML/CFT** terminology (educational; not legal advice) |
| `flash-loan-exploit-investigator-agent` | Flash-loan / atomic DeFi post-mortems: EVM + Solana traces, impact, mitigations, read-only sim |
| `honeypot-detection-techniques` | Honeypot-style token checks: EVM transfer gates, SPL/Token-2022, safe validation |
| `impersonator-dapp-devtools` | [Impersonator](https://github.com/impersonator-eth/impersonator) / [Impersonator Solana](https://github.com/impersonator-eth/impersonator-solana) — dApp **read-only address** UX via WalletConnect (dev/testing; strong ethics guardrails) |
| `katana-web-crawling` | Crawling / spidering with Katana |
| `lcamtuf-afl-documentation` | [lcamtuf AFL](https://lcamtuf.coredump.cx/afl/) — **American Fuzzy Lop** classic docs (coverage-guided fuzzing for C/C++; see **AFL++** for maintained fork) |
| `mev-bot-infrastructure-analysis-agent` | MEV infrastructure: searchers, bundles/builders, strategy fingerprints, concentration, public data |
| `mev-bot-rug-coordination-investigator-agent` | MEV × rug hypotheses: bundle overlap, timing, joint flows, confidence-scored case studies |
| `mots-transaction-semantics` | [MoTS](https://github.com/wuzhy1ng/MoTS) — legacy **KYT / transaction semantics** Scrapy research code (merged upstream note → prefer BlockchainSpider for current work) |
| `neodyme-solana-security-workshop` | [workshop.neodyme.io](https://workshop.neodyme.io/) + [neodyme-breakpoint-workshop](https://github.com/neodyme-labs/neodyme-breakpoint-workshop) — **mdBook** Solana security levels (intentionally vulnerable code; legal notice on site) |
| `on-chain-investigator-agent` | On-chain forensics persona: tracing, contracts, scam patterns, evidence reports |
| `on-chain-research-tokenomics` | On-chain metrics, tokenomics |
| `osec-solana-auditor-introduction` | [Osec blog](https://osec.io/blog/2022-03-14-solana-security-intro) — **Solana: An Auditor’s Introduction** (runtime, accounts, BPF; Mar 2022; verify current docs) |
| `phalcon-compliance-documentation` | Pointer to **Phalcon Compliance** public docs portal (compliance investigation / monitoring product docs) |
| `range-ai-investigation-playbook` | **Range AI** MCP investigation workflow (risk, sanctions, flows, cross-chain) + one-shot prompt |
| `risk-exposure-screening-concepts` | Risk **indicator** taxonomies, exposure value/%, address vs tx screening templates (educational) |
| `rug-pull-pattern-detection-agent` | Launch rug-risk: LP/dev patterns, locks, coordinated exits, red-flag scoring (public data) |
| `sandwich-attack-investigator-agent` | DEX sandwich MEV post-mortems: EVM + Solana bundles, slippage/profit estimates, evidence packs |
| `sealevel-attacks-solana` | [coral-xyz/sealevel-attacks](https://github.com/coral-xyz/sealevel-attacks) — **Anchor** examples of Solana exploit patterns & mitigations (educational) |
| `solana-clustering-advanced` | Advanced Solana clustering: graphs, bundles, launchpads, PDAs, ML |
| `solana-clustering-case-study-agent` | Solana clustering → public case studies, threads, evidence packs, reproducible exports |
| `solana-defi-vulnerability-analyst-agent` | Solana DeFi program risks: Anchor/PDAs/CPIs, oracles, pools, SPL, historical tx reconstruction |
| `solana-onchain-intelligence-resources` | Solana intel **resource router**: Helius, Range MCP, Tavily, PayAI x402, React Flow, Solana.com skills (`llms.txt` indexes), [Solana Policy Institute](https://www.solanapolicyinstitute.org/) (policy/education) |
| `solana-tracing-specialist` | Solana-focused tracing: ATAs, SPL, indexers, fund-flow graphs |
| `transaction-screening-workflow-concepts` | Tx/transfer screening, deposit vs withdrawal, CSV, list/detail, STR-style exports (educational) |

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
