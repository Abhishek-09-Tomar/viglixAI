# SentinelAI: AI-Powered Cyber Defense System

## 🚀 Project Overview

**SentinelAI** is an intelligent and autonomous system designed to detect, track, and respond to cyberattacks in real-time. It combines AI/ML, OSINT tools, and secure software practices to create an effective cyber defense solution.

---

## 🧩 System Architecture

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

## ⚙️ Tech Stack

| Module                     | Primary Tech                     | Alternatives                     |
|---------------------------|----------------------------------|----------------------------------|
| Web App                   | Flask / Node.js                  | Spring Boot, Express             |
| WAF                       | ModSecurity (with Nginx)         | Cloudflare, OpenWAF              |
| Logging                   | ELK Stack                        | Loki + Prometheus                |
| AI/ML                     | Python + Scikit-learn / TensorFlow | AutoML, PyTorch               |
| OSINT                     | SpiderFoot, Sherlock, Recon-ng   | Maltego                          |
| Automation                | Bash, Python, Cron               | Ansible                          |
| Alerts                    | Telegram Bot, Discord Webhooks   | Email, Slack                     |
| Dashboard                 | React + TailwindCSS              | Streamlit, Flask Templates       |
| Shell Tools               | Kali Linux CLI tools             | Parrot OS                        |

---

## 📦 Project Structure

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
└── README.md
```

---

## 🔧 Setup Instructions

### 1. Environment Setup
- OS: Kali Linux / Ubuntu Server
- Install: Python, Git, Flask or Node.js, Nginx

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Start Backend Server
```bash
python backend/app.py
```

### 4. Run WAF and Configure ModSecurity
- Configure ModSecurity with custom rules in Nginx

### 5. Launch Dashboard
```bash
cd frontend/dashboard
npm install
npm start
```

---

## 🤖 Machine Learning Integration

- Collect data: Normal vs. Malicious traffic logs
- Models: Isolation Forest, Random Forest, LSTM
- Deployment: Served as REST API using Flask

---

## 🕵️‍♂️ OSINT Integration

- Tools: Sherlock, SpiderFoot, whois, Shodan, ipinfo.io
- Scripts automate attacker profiling, fingerprinting, and tracking

---

## 📊 Visualization & Alerts

- Dashboard built using React or Streamlit
- Alerts: Telegram, Discord Webhooks, Slack

---

## 🛡️ Security Response Handler

- Auto-block IPs using iptables
- Log threats and respond in real-time
- Integrate OSINT + ML triggers for advanced protection

---

## 💡 Optional Advanced Modules

- **Honeypots**: Trap attackers with fake admin panels
- **Geo-Intelligence**: Use IP & headers for geo-tracking
- **Threat DB**: Maintain attacker fingerprint database
- **Legal Logger**: Generate chain-of-custody reports

---

## 📁 Deliverables

- ✅ `README.md` with documentation (this file)
- ✅ Sample ML detection scripts
- ✅ OSINT automation toolkit
- ✅ Auto-hardening scripts
- ✅ Dashboard UI wireframes or code

---

## ⚠️ Disclaimer

This project is meant **strictly for educational and ethical research purposes**. All active defense mechanisms must comply with local laws and regulations.

---

## 🧠 Contributors

- **Cybersecurity Specialist**: Arpit Rana
- **Full Stack & AI/ML Developer**: Abhishek Tomar

- **Cybersecurity Specialist**: Network defense, OSINT, automation
- **Full Stack & AI/ML Developer**: Web backend, ML engine, dashboard