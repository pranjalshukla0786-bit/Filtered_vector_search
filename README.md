# Filtered-vector-search
Benchmark of filtered vector search in PostgreSQL 16 with pgvector 0.8.0. Compares exact pre-filtering, HNSW with WHERE, over-fetch and iterative scan on 50,000 arXiv abstracts, measuring recall@10 and latency across filter selectivities, plus a selectivity-based router and real category filters.
