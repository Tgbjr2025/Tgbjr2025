# hey, i'm tom

independent developer. i build systems that run themselves.

### the agent
a server-resident autonomous agent with its own tool registry — **47 execution modes, 1,000+ tool functions**, multi-agent DAG orchestrator, ssh ops, code patching, schema migrations, ml retraining, infra diagnostics, deploy + rollback, log triage, file integrity checks. it doesn't ask permission unless it has to.

what makes it actually useful is the **11-layer memory stack** sitting underneath it — neural db, action log, semantic chat memory (sentence-transformers), agent intelligence, pattern db, execution kb, code indexer, retriever, compressor, failure bridge, project db. context, decisions, prior runs, error patterns, and operator preferences persist across sessions instead of getting nuked every restart. the agent gets smarter about my infra the longer it runs.

### what i'm working on
- a quantitative platform — **128 trained + calibrated models** (lightgbm + xgboost per-symbol, optuna-tuned), 15-pillar physics-first analysis compiled to c++20 via nuitka + pybind11, llm reasoning tier on top. **52 microservices** behind it, live in production on hardened oci with stripe / paypal / kraken integrations
- smart-contract security tooling — slither + semgrep + mythril + claude deep-review pipeline. ~5,000 line python verifier reproduces publicly-disclosed exploits in a local anvil fork sandbox, regression-tested against a 38-finding corpus from closed code4rena / sherlock / hats / cantina contests
- tiered llm routing across **haiku → sonnet → opus** with prompt caching and full tool-call traceability. cheap calls for cheap thinking, opus for the hard ones, none of them trusted as ground truth

### things i've shipped
- coding agent that operates against a 3.5M+ line codebase, ranks tasks, executes in natural language, persists state in sqlite
- self-healing safeguards: loop detection, phase sentinels, automatic restore from clean clones when an agent stomps a critical file
- four-service autonomous opportunity-scraping + lead-scoring daemon (~50k loc, 571 files, 12 sources scraped on a 4hr cadence, email monitor with telegram alerting)
- dual-ai audio mastering pipeline tuned for hip-hop / rap production
- [stash-plex-bridge](https://github.com/Tgbjr2025/stash-plex-bridge) — one-command windows installer for three production media-server plugins, publicly maintained
- hardened oci infra — dedicated low-privilege ingestion user, boot volume scaling without downtime, ssh key rotation, no data loss across instance lifecycle events
- provisional ip protection on the proprietary physics layer

### how i build
three things i care about in everything i ship:
- **observability** — if it breaks, i can see why in under a minute
- **security** — every merge is scanned; secrets stay out of git
- **cost discipline** — tiered llm routing, aggressive caching, no wasted cycles

operational discipline by default — R1–R11 standing rules: backup-before-every-write, archive-don't-delete, verify-then-claim, no-auto-push from agent loops, mandatory human-review gate before anything external ships.

physics first, ml second, llms as a reasoning layer — never as the source of truth. self-host what i can, encrypt what i can't. if a system can fix itself, it should.

### stack
- **languages** — python, typescript, javascript, rust, solidity, c++20, bash
- **ai / llm** — claude (opus / sonnet / haiku), groq (120b / 70b), tiered routing, prompt caching, sentence-transformers
- **ml** — lightgbm, xgboost, optuna, scikit-learn
- **security** — slither, semgrep, mythril, foundry / anvil, custom regex + AST scanners, claude code (--dangerously-skip-permissions enjoyer)
- **backend** — fastapi, uvicorn, websockets, sqlite, postgres, nuitka, pybind11
- **frontend** — react, svelte, ionic, capacitor, tauri, tailwind, vite
- **web3** — viem, wagmi, multi-chain (optimism, base, ethereum, starknet), ipfs / filecoin / storacha
- **infra** — oracle cloud (e5.flex), autonomous linux 9, nginx, systemd, docker, let's encrypt, github actions
- **field ops** — termux on android, home assistant + esphome for off-keyboard hours

### outside the terminal
post-frame woodworking, ebikes that probably shouldn't exist, and the occasional long cruise out of DTW.

> running on coffee and groq tokens
