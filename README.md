# Venkata Kishore Kotti

### AI Engineer — Building Production Agentic Systems

📍 Antwerp, Belgium · open to remote

> I came to AI from *inside* enterprise systems — SAP integrations and cross-region delivery across aerospace, medical-device, and manufacturing environments, where shipping means surviving an audit, not a demo. That's the lens I build with now: agentic systems designed for the constraints most prototypes skip — tenant isolation, deterministic guardrails, provider-agnostic deployment, an audit trail behind every decision.
>
> **Four production-grade AI systems, designed and shipped independently over the last two years.**
>
> *Not because I already have the title — because this is the work I want to do.*

---

### What I build

- **Multi-agent orchestration** — typed task DAGs, deterministic critic gates, fail-closed guardrails
- **Production RAG** — hybrid retrieval, rerankers, and a grounding check every claim has to pass
- **Enterprise-grade infrastructure** — tenant isolation, provider-agnostic deployment, audit trails

---

### Featured work

| Project | What it is | The engineering call |
|---|---|---|
| **[Enterprise Vendor Governance](https://github.com/kish21/agenticRag-rfp)** | A 9-agent LangGraph pipeline that evaluates RFP vendor proposals end-to-end | A deterministic critic gates *every* agent — an LLM can be prompted into confirming grounding that doesn't exist; a deterministic check cannot. 3-layer tenant isolation: JWT · Postgres RLS · Qdrant filters. |
| **[MarkVid + Master Director](https://github.com/kish21/markvid-product-docs)** | An 8-agent, 3-tier system for marketing-video production | A two-stage prompt engine extracts "Context DNA" from the brief and seeds it downstream, so eight agents stay on-message instead of drifting. |
| **[Module31](https://github.com/kish21/module31-showcase)** | Privacy-first SaaS — 30+ media tools on ephemeral GPU | Ephemeral Modal GPU with zero permanent file storage — privacy as an architecture decision, not a policy line. |
| **[Autonomous Dev Platform](https://github.com/kish21/agentplatform-showcase)** | A self-healing Code / Test / Review agent loop | 2-of-3 model consensus before any fix is applied; exposed as MCP tools that drop into Cursor or Claude Code. |

---

### Stack

**Agents** &nbsp;`LangGraph` · `LangChain` · `CrewAI` · `MCP`
**Models** &nbsp;`Claude` · `GPT-4o` · `Qwen 2.5` · `Gemini` *(multi-model consensus)*
**RAG** &nbsp;`Qdrant` · `Pinecone` · `FAISS` · `BGE reranker` · `HyDE`
**Backend** &nbsp;`FastAPI` · `Python` · `TypeScript` · `Docker` · `Modal` *(serverless GPU)*
**Cloud** &nbsp;`AWS` · `Azure` *(EU residency)* · `GCP`
**Enterprise** &nbsp;`SAP S/4HANA` · `BTP` · `CPI` · `Windchill PLM`

---

### Also worth a look

- **[product-playbook](https://github.com/kish21/product-playbook)** — a principle-driven Claude Code skill set: 15 commands that take an idea → shipped, one phase at a time, with evidence-based gates that keep both you and the AI disciplined.
- **[product-toolkit](https://github.com/kish21/product-toolkit)** — my personal library of reusable slash commands for building production-grade products.

---

### Find me

[Portfolio](https://kish21.github.io) · [LinkedIn](https://linkedin.com/in/kishorekv2) · kishorekv2@gmail.com

