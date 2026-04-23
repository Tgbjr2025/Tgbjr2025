# Thomas Bateman · DOMINUS AXIS

> Building agentic AI systems that plan, execute, and audit their own work.

🌐 **[dominusaxis.com](https://dominusaxis.com)** · ✉️ admin@dominusaxis.com

## What I'm building

**DOMINUS AXIS** is a production agentic platform with four running subsystems:

- **Signal Engine** — LightGBM + XGBoost + Optuna across 25 crypto markets, 128 trained models, live accuracy scoring
- **Command Center** — admin control room, 52 microservices, 10-layer memory, tiered-LLM cost router
- **APEX Agent** — 1,026 tool functions across 258 files, 47 modes, multi-agent DAG orchestrator
- **Bounty Hunter** — ML-powered security scanner (Slither, Semgrep, Mythril, Claude deep-review) for smart contracts and general code

~154,000 lines of Python, running under nginx + systemd on a hardened OCI instance.

## The 10-layer memory stack

Agents stay coherent across long-running workflows by injecting compact slices of ten memory layers into every LLM call:

| Layer | Purpose |
|---|---|
| L1 Chat history · L2 Action log · L3 Session | Short-term conversational + operational state |
| L4 Neural DB · L5 Intelligence registry | Semantic vector search + ML model metadata |
| L6 Pattern DB · L7 Execution KB | Learned patterns + static/learned procedures |
| L8 Compressor · L9 Failure bridge | Digests + lessons from past failures |
| L10 Project state | Active goals, milestones, revenue targets |

## Current focus

- Autonomous revenue engine (trading signals → SaaS → bounty hunting)
- Agentic invoicing Co-Pilot (see my [GovtInvoice proposal](https://github.com/seetadev/GovtInvoice/issues/37))
- ERC-8004 + x402 + MPP payment-protocol adapters
- Multi-chain (Optimism, Base, Ethereum, Starknet) via viem/wagmi

## Stack

Python · FastAPI · React · Ionic · TypeScript · SQLite · Postgres · nginx · systemd · LightGBM · XGBoost · Claude (Opus/Sonnet/Haiku) · Groq · Solidity · viem

## Contact

For collaboration, contract work, or security audits — **admin@dominusaxis.com**.
