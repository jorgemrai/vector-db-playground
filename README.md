# vector-db-playground
Sample about generate data embedding and store in vector database.

This repo compares how to build a semantic search pipeline using four different vector databases:

- [x] 🔵 Chroma
- [x] 🟢 FAISS
- [x] 🟠 Pinecone
- [x] 🟩 Weaviate


## 🧰 Tech Stack

- Python 3.10+
- `sentence-transformers` (MiniLM)
- Chroma / FAISS / Pinecone / Weaviate

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone [https://github.com/jorge-mendoza/vector-db-playground.git](https://github.com/jorgemrai/vector-db-playground.git)
cd vector-db-playground

# 2. Install dependencies
pip install -r requirements.txt

# 3. Create your .env file
cp .env.example .env

# 4. Run examples
vector-store-db.ipynb
