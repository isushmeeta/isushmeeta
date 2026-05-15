## Hi there 👋


<h1 align="center">Sushmita </h1>
<h3 align="center">AI Engineer · Full-Stack Developer · ML Researcher</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/isushmeeta/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:sushmitah0199@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/isushmeeta">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## About Me

Computer Science graduate from **Brac University, Dhaka** building production-grade AI and full-stack systems.

I've shipped an **AI-powered hospital management system** combining Gemini LLM and Random Forest classifiers, an **NLP pipeline for sentiment analysis and fake review detection** on Amazon datasets, and a full-stack food ordering platform. Currently exploring **neural style transfer** (PyTorch / VGG19) and **distributed parallel computing**.

I'm looking for **AI engineering, backend, or ML roles** — internships or full-time — where I can contribute real impact from day one.

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### AI / Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### Backend & APIs
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

### Databases & DevOps
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🚀 Projects
---

### [🎨 ArtifyAI — Neural Style Transfer System](https://github.com/isushmeeta/ArtifyAI)
> Python · PyTorch · VGG19 · AdaIN · Flask · Computer Vision

Built an end-to-end neural style transfer web application from scratch using **Adaptive Instance Normalization (AdaIN)** — a real-time feed-forward approach that decouples style from content without per-image optimization.

- Trained a custom **decoder network** paired with a frozen VGG19 encoder, optimizing a weighted combination of **perceptual content loss** and **Gram matrix-based style loss** across multiple feature layers
- Implemented **AdaIN normalization** to align channel-wise mean and variance of content features with style features, enabling arbitrary style transfer at inference time
- Deployed as a **Flask web app** with adjustable style strength (alpha blending) and real-time image preview

---
### 🏥 [AI-Powered Hospital Management System](https://github.com/isushmeeta/AI-HMS)
> React · Flask · Gemini LLM · Scikit-learn · PostgreSQL · JWT · RBAC

A modular, role-based healthcare platform for Admin, Doctor, Patient, and Receptionist workflows built on a decoupled REST architecture.

- **Dual-AI pipeline**: Random Forest classifiers for clinical risk prediction + Gemini LLM for diagnostic reasoning and automated SOAP note generation
- Drug–drug interaction detection and AI-assisted triage to automate risk flagging across patient records
- JWT authentication with fine-grained RBAC; PostgreSQL with JSONB for semi-structured longitudinal patient histories

---

### 🔍 [Sentiment Classification & Fake Review Detection — Amazon Reviews](https://github.com/isushmeeta/Sentiment-Classification-and-Fake-Review-Detection-on-Amazon-Reviews)
> Python · NLP · Scikit-learn · PyTorch · NLTK · Deep Learning · BERT

End-to-end NLP system for dual-task classification on large-scale Amazon review data.

- Sentiment analysis (positive / negative / neutral) + deceptive review detection in a single pipeline
- Text preprocessing: tokenisation, stopword removal, lemmatisation, TF-IDF and word embedding feature extraction
- Trained and benchmarked Logistic Regression, SVM, LSTM, and BERT — evaluated on accuracy, F1-score, and ROC-AUC
- Ensemble methods and metadata feature engineering improved fake review detection accuracy

---

### [⚙️ Distributed Parallel Processing System] (https://github.com/isushmeeta/Stream-ML) *(In Progress )*
> Python · Distributed Systems · Multiprocessing · Message Queues · Fault Tolerance

Task scheduler distributing compute workloads across parallel worker nodes with fault-tolerance and automatic retry on node failure.

- Implementing producer-consumer message queue patterns for inter-process communication and dynamic load balancing

---

### 🍔 [BiteBuddy — Full-Stack Food Ordering System](https://github.com/isushmeeta/BiteBuddy)
> MongoDB · Express.js · React · Node.js (MERN) · TailwindCSS

Full-stack food ordering platform with JWT-secured authentication, product listings, cart management, and end-to-end order processing.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=isushmeeta&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=isushmeeta&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=isushmeeta&theme=tokyonight&hide_border=true"/>
</p>

---

## 🌱 Currently Building

- 🎨 **Neural Style Transfer** — VGG19-based perceptual style synthesis (PyTorch)
- ⚙️ **Distributed Task Scheduler** — fault-tolerant parallel computing system
- 🤖 **AI/ML Coursework** — Prime Complete AI/ML, Apna College

---

<p align="center">
  <i>Open to AI engineering, backend, and ML internships / full-time roles · Bangladesh & Remote</i><br/>
  <a href="mailto:sushmitah0199@gmail.com">sushmitah0199@gmail.com</a>
</p>

