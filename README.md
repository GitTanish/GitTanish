### tanish

ai/ml engineer · backend systems · agents & retrieval

i build ai systems that can be tested, checked, and debugged.

i work on the parts that make these systems reliable: execution, retrieval, evaluation, and handling failures.

[portfolio](https://tanishsaroj.me/) · [linkedin](https://www.linkedin.com/in/tanishsaroj) · [email](mailto:tanish.me@outlook.com)

---

### selected work

[**insight**](https://github.com/GitTanish/Insight) — *deterministic analytics agent*  
turns natural-language questions into analysis plans and runs calculations through pandas, scipy, and a read-only duckdb sandbox. independently recomputes key aggregates instead of relying on the model's arithmetic. includes an mcp server and evaluation suite.

[**k-state**](https://github.com/GitTanish/K-State) — *corrective retrieval-augmented generation*  
combines faiss, bm25, and reciprocal rank fusion. checks retrieved evidence before generation, rewriting queries or falling back to web search when local context is weak. includes sentence-level filtering, a fastapi layer, redis caching, and golden-set evals.

[**heimdall**](https://github.com/GitTanish/Heimdall) — *automated github code review agent*  
a fastapi webhook service that verifies github signatures, fetches commit diffs, and posts structured review feedback. processes commits independently so a failure in one review doesn't block the rest of a push.

[**engine**](https://github.com/GitTanish/Engine) — *multi-agent drone defense simulation*  
built on `gym-pybullet-drones`. combines multi-agent target assignment, kalman-filter tracking, proportional-navigation guidance, and behavior-tree decisions. uses seeded experiments and monte carlo evaluation to compare coordination strategies and find problems.

---

### other systems

- [**light-rag**](https://github.com/amMagneto/Light-RAG) — grounded generation with claim-level evidence grading, citation verification, and reproducible evaluation.

---

### working stack

- **languages:** python, sql, bash
- **backend & data:** fastapi, postgresql, duckdb, sqlalchemy, pydantic, docker
- **retrieval & orchestration:** faiss, chromadb, bm25, langgraph

---

**recognition** · 1st place nationwide at smart india hackathon 2025 for a drone-defense simulation developed for bharat electronics limited (bel).
