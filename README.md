# Matthew Kennedy

MS Business Analytics | Data Analytics | Machine Learning | Infrastructure Analytics

I build analytics systems that solve real-world infrastructure, operational, and data problems. My projects combine data engineering, statistical modeling, machine learning, and interactive applications to turn complex data into actionable insights.
## Featured Projects

### Hyperscale Data Center Optimization Tool
Python | DuckDB | Streamlit | Climate Modeling

Developed a simulation platform to evaluate Power Usage Effectiveness (PUE) and Water Usage Effectiveness (WUE) across U.S. counties to identify optimal locations for hyperscale data centers.

The system integrates hourly climate data, energy pricing, water costs, and drought risk metrics to model cooling performance and infrastructure operating costs. A 27M+ row DuckDB analytics engine powers an interactive Streamlit dashboard for geographic comparison and site selection analysis.

Tech Stack

Python, DuckDB, Pandas, Streamlit, Climate APIs, Data Modeling

Repo
https://github.com/matthewkennedy22/hyperscale-data-center-optimization-tool

---

### BetBrain – Predictive Sports Analytics
Python | Machine Learning | APIs

Built a full-stack sports analytics platform that aggregates live betting odds, news sentiment, and line movement data to generate data-driven betting insights using Cursor AI (VS CODE).

The backend integrates The Odds API for sportsbook data and uses TextBlob sentiment analysis on sports news to capture market sentiment signals. A custom algorithm evaluates expected value (EV), odds discrepancies, and sentiment signals to rank betting opportunities. Results are served through a FastAPI backend and React dashboard for real-time analysis.

Tech Stack

Python, FastAPI, Pandas, NumPy, TextBlob, SQLite, React, APIs

Repo
https://github.com/matthewkennedy22/Bet_Brain

---

### RAG Movie Recommendation System
Python | LLM | Vector Search

Built a Retrieval-Augmented Generation (RAG) system for semantic search and question answering over IMDB movie reviews.

Reviews are processed using NLTK tokenization and custom text chunking, then embedded with SentenceTransformers (all-MiniLM-L6-v2) and stored in a Qdrant vector database. User queries are embedded and matched using cosine similarity retrieval, and retrieved context is passed to Gemma 3 via Ollama to generate grounded responses with citation-style references.

Tech Stack

Python, Qdrant, SentenceTransformers, NLTK, Ollama, Gemma 3, Vector Search

Repo
https://github.com/matthewkennedy22/RAG-System-Gemma3-IMDB

---

### SQL Auto Loan Database
SQL | Relational Database Design

Designed and implemented a relational database system for managing auto loan portfolios, including borrower profiles, loan contracts, payment schedules, and servicing records.

The schema models key financial relationships and supports queries for loan performance tracking, borrower risk analysis, and payment history reporting.

Tech Stack

SQL, Relational Database Design, Data Modeling

Repo
https://github.com/matthewkennedy22/SQL-Auto-Loan-Database

