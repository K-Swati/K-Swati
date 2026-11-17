## Hi, I'm Swati

AI engineer building production LLM systems: RAG and GraphRAG, tool-calling agents, and the event-driven backends that run them.

Currently building knowledge-graph and LLM systems that let business teams ask natural-language questions over their data. Before that, voice RAG and backend services.

I care about the engineering around the model: rules enforced in code rather than in the prompt, failure handling, tests that run offline in CI, and evaluations that report the honest number.

### Projects

| Project | What it shows |
|---|---|
| **[hellooo-voice-agent](https://github.com/K-Swati/hellooo-voice-agent)** | Voice AI front desk for clinics. OpenAI function calling with validated tools, guardrails that block unconfirmed writes and hand off emergencies, ElevenLabs / OpenAI speech, and a caller simulator for repeatable evaluation. |
| **[rag-hybrid-eval](https://github.com/K-Swati/rag-hybrid-eval)** | Hybrid-search RAG (Qdrant + BM25 + Reciprocal Rank Fusion + reranker) with a benchmark comparing 3 chunking strategies and 4 retrieval modes on hit rate, MRR, nDCG and answer accuracy. |
| **[pocket-pal](https://github.com/K-Swati/pocket-pal)** | Voice companion web app with a safety pipeline in code: crisis messages are detected (rules plus a model classifier) and answered with helplines without reaching the LLM, and replies are verified before they are spoken. LLM and speech providers fall back across free tiers. Admin console with role-based access; unit and Playwright browser tests. |
| **[support-ticket-automation](https://github.com/K-Swati/support-ticket-automation)** | Event-driven ticket triage on AWS SQS: dead-letter queues, exponential-backoff retries, idempotent processing, and an ML classifier that routes low-confidence tickets to human review. Runs locally on LocalStack. |

### Stack

**Languages:** Python, SQL
**LLM / AI:** OpenAI API, LangChain, RAG, GraphRAG, knowledge graphs, scikit-learn, speech-to-text / text-to-speech
**Backend:** FastAPI, REST APIs, async Python, microservices, event-driven design
**Infra:** AWS SQS, LocalStack, Docker, Docker Compose, GitHub Actions, Playwright
**Data:** Qdrant, MongoDB, MySQL

### Contact

[LinkedIn](https://linkedin.com/in/swatik0009) · swatikumari67516@gmail.com · Noida, India
