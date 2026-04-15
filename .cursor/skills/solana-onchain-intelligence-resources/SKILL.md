---
name: solana-onchain-intelligence-resources
description: Companion to blockint-skills Solana work—official doc indexes and stacks for RPC/indexers, sanctions and address intel MCP, web research, agent payments, graph UIs, Solana Foundation dev skills, and Solana Policy Institute (policy/regulatory education). Use when the user needs pointers to Helius, Range AI, Tavily, PayAI x402, React Flow, Solana.com skills, or SPI alongside on-chain forensics—not as a substitute for reading current provider docs, legal counsel, or API keys.
---

# Solana on-chain intelligence — external resources

Use this skill together with **solana-tracing-specialist**, **solana-clustering-advanced**, **solana-defi-vulnerability-analyst-agent**, and **on-chain-investigator-agent**. It does not duplicate blockint methodologies; it routes agents to authoritative documentation indexes and products so they pull current API shapes and scopes from the source.

## Solana Foundation (developer skills and docs)

- **Agent skills hub:** [solana.com/SKILL.md](https://solana.com/SKILL.md) — install foundation-maintained skills (for example `npx skills add` from linked repos); categories include security checklist, testing, Kit/web3.js interop, payments, IDL clients.
- Use when building or auditing programs and clients; pair with **solana-defi-vulnerability-analyst-agent** for review posture.

## Helius (Solana infrastructure and docs index)

- **Documentation index:** [helius.dev/llms.txt](https://www.helius.dev/llms.txt) — discover blog and guides on RPC, DAS, webhooks, compression, MEV, Surfpool, congestion, and tooling.
- Typical investigation uses: enhanced RPC and history, parsed transactions, webhooks, Geyser-style streaming. Always confirm methods against current Helius docs for your plan and tier.

## Range AI (MCP blockchain intelligence)

- **Docs index:** [docs.range.org/llms.txt](https://docs.range.org/llms.txt) — browse Range AI pages.
- **MCP endpoint:** `https://api.range.org/ai/mcp` — connect in MCP-compatible clients for address intel, risk and sanctions-oriented tools, and cross-chain pivots (per Range product scope). Requires a user Range API key where applicable.

## Tavily (web search and research for OSINT)

- **Documentation index:** [docs.tavily.com/llms.txt](https://docs.tavily.com/llms.txt) — search, extract, crawl, map, research skills and CLI patterns.
- Use to corroborate public claims, find primary sources, or extract pages lawfully, alongside **bellingcat-investigation-toolkit** and **crypto-investigation-compliance**.

## PayAI Network (x402 and agent payments)

- **Documentation index:** [docs.payai.network/llms.txt](https://docs.payai.network/llms.txt) — x402 protocol, clients, servers, facilitators, supported networks.
- Relevant when designing paid API or agent pipelines on supported chains; not required for basic tracing alone.

## React Flow (fund-flow and graph UIs)

- **Documentation index:** [reactflow.dev/llms.txt](https://reactflow.dev/llms.txt) — node-based diagrams, layouts, accessibility.
- Use when building or specifying interactive wallet or transaction graph UIs. Data still comes from RPC and indexers, not from React Flow itself.

## Solana Policy Institute (policy and regulatory education)

- **Site:** [solanapolicyinstitute.org](https://www.solanapolicyinstitute.org/) — describes itself as a non-partisan, non-profit focused on educating policymakers on decentralized networks such as Solana and on legal clarity for people building and using them.
- **Content types (as presented on the site):** issue-area explainers (for example stablecoins, developer protections, tax clarity for staking), **newsroom** and **blog**, and a **legal archive** (filings, amicus briefs, comment and coalition letters).
- **Use in blockint:** background on **public** policy and **regulatory** narratives around Solana—not case law for a specific investigation. Pair with **crypto-investigation-compliance** when the user needs to separate **on-chain facts** from **legal** or **institutional** follow-up.
- **Not** legal advice; **not** a substitute for qualified counsel or official government guidance.

## How to combine with blockint

| Task | blockint skill | Often paired with |
|------|----------------|-------------------|
| Parse Solana txs, ATAs | **solana-tracing-specialist** | Helius (RPC/indexer docs) |
| Cluster addresses, Jito | **solana-clustering-advanced** | Helius, on-chain data |
| Risk/sanctions screen | **crypto-investigation-compliance** | Range MCP (if connected) |
| Web corroboration | **bellingcat-investigation-toolkit** | Tavily |
| Program security | **solana-defi-vulnerability-analyst-agent** | Solana Foundation skills, Helius/Surfpool for testing |
| Graph UI | — | React Flow |
| Solana policy / regulatory context (education) | **crypto-investigation-compliance** | Solana Policy Institute site |

## Ethical guardrails

- Third-party APIs (Helius, Range, Tavily) require user credentials where needed; respect terms of service and rate limits.
- Range and sanctions-style tools support compliance workflows; they do not replace legal conclusions.
- PayAI and x402 involve real payments; the user must configure keys and networks.

**Goal:** give one place to tie Solana on-chain intel work in blockint to the documentation indexes and products teams already use: Helius, Range, Tavily, PayAI, React Flow, Solana Foundation, and the Solana Policy Institute for policy-facing context.
