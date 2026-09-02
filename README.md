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

I am **Yogeshvar**, a B.Tech Computer Science Engineering student at **Dayananda Sagar University**, graduating in **2027**. I build and ship production-grade systems across edge AI, computer visi[...]

**Currently open to 2026/2027 Software Engineering & AI/ML internships.**

---

## Quick Stats

- **3 shipped projects** spanning edge AI, computer vision, and NLP inference
- **28 FPS real-time** surveillance pipeline on constrained NVIDIA Jetson hardware
- **~65% latency reduction** via FP16 quantization and TensorRT optimization
- **~76% accuracy** on noisy real-world sentiment classification
- **Zero cloud dependency** — all models run entirely on-device

---

## What I work on

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>Edge AI &amp; Inference</h4>
      <p>TensorRT optimization, FP16 quantization, constrained-memory deployment on NVIDIA Jetson, and local-first LLM/VLM inference via llama.cpp.</p>
    </td>
    <td width="33%" valign="top">
      <h4>Computer Vision</h4>
      <p>Real-time detection and tracking pipelines (YOLOv8, ByteTrack), facial recognition (FaceNet512), and multi-stream edge processing at production frame rates.</p>
    </td>
    <td width="33%" valign="top">
      <h4>NLP &amp; Classical ML</h4>
      <p>TF-IDF feature engineering, SVM and Logistic Regression classifiers, stratified evaluation pipelines, and high-throughput REST inference microservices.</p>
    </td>
  </tr>
</table>

---

## Why me?

- **Shipping mindset:** All 3 projects are production-deployed and actively monitored—not just notebooks or Kaggle kernels.
- **Hardware-aware optimization:** Not just model development—deep focus on actual inference constraints (FP16, quantization, latency budgets, memory footprint).
- **End-to-end architecture:** From automated data collection → preprocessing → training → production inference → monitoring & telemetry.
- **Local-first philosophy:** Zero cloud dependency, privacy-by-design, and edge-native deployments.

---

## Projects

### Sentinel Surveillance — `shipped`

> Real-time edge-AI surveillance for NVIDIA Jetson: detect, track, identify, and understand locally.

<a href="https://github.com/Yogeshvar425/Sentinel-Surveillance"><img src="https://img.shields.io/badge/View_repository-1e293b?style=flat-square&logo=github&logoColor=white" alt="Repo" /></a>

**Pipeline:** `RTSP camera → detection + tracking → face recognition → local VLM analysis → dashboard + alerts`

- Modular real-time vision system on **NVIDIA Jetson** running **YOLOv8n + ByteTrack + FaceNet512** at **28 FPS**
- Models quantified to **FP16 via TensorRT** — inference latency reduced by **~65%** (120 ms → 35–45 ms)
- On-device VLM via `llama.cpp` for structured JSON scene intelligence, **zero cloud dependency**
- Flask live console for video feeds, event telemetry, and hardware health monitoring

<details>
<summary>Engineering signals</summary>
<br />

| Metric | Value |
| :--- | :--- |
| Sustained frame rate | 28 FPS |
| Latency reduction (FP16) | ~65% (120 ms → 35–45 ms) |
| Cloud dependency | None — fully local VLM |

`Python` · `NVIDIA Jetson` · `TensorRT` · `YOLOv8n` · `ByteTrack` · `FaceNet512` · `llama.cpp` · `Flask`

</details>

---

### TrueSentiment — `shipped`

> End-to-end NLP sentiment analysis with automated data collection and high-speed REST inference.

<a href="https://github.com/Yogeshvar425/TrueSentiment"><img src="https://img.shields.io/badge/View_repository-1e293b?style=flat-square&logo=github&logoColor=white" alt="Repo" /></a>

**Pipeline:** `YouTube Data API → spam filtering → preprocessing → model training → FastAPI service → live dashboard`

- Automated comment collection with custom spam/bot filtration and text normalization
- Logistic Regression and SVM classifiers with TF-IDF bigram features — **~76% accuracy** on noisy real-world data (5-fold stratified CV)
- Asynchronous **FastAPI REST microservice** with sub-**50 ms** inference latency
- HTML5 Canvas dashboard for live request throughput visualization

<details>
<summary>Engineering signals</summary>
<br />

| Metric | Value |
| :--- | :--- |
| Accuracy (noisy data) | ~76% |
| API response latency | <50 ms |
| Validation method | 5-fold stratified cross-validation |

`Python` · `Scikit-learn` · `TF-IDF` · `SVM` · `FastAPI` · `REST API` · `YouTube Data API` · `HTML5 Canvas`

</details>

---

### Aria — `shelved`

> Local-first agentic AI: voice interaction, vision-language understanding, and autonomous tool-use — intended for edge hardware.

A local autonomous agent combining multimodal perception with agentic orchestration and function calling. Development is currently shelved.

**Status:** Shelved — development paused

`Python` · `llama.cpp` · `NVIDIA Jetson` · `Agentic workflows` · `Function calling` · `Computer vision` · `Local LLM/VLM`

---

## Stack

| Layer | Technologies |
| :--- | :--- |
| Edge AI and inference | `NVIDIA Jetson` · `TensorRT (FP16)` · `YOLOv8n` · `ByteTrack` · `FaceNet512` · `llama.cpp` |
| Machine learning and NLP | `PyTorch` · `Scikit-learn` · `OpenCV` · `TF-IDF` · `SVM` · `Logistic Regression` |
| Backend and services | `FastAPI` · `Flask` · `REST APIs` · `YouTube Data API` |
| Languages | `Python` · `Java` · `SQL` · `JavaScript` |
| Platforms and tooling | `Linux (Ubuntu)` · `Bash` · `Git` · `GitHub` · `VS Code` |

---

## Interests

`Local-first AI` · `Edge inference` · `Computer vision` · `Systems engineering` · `NLP & language models` · `Production software`

---

## Get in touch

- **Email:** [vsyogeshvar425@gmail.com](mailto:vsyogeshvar425@gmail.com)
- **LinkedIn:** [@yogeshvarvs](https://www.linkedin.com/in/yogeshvarvs)
- **GitHub:** [@Yogeshvar425](https://github.com/Yogeshvar425)

Open to **2026/2027 internships** in Software Engineering & AI/ML.

---

<div align="center">
  <img src="assets/footer.svg" width="100%" alt="—" />
</div>
