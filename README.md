<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=28&duration=2800&pause=2000&color=7C6DFA&center=true&vCenter=true&width=940&lines=Hi%2C+I'm+Pradumn+Patidar+%F0%9F%91%8B;Data+Scientist+%7C+AI+Engineer;Building+Production-Grade+AI+Systems;LangGraph+%7C+RAG+%7C+MCP+Agents+%7C+AWS+Bedrock" alt="Typing SVG" />
</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pradumn-patidar/)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C6DFA?style=for-the-badge&logo=google-chrome&logoColor=white)](https://pradumn13.github.io/portfolio/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pradumpatidar@gmail.com)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy_Me_a_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/pradumpatidar)

</div>

---

## 🚀 About Me

I'm a **Data Scientist & AI Engineer** at **Tredence Analytics** (IIT Indore, 2023), building production AI systems at the intersection of agentic workflows, distributed backends, and large-scale data. From LangGraph pipelines, to MCP agents with zero-downtime hot-swapping, to distributed URL shorteners hitting **1,497 req/s** — I ship systems that work at scale.

**What I Do:**
- 🤖 Architect **agentic AI systems** — LangGraph, RAG pipelines, MCP agents, multi-agent orchestration
- ☁️ Build and provision **AWS infrastructure** (Bedrock, OpenSearch, DynamoDB, Lambda) via Terraform
- ⚡ Engineer **high-performance backends** with async I/O, sharding, caching, and event-driven pipelines
- 📊 Instrument systems with **Prometheus + Grafana** — P50/P95/P99 latency, error rate, throughput
- 🔧 Deploy **containerized stacks** on Docker Compose with full observability from day one

**Core Strengths:** GenAI systems, distributed systems, RAG, agentic workflows, AWS, system design.

---

## 💼 Featured Projects

<table>
<tr>
<td width="50%">

### 🤖 [MCP Hot-Swap Multi-Agent Assistant](https://github.com/Pradumn13/mcp-hotswap-agent)
Hot-pluggable AI agent platform with runtime tool extensibility via MCP stdio transport

**Engineering Highlights:**
- **4 isolated MCP servers** exposing **14 tools**; static AST scanning catalogs dormant servers without process spawning
- **Zero-downtime hot-swap** within a single query lifecycle — **3 verified attach/detach cycles**
- `asyncio.gather()` parallel dispatch + Redis registry (Hash + Sorted Set + pipeline atomic ops)
- Param auto-correction heuristic resolving LLM key-name mismatches at zero latency overhead
- **7-container** Docker Compose stack — **6 Prometheus instruments** tracking P50/P95/P99, tool call rate, error rate
- **40+ async pytest** tests across 5 fault modes · **100% local** on llama3.2 · **$0 API cost**

**Tech:** Python, MCP SDK, FastAPI, Ollama, llama3.2, Redis, Docker, Prometheus, Grafana, Streamlit

</td>
<td width="50%">

### 🔗 [Distributed URL Shortener](https://github.com/Pradumn13/distributed-url-shortner)
High-performance distributed URL shortening service with full-stack observability

**Engineering Highlights:**
- **1,497 RPS** with zero errors across **90,000 requests** — sharded across **3 PostgreSQL nodes** via consistent hashing (uhashring)
- Multi-layer caching (Look-Aside + Cache-Null) — **100% cache hit rate**, **2.7ms P50**, **sub-230ms P99**
- Per-shard connection pooling (**50 connections × 3 shards**) sustaining load under 1,500 RPS
- **37% throughput improvement** (1,094 → 1,497 RPS) migrating to fully async `aiohttp + uvloop`
- Redpanda (Kafka-compatible) event-driven analytics pipeline — **20+ metric panels** across **16 containerized services**

**Tech:** FastAPI, PostgreSQL, Redis, Redpanda, Docker, Prometheus, Grafana, aiohttp, uvloop

</td>
</tr>
</table>

---

## 🏢 Experience

**Data Scientist @ Tredence Analytics** · Bengaluru · June 2023 → Present

| Project | Impact |
|---|---|
| **Autonomous Deviation Intelligence System** — LangGraph, Bedrock, OpenSearch, DynamoDB, Terraform | CAPA recommendation: **48 hrs → 23 sec** across **13.5K+ deviations** · **94% match accuracy** · **22% precision lift** |
| **Enterprise Text-to-SQL Platform** — LangChain, FastAPI, PostgreSQL, BigQuery, Snowflake, Milvus | **70% latency reduction** · **60% API cost reduction** across **500+ daily queries** · 4 databases · 5+ LLMs |
| **GraphRAG + Anomaly Detection** — Neo4j, spaCy, Isolation Forest, Autoencoders | KOL identification across **50K+ physician records** · **12% reduction** in batch failures |

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ML/AI & GenAI
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### Cloud & MLOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

### Databases & Streaming
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)
![Redpanda](https://img.shields.io/badge/Redpanda-FF4B4B?style=for-the-badge)

### Monitoring & Tools
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Pradumn13&theme=tokyonight" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Pradumn13&theme=tokyo-night&hide_border=true" alt="Contribution Graph" />
</div>

---

## 🏆 Competitive Programming

| Platform | Handle | Rating / Rank |
|---|---|---|
| ⚡ LeetCode | [Pradumn_89](https://leetcode.com/Pradumn_89/) | Rating **1529** · 450+ problems |
| 🏆 CodeForces | [Pradumn13](https://codeforces.com/profile/Pradumn13) | **Pupil** |
| 🍴 CodeChef | [pradumn_01](https://www.codechef.com/users/pradumn_01) | Rating **1806** · **3★** |
| 📊 Total | — | **1000+ problems solved** |

---

## 🎯 Current Focus

- 🔭 Building **production AI agents** with LangGraph, MCP, and AWS Bedrock
- 🏗️ Deepening expertise in **distributed systems** and **agentic workflow orchestration**
- ☁️ Expanding **AWS + Terraform** infrastructure-as-code practices
- 🤖 Exploring advanced **RAG architectures** and **multi-agent coordination patterns**
- 💬 Ask me about **LangGraph, RAG, MCP agents, AWS Bedrock, distributed systems, caching**

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pradumn-patidar/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pradumpatidar@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C6DFA?style=for-the-badge&logo=google-chrome&logoColor=white)](https://pradumn13.github.io/portfolio/)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy_Me_a_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/pradumpatidar)

</div>

---

<div align="center">

### 💡 "Shipping AI and Distributed Systems that work in production."

![Profile Views](https://komarev.com/ghpvc/?username=Pradumn13&color=7c6dfa&style=flat-square&label=Profile+Views)

</div>
