## Hi there 👋

### RAG Challenge

2025-Feb-27 i had [ranked 34rd in the RAG Challenge](https://abdullin.com/erc/).

I found that the things I need to improve are document chunk retrieval and document page reference extraction. 

It looks like a plan.

the parts of the software solution: 

* locally hosted LLM gemma-2-9b
* MLC-AI inference
* Apache Tika
* 2 PG extensions by paradedb: pgsearch w/BM25, pgvector for embeddings
* haystack-ai pipeline with several custom components

UPD 14.04 updated parts of RAG solution: 
* locally hosted LLM gemma-3-27b-qat
* llama.cpp for inference, for support tensor parallelism with 2 GPU 
* IBM docling for PDF processing for more accurate parcing
