<div align="center">

  <img src="assets/header.svg" width="100%" alt="Yogeshvar — Software × AI/ML Engineer" />

  <br /><br />

  <a href="https://github.com/Yogeshvar425?tab=repositories">
    <img src="https://img.shields.io/badge/Explore_projects-1e293b?style=flat-square&logo=github&logoColor=white" alt="Projects" />
  </a>&nbsp;
  <a href="https://www.linkedin.com/in/yogeshvarvs" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>&nbsp;
  <a href="mailto:vsyogeshvar425@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>

</div>

---

## About

I am **Yogeshvar**, a B.Tech Computer Science Engineering student at **Dayananda Sagar University**, graduating in **2027**.

I build and ship production-grade systems across edge AI, computer vision, NLP pipelines, and backend microservices. My work prioritizes **real hardware constraints, measurable performance benchmarks, and software that works outside a demo environment**.

Currently open to **2026/2027 Software Engineering & AI/ML internships**.

---

## Technical focus

| Edge AI and inference | Computer vision | NLP and classical ML |
|---|---|---|
| TensorRT optimization, FP16 quantization, constrained-memory deployment on NVIDIA Jetson, and local-first LLM/VLM inference | Real-time detection and tracking pipelines (YOLOv8, ByteTrack), facial recognition (FaceNet512), and multi-stream processing | TF-IDF feature engineering, SVM and Logistic Regression classifiers, stratified evaluation, and high-speed REST inference |

---

## Stack

| Layer | Technologies |
| :--- | :--- |
| Edge AI and inference | `NVIDIA Jetson` · `TensorRT (FP16)` · `YOLOv8n` · `ByteTrack` · `FaceNet512` · `llama.cpp` |
| Machine learning and NLP | `PyTorch` · `Scikit-learn` · `OpenCV` · `TF-IDF` · `SVM` · `Logistic Regression` |
| Backend and services | `FastAPI` · `Flask` · `REST APIs` · `YouTube Data API` |
| Languages | `Python` · `Java` · `C` · `C++` · `SQL` · `JavaScript` |
| Platforms and tooling | `Linux (Ubuntu)` · `Bash` · `Git` · `GitHub` · `VS Code` |

---

## Systems — Featured

### 01 — [SENTINEL SURVEILLANCE](https://github.com/Yogeshvar425/Sentinel-Surveillance) `SHIPPED`

**Real-time edge-AI surveillance for NVIDIA Jetson: detect, track, identify, and understand locally.**

```
RTSP camera → detection and tracking → face recognition → local VLM analysis → dashboard and alerts
```

Shipped prototype:

- Modular real-time computer vision pipeline on **NVIDIA Jetson** hardware running **YOLOv8n detection + ByteTrack tracking + FaceNet512 recognition** concurrently at **28 FPS**
- Deep learning models quantized to **FP16 via TensorRT**, reducing inference latency by **~65%** (120 ms → 35–45 ms) to fit within embedded hardware thermal and power constraints
- On-device Vision-Language Model inference via `llama.cpp` generating structured JSON scene descriptions with **zero cloud dependency**
- Flask-based live monitoring console for real-time video feeds, event telemetry, and hardware health metrics

**Verified engineering signals:** `28 FPS sustained` · `~65% latency reduction (FP16)` · `zero-cloud local VLM`

`Python` · `NVIDIA Jetson` · `TensorRT` · `YOLOv8n` · `ByteTrack` · `FaceNet512` · `llama.cpp` · `Flask`

---

### 02 — [TRUE SENTIMENT](https://github.com/Yogeshvar425/TrueSentiment) `SHIPPED`

**End-to-end NLP sentiment analysis pipeline with automated data collection and high-speed REST inference.**

```
YouTube Data API ingestion → spam filtering → text preprocessing → model training → FastAPI service → live dashboard
```

Shipped service:

- Automated YouTube comment collection pipeline with custom spam/bot filtration and text normalization
- Trained Logistic Regression and SVM classifiers using TF-IDF bigram features, validated via 5-fold stratified cross-validation achieving **~76% accuracy** on noisy real-world data
- Deployed as an asynchronous **FastAPI REST microservice** with sub-**50 ms** inference response latency
- Lightweight JavaScript/HTML5 Canvas dashboard for real-time request queue throughput monitoring

**Verified engineering signals:** `~76% accuracy (noisy data)` · `<50 ms API response` · `5-fold stratified CV`

`Python` · `Scikit-learn` · `TF-IDF` · `SVM` · `FastAPI` · `REST API` · `YouTube Data API` · `HTML5 Canvas`

---

### 03 — ARIA `ACTIVE BUILD`

**Local-first agentic AI system with on-device multimodal intelligence, autonomous tool-use, and edge-native execution.**

A fully local autonomous agent that combines voice interaction, vision-language understanding, and agentic orchestration — running entirely on edge hardware with zero cloud dependency.

Building with:

`Python` · `llama.cpp` · `NVIDIA Jetson` · `Agentic workflows` · `Function calling` · `Computer vision` · `Local LLM/VLM inference`

---

## Interests

`Local-first AI` · `Edge inference` · `Computer vision` · `Systems engineering` · `NLP & language models` · `Production software`

---

<div align="center">

> `build_status: curious / shipping / learning`

</div>

<br />

<div align="center">
  <img src="assets/footer.svg" width="100%" alt="—" />
</div>
