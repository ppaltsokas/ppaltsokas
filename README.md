<h1 align="center">Hi, I'm Panagiotis (Panos) Paltsokas 👋</h1>
<h3 align="center">AI/ML Engineer | Data Scientist</h3>

<p align="center">Building data pipelines, machine learning systems, and LLM applications that work beyond the notebook.</p>

I'm an **AI/ML Engineer at DOTSOFT S.A.** in Thessaloniki, Greece. I build end-to-end data and AI systems spanning **IoT data ingestion, ETL, forecasting, federated/edge AI, and LLM-powered services**.

My background combines an **MSc in Data Science & Machine Learning (9.98/10)**, a **BSc in Mathematics**, previous **Trust & Safety / Responsible AI** evaluation experience, and 17 years of mathematics education.

---

## 🔬 What I Work On

- 🏙️ **Data & ML Engineering:** Python/SQL pipelines, IoT ingestion, relational databases, ETL, 15-minute time-series features, automated processing and validation.
- 📈 **Time-Series Forecasting:** Multi-horizon occupancy forecasting, chronological evaluation and operational baselines.
- 🌐 **Federated & Edge AI:** Flower, FedAvg, privacy-preserving local training, ONNX Runtime, WebAssembly and browser/edge inference.
- 🤖 **LLM Applications & Agents:** RAG, semantic/vector retrieval, structured extraction, tool calling, MCP, recommendation systems and deterministic backend constraints.
- 🧩 **AI Architecture:** Specification-Driven Development (SDD), API contracts, modular services, acceptance criteria and evaluation of agent orchestration and Knowledge Graphs.
- 🛡️ **Responsible AI:** Trust & Safety, human-in-the-loop policy evaluation, quality calibration and model-behavior analysis.


---

## 🚀 Selected Work

### 🏙️ Patras Smart Parking | Data Engineering & Forecasting

Developed end-to-end Python/SQL workflows transforming approximately **3.06M raw IoT sensor events** from MariaDB into PostgreSQL-backed 15-minute datasets. Engineered occupancy, sensor activity, turnover, temporal and lag features. Built recurring ETL/model-training workflows for city- and zone-level forecasts across **15-minute, 60-minute and 24-hour horizons**, with chronological validation and baseline comparisons.

**Tech:** `Python` `SQL` `MariaDB` `PostgreSQL` `pandas` `scikit-learn` `ETL` `Time Series`

### 🌐 DARIUS | Federated Learning & Edge AI

Owned the technical implementation of a **multi-city federated AI research demonstrator**, integrating Patras data from MariaDB and Kalamaria/Agrinio data from municipal APIs. Built feature engineering, client-side training, Flower coordination, FedAvg aggregation, validation and lightweight ONNX/browser inference. Evaluated model accuracy, latency, size and computational efficiency.

**Result:** Approximately **91% classification accuracy** in one consolidated 20-round run.

**Tech:** `Python` `Flower` `FedAvg` `ONNX Runtime` `WebAssembly` `TypeScript` `Docker`

**Status:** Validated research prototype. WebGPU was investigated experimentally, not deployed as a production execution backend.

### 🧭 INDIANA | LLM-Powered Tourism Recommendations

Developed Python backend components for **structured LLM query extraction, location resolution, geographic anchors, distance-based filtering, category matching, persona-aware ranking and multi-turn recommendation flows**. Deterministic rules enforce geographic and business constraints independently of LLM-generated text.

**Tech:** `Python` `LLMs` `REST APIs` `Geocoding` `Haversine` `Recommendation Systems`

### 🗺️ DMS Attica | Tourism Destination Management AI Chatbot

Contribute to the **architecture and technical implementation** of a chatbot within a tourism Destination Management System. Apply **Specification-Driven Development (SDD)** to translate functional requirements into technical specifications, component dependencies, API contracts and acceptance criteria.

Evaluate **LangChain, LangGraph, Knowledge Graphs and graph-enhanced retrieval** for stateful orchestration and knowledge access. These are architecture evaluations, not claims of deployed production integrations.

**Status:** In development.

### 🛠️ Municipal Operations | LLM/MCP Assistant

Built a **runnable prototype** connecting natural-language requests to controlled tools and deterministic municipal waste-collection vehicle rerouting logic.

**Tech:** `LLMs` `Model Context Protocol (MCP)` `Tool Calling` `Python`

**Status:** Prototype, not a deployed municipal routing service.

### 🤖 Virtual Panos | RAG Portfolio Assistant

Designed and deployed an interactive AI portfolio with a **React/TypeScript frontend** and a **FastAPI/Python backend**. It retrieves context from my CV, professional experience, publications and project documentation using **embeddings and a FAISS vector index**, then generates grounded answers with **source-aware citation checks**, streaming responses and conversational session handling. The backend supports **configurable LLM providers (OpenAI and Gemini)** rather than requiring one provider in the frontend. The application uses **Docker**, with deployment infrastructure documented for **Google Cloud Run** and **Railway**.

- **Code:** [virtual-me-chatbot-v2](https://github.com/ppaltsokas/virtual-me-chatbot-v2)
- **Portfolio:** [www.ppaltsokas.com](https://www.ppaltsokas.com/)

> 🔒 **Portfolio access:** [www.ppaltsokas.com](https://www.ppaltsokas.com/) is password-protected. To request the password, email **[ppaltsokas@gmail.com](mailto:ppaltsokas@gmail.com)**.

**Tech:** `React` `TypeScript` `FastAPI` `Python` `RAG` `FAISS` `Embeddings` `OpenAI API` `Gemini API` `Docker` `Google Cloud Run` `Railway`

### 🖼️ AI Photo Library | Multimodal Retrieval

Built an image-indexing and semantic-search system for natural-language discovery across photo collections using multimodal embeddings.

**Tech:** `Python` `Image Embeddings` `Semantic Search` `Multimodal AI`

---

## 📚 Publication & Conferences

**ACM demo paper:** Filippidou, D. E., Manos, A., Karanasios, G., & Paltsokas, P. (2026). *Demo: DARIUS – Real-Time Edge–Cloud Data Management and Federated Intelligence for Distributed IoT Systems.* ACM MobiSys Workshops 2026, pp. 394–395. **[DOI: 10.1145/3812836.3814793](https://doi.org/10.1145/3812836.3814793)**.

Research and technical conference activity associated with **MobiSys 2026** and **IEEE MDM 2026**. Scheduled presentations are not described as completed until delivered.

---

## 🛠️ Technical Stack

### Programming & Data Engineering

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![ETL](https://img.shields.io/badge/ETL-475569?style=flat-square) ![REST APIs](https://img.shields.io/badge/REST%20APIs-475569?style=flat-square) ![Data Validation](https://img.shields.io/badge/Data%20Validation-475569?style=flat-square) ![Time-Series Features](https://img.shields.io/badge/Time--Series%20Features-475569?style=flat-square) ![IoT Data](https://img.shields.io/badge/IoT%20Data-475569?style=flat-square)

### Machine Learning & Analytics

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Forecasting](https://img.shields.io/badge/Forecasting-526D82?style=flat-square) ![Regression](https://img.shields.io/badge/Regression-526D82?style=flat-square) ![Classification](https://img.shields.io/badge/Classification-526D82?style=flat-square) ![Chronological Validation](https://img.shields.io/badge/Chronological%20Validation-526D82?style=flat-square) ![Model Evaluation](https://img.shields.io/badge/Model%20Evaluation-526D82?style=flat-square)

### LLM Applications & Agents

![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-405E83?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-405E83?style=flat-square) ![Embeddings](https://img.shields.io/badge/Embeddings-405E83?style=flat-square) ![Vector Retrieval](https://img.shields.io/badge/Vector%20Retrieval-405E83?style=flat-square) ![Structured Outputs](https://img.shields.io/badge/Structured%20Outputs-405E83?style=flat-square) ![Tool Calling](https://img.shields.io/badge/Tool%20Calling-405E83?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-405E83?style=flat-square) ![AI Agents](https://img.shields.io/badge/AI%20Agents-405E83?style=flat-square) ![Recommendation Systems](https://img.shields.io/badge/Recommendation%20Systems-405E83?style=flat-square)

**Architecture evaluation (not claimed as production integrations):**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![Knowledge Graphs](https://img.shields.io/badge/Knowledge%20Graphs-526D82?style=flat-square) ![Graph-Enhanced Retrieval](https://img.shields.io/badge/Graph--Enhanced%20Retrieval-526D82?style=flat-square)

### Federated & Edge AI

![Flower](https://img.shields.io/badge/Flower-6B4EFF?style=flat-square) ![FedAvg](https://img.shields.io/badge/FedAvg-6B4EFF?style=flat-square) ![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) ![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat-square&logo=onnx&logoColor=white) ![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white) ![Browser Inference](https://img.shields.io/badge/Browser%20Inference-526D82?style=flat-square) ![Federated Learning](https://img.shields.io/badge/Federated%20Learning-526D82?style=flat-square) ![WebGPU (Experimental)](https://img.shields.io/badge/WebGPU%20%28Experimental%29-526D82?style=flat-square)

### Software Engineering & Deployment

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Google Cloud Run](https://img.shields.io/badge/Google%20Cloud%20Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white) ![Python Backends](https://img.shields.io/badge/Python%20Backends-475569?style=flat-square) ![API Integration](https://img.shields.io/badge/API%20Integration-475569?style=flat-square) ![Data / ML Automation](https://img.shields.io/badge/Data%20%2F%20ML%20Automation-475569?style=flat-square) ![Testing](https://img.shields.io/badge/Testing-475569?style=flat-square) ![SDD](https://img.shields.io/badge/SDD-475569?style=flat-square)

### Responsible AI & Evaluation

![Trust & Safety](https://img.shields.io/badge/Trust%20%26%20Safety-425A77?style=flat-square) ![Human-in-the-Loop](https://img.shields.io/badge/Human--in--the--Loop-425A77?style=flat-square) ![AI Policy Evaluation](https://img.shields.io/badge/AI%20Policy%20Evaluation-425A77?style=flat-square) ![Quality Calibration](https://img.shields.io/badge/Quality%20Calibration-425A77?style=flat-square) ![Model-Behavior Analysis](https://img.shields.io/badge/Model--Behavior%20Analysis-425A77?style=flat-square)

---

## 🛡️ Responsible AI & Team Contributions

Before DOTSOFT, I worked in **AI Operations & Human Data (Trust & Safety) at TaskUs**, conducting human-in-the-loop evaluations of conversational AI outputs against safety policies and quality standards. I built an operational analytics dashboard tracking label drift, policy hot spots, quality signals and engagement.

At DOTSOFT, I also participate in **AI/LLM technical hiring**, reviewing assignments, code and architectures and contributing to structured interviews.

## 🎓 Background

- **MSc, Data Science & Machine Learning** | Hellenic Open University, **9.98/10** (2025)
- **BSc, Mathematics** | University of Ioannina (2014)
- **17 years of mathematics education**, shaping my analytical reasoning, problem decomposition and communication.

---

## 🌐 Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/ppaltsokas/)
- 💻 [GitHub](https://github.com/ppaltsokas)
- 🌐 [Portfolio & AI CV](https://www.ppaltsokas.com/) (access instructions under Virtual Panos above)
- ✉️ [ppaltsokas@gmail.com](mailto:ppaltsokas@gmail.com)

---

> From raw operational data to validated AI systems, backed by engineering ownership and measurable evidence.
