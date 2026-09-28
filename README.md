# Rishav Upadhaya

**AI engineer — RAG, agents, and LLM inference.** Python · FastAPI · LangGraph · pgvector. Kathmandu, Nepal.

[Portfolio](https://www.rishavupadhaya.com.np) · [LinkedIn](https://www.linkedin.com/in/rishav-upadhaya/) · [Writing](https://medium.com/@rishavupadhaya266) · [Email](mailto:rishavupadhaya266@gmail.com)

I build LLM systems that can be measured: retrieval quality, latency, token cost, and failure modes. Previously AI Engineer at AsterGaze Technologies (multi-agent RAG for a study-abroad CRM) and backend intern at Proshore (multi-engine OCR pipeline).

## Selected work

**[SWLP](https://github.com/Rishav-Upadhaya/SWLP)** — exact-FP16 LLM inference for models larger than RAM.
Streams transformer layers through a prefetched sliding window: a 26 GB model runs at 1.7 GB peak RAM on a 16 GB machine, ~2.5× AirLLM's throughput, byte-identical output. [Write-up](https://medium.com/@rishavupadhaya266/swlp-sliding-window-layer-pipeline-d9273e5feec4)

**[Sentinel](https://sentinel-ams.netlify.app/)** — support-automation platform (private beta).
Doc-grounded answers with citations, hybrid pgvector + full-text retrieval, provider-agnostic LLM routing, MCP tools over OAuth 2.1, multi-tenant secrets vault, per-run traces.

**[ContextWatch](https://github.com/Rishav-Upadhaya/ContextWatch)** — anomaly detection for AI-agent traces (final-year project).
Normalizes MCP/A2A logs, flags anomalies against an embedding baseline of normal behaviour, and runs graph-based root-cause analysis.

**[JobRAG](https://github.com/Rishav-Upadhaya/jobrag)** — job-search RAG over 1,000+ listings.
LangGraph intent → retrieve → rerank → judge graph, pgvector HNSW, Jina reranker, FastAPI.

**[Booking-RAG](https://github.com/Rishav-Upadhaya/Booking-RAG)** — conversational RAG with a deterministic booking flow.
Dense + sparse retrieval in Pinecone with bge reranking, Redis session memory, SSE streaming.

Graduating December 2026 — open to AI and backend engineering roles.
