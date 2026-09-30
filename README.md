<h1 align="center">Jinson E B</h1>
<p align="center">
Backend & AI Systems Engineer · Production AI pipelines · Enterprise data systems
</p>

---

I take messy domain problems — insurance claims, HR, finance — and build backend systems that stay understandable as they grow. I care more about how a system holds up in its third year than how clever it looked in its first week.

### What I've built

- **AI-assisted claims validation pipeline** — sole architect. Cut claim turnaround from **7–8 days to ~half a day** at 3–4K claims/month. FastAPI, self-hosted LLMs (vLLM), Oracle queue-table processing, full observability stack. Lead a small team of junior engineers through phased client delivery.
- **Vehicle damage image analysis** — vision-model pipeline with Pydantic contracts, perceptual-hash dedup, and cross-image consistency checks.
- **Claims eval harness** — deterministic scoring + LLM-as-judge, Postgres-backed, with regression gates before anything ships.
- **Enterprise data plumbing** — Oracle PL/SQL for payroll-to-finance posting, reconciliation, and multi-branch reporting.
- **Open source** — maintainer on [Meshery](https://github.com/meshery/meshery) (CNCF).

### How I work

- **Maintainable over clever.** Code should make sense to whoever inherits it.
- **Fit the tool to the constraint.** Sometimes that's Kafka; sometimes it's an Oracle table used as a queue.
- **If it's in production, it's observable.** Logs, metrics, traces — and evals for anything with an LLM in it.
- **Ship in phases.** Small, verifiable increments with the client in the loop.

### Stack

| | |
|---|---|
| **Backend** | C# / .NET · Python (FastAPI) · Go |
| **Data** | Oracle PL/SQL · PostgreSQL · Redis · Qdrant · Neo4j |
| **AI** | vLLM · Qwen · OpenAI / Gemini / Claude APIs · RAG · LLM evals |
| **Infra** | Docker · Kafka / RabbitMQ · AWS · Prometheus · Grafana · Loki · OpenTelemetry |
| **Frontend** | Angular · React |

### Connect

📫 jinsoneb@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/jinsoneb)
