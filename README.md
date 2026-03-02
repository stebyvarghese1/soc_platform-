<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,8&height=240&section=header&text=SOC%20Platform&fontSize=74&fontColor=ffffff&fontAlignY=42&desc=AI-Automated%20Security%20Operations%20Center%20%E2%80%94%20Real-Time%20Threat%20Intelligence.&descAlignY=63&descSize=16&descColor=94a3b8&animation=fadeIn" width="100%"/>

</div>

<br>

<div align="center">

   AI-Powered  ·  Real-Time  ·  Cross-Platform  ·  Auto-Mitigation

</div>

<br>

<div align="center">

[![Flask](https://img.shields.io/badge/Flask-SocketIO-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com/atlas)
[![NLP](https://img.shields.io/badge/🤗_MiniLM-Transformers-FFD21E?style=for-the-badge)](https://huggingface.co)
[![Redis](https://img.shields.io/badge/Redis-WebSocket-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io)
[![ReportLab](https://img.shields.io/badge/ReportLab-PDF_Reports-FF6F61?style=for-the-badge&logo=python&logoColor=white)](https://reportlab.com)
[![License](https://img.shields.io/badge/License-MIT-fbbf24?style=for-the-badge)](LICENSE)

<br>

[![Stars](https://img.shields.io/github/stars/stebyvarghese1/soc_platform-?style=flat-square&color=fbbf24&label=⭐%20Stars)](https://github.com/stebyvarghese1/soc_platform-/stargazers)
&nbsp;
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-38bdf8?style=flat-square)](#)
&nbsp;
[![Built by](https://img.shields.io/badge/by-Steby%20Varghese-a78bfa?style=flat-square)](https://github.com/stebyvarghese1)

</div>

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 01 `&nbsp;&nbsp; THE PRODUCT

</div>

<br>

<div align="center">

<img src="https://github.com/user-attachments/assets/b0ca0118-672d-456e-a440-aad7526549a4" width="96%"/>
<br><br>
<b>📊 THREAT DASHBOARD</b>
<br>
<sub>Real-time log aggregation, AI threat detection, and live severity analytics.</sub>

<br><br>

<img src="https://github.com/user-attachments/assets/f6b93f46-700e-41f8-97e1-f4b20357f9eb" width="96%"/>
<br><br>
<b>🔐 SECURE LOGIN & CREDENTIAL MANAGEMENT</b>
<br>
<sub>Hardened authentication gateway before accessing the operations center.</sub>

</div>

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 02 `&nbsp;&nbsp; THE IDEA

</div>

<br>

> ### *"A full Security Operations Center — AI threat detection, real-time alerts, auto-blocking, and PDF reporting. In a single open-source platform."*

<br>

**SOC Platform** is a production-grade, open-source security operations center that aggregates logs from multiple systems across your network, runs them through three layers of threat detection (rule-based, anomaly-based, and AI/NLP), fires real-time WebSocket alerts, and auto-responds to threats — all from a single dashboard.

```
  ┌──────────────────────────────────────────────────────────────┐
  │  🌐  Multi-system log aggregation  (local + external agents) │
  │  🧠  Three detection engines       (rules + anomaly + AI)    │
  │  ⚡  Real-time WebSocket alerts    (instant notifications)   │
  │  🚫  Automated mitigation          (block + isolate + log)   │
  │  📄  PDF SOC reports               (charts + full analysis)  │
  └──────────────────────────────────────────────────────────────┘
```

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 03 `&nbsp;&nbsp; FEATURES

</div>

<br>

<div align="center">

| &nbsp; | Feature | Description |
|--------|---------|-------------|
| 🌐 | **Log Aggregation** | Collect logs from Windows, Linux, macOS — local or remote agents |
| 🔍 | **AI / NLP Detection** | Semantic threat matching via MiniLM sentence-transformers |
| 📖 | **Rule-Based Engine** | Custom regex patterns with configurable severity levels |
| 📊 | **Anomaly Detection** | Log vector comparison against historical baselines |
| 🚫 | **Auto-Mitigation** | IP blocking via iptables · isolation · timestamped action log |
| 📡 | **Real-Time Alerts** | Live dashboard notifications via WebSocket + Redis pub/sub |
| 📄 | **PDF SOC Reports** | Export threat summaries, charts, and log details via ReportLab |
| 🔒 | **Secure Auth** | Protected login with credential management |

</div>

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 04 `&nbsp;&nbsp; THREAT DETECTION ENGINE

</div>

<br>

<div align="center">

```
  ┌─────────────────────────────────────────────────────────────────┐
  │                   THREE DETECTION LAYERS                        │
  ├────────────────────┬────────────────────────────────────────────┤
  │                    │                                            │
  │  LAYER 1           │  Rule-Based                                │
  │                    │  Regex pattern matching · custom severity  │
  │                    │  Fully editable in the UI                  │
  │                    │                                            │
  ├────────────────────┼────────────────────────────────────────────┤
  │                    │                                            │
  │  LAYER 2           │  Anomaly-Based                             │
  │                    │  Log vectors vs. historical baseline data  │
  │                    │  Catches unknown patterns                  │
  │                    │                                            │
  ├────────────────────┼────────────────────────────────────────────┤
  │                    │                                            │
  │  LAYER 3           │  AI / NLP                                  │
  │                    │  Semantic matching via MiniLM embeddings   │
  │                    │  Pre-trained on security corpora           │
  │                    │                                            │
  └────────────────────┴────────────────────────────────────────────┘
```

</div>

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 05 `&nbsp;&nbsp; ARCHITECTURE

</div>

<br>

<div align="center">

```
  ┌─────────────────────┐    ┌────────────────────────────────────────┐
  │  External Agents     │    │          SOC Platform Server           │
  │  (log_collection.py) │    │                                        │
  │  Windows / Linux /   │───▶│  Flask + SocketIO  (app.py)           │
  │  macOS               │    │  Detection Engine  (rules+anomaly+AI)  │
  └─────────────────────┘    │  Mitigation Engine (iptables/isolate)  │
                              └────────┬──────────────┬───────────────┘
                                       │              │
                          ┌────────────▼──┐  ┌────────▼───────────┐
                          │  MongoDB Atlas │  │  Redis + WebSocket │
                          │  Logs · Threats│  │  Real-time alerts  │
                          │  Rules · Users │  │  to dashboard UI   │
                          └───────────────┘  └────────────────────┘
```

</div>

<br>

<div align="center">

| Layer | Technology |
|-------|-----------|
| ⚙️ **Backend** | Flask · Flask-SocketIO · Python |
| 🗄️ **Database** | MongoDB Atlas |
| 🧠 **AI / NLP** | sentence-transformers · MiniLM embeddings |
| 📡 **Real-Time** | WebSocket · Redis pub/sub |
| 📄 **Reporting** | ReportLab · Matplotlib |
| 🌐 **Frontend** | HTML · CSS · JavaScript |
| 🔗 **Log Agents** | Cross-platform Python agent (Windows · Linux · macOS) |

</div>

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 06 `&nbsp;&nbsp; GETTING STARTED

</div>

<br>

**Prerequisites** — Python 3.x · Redis (local or Docker) · MongoDB Atlas account

<br>

**Step 1 — Clone**
```bash
git clone https://github.com/stebyvarghese1/soc_platform-.git
cd soc_platform-
```

**Step 2 — Install dependencies**
```bash
pip install flask flask-socketio pymongo sentence-transformers reportlab matplotlib
```

> Redis must be running locally or via Docker before launching.

**Step 3 — Launch the platform** *(admin privileges required)*
```bash
python app.py
```

<div align="center">

> 🟢 &nbsp;**`http://localhost:5000`** &nbsp;— your SOC is operational.

</div>

**Step 4 — Deploy external log agents**

Edit `log_collection/log_collection.py` — set `API_IP` to your platform server, then run on any machine you want to monitor:
```bash
python log_collection.py
```

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 07 `&nbsp;&nbsp; PROJECT STRUCTURE

</div>

<br>

```
soc_platform/
│
├── app.py                          ← Main Flask application & detection engine
│
├── log_collection/
│   └── log_collection.py           ← External agent — deploy on monitored systems
│
└── templates/
    ├── login.html                  ← Secure authentication page
    ├── logs.html                   ← Live log & threat dashboard
    └── logo.jpg                    ← UI branding asset
```

<br>
<br>

---

<div align="center">

## &nbsp;&nbsp;&nbsp;` 08 `&nbsp;&nbsp; SOC REPORT

</div>

<br>

From the dashboard, click **"Download SOC Report"** to export a full PDF containing:

<div align="center">

```
  📋  Threat summary & severity breakdown
  📊  Visual threat charts (Matplotlib)
  🗒️  Full log details with timestamps
  🔎  Severity analysis & mitigation actions taken
```

</div>

<br>
<br>

---

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,8&height=130&section=footer&animation=fadeIn" width="100%"/>

### Built to defend the digital world by [Steby Varghese](https://github.com/stebyvarghese1)

[![GitHub](https://img.shields.io/badge/GitHub-stebyvarghese1-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/stebyvarghese1)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-a78bfa?style=flat-square&logo=firefox&logoColor=white)](https://portfolio-v3ia.onrender.com/)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/steby-varghese)

<br>

**⭐ Star this repo if it helped you lock down your systems!**

Licensed under [MIT](LICENSE)

</div>
