<div align="center">

<h1>🧠 SADOP</h1>
<h3>Smart AI-Driven Database Optimization Platform</h3>

<p>
An academic project combining <b>Databases</b>, <b>Machine Learning</b>, <b>Reinforcement Learning</b>, and <b>LLMs</b> to analyze, predict, and optimize MySQL performance.
</p>

<hr/>

<!-- Tech Stack Icons -->
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="50"/>
</p>

</div>

---

## 🧠 Project Overview

**SADOP (Smart AI-Driven Database Optimization Platform)** is a system designed to:

- Monitor MySQL performance
- Detect slow and inefficient queries
- Predict performance problems using Machine Learning
- Automatically recommend database indexes using Reinforcement Learning
- Interact with the database using Natural Language (LLMs)

---

## 🧱 Phase 1 — Environment & Tools (M1)

### 🎯 Goal

Prepare a **professional development environment** capable of:

- Running MySQL
- Generating large datasets
- Training ML & RL models
- Interacting with LLMs

### ✅ Completed Tasks

#### 💻 Operating System

- Windows 11 Pro (development environment)

#### 🛢️ Database

- MySQL Server 8.x
- Running on port **3307**
- Managed via MySQL Workbench

#### 🔐 Security

- Root account secured
- Dedicated database user created:
  sadop_user

markdown
Copy code

- Restricted privileges applied

#### 🐍 Python Environment

- Python 3.12
- Conda virtual environment: **SADOP**
- JupyterLab / Jupyter Notebook configured

#### 📦 Installed Libraries

**Core**

- mysql-connector-python
- pandas, numpy

**Machine Learning**

- scikit-learn
- tensorflow / pytorch

**Reinforcement Learning**

- gymnasium
- stable-baselines3

**LLM**

- langchain
- Ollama (local LLM)

#### 📁 Project Structure

SADOP/
├── db/
├── monitoring/
├── data/
├── ml/
├── rl/
├── llm/
├── api/
└── report/

yaml
Copy code

✅ **Milestone M1 completed**

---

## 🧱 Phase 2 — Database Design & Data Generation (M2)

### 🎯 Goal

Create a **realistic, large, and normalized database** able to:

- Stress MySQL
- Generate performance issues
- Feed ML & RL models

---

### 🏦 Use Case

**Banking System**

---

### 🧩 Database Design

#### Main Entities

- Users
- Accounts
- Transactions
- Logs

#### Design Quality

- ER diagram created
- Schema normalized to **3NF**
- Primary keys defined
- Foreign keys enforced
- Basic indexes added

---

### 🧠 Schema Implementation

- SQL DDL scripts written
- Tables created via Jupyter
- User-based access (no root usage)

---

### 🧪 Data Generation

#### Small Dataset

- Inserted for testing
- Data consistency validated
- Errors fixed (phone number length)

#### Large Dataset (Production-Scale)

- Users: ~10,000
- Accounts: ~20,000+
- Transactions: **100,000+**
- Logs: **50,000 – 100,000**

✔ Data inserted:

- In batches
- Safely (no crashes)
- With realistic timestamps and values

---

### 💾 Backup

- Full MySQL dump created:
  db/sadop_db_backup.sql

yaml
Copy code

✅ **Milestone M2 completed**

---

## 🧱 Phase 3 — Monitoring & Performance Data (M3) _(In Progress)_

### 🎯 Goal

Collect **real MySQL performance signals** for AI models.

### 🔍 Completed Steps

- Enabled MySQL `slow_query_log`
- Configured aggressive threshold:
  - Queries slower than **0.5s** are logged
- Located physical slow query log file

This enables:

- Real workload observation
- Performance labeling
- ML/RL feature extraction

---

## 🧭 Next Steps

- Enable `performance_schema`
- Extract execution metrics
- Generate ML-ready datasets
- Train diagnostic models
- Build RL index optimization agent
- Add LLM natural language interface

---

## 🎓 Academic Value

This project demonstrates:

- Advanced database engineering
- AI-driven optimization
- Real-world workload simulation
- End-to-end system integration

---

<div align="center">
<b>SADOP — Turning database performance into intelligent decisions.</b>
</div>
