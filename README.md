<h1 align="center">Christopher Simon Garcia</h1>
<h3 align="center">Systems Engineer · Home Lab Architect · AI Infrastructure Builder</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Role-Maintenance%20Technician-0d1117?style=flat-square&logo=wrench&logoColor=white" />
  <img src="https://img.shields.io/badge/Company-CBRE%20%7C%20ASML%20San%20Diego-blue?style=flat-square&logo=building&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-San%20Diego%2C%20CA-orange?style=flat-square&logo=google-maps&logoColor=white" />
</p>

<p align="center">
  Maintenance Technician at CBRE supporting ASML San Diego — and on my own time, I build and operate a distributed AI home lab that runs production-grade inference, computer vision pipelines, and automated security systems across a three-node cluster.
</p>

---

## 🖥️ CHRIDCUH — Distributed AI Home Lab

> A self-hosted, multi-node AI stack connected via Tailscale, designed for real workloads — not tutorials.

| Node | OS | CPU | GPU | Role |
|---|---|---|---|---|
| **ROBIN** | Ubuntu 24.04 | Ryzen 7 5700X | GTX 1080 Ti | Primary AI inference · Frigate NVR · ML pipelines |
| **OP** | Windows 11 | Ryzen 7 7700 | RTX 4060 Ti | Secondary compute · Gaming rig |
| **The Rift** | Home Assistant OS | — | — | Automation hub · MQTT broker |

---

## 🛠️ Tech Stack

**AI & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logo=databricks&logoColor=white)

**Infrastructure & Automation**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-41BDF5?style=flat-square&logo=home-assistant&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-3C5280?style=flat-square&logo=eclipse-mosquitto&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-000000?style=flat-square&logo=linux&logoColor=white)

**Data & Storage**

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Frigate NVR](https://img.shields.io/badge/Frigate%20NVR-00B300?style=flat-square&logo=camera&logoColor=white)

---

## 🚀 Projects

### 🔍 ReID Surveillance System
Person re-identification using **OSNet ONNX** embeddings integrated with **Frigate NVR**. Tracks subjects across camera zones using a custom SQLite database, with a Flask-based SOC dashboard featuring clip playback, priority flagging, and exportable investigation reports.

### 🛡️ Active Defense Layer
A **TFX-based ML pipeline** for security event classification, combining blended ML scoring with rule-based heuristics. Models are automatically promoted to production inference when validation thresholds are met — no manual intervention required.

### 🗣️ JARVIS Voice Assistant
Full local voice pipeline: wake word detection (**openWakeWord**) → speech-to-text (**faster-whisper**) → LLM reasoning (**Ollama**) → text-to-speech (**Piper**). Audio is bridged between nodes over UDP, keeping latency low and all processing on-premise.

### 📡 SOAR-Lite MQTT Automation
Lightweight security orchestration built on MQTT — handles threat fusion, SSH lockdown delegation, and self-DoS protection via a Tailscale CIDR safelist. Designed to operate autonomously with minimal operational overhead.

### 🧠 ChromaDB Vector Memory
A persistent semantic memory layer with **12,000+ ingested entries** spanning game session logs, operational notes, and system state. Enables semantic recall across the entire CHRIDCUH stack.

---

## ⚙️ Outside the Terminal

When I'm not pushing commits, I'm doing one of these:

- **3D Printing** — Functional prints, enclosures, and lab hardware mounts
- **Game Modding** — Digging into game internals and building custom tools
- **Anaheim Ducks 🏒🦆** — Season follower, always
- **Mazda Miata Wrenching** — Keeping it running, keeping it fun

---

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Collaboration-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Home%20Lab%20%26%20AI%20Infrastructure-blueviolet?style=flat-square" />
</p>
