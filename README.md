# 🧭 Chatbot Tourisme & Culture (RAG)

## 📌 Description du projet
Ce projet consiste à développer un **chatbot intelligent basé sur l’approche RAG (Retrieval-Augmented Generation)**, spécialisé dans le **tourisme et la culture tunisienne**.  
Le chatbot permet de poser des questions en langage naturel et d’obtenir des réponses précises à partir d’un **dataset textuel local**, enrichi et structuré.

Le système combine :
- la **recherche sémantique** (FAISS + embeddings),
- et la **génération de réponses** via un **LLM local (Ollama)**.

---

## 🎯 Objectifs du projet
- Construire un chatbot informatif sans dépendre d’API payantes
- Exploiter des données culturelles et touristiques locales
- Mettre en œuvre une architecture RAG complète
- Travailler en collaboration via Git et GitHub

---

## 🧠 Architecture RAG (vue simplifiée)

1. **Dataset texte** (sites touristiques et culturels)
2. **Nettoyage & structuration des données**
3. **Découpage en chunks**
4. **Génération des embeddings**
5. **Indexation avec FAISS**
6. **Recherche des passages pertinents**
7. **Génération de la réponse avec Ollama**


---

## 🛠️ Technologies utilisées 

- **Python 3**
- **Streamlit** : interface utilisateur
- **Sentence-Transformers** : embeddings sémantiques
- **FAISS** : recherche vectorielle
- **Ollama** : modèle de langage local (LLM)




