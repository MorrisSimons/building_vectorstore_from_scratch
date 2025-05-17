# BUILD VECTOR STORE and  SEARCH From Scratch
![top language](https://img.shields.io/github/languages/top/gpt-null/template)
![code size](https://img.shields.io/github/languages/code-size/gpt-null/template)
![last commit](https://img.shields.io/github/last-commit/gpt-null/template)
![issues](https://img.shields.io/github/issues/gpt-null/template)
![contributors](https://img.shields.io/github/contributors/gpt-null/template)
![License](https://img.shields.io/github/license/gpt-null/template)
---
## My plan: TODO
- [ ] **Embeddings:** Train Word2Vec model to generate vector representations.
    - [ ] my own custom made
        - [ ] Build vocab
        - [ ] Train a model
    - [*] A normal one


- [ ] **Most of my code will be Word2vec that i will rebuild to Doc2vec**

--- 

- [ ] **Vector Store:** Integrate a vector store library or database, such as FAISS - mabye do from scratch.
    - [ ] my own custom made
    - [ ] A common solution

- [ ] **Indexing:** Use FAISS's indexing capabilities to enable fast similarity search and experiment with building a custom index.
    - [ ] my own custom made
    - [ ] a common one like FAISS Index

- [ ] **Data Mapping:** Maintain a mapping between original data and their corresponding vectors to interpret search results accurately.

- [ ] **Query/Similarity Function:** Implement a search function to query the vector store and retrieve the most similar vectors to a given input.
    - [ ] my own custom made
    - [ ] a common one like FAISS Search
---

#### the dataset we want to use for our vector storehttps://www.kaggle.com/datasets/yorkyong/text8-zip

### FAISS

**FAISS** (Facebook AI Similarity Search) is an open-source library by Meta (Facebook) for **efficient similarity search** and clustering of high-dimensional vectors.

#### What does it do?

* Lets you **store and search millions (or billions) of vectors** fast.
* Used for **nearest neighbor search**—finding the most similar vectors (e.g., which documents, images, or words are closest to a query).

#### Why use it?

* Regular brute-force search is slow when you have a lot of data.
* FAISS is **optimized for speed and scale**. It uses smart algorithms and (optionally) your GPU.

#### How does it work (in a nutshell)?

* You give it a big list of vectors (from Word2Vec, BERT, etc.).
* It indexes them for **fast lookup**.
* You query with a new vector, and FAISS quickly finds the closest vectors (most similar items).




### LICENSE

```markdown
MIT License

Copyright (c) Morris Simons

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```