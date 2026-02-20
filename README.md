# Chatbot RAG – PDF QA

Agent conversationnel permettant de poser des questions sur un fichier PDF en utilisant l’approche **RAG (Retrieval-Augmented Generation)** avec un LLM local.

## Tech Stack

* Python
* Streamlit
* LangChain
* ChromaDB
* Ollama (LLM local)


## Fonctionnement

1. Upload du PDF
2. Extraction du texte
3. Découpage en chunks
4. Génération des embeddings
5. Stockage dans ChromaDB
6. Recherche des passages pertinents
7. Génération de réponse via LLM

## Installation

```bash
pip install -r requirements.txt
ollama pull llama2
streamlit run app.py
```

## Points clés

* LLM exécuté localement (pas de cloud)
* Base vectorielle persistante
* Conversation avec mémoire


