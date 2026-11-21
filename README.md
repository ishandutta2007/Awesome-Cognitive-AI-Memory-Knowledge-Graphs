# Awesome-Cognitive-AI-Memory-Knowledge-Graphs

## Top Cognitive AI Memory & Knowledge Graphs Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Long-Term AI Agent Memory, Temporal Knowledge Graphs, GraphRAG, Semantic Caching & Cognitive Context Engines*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Cognitive AI Memory & Knowledge Graphs**. These tools extract, structure, store, retrieve, decay, and reason over episodic, semantic, and procedural memories across AI agents and LLM applications using vector embeddings, temporal knowledge graphs, GraphRAG pipelines, and semantic caches.



**Examples** include Mem0, Zep, LangMem, Letta Platform (formerly MemGPT), Graphlit, Pinecone Memory, Qdrant LangCache, Redis LangCache, Weaviate Memory, Ragie, and topoteretes/cognee (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for cognitive AI memory engines (`topoteretes/cognee`, `Mem0`, `Letta`, `Graphiti`, `LangMem`, `Motorhead`), GraphRAG & knowledge-graph builders (`Microsoft GraphRAG`, `LightRAG`, `Nano-GraphRAG`), and self-hosted vector/graph/semantic-cache backends (`Qdrant`, `Weaviate`, `Redis`, `Neo4j`, `GPTCache`) — ideal for AI agent engineers, RAG architects, cognitive AI researchers, and developers building stateful assistants.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global knowledge graph and cognitive AI memory market is estimated at **$2.9B - $3.5B in 2026** and is projected to surpass **$15B - $25B by the early 2030s** (surging at a CAGR of ~28% - 37%), driven by enterprise migration from basic vector similarity toward stateful agent architectures and hybrid GraphRAG. The sector is currently **highly fragmented** rather than winner-take-all; distinct architectural approaches (specialized agent memory services, temporal graph engines, serverless vector databases, and in-memory semantic caching) actively compete and interoperate across diverse enterprise ontology and privacy requirements.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Starting Pricing Tier | Free Tier & Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[LangSmith & LangGraph Platform (LangMem)](https://langchain.com)** | **$3.0B Valuation** (~$460M raised) | **$39/seat/month** (Plus plan) | **Always Free Developer Plan**: 1 seat, up to 5,000 base traces/month, 14-day data retention, 50,000 events/hour. | Managed agent orchestration, observability, and persistent cross-thread memory stores (`LangMem`) with stateful checkpointing. |
| **[Redis Cloud (LangCache & Memory)](https://redis.io)** | **$2.0B Valuation** (Crossed $300M+ ARR) | **$5/month** (~$0.007/hr, Essentials 250 MB plan) | **Always Free Plan**: 1 database, up to 30 MB storage, 30 concurrent connections, and 100 ops/sec throughput. | Managed in-memory database and semantic caching platform (`LangCache`) accelerating agent session state and hybrid vector/graph memory. |
| **[Pinecone (Assistant & Memory Storage)](https://pinecone.io)** | **$750M Valuation** (~$15M–$27M ARR) | **$20/month** (Builder plan) / **$50/mo min** (Standard) | **Always Free Starter Plan**: 1 project, up to 5 serverless indexes, 2 GB storage (~300k vectors), 2M write units/mo, 1M read units/mo, and 5M embedding tokens/mo in AWS `us-east-1` (plus 21-day Standard trial with $300 credits). | Serverless vector database and managed RAG/memory platform delivering low-latency semantic recall and hybrid sparse-dense retrieval. |
| **[Qdrant Cloud (Semantic Memory)](https://qdrant.tech)** | **$250M–$500M Est. Valuation** (~$9.2M ARR, $96.5M raised) | **~$25/month** (~$0.034/hr dedicated Standard node) | **Always Free Tier**: 1 single-node cluster, 0.5 vCPU, 1 GB RAM, 4 GB disk (fits ~1M 768-dim vectors; auto-pauses after 7 days inactivity). | Managed vector search cloud optimized for long-term AI agent memory, semantic caching, and multi-tenant payload filtering. |
| **[Weaviate Cloud (Agentic Memory)](https://weaviate.io)** | **~$200M Valuation** (~$12.3M ARR, $67.7M raised) | **$45/month** (Flex pay-as-you-go starting tier) | **Always Free Sandbox**: 1 cluster, 1 GB RAM, 10 GB disk, up to 100,000 objects, 1 collection, and up to 3 tenants. | Managed AI-native vector database offering generative search, hybrid keyword/vector recall, and multi-tenancy for persistent agent memory. |
| **[Letta Cloud (formerly MemGPT)](https://letta.com)** | **$70M Valuation** (~$1.4M ARR, $10M raised) | **$20/month** (Pro plan) | **Always Free Developer Plan**: Up to 3 stateful memory agents with Bring-Your-Own-Key (BYOK). | Cloud platform for building and deploying stateful, self-editing memory agents managing virtual context windows alongside archival memory. |
| **[Mem0 Cloud](https://mem0.ai)** | **$24.5M Raised** (~$1.0M ARR, Series A stage) | **$19/month** (Starter tier; Custom for enterprise) | **Always Free Tier**: First 30 days includes 10,000 add requests & 1,000 retrievals (platform LLM); after 30 days with BYOK includes 50,000 adds & 10,000 retrievals/month. | Managed universal memory layer for AI agents providing automatic user/session/agent memory extraction and graph relationships. |
| **[Zep Cloud](https://getzep.com)** | **Seed Backed** (~$1.0M ARR, YC / VC funded) | **$125/month** (Flex plan, 50,000 credits/mo) | **Always Free Prototyping Plan**: 10,000 credits/month for prototyping, testing, and temporal context graph assembly. | Managed long-term memory and temporal knowledge graph platform for AI assistants featuring real-time entity resolution and fact extraction. |
| **[Ragie](https://ragie.ai)** | **$5.5M Raised** (Craft Ventures Seed) | **$100/month** (Starter plan, ~10,000 pages) | **Always Free Developer Plan**: Up to 1,000 documents/pages and 1,000 retrievals/month with hybrid search and reranking. | Fully managed RAG-as-a-Service and agent memory connector platform providing automated chunking, entity extraction, and retrieval APIs. |
| **[Graphlit](https://graphlit.com)** | **$3.6M Raised** (Seed stage, Unstruk Data) | **$49/month** (Hobby plan) | **Always Free Tier**: 1 GB storage, up to 1,000 content items, 3 feeds, 100 credits/month, and unlimited chat/RAG conversations. | Cloud-native unstructured data ingestion, multimodal RAG, and automated knowledge graph API built for AI agents. |





## Open-Source GitHub Projects



- **[topoteretes/cognee](https://github.com)**  

  Flagship open-source AI memory engine that transforms raw documents, conversations, and structured data into interconnected knowledge graphs and vector stores in just a few lines of Python.



- **[Mem0 (`mem0ai/mem0`)](https://github.com)**  

  Popular open-source intelligent memory layer for AI assistants and agents that dynamically extracts, updates, and retrieves personalized user and session memories.



- **[Letta (`letta-ai/letta`, formerly MemGPT)](https://github.com)**  

  Open-source framework for stateful LLM agents featuring OS-inspired virtual context management, self-editing core memory blocks, and persistent archival storage.



- **[Graphiti (`getzep/graphiti`)](https://github.com)**  

  Open-source framework by Zep for building and querying real-time, temporally aware knowledge graphs specifically tailored for dynamic AI agent memory.



- **[LangMem (`langchain-ai/langmem`)](https://github.com)**  

  Open-source SDK from LangChain enabling agents to extract, consolidate, and manage semantic, episodic, and procedural memories across conversations.



- **[Microsoft GraphRAG (`microsoft/graphrag`)](https://github.com)**  

  Foundational open-source modular graph-based Retrieval-Augmented Generation system extracting entity-relationship graphs and hierarchical community summaries from unstructured text.



- **[LightRAG (`HKUDS/LightRAG`)](https://github.com)**  

  Fast, lightweight open-source GraphRAG framework integrating dual-level (low-level entity and high-level theme) knowledge graph retrieval with incremental updates.



- **[Qdrant (`qdrant/qdrant`)](https://github.com)**  

  High-performance open-source vector similarity search engine and semantic cache backend written in Rust with rich filtering and quantization.



- **[Weaviate (`weaviate/weaviate`)](https://github.com)**  

  Open-source AI-native vector database written in Go supporting hybrid BM25/vector search, cross-references, and modular embedding pipelines.



- **[GPTCache (`zilliztech/GPTCache`)](https://github.com)**  

  Open-source semantic caching library (`LangCache` equivalent) that stores and matches similar LLM queries using vector embeddings to cut API latency and token costs.



- **[Neo4j Community (`neo4j/neo4j`) & FalkorDB (`FalkorDB/FalkorDB`)](https://github.com)**  

  Leading open-source property-graph databases engineered for low-latency GraphRAG traversals, Cypher querying, and cognitive AI knowledge graphs.



### Additional Strong Open-Source Options



- **[Memobase (`memodb-io/memobase`)](https://github.com)** and **[Khoj (`khoj-ai/khoj`)](https://github.com)** for open-source profile-based user memory systems and self-hosted personal AI second brains.

- **[Chroma (`chroma-core/chroma`)](https://github.com)** and **[Milvus (`milvus-io/milvus`)](https://github.com)** for open-source developer-friendly and distributed enterprise vector memory stores.

- **[RedisVL (`redis/redis-vl-python`)](https://github.com)** for open-source Python client abstractions powering semantic caching (`LangCache`), session memory, and vector search on Redis.

- **[Kùzu (`kuzudb/kuzu`)](https://github.com)** for an embedded, ultra-fast open-source graph database ("DuckDB for graphs") ideal for local-first AI knowledge graphs.

- **[HippoRAG (`OSU-NLP-Group/HippoRAG`)](https://github.com)** for neurobiologically inspired long-term memory combining knowledge graphs with Personalized PageRank for multi-hop associative recall.



**Frameworks for building custom systems**: Combine **topoteretes/cognee** or **Graphiti** for automated temporal knowledge graphs, **Mem0** or **Letta** for conversational agent memory management, and **Qdrant + RedisVL** for high-speed vector recall and semantic caching.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Persistent AI memory systems store user preferences, conversational history, and entity relationships across sessions; enforce strict multi-tenant user isolation, PII redaction, and right-to-be-forgotten deletion workflows.

- Automated knowledge-graph extraction pipelines (`Cognee`, `GraphRAG`, `Graphiti`) perform background LLM entity/relation calls that can incur substantial token usage on large document corpora.



---



**Made for AI agent architects, RAG engineers, cognitive AI researchers, and open-source contributors.**  

Let's make AI memory and knowledge graphs more open, persistent, and interpretable.
