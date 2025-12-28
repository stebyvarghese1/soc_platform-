# 🛡️ AI Automated Open-Source SOC Platform

A powerful, cross-platform **Security Operations Center (SOC) platform** built using **Flask**, **MongoDB**, **WebSocket**, and **AI-based NLP detection** to provide real-time threat monitoring, log aggregation, and automated mitigation for internal and external systems.
---

## screenshots

<img width="1910" height="859" alt="Screenshot 2025-12-28 144323" src="https://github.com/user-attachments/assets/b0ca0118-672d-456e-a440-aad7526549a4" />

<img width="1917" height="844" alt="Screenshot 2025-12-28 144104" src="https://github.com/user-attachments/assets/f6b93f46-700e-41f8-97e1-f4b20357f9eb" />


## 🚀 Key Features


- 🌐 **Multi-System Log Aggregation** (Local + External)
- 🔍 **AI/NLP-Based Threat Detection** using MiniLM (sentence-transformers)
- 📖 **Rule-Based + Anomaly-Based Detection Engine**
- 🔒 **Secure Login + Credential Management**
- 🧠 **Threat Mitigation Engine** with auto-blocking and isolation
- 📈 **PDF Report Generator** with charts using ReportLab
- 📡 **Real-time UI Notifications** via WebSocket/Redis
- 🧪 **Custom Rule Pattern Editor (Regex + Severity)**

---

## 🧰 Technologies Used

- **Backend:** Flask + Flask-SocketIO
- **Database:** MongoDB Atlas (remote)
- **AI:** `sentence-transformers` (MiniLM for log embeddings)
- **PDF/Charts:** ReportLab, Matplotlib
- **Frontend:** HTML + CSS + JS (Styled login, logs, and threat dashboard)
- **Cross-Platform Log Collection:** Windows, Linux, macOS

---

## 📂 Project Structure

```

.
├── app.py               # Main Flask application
├── templates\login.html           # Login page
├── templates\logs.html            # Log + Threat dashboard
├── log_collection\log_collection.py    # External agent script for other systems
├── templates\logo.jpg             # UI icon/logo

````

---

## ⚙️ How to Run

### 🖥️ 1. Install Requirements

```bash
pip install flask flask-socketio pymongo sentence-transformers reportlab matplotlib
````

> Redis must also be installed and running locally or via Docker.

---

### 🚀 2. Run the Platform (Admin Privileges Required)

```bash
python app.py
```

App runs at:
🔗 `http://localhost:5000`

---

### 🌐 3. Deploy External Agents

Edit and run `log_collection.py` on any external system you want to monitor:

```bash
python log_collection.py
```

> Make sure the IP and port in `API_IP` match the main platform server.

---

## 📤 Downloadable SOC Report (PDF)

From the dashboard, click **“Download SOC Report”** to export:

* Threat summary
* Visual threat charts
* Log details with timestamps
* Severity analysis

---

## 🛡️ Threat Detection Modes

| Mode          | Description                                                    |
| ------------- | -------------------------------------------------------------- |
| Rule-Based    | Regex pattern matches (customizable in UI)                     |
| Anomaly-Based | Log vector comparison vs. historical data                      |
| AI-Based      | Semantic match using MiniLM embeddings (pre-trained NLP model) |

---

## 🧠 Automated Response

* 🚫 IP Blocking via iptables
* 🔒 IP Isolation
* 📉 Mitigation actions logged with timestamp and threat context

---
---

## 🙌 Credits

* Built by **Steby Varghese**
* Powered by: Flask, MongoDB, NLP models, WebSocket, ReportLab

---
