# BUILD VECTOR STORE and  SEARCH From Scratch
![top language](https://img.shields.io/github/languages/top/gpt-null/template)
![code size](https://img.shields.io/github/languages/code-size/gpt-null/template)
![last commit](https://img.shields.io/github/last-commit/gpt-null/template)
![issues](https://img.shields.io/github/issues/gpt-null/template)
![contributors](https://img.shields.io/github/contributors/gpt-null/template)
![License](https://img.shields.io/github/license/gpt-null/template)
---

### NOTES
- word2vec, don't use bigram because its's to compute expensive, only words on low data.
- Lesson some chunks that are right after each other might not share the similar vector space even though they are from the same

## My plan: TODO
- [ ] **Embeddings:** Train Word2Vec model to generate vector representations.
    - ~~[ ] my own custom made word2vec - Scrapped, not worth it~~
        - ~~[ ] Build vocab~~
        - ~~[ ] Train a model~~
    - [x] A normal one

- [ ] **Built my own custom made doc2vec**
    - [x] use word2vec to build doc2vec
    - [x] build the embedding

- [x] **Query/Similarity Function:** Implement a search function to query the vector store and retrieve the most similar vectors to a given input.
    - [x] my own custom made


--- 


**Most of my code will be Word2vec that i will rebuild to Doc2vec**


---

#### the dataset we want to use for our vector storehttps://www.kaggle.com/datasets/yorkyong/text8-zip


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