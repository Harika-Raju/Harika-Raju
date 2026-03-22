# Hi, I'm Harika 👋

I'm a final-year B.Tech Information Technology student (2026) with a deep interest in how AI models actually work — not just using them, but understanding and building them from the ground up.

My focus areas:

- **AI/ML Engineering** — designing, training, and fine-tuning models with an emphasis on efficiency
- **Model Optimization** — quantization, pruning, inference optimization, and making models leaner without sacrificing performance
- **Research → Implementation** — I read research papers and implement them. If a paper has interesting architecture or optimization ideas, I want to build it
- **Hardware-level AI** — currently exploring how AI workloads map to silicon: GPU/NPU architecture, CUDA programming, memory hierarchies, and chip design for AI inference
- **ML Math** — linear algebra, calculus, probability, and information theory as they underpin model behaviour
- **API*** - Actively learning and implementing APIs, focusing on design principles, integration patterns, and real-world use cases. Have successfully built and integrated multiple APIs as part of this exploration.
- **System design** - Focusing on building scalable, reliable, and efficient architectures. Applying concepts through practical implementations and projects.

---

## 🛠️ Tech Stack

**Languages:** Python · Dart · JavaScript · C++ · JAVA · CUDA
**ML/AI:** PyTorch · Scikit-learn · FAISS · Sentence Transformers · Autogen · GoogleADK  · CrewAI · Claude · NLP
**Backend:** FastAPI · Node.js · MongoDB · SQLite · PostgreSQL  
**Mobile/Cross-platform:** Flutter · React
**Tools:** Git · Docker · Kubernetes · Jenkins
**Cloud Platforms** - Google cloud platform · AWS · Microsoft Azure

---
 
## 💼 Experience

###🤖 AI & Backend Intern — AidenAI, Hyderabad
Present
Working across the full stack at an AI startup — from backend system design to building AI-powered applications.

Spanning backend architecture, system design, and applied AI development
Working in a fast-paced startup environment across multiple problem domains

Stack: actively expanding across backend systems and AI applications
---
 
### 🛰️ AI Intern — ISRO-ISTRAC (ISRO Telemetry, Tracking and Command Network), Bangalore
**Aug 2025 – Nov 2025**
 
Building production-grade Agentic AI systems for ISRO's ground operations — designed for offline, mission-critical deployment.
 
- **Multi-agent routing:** Designed a four-crew architecture (Intent Classification, Time-Series LLM, RAG, and Offline GPT) with an autonomous router agent for dynamic query assignment
- **Time-series extraction:** Built a pipeline to extract PIDs, mnemonics, statistical actions, and time ranges (relative and absolute) from natural language queries
- **Hybrid retrieval:** Implemented a fusion retriever combining BM25 + FAISS embeddings with feedback fusion — results improve continuously through user interactions
- **Document processing + RAG:** Converted complex technical PDFs into structured Markdown, embedded them for semantic retrieval, and enabled context-aware responses grounded in ISRO documentation
- **Offline GPT:** Integrated a local LLM (Ollama Llama 3.2) for robust, internet-independent operations
 
*Built using CrewAI · LangChain · FAISS · BM25 · Ollama · RAG pipelines*
 
---
 
## 🚀 Projects
 
### 🔍 Real-Time Defect Detection System (Object-Conditioned Anomaly Detection)
An unsupervised defect detection pipeline for industrial quality control — no labeled defect data required.
 
- Integrated **YOLO** for object localization to isolate target objects from complex scenes, reducing background noise and handling scale/orientation variation
- Applied **EfficientAD** (unsupervised anomaly detection) on extracted object regions — learns normal visual patterns during training and flags deviations as defects
- Detects both **local defects** (scratches, missing parts) and **global logical anomalies** (incorrect configurations) at millisecond-level inference speed
- Robust to real-time variations: illumination changes, orientation shifts, object size differences
- No defect-labeled training data required — suitable for high-speed industrial inspection
 
*Stack: Python · YOLO · EfficientAD · PyTorch · OpenCV*
 
---
 
### 🩺 LLM-Powered Health Report Summarizer
A secure web platform that processes medical PDFs and makes lab results accessible to non-specialist users — without the overhead of VLM-based full-image processing.
 
- **PDF → Markdown:** Used `docling` + RapidOCR to convert medical reports into structured markdown while preserving tables and lab values
- **Structured extraction:** Chunked markdown passed to a QWEN-based model with targeted prompts to extract lab test names, values, and units as JSON
- **JSON repair + cleaning:** Used `json-repair` to fix model outputs; filtered duplicates and irrelevant data
- **Patient-friendly summaries:** Highlights critical findings and abnormal values in plain language
- **Visualization + storage:** Extracted data securely stored and rendered in a dedicated visualization tab
- **Contextual chatbot:** Users can ask questions about their results; responses are grounded in the extracted lab values
 
*Stack: Python · QWEN · docling · RapidOCR · json-repair · FastAPI*
 
---
 
### 🚁 [AI-Payload Drone System (AIPDS)](https://github.com/Harika-Raju/DRONE)
**Sept 2024 – Jan 2025**
 
An autonomous AI-powered drone system for real-time human detection and strategic mission control.
 
- Deployed **YOLOv5** on **Jetson Xavier NX** for real-time human detection and object tracking at the edge
- Enabled strategic mission control via **DroneKit + MAVLink** protocol integration
- Built a **MERN stack** web app for live tracking, telemetry visualization, and remote command dispatch
- Achieved real-time analytics through GPU-accelerated asynchronous video processing
 
*Stack: Python · YOLOv5 · Jetson Xavier NX · DroneKit · MAVLink · MERN · CUDA*
 
---
 
### 🪐 [Chronicles of Exoplanet Exploration](https://github.com/Harika-Raju/Cosmic_Quest) — NASA Space Apps Hackathon 2024
**Sept 2024 – Oct 2024**
 
An educational Flutter app that gamifies exoplanet exploration, built for the NASA Space Apps Challenge.
 
- Planet type classifier using a **Random Forest** model served via **FastAPI**
- **RAG pipeline** with FAISS vector indexing + sentence transformers for dynamically generating interactive quizzes
- **SQLite** for offline data storage and seamless user experience
- User behaviour tracking to personalize learning paths
 
*Stack: Flutter · Python · FastAPI · FAISS · Sentence Transformers · SQLite*
 
---
 
### 🐑 [Farm to Fabric](https://github.com/Harika-Raju/Farm_to_fabric_wool)
**Oct 2023 – Jan 2024**
 
A cross-platform app digitally transforming India's wool sector.
 
- Supply chain mapping, quality assurance modules, and market analytics
- **Google Maps API** integration for geolocation-based service access and logistics
- Backend built with **Node.js + MongoDB**; data handling via CSV parsing
 
*Stack: Flutter · Node.js · MongoDB · Google Maps API · JavaScript*
 
---


## 📚 What I'm Currently Exploring

- MLSys — systems-level optimization for ML (kernel fusion, memory layout, tiling strategies)
- AI chip architecture — how TPUs and NPUs are designed around tensor operations
- Reading and implementing papers on attention mechanisms, efficient transformers, and model compression
- CUDA programming basics for GPU-accelerated ML

---

## 📫 Connect

[![LinkedIn](www.linkedin.com/in/harikaraju2005)
[![GitHub]](https://github.com/Harika-Raju)

---

*"The best way to understand a model is to implement it yourself."*
<!--
**Harika-Raju/Harika-Raju** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
