# <center>Retrieval Augmented Generation</center>

The objective of this research is to explore the use of Retrieval-Augmented Generation (RAG) in creating a personal chat-bot powered by pretrained large language models (LLMs). By utilizing Langchain as a vector database for efficient data retrieval, this study aims to demonstrate the practicality of open-source LLMs for personal, privacy-preserving use. The research will focus on minimizing computational resources, enabling users to interact with their personal data securely on their local devices.

### Dataset:
Book - Encyclopedia of Foods: A Guide to Healthy Nutrition.pdf

### Models:
| Embedding Models | all-MiniLM-L6-v2 | stella-base-en-v2 |
|----------|----------|----------|
| Size | 0.08GB | 0.2GB |
| Embedding Dimension | 384 | 768 |
| Parameter | 22.7M | 55M|
| Max Tokens | 512 | 512 |
| Language | English | English |
| Retrieval Accuracy | 73% | 85% |

Embedding model with higher embedding dimension has high retrieval accuracy.

| Chat Models | Google/T5-Base |
|-------------|----------------|
| Size | 0.9GB |
| Parameter | 223M |
| Year | 2020 |


### Vector Database:
Langchain - FAISS

### Computing Power
| Apple Silicon | M1 |
|--------------|----|
| TFLOPS | 2.60 |

-----------------------------------------------------------------
#### References:
Embedding models: https://huggingface.co/spaces/mteb/leaderboard \
Embeddings: https://vickiboykis.com/what_are_embeddings/ 
