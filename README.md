<div align="center">

<!-- ANIMATED WAVE HEADER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FFF,50:2575FC,100:00D4FF&height=220&section=header&text=Jai%20Raj%20Choudhary&fontSize=58&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20NLP%20%E2%80%A2%20LLM%20Systems%20%E2%80%A2%20San%20Francisco%2C%20CA&descAlignY=58&descSize=19"/>

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1200&color=00D4FF&center=true&vCenter=true&random=false&width=680&height=65&lines=Building+Production+AI+Systems+%F0%9F%A4%96;NLP+%26+LLM+Engineer+%40+StackAI+(Y+Combinator);RAG+%7C+Vector+DBs+%7C+LLM+Pipelines+%7C+MLOps;Featured+in+Times+of+India+%F0%9F%97%9E%EF%B8%8F;M.S.+AI+%E2%80%94+Illinois+Institute+of+Technology+%F0%9F%8E%93;9+to+9%2C+Six+Days+a+Week+%E2%80%94+and+Worth+Every+Second" alt="Typing SVG" />
</a>

<br/>

<p>
  <a href="https://www.linkedin.com/in/jai-raj-choudhary-a6843a171/">
    <img src="https://img.shields.io/badge/LinkedIn-Jai%20Raj%20Choudhary-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=jairajc&style=for-the-badge&color=7B2FFF&label=PROFILE+VIEWS"/>
  &nbsp;
  <img src="https://img.shields.io/badge/📍-San%20Francisco%2C%20CA-FF6B6B?style=for-the-badge"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-00D4FF?style=for-the-badge"/>
</p>

<p>
  <img src="https://img.shields.io/github/followers/jairajc?label=Followers&style=flat-square&color=7B2FFF&labelColor=0D1117"/>
  &nbsp;
  <img src="https://img.shields.io/github/last-commit/jairajc/jairajc?label=Last%20Active&style=flat-square&color=00D4FF&labelColor=0D1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/YC%20Backed-StackAI-FF6600?style=flat-square&labelColor=0D1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Experience-3%2B%20Years%20AI-7B2FFF?style=flat-square&labelColor=0D1117"/>
</p>

</div>

---

<div align="center">

## 📰 As Featured In

<a href="https://timesofindia.indiatimes.com/etimes/trending/meet-jai-raj-choudhary-indian-origin-techie-who-says-working-in-ai-startup-9-to-9-six-days-a-week-changed-his-life/amp_articleshow/128782911.cms">
  <img src="https://img.shields.io/badge/Times%20of%20India-Read%20My%20Story%20%E2%86%92-FF6600?style=for-the-badge&logoColor=white" height="40"/>
</a>
&nbsp;
<a href="https://www.aol.com/articles/pivoted-software-engineering-ai-taking-101001702.html">
  <img src="https://img.shields.io/badge/Business%20Insider-Featured%20Engineer-212529?style=for-the-badge&logoColor=white" height="40"/>
</a>

<br/>
</div>

---

## `> whoami`

```python
class AIEngineer:
    def __init__(self):
        self.name        = "Jai Raj Choudhary"
        self.role        = "AI Engineer II @ StackAI (Y Combinator)"
        self.location    = "San Francisco, CA"
        self.education   = ["M.S. AI — Illinois Institute of Technology",
                            "B.Tech CS — UPES Dehradun"]
        self.experience  = "3+ years"
        self.stack       = ["RAG Pipelines", "LLMs", "Vector DBs",
                            "Temporal", "Kafka", "Kubernetes", "AWS"]
        self.philosophy  = "Ship fast. Learn faster. Obsess over the problem."

    def say_hi(self):
        print("Thanks for stopping by — let's build something intelligent.")

me = AIEngineer()
me.say_hi()
```

---

## `> story.md`

I made a bet on AI early — pivoting from software engineering to ML when the path wasn't obvious.

The **best decision I made** was joining **StackAI** for a role I didn't quite have all the experience for yet. I learned by building real systems, in production, for real clients — at a pace that forces you to grow.

In San Francisco, the culture hits differently. Every coffee shop has two founders at the table next to you. The people around you are solving hard problems, and that energy is contagious. It's **9-to-9, six days a week** — and I wouldn't trade it.

I specialize in **NLP pipelines**, **LLM systems**, and **document intelligence** — turning unstructured data into decisions that drive real revenue. My work at **Lineal Services, LLC** led to substantial revenue growth through intelligent document processing and real-time ML data frameworks.

> 🎓 &nbsp; M.S. AI · Illinois Institute of Technology &nbsp;|&nbsp; 📍 San Francisco, CA

---

## `> ./architecture`

**RAG Pipeline — Production**

```mermaid
flowchart LR
    A([User Query]) -->|embed| B[SQL Pre-filter\n+ Embedder]
    B -->|vector search| C[(HNSW Search\nWeaviate · Pinecone)]
    C -->|rerank| D[BM25 Reranker\n+ Context Builder]
    D -->|generate| E([LLM Response\nGPT-4 · Claude])

    style A fill:#161B22,stroke:#7B2FFF,stroke-width:2px,color:#E6EDF3
    style B fill:#161B22,stroke:#7B2FFF,stroke-width:2px,color:#E6EDF3
    style C fill:#161B22,stroke:#00D4FF,stroke-width:2px,color:#E6EDF3
    style D fill:#161B22,stroke:#7B2FFF,stroke-width:2px,color:#E6EDF3
    style E fill:#161B22,stroke:#00D4FF,stroke-width:2px,color:#E6EDF3

    linkStyle default stroke:#484F58,stroke-width:2px
```

**Multi-Agent Orchestration System**

```mermaid
graph TB
    PA["Parser Agent\nApache Tika · chunking"] --> ORC
    IA["Indexer Agent\nKafka · embed · index"] --> ORC
    ORC(["Orchestrator\nTemporal · Task Routing\nRedis Backpressure"])
    ORC --> RA["Retriever Agent\nHNSW · BM25 hybrid"]
    ORC --> LA["LLM Agent\nGPT-4 · Claude"]
    R[("Redis\nper-org limits")] -.-> ORC
    P[("Postgres\nltree virtual FS")] -.-> ORC
    K[("Kafka DLQ\ncircuit breaker")] -.-> ORC

    style ORC fill:#161B22,stroke:#00D4FF,stroke-width:3px,color:#E6EDF3
    style PA fill:#161B22,stroke:#7B2FFF,stroke-width:1.5px,color:#E6EDF3
    style IA fill:#161B22,stroke:#7B2FFF,stroke-width:1.5px,color:#E6EDF3
    style RA fill:#161B22,stroke:#00D4FF,stroke-width:1.5px,color:#E6EDF3
    style LA fill:#161B22,stroke:#00D4FF,stroke-width:1.5px,color:#E6EDF3
    style R  fill:#161B22,stroke:#484F58,color:#8B949E
    style P  fill:#161B22,stroke:#484F58,color:#8B949E
    style K  fill:#161B22,stroke:#484F58,color:#8B949E
```

---

## `> ls skills/`

<div align="center">

<p><b>Languages</b></p>
<img src="https://skillicons.dev/icons?i=python,java,cpp,js,bash&perline=5" />

<br/><br/>

<p><b>LLM · ML · Deep Learning</b></p>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow&perline=2" />
&nbsp;
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/GPT--4-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-CC785C?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Llama%202%2F3-0467DF?style=for-the-badge&logo=meta&logoColor=white" />

<br/><br/>

<p><b>RAG · Vector Databases</b></p>
<img src="https://img.shields.io/badge/Weaviate-00BB7F?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/HNSW-7B2FFF?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/BM25%20Hybrid-2575FC?style=for-the-badge&logoColor=white" />

<br/><br/>

<p><b>Data Pipelines · Streaming</b></p>
<img src="https://skillicons.dev/icons?i=kafka&perline=1" />
&nbsp;
<img src="https://img.shields.io/badge/Temporal-000000?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />

<br/><br/>

<p><b>Infrastructure · Cloud</b></p>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,redis,postgres,aws,azure,gcp&perline=7" />

<br/><br/>

<p><b>APIs</b></p>
<img src="https://skillicons.dev/icons?i=fastapi,graphql&perline=2" />
&nbsp;
<img src="https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/REST-009688?style=for-the-badge&logoColor=white" />

</div>

---

## `> cat ./experience`

<details>
<summary><b>StackAI (Y Combinator) — AI Engineer II</b> &nbsp; <code>May 2025 – Present · San Francisco, CA</code></summary>

<br/>

> No-code platform to build and deploy production AI agents at scale · YC-backed

| What I Built | Impact |
|---|---|
| Scalable RAG pipeline — SQL pre-filtering → vector search | ↓ p95 latency &nbsp; ↓ cost/query |
| Temporal workflow orchestration: ingest, parse, index, enrich metadata | ↑ indexing throughput &nbsp; ↓ failure rates |
| Multi-tenant HNSW + hybrid vector layer, tuned timeouts & retries | ↑ tail reliability under prod load |
| Postgres `ltree` virtual file system with UTF-8-safe materialized paths | Hierarchical queries at scale |
| Redis backpressure with per-org / per-connector concurrency limits | ↓ rate-limit errors &nbsp; ↑ job success |
| High-throughput async data loaders — batching, caching, normalization | ↑ retrieval precision &nbsp; ↓ cost/query |

<br/>
</details>

<br/>

<details>
<summary><b>Lineal Services, LLC — Data Scientist</b> &nbsp; <code>May 2023 – Jan 2024 · Chicago, IL</code></summary>

<br/>

> Production ML systems for enterprise document processing and intelligent automation

| What I Built | Impact |
|---|---|
| Multimodal document structuring engine — LangChain + GPT-4 | **50K+ enterprise tasks/day** |
| Real-time inference pipelines — Kafka + TensorFlow | **sub-200ms latency** · 3M+ msgs/day |
| Containerized agent orchestration on Docker + Kubernetes | **35% infra cost reduction** · 99.9% uptime |
| RAG-enhanced agents with Pinecone | **28% fewer hallucinations** · 94% task accuracy |

<br/>
</details>

<br/>

<details>
<summary><b>SCS Lab, Illinois Institute of Technology — AI Research Engineer</b> &nbsp; <code>Jan – May 2022 · Chicago, IL</code></summary>

<br/>

> Multimodal AI research for predictive healthcare applications

| What I Built | Impact |
|---|---|
| Multimodal pipelines — CV + time-series for predictive healthcare | Research-scale diagnostics |
| Hybrid CNN-RNN architectures for medical imaging | **+15% diagnostic accuracy** |
| Apache Airflow research pipelines with automated validation | Reproducible data workflows |

<br/>
</details>

---

## `> ls ./projects/`

<details>
<summary><b>CiteGuard QA</b> — Policy-Aware · Citation-First RAG API &nbsp; <img src="https://img.shields.io/badge/FastAPI-Kubernetes-009688?style=flat-square&logo=fastapi&logoColor=white"/></summary>

<br/>

**Stack:** `FastAPI` · `k-NN hybrid ranking` · `OPA` · `Docker` · `Kubernetes` · `Distributed Tracing`

- Citation-first answering via hybrid ranking + reranking — every response grounded with verifiable evidence
- Query-time authorization with attribute-based access control enforcing tenant and document-level permissions
- Shipped `Recall@k`, `MRR`, and groundedness evaluation with distributed tracing to tune tail latency and reduce unit cost

<br/>
</details>

<br/>

<details>
<summary><b>IndexPulse</b> — Event-Driven Ingestion & Index Refresh Platform &nbsp; <img src="https://img.shields.io/badge/Airflow-Kafka-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/></summary>

<br/>

**Stack:** `Airflow` · `Kafka` · `Kubernetes Jobs` · `Apache Tika` · `Dead-letter Queues` · `Circuit Breakers`

- Incremental sync with checkpoints and deduplication — supports continuous updates and safe backfill replays
- parse → chunk → embed → index orchestrated as Airflow DAGs on Kubernetes for horizontal scalability
- Kafka consumer groups, DLQs, and circuit breakers maximize throughput under throttling and flaky upstreams

<br/>
</details>

---

## `> ./github-stats.sh`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://github-readme-stats.vercel.app/api?username=jairajc&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00D4FF&icon_color=7B2FFF&text_color=C9D1D9" />
  <img height="180em"
    src="https://github-readme-stats.vercel.app/api?username=jairajc&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" />
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=jairajc&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D4FF&text_color=C9D1D9" />
  <img height="180em"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=jairajc&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://streak-stats.demolab.com?user=jairajc&theme=tokyonight&hide_border=true&background=0D1117&ring=7B2FFF&fire=00D4FF&currStreakLabel=00D4FF&sideLabels=8B949E&dates=6E7681" />
  <img src="https://streak-stats.demolab.com?user=jairajc&theme=tokyonight&hide_border=true" />
</picture>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=jairajc&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=4" alt="GitHub Trophies" />

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://github-readme-activity-graph.vercel.app/graph?username=jairajc&theme=tokyo-night&hide_border=true&area=true&bg_color=0D1117&color=00D4FF&line=7B2FFF&point=00D4FF&area_color=7B2FFF&custom_title=Jai's%20Contribution%20Graph" />
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=jairajc&theme=tokyo-night&hide_border=true&area=true&custom_title=Jai's%20Contribution%20Graph" />
</picture>

</div>

---

## `> ./contributions.sh`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/jairajc/jairajc/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/jairajc/jairajc/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub Contribution Snake"
    src="https://raw.githubusercontent.com/jairajc/jairajc/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## `> cat current_focus.yaml`

```yaml
role:
  company:  StackAI (Y Combinator)
  title:    AI Engineer II
  focus:    RAG · LLM Orchestration · Document Intelligence · MLOps

currently_building:
  - Multi-tenant RAG pipelines with SQL pre-filtering and HNSW vector search
  - Temporal-orchestrated ingestion workflows for enterprise document intelligence
  - Redis-backed backpressure systems for high-throughput async AI pipelines

learning:
  - Multi-agent frameworks   →  LangGraph, CrewAI, AutoGen
  - Advanced PEFT techniques →  LoRA, QLoRA, DPO, RLHF
  - Distributed vector ops   →  Weaviate, Qdrant at scale

philosophy: >
  The best way to grow is to take on what scares you.
  Ship fast. Stay curious. Embrace the 9-to-9.

open_to:
  - Senior AI / ML Engineering roles
  - LLM architecture consulting
  - Open-source on RAG, vector search, or agent systems
```

---

<div align="center">

### Let's build something intelligent.

<a href="https://www.linkedin.com/in/jai-raj-choudhary-a6843a171/">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="https://timesofindia.indiatimes.com/etimes/trending/meet-jai-raj-choudhary-indian-origin-techie-who-says-working-in-ai-startup-9-to-9-six-days-a-week-changed-his-life/amp_articleshow/128782911.cms">
  <img src="https://img.shields.io/badge/Read%20My%20Story-Times%20of%20India-FF6600?style=for-the-badge"/>
</a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2FFF,50:2575FC,100:00D4FF&height=120&section=footer"/>

</div>
