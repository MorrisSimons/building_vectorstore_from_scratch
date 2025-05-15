## FAISS

**FAISS** (Facebook AI Similarity Search) is an open-source library by Meta (Facebook) for **efficient similarity search** and clustering of high-dimensional vectors.

### What does it do?

* Lets you **store and search millions (or billions) of vectors** fast.
* Used for **nearest neighbor search**—finding the most similar vectors (e.g., which documents, images, or words are closest to a query).

### Why use it?

* Regular brute-force search is slow when you have a lot of data.
* FAISS is **optimized for speed and scale**. It uses smart algorithms and (optionally) your GPU.

### Where is it used?

* AI search (semantic search, recommendations)
* Retrieval-augmented generation (RAG)
* Clustering similar items

### How does it work (in a nutshell)?

* You give it a big list of vectors (from Word2Vec, BERT, etc.).
* It indexes them for **fast lookup**.
* You query with a new vector, and FAISS quickly finds the closest vectors (most similar items).

**Bottom line:**
If you have embeddings and want to do **similarity search** at scale, FAISS is a top tool.

Want to see a basic FAISS code example?
