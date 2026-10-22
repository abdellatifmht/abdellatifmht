<!-- ============================== HEADER ============================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:163048,100:2E86AB&height=220&section=header&text=Abdellatif%20Mahamat%20Dougouye&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=AI%20%E2%80%A2%20Machine%20Learning%20%E2%80%A2%20MLOps%20%E2%80%A2%20Agentic%20Systems&descSize=18&descAlignY=58&animation=fadeIn" alt="header" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=2E86AB&center=true&vCenter=true&width=640&lines=Final-year+Engineering+Student+%40+ENSA+Khouribga;Building+AI+systems+that+ship+to+production;Looking+for+a+PFE+in+AI+%2F+ML+%E2%80%94+January+2027" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abdellatif-mahamat-dougouye/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:abdelmahamt50@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open_to-PFE_Internship-2EA44F?style=for-the-badge" alt="Open to work">
  <img src="https://img.shields.io/badge/Location-Khouribga,_Morocco-163048?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
</p>

---

## 👨‍💻 About me

```python
class Abdellatif:
    role     = "Information Systems Engineering Student (PFE year)"
    school   = ["ENSA Khouribga", "1337 (42 Network)"]
    focus    = ["Machine Learning", "MLOps", "Agentic AI & LLM systems"]
    looking  = "5–6 month End-of-Studies Internship in AI / ML — starting January 2027"
    languages = {"French": "Fluent", "Arabic": "Fluent", "English": "B2"}

    def mindset(self):
        return "Go beyond the notebook: from model to deployed, monitored service."
```

- 🧠 Exploring **agentic AI**: multi-agent orchestration, tool use, RAG, self-critique loops
- 🚀 Passionate about **MLOps**: serving, experiment tracking, drift monitoring, CI/CD
- 📈 Experienced with **time-series ML** and rigorous, leakage-free evaluation

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 AgentHub
**Multi-agent system for automated tech watch & report generation**

An autonomous team of agents that researches a topic and writes a cited technical report.

- 🧩 **LangGraph** orchestration: Planner, Researcher, Analyst, Writer, Reviewer
- 🔁 **ReAct** loop + self-critique agent to reduce hallucinations
- 🛠️ Tool use / function calling (web search)
- 🧠 Persistent memory with **ChromaDB**
- 🔍 Agent tracing with **LangSmith**
- 🐳 Served with **FastAPI / Streamlit** and **Docker**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
<td width="50%" valign="top">

### ⚙️ Predictive Maintenance
**RUL estimation on industrial sensor data (NASA C-MAPSS)**

End-to-end time-series ML pipeline built during my internship at 1337 Coding School.

- 📊 Feature engineering: rolling windows, trend/slope features
- 🏆 Compared **Linear Regression, XGBoost, LightGBM, LSTM**
- 🎯 Custom score penalizing *late* failure predictions
- 🚢 **FastAPI + Docker** deployment, **MLflow** tracking
- 📉 Drift detection (**PSI**, **KS test**) + **Streamlit** dashboard

![XGBoost](https://img.shields.io/badge/XGBoost-017CEE?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
</tr>
</table>

> 📌 *Add the links to your repositories here once they are public.*

### 🧭 AgentHub architecture

```mermaid
flowchart LR
    U([User topic]) --> P[Planner]
    P --> R[Researcher<br/>web search tool]
    R --> A[Analyst]
    A --> W[Writer]
    W --> V{Reviewer}
    V -- needs fixes --> A
    V -- approved --> O([Cited report])
    A <--> M[(Vector memory<br/>ChromaDB)]
```

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,kubernetes,azure,githubactions,linux,git,postgres,mysql,java,js,c,grafana&perline=8" alt="Tech stack icons" />
</p>

| 🧠 AI & ML | ⚙️ MLOps & Monitoring | ☁️ DevOps & Backend |
|---|---|---|
| Scikit-learn, XGBoost, LightGBM | MLflow, FastAPI, Model Serving | Docker, Kubernetes |
| PyTorch, LSTM, 1D-CNN | Data drift (PSI, KS test) | Microsoft Azure |
| LangGraph, CrewAI, RAG | Streamlit, Grafana | GitHub Actions, CI/CD |
| ChromaDB, LangSmith | Experiment tracking | Git, Linux, PostgreSQL, MySQL |

**Languages:** Python • SQL • Java • JavaScript • C

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=abdellatifmht&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdellatifmht&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=abdellatifmht&theme=tokyonight&hide_border=true&background=0d1117" alt="GitHub streak" />
</p>

---

## 📫 Let's connect

I'm open to **AI / Machine Learning internship opportunities** and always happy to talk about MLOps, agentic systems or time-series ML.

<p align="center">
  📧 <b>abdelmahamt50@gmail.com</b> &nbsp;•&nbsp;
  💼 <a href="https://www.linkedin.com/in/abdellatif-mahamat-dougouye/">LinkedIn</a> &nbsp;•&nbsp;
  📍 Khouribga, Morocco
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E86AB,100:163048&height=110&section=footer" alt="footer" />
</p>
