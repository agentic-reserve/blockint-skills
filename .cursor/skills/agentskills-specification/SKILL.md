---
name: agentskills-specification
description: Points to the official Agent Skills open-format specification and documentation—agentskills/agentskills on GitHub (spec, docs, reference SDK, example skills) and agentskills.io. Use when the user asks how Agent Skills work, SKILL.md structure, contributing to the ecosystem, or aligning blockint skills with the upstream format—not as a substitute for reading the live specification and LICENSE terms in the upstream repo.
---

# Agent Skills — open format (reference)

**Educational routing only.** This skill does **not** reproduce the specification. Use the **canonical** links below for authoritative text, schema details, and license terms.

## Canonical URLs

| Resource | URL |
|----------|-----|
| **Repository** | [github.com/agentskills/agentskills](https://github.com/agentskills/agentskills) |
| **Site** | [agentskills.io](https://agentskills.io) — documentation hub (per upstream README) |

The upstream project describes **Agent Skills** as a simple, open format: folders of instructions, scripts, and resources that agents can discover for task-specific expertise (“write once, use everywhere”). The repo holds the **specification**, **documentation**, **reference SDK** material, and pointers to **example skills** and community channels (e.g. Discord — see live README).

## What to read there

| Area | Typical use |
|------|----------------|
| **Specification** | Exact format expectations for portable skills |
| **Documentation** | Guides and tutorials |
| **Example skills** | Patterns and breadth of what skills can encode |
| **Contributing** | [CONTRIBUTING.md](https://github.com/agentskills/agentskills/blob/main/CONTRIBUTING.md) in-repo |

## License (summary)

Upstream states: code in the repository is under **Apache-2.0**; documentation under **CC-BY-4.0** — confirm in-repo **LICENSE** and per-directory notices. The format is **community-open**; Anthropic is named as a maintainer in the public README.

## How to combine with blockint

| Need | Skill |
|------|--------|
| This repo’s BI / chain-focused skills | **blockchain-intelligence-playbook** |
| Portable skill format vs domain content | **agentskills-specification** (upstream spec); topical skills here for blockchain intel |

## Guardrails

- **Upstream wins** — If blockint layout ever diverges from the published spec, treat **agentskills** as the portability reference.  
- **No credential paste** — Spec work does not require embedding secrets in skills.

**Goal:** stable pointers to **[agentskills/agentskills](https://github.com/agentskills/agentskills)** and **[agentskills.io](https://agentskills.io)** for **Agent Skills** format and documentation alignment.
