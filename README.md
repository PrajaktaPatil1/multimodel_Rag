#  Multimodal RAG using LangChain (Text + Image Embedding)

This project demonstrates a simple **Multimodal Retrieval-Augmented Generation (RAG)** application using **LangChain**, which supports embedding and retrieval of both **text** and **image** content. 

It uses OpenAI's `openai/clip-vit-base-patch32` model via LangChain to convert both image and text inputs into vector embeddings, stores them in a FAISS index, and enables retrieval-based question answering.

---

##  Features

- Multimodal embeddings: Supports both **text** and **image** inputs
-  Vector-based similarity search using **FAISS**
-  Question-answering using context retrieved from a multimodal document store
-  Uses **LangChain**, **OpenAI CLIP**, **FAISS**, and **OpenAI chat models**

---

##  Requirements

- Python 3.8+
- `langchain`
- `faiss-cpu`
- `openai`
- `pillow`
- `ipython` (for Jupyter/IPython compatibility)
- `tiktoken` (for token counting)


