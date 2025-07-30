###  SentinelAI: AI-Powered Cyber Defense System

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%2FWeb-blue" />
  <img src="https://img.shields.io/badge/AI-Enabled-success" />
  <img src="https://img.shields.io/badge/Cybersecurity-Focused-critical" />
</p>

---

##  Project Overview

**SentinelAI** is an autonomous system to detect, analyze, and respond to cyberattacks in real-time using AI/ML, OSINT, and automation.

---

##  System Architecture

```
[ User Request ]
       ↓
[ Web App Firewall (WAF) ]
       ↓
[ Logging + Behavior Capture ]──▶ [AI/ML Anomaly Detection]
       ↓                                    │
  [ Web Server ]                            ▼
       ↓                          [Threat Classification Engine]
[ App Code + DB ]                          │
       ↓                                   ▼
 [ Security Response Handler ] ─────▶ [OSINT + Fingerprinting]
       ↓                                   │
 [ Alerting + Logging ] ◀───────┐          ▼
                               [Visualization + Dashboard]
```

---

##  Tech Stack

| Module          | Tech Used                                                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| 💻 Web App      | ![Flask](https://img.shields.io/badge/-Flask-black?logo=flask) ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js)              |
| 🔐 WAF          | ModSecurity + Nginx                                                                                                                               |
| 📊 Logging      | ELK Stack (Elasticsearch, Logstash, Kibana)                                                                                                       |
| 🤖 AI/ML        | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow) |
| 🕵️ OSINT       | Sherlock, SpiderFoot, Recon-ng                                                                                                                    |
| 🔁 Automation   | Bash, Python, Cron                                                                                                                                |
| 🚨 Alerts       | Telegram, Discord, Slack                                                                                                                          |
| 🧑‍🎨 Dashboard | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react) TailwindCSS                                                                       |

---

## Project Structure

```
SentinelAI/
│
├── backend/
│   ├── app.py                # Flask or Node.js backend
│   ├── ml_model/             # Trained ML models
│   └── scripts/              # IP blocking, OSINT integration
│
├── frontend/
│   ├── dashboard/            # React or Streamlit UI
│   └── assets/               # Static files and styles
│
├── osint_toolkit/
│   ├── spiderfoot_runner.py  # Automation scripts for OSINT
│   └── sherlock_runner.py
│
├── logging_monitoring/
│   ├── logstash.conf         # Logstash configuration
│   └── dashboards/           # Kibana dashboards
│
├── scripts/
│   ├── hardening.sh          # Auto-hardening bash script
│   └── deploy.sh             # Deployment automation
│
└── README.md                 # Project documentation

```

---

##  Setup Instructions

1. **Environment**: Kali Linux or Ubuntu
2. **Install Dependencies**:

```bash
pip install -r requirements.txt
```

3. **Run Backend**:

```bash
python backend/app.py
```

4. **Frontend**:

```bash
cd frontend/dashboard
npm install && npm start
```

---

##  ML Integration

* Models: Isolation Forest, LSTM, Random Forest
* Exposed via Flask REST API
* Trained on network logs (normal vs attack)

---

## OSINT Tools

* Sherlock, SpiderFoot, Whois, Shodan
* Auto-run via cron/python integration

---

## Visualization

* UI: React + TailwindCSS
* Shows: attack sources, blocked IPs, OSINT data
* Alerts via: Discord, Telegram, Slack

---

## Advanced Features

| Feature         | Description                     |
| --------------- | ------------------------------- |
| 🎯 Honeypots    | Trap attackers with fake panels |
| 🌍 Geo-Intel    | IP + headers + time tracking    |
| 🧬 Threat DB    | Attacker fingerprint archive    |
| 🧾 Legal Logger | Chain-of-custody audit logs     |

---

## Deliverables

✅ Dashboard & Backend
✅ ML & OSINT Scripts
✅ Automation Tools
✅ Documentation (`README.md`)

---

##  Disclaimer

> **Ethical Use Only** — Comply with local cyber laws before deploying.

---

## 👨‍💻 Contributors

| Name               | Role                                      |
| ------------------ | ----------------------------------------- |
| **Arpit Rana**     | Cybersecurity Specialist (Defense, OSINT) |
| **Abhishek Tomar** | Full Stack & AI/ML Developer              |
