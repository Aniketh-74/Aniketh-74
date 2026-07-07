# Hi, I'm Aniketh 👋

**AI/ML Engineer — production ML systems + agentic RAG** · Bengaluru, India
Pre-Sales Product Technologist & Dell AI Factory SME @ Dell Technologies

I build ML systems that run in production, not notebooks: fraud detection at 590K-transaction scale, drift-triggered retraining pipelines, and Kubernetes-native agentic RAG design for the Kubeflow (CNCF) ecosystem. Currently building **RepoAtlas** — a GraphRAG codebase-onboarding agent with a live "flat RAG vs GraphRAG" eval ablation.

---

### 🔨 Flagship work

| Project                                                                           | What it proves                                                        | Headline numbers                                                                    |
| --------------------------------------------------------------------------------- | --------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| **[FraudShield](https://github.com/Aniketh-74/fraudshield)**                      | Real-time ML at scale — streaming, calibration, interpretability      | 0.954 ROC-AUC · 23ms end-to-end · 590K+ transactions · 12 microservices             |
| **[Agentic RAG on Kubeflow](https://github.com/Aniketh-74/kubeflow-agentic-rag)** | K8s-native multi-agent RAG design (GSoC 2026 proposal) + upstream PRs | 3-collection Milvus architecture · intent routing · KFP/KServe · 30-case test suite |
| **[Credit-Risk Pipeline](https://github.com/Aniketh-74/credit-risk-pipeline)**    | Production MLOps — drift detection → automated retraining             | Airflow DAG · MLflow champion aliasing · CB-PDD (arXiv 2412.10545)                  |
| **RepoAtlas** _(in build)_                                                        | GraphRAG, MCP, eval design                                            | Flat-RAG vs GraphRAG ablation, RAGAS-measured                                       |

_At Dell: built an NLP pipeline (BERTopic — sentence-transformers, UMAP, HDBSCAN, c-TF-IDF) processing 41,000+ enterprise feedback records. Internal codebase — happy to discuss the architecture._

---

### 🌱 Open source — Kubeflow (CNCF)

Active in the `kubeflow/docs-agent` project (the Kubeflow Documentation AI Agent):

- **[PR #173](https://github.com/kubeflow/docs-agent/pull/173)** — 30-case unit test suite for the WebSocket server (addresses [#44](https://github.com/kubeflow/docs-agent/issues/44)): MilvusSearchClient, tool execution, health checks, config validation, message parsing — fully mocked, zero external dependencies. _(under review)_
- **[PR #159](https://github.com/kubeflow/docs-agent/pull/159)** — Milvus connection pooling (singleton pattern) across both servers, eliminating per-request model-load and TCP overhead (addresses [#28](https://github.com/kubeflow/docs-agent/issues/28)). _(CONFIRM STATUS: under review)_
- **[GSoC 2026 design discussion (#59)](https://github.com/kubeflow/docs-agent/issues/59)** — proposed a 3-phase multi-agent RAG architecture; active in #kubeflow-doc-agent on CNCF Slack since March 2026.

---

### 🧰 Stack I actually ship with

**ML/GenAI:** LightGBM · BERTopic · LangGraph · Milvus · pgvector · sentence-transformers · SHAP/TreeSHAP · Optuna · RAGAS
**Infra:** GCP Cloud Run · Docker · Kubernetes (KFP · KServe) · Kafka · Redis · FastAPI · Airflow · MLflow
**Languages:** Python · SQL · JavaScript/React (when the demo needs a face)

---

### 📫 Reach me

[LinkedIn](https://linkedin.com/in/aniketh-mahadik) · anikethani32@gmail.com

_Open to AI/ML Engineer and GenAI Engineer roles — production systems, agents, and evaluation infrastructure._
