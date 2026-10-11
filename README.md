

<p align="center">
<pre style="font-size:14px; color:#39ff14;">
███████╗██╗   ██╗██████╗ ███████╗██╗   ██╗██████╗ ███████╗███████╗
██╔════╝██║   ██║██╔══██╗██╔════╝╚██╗ ██╔╝██╔══██╗██╔════╝██╔════╝
█████╗  ██║   ██║██████╔╝█████╗   ╚████╔╝ ██████╔╝█████╗  ███████╗
██╔══╝  ██║   ██║██╔══██╗██╔══╝    ╚██╔╝  ██╔══██╗██╔══╝  ╚════██║
███████╗╚██████╔╝██║  ██║███████╗   ██║   ██║  ██║███████╗███████║
╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝   ╚═╝   ╚═╝  ╚═╝╚══════╝╚══════╝
</pre>
</p>

<p align="center">
<img src="https://dummyimage.com/1200x200/000000/39ff14&text=JOBVERSE+AI+INTERVIEW+ENGINE" />
</p>

---

<p align="center">
  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)  
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)  
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)  
![WebSockets](https://img.shields.io/badge/WebSockets-000000?style=for-the-badge&logo=websocket&logoColor=white)  
![ASGI](https://img.shields.io/badge/ASGI-FF00FF?style=for-the-badge)

</p>

---

# 🧠 **Tech Stack Grid**

<p align="center">

| Technology | Purpose |
|-----------|---------|
| 🐍 Python | Core backend |
| 🌿 Django | REST API + Admin |
| 🔌 Daphne | ASGI + WebSockets |
| 📡 Redis | Real-time engine |
| ⚡ Celery | Background workers |
| 🔐 JWT | Authentication |
| 🧠 AI Modules | Evaluation tasks |

</p>

---

# 🏗️ **System Architecture**

```

Frontend (React)
│
▼
Django Backend (ASGI)
│
├── Redis  (Real-time Memory)
│
├── Celery Workers (Async AI Tasks)
│
└── Database (PostgreSQL/Mongo)

```
...

---

# 🏗️ **System Architecture**  
(Place your actual architecture image here later)

<p align="center">
<img src="https://dummyimage.com/900x450/000000/39ff14&text=JOBVERSE+ARCHITECTURE+DIAGRAM" />
</p>

---

# 🔁 **Backend Workflow Diagram**

```

User → Django API → Task Queued → Redis Broker → Celery Worker → AI Processing → Result Saved → WebSocket → User

```

---

# 🚦 **Setup Flowchart**

```]]

Clone Repo
↓
Create venv
↓
Install deps
↓
Fix errors (force reinstall)
↓
Install Celery + Redis plugin
↓
Setup Redis
↓
Run Django + Daphne + Celery

```

---

# ⚡ **ONE-SHOT CONTINUOUS SETUP SECTION**  
*(Everything in one flow as requested)*

git clone [https://github.com/GautamSutar/JobVerse.git](https://github.com/GautamSutar/JobVerse.git)
cd backend

python -m venv venv

# Activate venv

# Windows:

source venv/Scripts/activate

# Linux/macOS:

source venv/bin/activate

pip install -r requirements.txt
pip install --upgrade --force-reinstall --use-deprecated=legacy-resolver -r requirements.txt

pip install celery
pip install django-redis
pip show django-redis

# Redis Setup

Download Redis MSI:
[https://github.com/MicrosoftArchive/redis/releases](https://github.com/MicrosoftArchive/redis/releases)

Enable: "Add to environment variables"
Install Redis

redis-cli --version

redis-cli -h <your-redis-url>

PING → PONG

# Django Commands

python manage.py makemigrations
python manage.py migrate
python manage.py runserver

python ../../manage.py startapp interviews_ai
python manage.py add_questions

# Celery Worker

celery -A Django worker -l info

# Daphne WebSocket Server

daphne Django.asgi:application --port 8001

# WebSocket Test

ws://127.0.0.1:8001/ws/test/a82de10f-6c79-4dc4-aa59-c0fa0f2b73be/


# 🌟 **Key Features**

### 🔥 Real-time AI Interview Engine  
### 🎤 Speech-to-Text + Sentiment Analysis  
### 👀 Face/Gaze Tracking  
### ⚡ Celery-Powered Background AI  
### 📡 WebSocket Live Interaction  
### 🛡 Proctoring System (Tab Switch, Multiface Detection)


# 🔗 **Social Footer**

<p align="center">
<a href="https://github.com/GautamSutar"><img src="https://img.shields.io/badge/GitHub-Gautam_Sutar-181717?style=for-the-badge&logo=github"></a>
<a href="#"><img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin"></a>
<a href="#"><img src="https://img.shields.io/badge/Portfolio-Visit-39ff14?style=for-the-badge&logo=firefoxbrowser&logoColor=white"></a>
</p>

---

<p align="center">
✨ Built with passion, AI, and caffeine — Welcome to the future of mock interviews. ✨
</p>


