This repository contains the codes for the IR-RAG course, which teaches advanced retrieval techniques to improve the relevancy of retrieved results.

## Overview

Information Retrieval (IR) and Retrieval Augmented Generation (RAG) are only effective if the information retrieved from a database as a result of a query is relevant to the query and its application. This course addresses the challenge of improving the relevancy of retrieved results by teaching advanced retrieval techniques.

## Techniques Covered

The techniques covered in this course include:

- **Query Expansion**: Expanding user queries improves information retrieval by including related concepts and keywords. Utilizing an LLM makes this traditional technique even more effective. Another form of expansion has the LLM suggest a possible answer to the query which is then included in the query.

- **Cross-encoder Reranking**: Reranking retrieval results to select the results most relevant to your query improves your results.

- **Training and Utilizing Embedding Adapters**: Adding an adapter layer to reshape embeddings can improve retrieval by emphasizing elements relevant to your application.
