# Hi, I'm Aman 👋
### Python Backend Developer & AI Engineer

I am a Python developer focused on Backend Engineering and AI. I build reliable APIs using FastAPI, manage data with PostgreSQL, and build tools that use AI to solve real problems

---

### 🛠️ Technical Skills

| Domain | Stack |
| :--- | :--- |
| **Backend Engineering** | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| **Database & ORM** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-red?style=flat) |
| **Applied AI** | ![Groq](https://img.shields.io/badge/Groq%20SDK-orange?style=flat) ![ChromaDB](https://img.shields.io/badge/ChromaDB-purple?style=flat) ![RAG](https://img.shields.io/badge/RAG-Architecture-green?style=flat) |

---

### 🚀 Featured Engineering Projects

#### 1) [AI Resume Analyzer](https://github.com/Aman00240/RESUME_SCANNER)
**Automated RAG-Based Screening System**
An intelligent document-parsing and evaluation API that deterministically scores candidates against job descriptions.
* **Core Problem:** Manual resume screening is slow, highly subjective, and standard keyword parsers often fail to understand true technical context.
* **Solution:** Architected a Retrieval-Augmented Generation (RAG) pipeline utilizing **ChromaDB** for semantic search, and implemented **Instructor/Pydantic** to force the LLM into outputting strict, hallucination-free JSON decisions (Match/Reject).
* **Key Tech:** Python, FastAPI, ChromaDB, Groq LLM, RAG, Streamlit.

#### 2) [BookFast API](https://github.com/Aman00240/BOOKFAST)
**High-Concurrency Ticketing System**
A robust booking API designed to handle race conditions during high-demand events.
* **Core Problem:** Preventing "double-booking" when thousands of users hit the endpoint simultaneously.
* **Solution:** Implemented **Atomic Transactions** and database locking strategies to guarantee inventory consistency.
* **Key Tech:** FastAPI, PostgreSQL, JWT Authentication, Docker Compose.

#### 3) [AI Receipt Parser](https://github.com/Aman00240/RECEIPT-PARSER)
**Structured Data Extraction Pipeline**
A vision-based tool that transforms unstructured receipt images data into strict, validated JSON.
* **Core Problem:** Manual data entry from receipts is time-consuming and prone to typos/human error.
* **Solution:** Built an intelligent extraction pipeline using **Llama Vision** to read messy images and **Pydantic** to enforce strict accuracy (ensuring data format is correct).
* **Key Tech:** Llama Vision (via Groq), Python, Pydantic.

---
### Current Research & Development
I am currently transitioning from standard RAG pipelines to building autonomous, stateful AI agents.
* **Active Experiment:** Developing a multi-tool autonomous agent using **LangGraph**, **Python (AsyncIO)**, and local **SQLite** persistence.
* **Goal:** Building an end-to-end "Coder Agent" capable of dynamic web searching, real-time web scraping, and local file system execution.
---

### 📫 Connect
[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/aman-saini-425b9b2b4/)
