<!-- date: 2025-08-10 -->
# Vector DB tradeoffs
Quick notes on FAISS vs pgvector vs Azure search...

- FAISS: blazing fast, but you manage persistence.
- pgvector: great for small-to-mid workloads; one DB to backup.
- Azure Search: managed + scalable; latency depends on SKU.
