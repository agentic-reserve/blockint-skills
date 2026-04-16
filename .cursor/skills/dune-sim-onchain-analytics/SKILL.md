---
name: dune-sim-onchain-analytics
description: "Routes to Dune Sim and Dune Analytics API documentation (docs.sim.dune.com)—real-time multichain wallet and token analytics (EVM and SVM or Solana), subscriptions and webhooks, plus historical SQL via the Analytics API. Use when the user names Dune Sim, Sim API, on-chain analytics with Dune, or needs the llms.txt doc index—not for embedding API keys in clients or substituting live billing, quotas, and Terms."
---

# Dune — Sim and on-chain analytics (reference)

**Educational routing only.** Read **live** docs for endpoint paths, auth headers, chain coverage, and **Compute Units (CUs)**. This skill summarizes discovery entry points and how Sim relates to **Dune Analytics** SQL access.

## Canonical discovery

| Resource | URL |
|----------|-----|
| **LLM / agent index** | [docs.sim.dune.com/llms.txt](https://docs.sim.dune.com/llms.txt) — machine-readable list of pages (start here to find Markdown topics). |
| **Developer quickstart** | [docs.sim.dune.com/index.md](https://docs.sim.dune.com/index.md) |
| **Build with AI** | [docs.sim.dune.com/build-with-ai.md](https://docs.sim.dune.com/build-with-ai.md) — `llms.txt`, per-page Markdown, OpenAPI, AI search. |
| **Agent reference (IDE agents)** | [docs.sim.dune.com/agent-reference.md](https://docs.sim.dune.com/agent-reference.md) — copy-in reference for Claude Code, Cursor, Codex, Gemini CLI, etc. |
| **OpenAPI** | [docs.sim.dune.com/openapi.json](https://docs.sim.dune.com/openapi.json) |

## What “Sim” vs “Dune Analytics API” means here

| Layer | Role |
|--------|------|
| **Sim APIs** | Real-time and streaming-style **wallet** and **token** surfaces—balances, activity, transactions, NFT collectibles, DeFi positions, stablecoins, **subscriptions** (webhooks), plus many **per-chain** guides under `chains/`. |
| **Dune Analytics API** | **[Custom SQL](https://docs.sim.dune.com/dune-analytics-api.md)** over **historical** blockchain datasets—complements Sim’s realtime APIs for analytics and research workflows. |

## Doc clusters (high level)

- **Billing and limits:** [Compute Units](https://docs.sim.dune.com/compute-units.md); [Error handling](https://docs.sim.dune.com/error-handling.md).
- **EVM:** [Overview](https://docs.sim.dune.com/evm/overview.md), [Activity](https://docs.sim.dune.com/evm/activity.md), [Balances](https://docs.sim.dune.com/evm/balances.md), [Transactions](https://docs.sim.dune.com/evm/transactions.md), [Subscriptions](https://docs.sim.dune.com/evm/subscriptions.md), [Token holders / info](https://docs.sim.dune.com/evm/token-holders.md), [Supported chains](https://docs.sim.dune.com/evm/supported-chains.md), [Token filtering / spam](https://docs.sim.dune.com/token-filtering.md).
- **SVM (Solana and related):** [SVM overview](https://docs.sim.dune.com/svm/overview.md), [Solana balances](https://docs.sim.dune.com/svm/balances.md), [Solana transactions](https://docs.sim.dune.com/svm/transactions.md); chain hub includes [Solana](https://docs.sim.dune.com/chains/solana.md) and [Eclipse](https://docs.sim.dune.com/chains/eclipse.md) per index.
- **Security pattern for keys:** [Cloudflare proxy](https://docs.sim.dune.com/proxy.md) — avoid exposing API keys in browser clients.

## How to combine with blockint

| Need | Skill |
|------|--------|
| Abstract BI / analytics product context | **blockchain-analytics-operations** |
| Solana tracing and forensics patterns | **solana-tracing-specialist**, **solana-onchain-intelligence-resources** |
| End-to-end investigator persona | **on-chain-investigator-agent** |
| Range / sanctions / risk products | **range-ai-investigation-playbook** (different vendor; compare scopes in live docs) |

## Guardrails

- **Secrets** — Keep API keys in **environment variables**, secret stores, or server-side proxies; follow Dune’s **proxy** guidance for client-facing apps.  
- **Compliance** — Analytics data supports research; **sanctions / legal** conclusions need purpose-built screening and counsel.  
- **Rate limits / CUs** — Design retries and budgets using current **Compute Units** documentation.  
- **Accuracy** — Token lists, pricing, and spam filters evolve; confirm parameters (e.g. `exclude_spam_tokens`) in live API references.

**Goal:** stable pointers to **[docs.sim.dune.com/llms.txt](https://docs.sim.dune.com/llms.txt)** and **[openapi.json](https://docs.sim.dune.com/openapi.json)** for **Dune Sim** and **Dune Analytics API** work in on-chain analytics and agent integrations.
