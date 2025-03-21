## Hi there 👋

### RAG Challenge

2025-Feb-27 i had [ranked 34rd in the RAG Challenge](https://abdullin.com/erc/).

I found that the things I need to improve are document chunk retrieval and document page reference extraction. 

It looks like a plan.

Other parts of the software solution will remain unchanged: 

* locally hosted LLM gemma-2-9b
* MLC-AI inference
* Apache Tika
* 2 PG extensions by paradedb: pgsearch w/BM25, pgvector for embeddings
* haystack-ai pipeline with several custom components
