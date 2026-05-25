### Chris — Systems Engineer & Home Lab Architect

Maintenance Technician @ CBRE | ASML San Diego | Building distributed AI infrastructure in my spare time. Santa Ana raised.

## CHRIDCUH — Distributed AI Home Lab

A production-grade, multi-node AI stack running across three machines connected via Tailscale.

**Stack:** Python · Frigate NVR · Home Assistant · Ollama · MQTT (TLS) · ChromaDB · Docker · systemd · FastAPI · SQLite · OSNet ONNX

**Nodes:**
- `ROBIN` — Ubuntu 24.04 · Ryzen 7 5700X · GTX 1080 Ti — Primary AI inference, Frigate, pipelines
- `OP` — Windows 11 · Ryzen 7 7700 · RTX 4060 Ti — Gaming rig / secondary compute
- `The Rift` — Home Assistant OS — Automation hub, MQTT broker

## Projects
- 🔍 **ReID Surveillance System** — Person re-identification using OSNet ONNX embeddings, Frigate NVR, custom SQLite tracking DB, and a Flask SOC dashboard with clip playback, priority flagging, and investigation reports
- 🛡️ **Active Defense Layer** — TFX-based ML pipeline for security event classification with blended ML + rule-based scoring promoting models to production inference
- 🗣️ **JARVIS Voice Assistant** — Wake word (openWakeWord) → STT (faster-whisper) → LLM (Ollama) → TTS (Piper) with UDP audio bridge between nodes
- 📡 **SOAR-Lite MQTT Automation** — Threat fusion, SSH lockdown delegation, self-DoS protection via Tailscale CIDR safelist
- 🧠 **ChromaDB Vector Memory** — 12,000+ ingested entries, game session logging, semantic recall across the stack

## Other Interests
3D printing · Game modding · Anaheim Ducks · Mazda Miata wrenching

## Certs in Progress
EPA 608 Universal