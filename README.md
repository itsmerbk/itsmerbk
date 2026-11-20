# Hi, I'm Bharath Kumar (`@itsmerbk`)

**Computer Science & Engineering Undergraduate @ SRM Institute of Science and Technology**  
Building low-latency backend infrastructure, AI observability & security middleware, and fault-tolerant distributed tooling.

---

### Career-Focused Systems, Backend & AI Platform Projects

| Repository | Engineering Problem & Architecture | Verified Benchmark / CI |
| :--- | :--- | :--- |
| **[`trace-lens`](https://github.com/itsmerbk/trace-lens)** | Production AI agent observability & automated eval engine with `@trace_span` SDK, waterfall timeline UI, and CI cost/accuracy regression gates (`Python`, `FastAPI`, `SQLite`). | Automated CI eval gate · Token cost & latency waterfall |
| **[`idempo-queue`](https://github.com/itsmerbk/idempo-queue)** | Fault-tolerant webhook & job broker using **Java 21 Virtual Threads**, atomic idempotency keys, lease crash-recovery reapers, exponential backoff, and DLQ replay (`Java 21`, `JDBC`). | 200-webhook burst & worker-crash recovery · GitHub Actions CI |
| **[`perm-graph`](https://github.com/itsmerbk/perm-graph)** | Google Zanzibar-style Relationship-Based Access Control (ReBAC) graph engine with cycle-safe DFS, explainable proof paths, and Zookie revision cache invalidation (`Python`, `FastAPI`). | **576,173 checks/sec** cached · **0.019 ms** p99 cold graph traversal |
| **[`logpulse-sre`](https://github.com/itsmerbk/logpulse-sre)** | Streaming log anomaly detector & automated `git log -p` root-cause correlator using variable masking template clustering and rolling Z-score spike detection (`Python`, `Rich`). | Automated suspect commit & diff line ranking · GitHub Actions CI |
| **[`sentinel-proxy`](https://github.com/itsmerbk/sentinel-proxy)** | Real-time LLM tool-call firewall & prompt injection sandbox with Base64 payload decoding, path/shell guards, and SQLite WAL audit telemetry (`Python`, `FastAPI`, `Rich`). | **0.06 ms** avg inspection latency · **100%** red-team suite pass rate |
| **[`pulse-jvm`](https://github.com/itsmerbk/pulse-jvm)** | Zero-bloat macOS process & network socket profiler streaming native BSD `ps`/`lsof` metrics into indexed SQLite time-series batches with live Unicode CPU sparklines (`Java 21`, `JDBC`). | **0.20 ms** SQLite batch writes · Automated CPU/RSS spike detection |
| **[`cite-verify`](https://github.com/itsmerbk/cite-verify)** | Offline PDF research engine combining SQLite FTS5 (BM25) retrieval with a deterministic sentence & numeric grounding verifier to flag LLM hallucinations (`Python`, `PyMuPDF`). | Page-level verbatim citations & numeric mismatch interception |
| **[`rate-guard`](https://github.com/itsmerbk/rate-guard)** | Thread-safe **Token Bucket**, **Sliding Window Log**, and **Leaky Bucket** rate limiters built from scratch with an HTML5 Canvas burst visualizer (`Python`, `FastAPI`, `AsyncIO`). | **7,379 req/s** throughput · **0.14 ms** p99 latency (3,000 concurrent reqs) |

---

### Core Stack

* **Languages:** Python, Java (21+ Virtual Threads), SQL, JavaScript, HTML/CSS
* **Backend & Distributed Systems:** FastAPI, JDBC, Multithreading (`ExecutorService`), Idempotency, Rate Limiting, ReBAC Graph Authorization, Docker, GitHub Actions CI
* **Databases & Storage:** SQLite (WAL Mode, FTS5 Full-Text Search, Composite Indexing)
* **AI Infrastructure & SRE:** LLMOps Tracing & Evals, Prompt Injection Defense, Deterministic RAG Verification, Log Anomaly & Root-Cause Analysis

---

### Certifications & Technical Initiatives

* **HackerRank Certified:** Python & Java Skill Certifications
* **ISRO (IIRS):** Remote Sensing & Geospatial Distance Learning Certification
* **Hackathons & Bootcamps:** IBM Z Datathon 2026 (*TruthShield*), SUSTAIN Agentic Bootcamp 2026, Finlatics Full-Stack Development with AI
