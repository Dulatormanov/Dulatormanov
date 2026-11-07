## Hi, I'm Dulat

Applied AI engineer in Almaty, Kazakhstan (UTC+5), open to remote work. I build production LLM agents (LangGraph, RAG, GraphRAG text-to-SQL, voice AI) and the tests and evals that keep them reliable.

### Now: crash-testing LiveKit Agents 2.0

I test what happens to an agent's work when a worker dies, a save fails or a client resends a message.

- [lost-run-effects](https://github.com/Dulatormanov/lost-run-effects): 9 crash and resend tests on LiveKit's own test setup, a Rust fix, and a prototype that stops a payment tool from charging twice after a crash.
- Reported [livekit/agents#8367](https://github.com/livekit/agents/issues/8367), plus findings on [#8200](https://github.com/livekit/agents/pull/8200#issuecomment-6618539267), [#8202](https://github.com/livekit/agents/pull/8202#issuecomment-6627975491) and [#8255](https://github.com/livekit/agents/pull/8255#discussion_r4466170827).
- Fixes: [#8436](https://github.com/livekit/agents/pull/8436) (the fix for #8367, with a regression test) and [#8437](https://github.com/livekit/agents/pull/8437) (baseten STT ignored `stream(language=...)`).

### Work

- **DanAI**, founding AI engineer (2026). I built the GraphRAG text-to-SQL engine behind an analytics platform live with 10+ businesses. Field coverage went from 54% to 88% and selection precision from 40% to 82%. Hybrid search (BM25 + dense + RRF) raised recall@5 from 89% to 98%. Also Temporal workflows and Langfuse tracing.
- **Newo.ai**, contract (2025–2026): production voice AI agents for 10+ US businesses.
- **Monte Group**, co-founder (2024–2026): led 3 developers shipping production AI systems (LangGraph, RAG, WhatsApp and Telegram, CRM).

### Projects

- [ContextOS](https://contextos.pro/): decision memory for engineering teams, built with a friend because we kept hitting this problem at our own jobs. When someone asks why a system works the way it does, ContextOS finds the Slack threads, PRs, tickets, docs and meetings behind the decision and links them into one verified record. I built the GraphRAG decision graph and the Slack, Notion, Jira, Linear and GitHub integrations.
- [agent-spend-guard](https://github.com/Dulatormanov/agent-spend-guard): a guard and eval suite for AI agents that pay. The model proposes, and code decides. It includes a LangGraph integration and an MCP server, tested on 510 code-judged runs across 3 models.
- [right-sized-answers](https://github.com/Dulatormanov/right-sized-answers): evals for when an assistant should answer directly, think, build a report or ask, measured on quality, cost and latency.

**Stack:** Python · LangGraph · FastAPI · PostgreSQL / pgvector · Temporal · Langfuse · Docker / Kubernetes · pytest

**Contact:** dulatpingood@gmail.com · [LinkedIn](https://linkedin.com/in/dulat-ormanov-24964a229)
