# Péter Berekvölgyi

**Senior software engineer (~10 yrs).** Production agentic AI · Backend systems · Web3.

## About me

- 🤖 **Currently shipping production agentic-AI systems at R34dy zrt.** on the [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-python) and [Pydantic AI](https://github.com/pydantic/pydantic-ai) for analysis of large enterprise codebases and documents. Dozens of parallel subagents with per-server MCP wrappers, [Milvus](https://milvus.io) graph-RAG, [Logfire](https://pydantic.dev/logfire) + [Opik](https://www.comet.com/site/products/opik/) observability, and output-validation guardrails driving retry-with-feedback loops.
- 🧠 **Founding engineer at [Mercury Protocol](https://github.com/mercury-protocol/litepaper)** — decentralized AI-training network with on-chain proof-of-training. Co-designed the protocol; built the TEE component: Gramine SGX enclave with EPID remote attestation and ECDH/Fernet-encrypted data + model channels. See [`mcy-sgx-gramine`](https://github.com/mercury-protocol/mcy-sgx-gramine).
- ⛓️ **Web3 / smart contracts (Cyfrin Updraft coursework)** — Solidity, Foundry, EVM. Pinned: collateralized stablecoin with Foundry invariant testing + Slither in CI, Sepolia-verified. Full course index in [Learning & coursework](#learning--coursework).
- 🛠️ Previously: backend at [CoinPanel](https://coinpanel.com) (multi-exchange crypto trading on GCP, 8 exchanges including Binance/Coinbase/Kraken, FastAPI + asyncio + Bigtable + Pub/Sub, thousands of paid subscribers); backend at [Finmatics](https://finmatics.com) (Django / PostgreSQL bookkeeping platform); solo crypto trading bot (side project); embedded ASIL-D automotive C at [thyssenkrupp](https://www.thyssenkrupp.com/) (electric-steering systems).

## Selected work

- **[mcy-sgx-gramine](https://github.com/mercury-protocol/mcy-sgx-gramine)** — Mercury Protocol's confidential compute node (MVP). Two building blocks for the off-chain node: synchronous data-parallel PyTorch training over file-based IPC, and a Gramine SGX enclave with EPID remote attestation and ECDH/Fernet-encrypted data + model channels. Python · Intel SGX · Gramine · asyncio · multiprocessing.
- **[cyfrin-advanced-foundry-defi-stablecoin](https://github.com/berekvolgyipeter/cyfrin-advanced-foundry-defi-stablecoin)** — Exogenously-collateralized USD-pegged ERC20 stablecoin in Foundry. Over-collateralized 200% with WETH/WBTC, Chainlink-priced, 10% liquidation bonus. Foundry invariant testing · Slither in CI · Sepolia-verified.
- **[dotclaude](https://github.com/berekvolgyipeter/dotclaude)** — How I work with Claude Code: rules, skills, sub-agents, hooks, daily-loop MCP servers (`context7`, `sequential-thinking`, `claude-context`, `serena`). Symlinked into `~/.claude/` so changes propagate across every project I touch.

## Learning & coursework

- [cyfrin-foundry-projects](https://github.com/berekvolgyipeter/cyfrin-foundry-projects) — Index of completed [Cyfrin Updraft](https://updraft.cyfrin.io/courses/advanced-foundry) project repos (AA, CCIP, DAO, ERC20, Merkle airdrop, NFT, VRF lottery, stablecoin, UUPS).
- [webservice-template](https://github.com/berekvolgyipeter/webservice-template) — Opinionated Flask / SQLAlchemy / PostgreSQL backend template (Docker Compose + Kubernetes / minikube).

## Find me

- 💼 [LinkedIn](https://linkedin.com/in/peterberekvolgyi)
- 📍 Budapest, Hungary · Remote (CET)
