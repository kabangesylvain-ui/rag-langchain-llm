# 📚 Summarize Private Documents Using RAG, LangChain, and LLMs

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-0.3-green)](https://www.langchain.com/)
[![IBM](https://img.shields.io/badge/IBM-watsonx.ai-blue)](https://www.ibm.com/watsonx)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

## 📌 Contexte du projet

Ce projet permet de résumer des documents privés en utilisant la technique **RAG (Retrieval-Augmented Generation)** avec **LangChain** et les **LLMs d'IBM watsonx.ai**.

**Objectif** : Créer un assistant capable de lire et résumer des documents confidentiels sans les exposer à des modèles publics.

---

## 🧠 Architecture RAG

| **Composant** | **Description** |
|---------------|-----------------|
| **Indexing** | Chargement, split en chunks, embedding et stockage vectoriel |
| **Retrieval & Generation** | Récupération des chunks pertinents et génération de réponses |

---

## 🛠️ Stack technique

- **LangChain** : Gestion des chaînes de traitement
- **HuggingFace Embeddings** : Génération des embeddings
- **Chroma DB** : Stockage vectoriel
- **IBM watsonx.ai** : LLM (Llama, Mistral)
- **Python** : Langage principal

---

## 📊 Résultats

- ✅ Chargement et split du document en 16 chunks
- ✅ Embedding et stockage dans Chroma DB
- ✅ Question-réponse avec mémoire de conversation
- ✅ Agent interactif pour poser des questions

---

## 🔧 Installation

```bash
# Cloner le dépôt
git clone https://github.com/kabangesylvain-ui/rag-langchain-llm-summarizer.git
cd rag-langchain-llm-summarizer

# Installer les dépendances
# Lancer l'agent interactif
qa()
pip install -r requirements.txt
