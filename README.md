# AI SQL Agent System

## 📌 Overview
The **AI SQL Agent System** is an intelligent two-agent framework that allows users to interact with databases using **natural language queries**.  
It removes the need for manual SQL writing by leveraging **LLMs (Large Language Models)** and **NLP techniques** to automatically generate and execute SQL queries.  

---

## ⚙️ System Architecture

### Agent 1 – Entity Extractor
- Processes user input in plain English.
- Identifies **entities, attributes, filters, and intent** using NLP/LLM.
- Produces a structured representation of the query.

### Agent 2 – SQL Generator & Executor
- Converts extracted entities into **valid SQL queries**.
- Optimizes the SQL for better performance.
- Executes the query on a **MySQL (or other) database**.
- Returns results in a **user-friendly format** (tables, summaries, or visualizations).

---

## 🚀 Features
- ✅ Natural Language → SQL Conversion  
- ✅ Multi-Database Support (MySQL, PostgreSQL, etc.)  
- ✅ Query Optimization & Error Handling  
- ✅ User-Friendly Outputs (tables, charts, insights)  
- ✅ Scalable and extensible for enterprise use  

---

## 🏗️ Tech Stack
- **Language:** Python  
- **Libraries:** LangChain, OpenAI API, SQLAlchemy, Pandas  
- **Database:** MySQL / PostgreSQL / SQLite  
- **Other Tools:** Streamlit / Flask (for UI)  

---

## 📂 Project Structure
