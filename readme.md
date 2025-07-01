# 🩺 Doctor-Appointment-Multiagent

**Doctor-Appointment-Multiagent** is a multi-agent AI system that automates the doctor appointment process using multiple collaborative agents. Each agent performs a specific task—from understanding the user’s request to booking the appointment and notifying the user.

---

## 📌 Features

- 🧠 **Intent Understanding** – Detect doctor, date, time, and purpose of visit from natural language input.
- 📅 **Schedule Management** – Check doctor availability and book appointments.
- 📩 **Notifications** – Automatically send confirmation via email or SMS.
- 🔁 **Rescheduling Support** – Handles rescheduling if the selected time is unavailable.
- 💬 **Multi-turn Dialogue Support** – Asks follow-up questions if user input is incomplete.

---

## 🏗️ Architecture
![output](https://github.com/user-attachments/assets/cbbaa939-a34d-4871-a301-189eb182a98d)
 


- **Intent Agent**: Parses user queries and extracts intent, doctor name, date/time.
- **Schedule Agent**: Verifies availability and reserves appointment slots.
- **Notification Agent**: Sends confirmation or reminder to the user.

---

## 🧰 Tech Stack

- **Language Models**: OpenAI GPT-4 / Claude 3 / Local LLMs
- **Backend**: Python (FastAPI)
- **Agent Orchestration**: LangChain
- **Messaging**: Twilio (SMS), SendGrid (Email)
- **Database**: SQLite / PostgreSQL
- **Deployment**: Docker-ready

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sundaram25018/Doctor-Appointment-Multiagents.git
cd Doctor-Appointment-Multiagents
```
```base
pip install -r requirements.txt
```
```base
uvicorn main:app --reload
```

🚧 Roadmap

-  **Multi-turn conversation support**
-  **Modular agent logic**
- **Doctor specialization filters**
- **Frontend integration**
- **Calendar sync with Google/Outlook**


