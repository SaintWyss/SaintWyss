<h1 align="left">Santiago Vicente Scacciaferro Wyss 👋</h1>

<h3 align="left">
  GenAI & Systems Engineer · <b>Production-Grade RAG</b> · <b>Secure Systems</b> · <b>Observability</b>
</h3>

<p align="left">
  <i>“I build AI systems where evaluation isn't an afterthought, but the foundation — pro engineering over fragile demos.”</i>
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/santiago-vicente-scacciaferro-wyss-48b69a223/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:sanv.swyss@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/SaintWyss" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=SaintWyss&style=for-the-badge&color=ff2d55" alt="profile views" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Evaluation--First-6E40C9?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Clean%20%2F%20Hexagonal-2EA043?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Security--First-FF2D55?style=for-the-badge&logo=securityscorecard&logoColor=white" />
  <img src="https://img.shields.io/badge/Offline--First-00C2FF?style=for-the-badge&logo=linux&logoColor=white" />
</p>

---

<table>
<tr>
<td width="62%" valign="top">

<h2>🧠 About Me</h2>

<p>
  I’m a <b>4th-year Systems Engineering</b> student at <b>UTN FRRe</b>, building systems where <b>quality</b>, <b>security</b>, and <b>measurement</b> are non-negotiable.
</p>

<p>
  <b>⚙️ GenAI / RAG Engineering</b><br/>
  Hybrid retrieval, reranking, and grounded generation with citations.
</p>

<p>
  <b>📏 Evaluation-First</b><br/>
  MRR / Recall@k / NDCG, reproducible suites, CI regressions tracked by commit/SHA.
</p>

<p>
  <b>🛡️ Security-First</b><br/>
  RBAC/ACL, scoped access (anti-IDOR), defensive limits (fail-fast, anti-OOM).
</p>

<p>
  <b>🧱 Architecture</b><br/>
  Clean / Hexagonal, SOLID/GRASP, strict boundaries, typed errors.
</p>

<p>
  <b>🔭 Workflow & Observability</b><br/>
  WSL/Linux, structured logging, deterministic offline-first tooling, strict PR discipline (1 capability = 1 PR).
</p>

</td>
<td width="38%" valign="top">

<h2>📊 GitHub</h2>

<p>
  <img src="https://streak-stats.demolab.com?user=SaintWyss&theme=tokyonight&hide_border=true" width="100%" alt="github streak" />
</p>

</td>
</tr>
</table>

---

<h2>🛠️ Core Engineering Principles</h2>

<ul>
  <li><b>🎯 Data-Driven Optimization</b> — measurable deltas, not intuition. Benchmarks tracked by commit/SHA; if it doesn’t improve metrics, it doesn’t merge.</li>
  <li><b>🧭 Architecture Rigor</b> — Clean/Hexagonal + SOLID/GRASP. Business logic fully decoupled from vendors (LLMs / Vector DBs).</li>
  <li><b>🧨 Security by Design</b> — prompt injection defense, granular access control (RBAC/ACL), data-leak mitigation (anti-IDOR).</li>
  <li><b>🧪 CI/CD & Repo Discipline</b> — contracts, types, tests, and performance regressions validated in CI; small incremental PRs.</li>
</ul>

---

<h2>⚙️ Evaluation-First CI/CD</h2>

```mermaid
flowchart TD
  A[Git PR] --> B{CI/CD Gates}
  B --> C[Linter & Typed Errors]
  B --> D[Security & RBAC Tests]
  B --> E[RAG Eval Suite]
  E --> F((MRR & NDCG))
  F -->|Delta < 0 baseline| G[❌ Block Merge]
  F -->|Delta ≥ 0 baseline| H[✅ Allow Merge]

  style G fill:#d73a49,stroke:#333,stroke-width:2px,color:#fff
  style H fill:#2ea043,stroke:#333,stroke-width:2px,color:#fff
  style F fill:#6e40c9,stroke:#333,stroke-width:2px,color:#fff
```

---

<h2>🏗️ System Architecture: Production RAG</h2>

```mermaid
graph LR
  subgraph "Ingestion Pipeline (Offline)"
    A[Raw Data] -->|Connectors| B(Deterministic Chunking)
    B --> C(Embedding Model)
    C -->|Vector + Metadata| D[(pgvector / PostgreSQL)]
  end

  subgraph "Retrieval & Generation (Online)"
    E[User Query] --> F(Hybrid Search: BM25 + Semantic)
    D -.-> F
    F --> G(Cross-Encoder Reranker)
    G -->|Top K Context| H{Guardrails + Eval}
    H -->|Groundedness Check| I[Response w/ Citations]
  end

  style D fill:#336791,stroke:#ffffff,stroke-width:2px,color:#ffffff
  style H fill:#6e40c9,stroke:#ffffff,stroke-width:2px,color:#ffffff
```

---

<table>
<tr>
<td width="58%" valign="top">

<h2>🚀 Featured Projects</h2>

<h3>🧠 RAG Corp</h3>

<p>
  Production-grade knowledge platform focused on <b>evaluation</b>, <b>security</b>, and <b>scale</b>.
</p>

<ul>
  <li><b>Ingestion</b>: deterministic pipeline + connectors</li>
  <li><b>Retrieval</b>: hybrid (semantic + BM25) + reranking</li>
  <li><b>Evaluation</b>: groundedness/faithfulness + regression gates</li>
  <li><b>Infra</b>: defensive limits, CI gates, observability</li>
</ul>

<p align="left">
  <a href="https://github.com/SaintWyss/rag-corp" target="_blank">
    <img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="View Repository" />
  </a>
</p>

<h3>🧩 Backend & Platform Work</h3>

<ul>
  <li>RBAC/ACL, scoping, typed errors, safe logs</li>
  <li>DTO/contract discipline, fail-fast validations</li>
  <li>reproducible CLI tooling, templates, playbooks</li>
</ul>

<p align="left">
  <a href="https://github.com/SaintWyss?tab=repositories" target="_blank">
    <img src="https://img.shields.io/badge/View%20Repositories-6E40C9?style=for-the-badge&logo=github&logoColor=white" alt="View Repositories" />
  </a>
</p>

</td>
<td width="42%" valign="top">

<h2>🧬 RAG Evaluation Stack</h2>

| Layer          | Target metrics                        | Methodology               |
| :------------- | :------------------------------------ | :------------------------ |
| **Retrieval**  | MRR, Recall@k, NDCG, Latency          | Benchmarks + ablations    |
| **Reranking**  | Win-rate, NDCG lift                   | Baselines + comparisons   |
| **Generation** | Groundedness, Faithfulness, Relevance | LLM-as-a-judge + datasets |
| **System**     | Cost, Limits, Error rate              | Observability + defenses  |

</td>
</tr>
</table>

---

<h2>🧰 Tech Stack & Tools</h2>

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-111111?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=111111" />
</p>

---

<h2>💬 Languages</h2>

* 🇪🇸 <b>Spanish</b>: Native
* 🇺🇸 <b>English</b>: Professional working proficiency (C1 / technical)
