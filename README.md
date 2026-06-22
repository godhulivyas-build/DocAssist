<div align="center">

# 🏥 DocAssist
### AI-Powered Patient Assistance System

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-LLM_Inference-F55036?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-Medical_AI-00B4D8?style=for-the-badge)
![Users](https://img.shields.io/badge/Real_Users-15%2B_Hospital_Tested-2DC653?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Response_Relevance-+30%25-FF6B6B?style=for-the-badge)

**An LLM-powered healthcare system delivering symptom triage, automated diagnostic support, and multi-turn medical Q&A — validated with 15+ real hospital users.**

[▶️ Watch Demo](https://drive.google.com/file/d/1ZGi5UvTm7qNwh-bhKQcpu6Adle6jmVXx/view?usp=sharing) &nbsp;·&nbsp; [🏆 Top 15, Unleash LLM Innovation Challenge](#achievements)

</div>

---

## 🔍 The Problem

Patients navigating healthcare face gaps no current tool fills well:

| Pain Point | Reality |
|---|---|
| 🚨 Symptom confusion | Patients can't tell if symptoms need urgent care |
| 📋 Manual documentation | Doctors spend hours on paper-based clinical workflows |
| 🔄 Zero continuity | Each hospital interaction starts from scratch |
| 📊 No vital tracking | Vitals tracked on paper, siloed per visit |

DocAssist addresses all four with a single AI-powered system.

---

## 🏗️ System Architecture

![DocAssist System Architecture](docassist-architecture.svg)

Three layers work together: the **Patient Layer** captures symptoms, vitals, and queries. The **AI Core** runs NLP extraction, prompt structuring, Groq LLM inference, and response evaluation. The **Doctor Layer** surfaces everything as a clean dashboard with diagnostic support and report tracking.

---

## 🔄 Patient Journey

![DocAssist Patient Flow](docassist-patient-flow.svg)

From symptom input to a doctor-ready summary in under 60 seconds — five steps, fully automated.

---

## ✨ Key Features

| Feature | Description | Status |
|---|---|---|
| 🤖 **24/7 AI Chatbot** | Symptom assessment with multi-turn memory | ✅ Live |
| 📄 **Document Summarisation** | NLP pipeline converts medical docs to plain-language summaries | ✅ Live |
| 🩺 **Diagnostic Support** | AI-generated suggestions for doctors | ✅ Live |
| 📊 **Vital Signs Dashboard** | Real-time tracking of HR, BP, O₂, glucose | ✅ Live |
| 👤 **Patient Profiles** | Full history, report tracking, appointment scheduling | ✅ Live |
| 📈 **Evaluation Engine** | Rubric-based response scoring with feedback loop | ✅ Live |

---

## ⚡ Why Groq API?

Standard LLM inference adds 2–4s latency per turn — unacceptable for live clinical triage. DocAssist uses Groq API for sub-second inference, making real-time symptom assessment viable at the point of care.

```
OpenAI GPT-4:   ████████████████████  ~3.2s avg
Groq LLaMA 3:   ██                    ~0.4s avg  ← DocAssist
```

---

## 🛠️ Tech Stack

| Layer | Stack |
|---|---|
| AI / LLM | Groq API · Open-source LLMs · NLP Pipelines |
| Backend | Python · Flask |
| Prompt Eng | Structured templates · Context management |
| Evaluation | Rubric-based scoring · Quality metrics |
| Tools | Git / GitHub · VS Code |

---

## 📊 Performance

| Metric | Baseline | DocAssist | Improvement |
|---|---|---|---|
| Response Relevance | ~60% | ~90% | **+30%** |
| Document Summarisation | Manual (15 min) | Under 10s | **Fully automated** |
| Triage Accuracy | None | Hospital-validated | **15+ real users** |

---

## 🚀 Getting Started

**1. Clone the repo**
```bash
git clone https://github.com/godhulivyas-build/DocAssist.git
cd DocAssist
```

**2. Create virtual environment**
```bash
python -m venv venv

# macOS / Linux
source venv/bin/activate

# Windows
venv\Scripts\activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Add your Groq API key**
```bash
echo "GROQ_API_KEY=your_key_here" > .env
```
Get a free key at [console.groq.com](https://console.groq.com)

**5. Run**
```bash
python app.py
```
App runs at `http://localhost:5000`

---

## 🎥 Demo

[![Watch the Demo](https://img.shields.io/badge/Watch_Demo-Google_Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1ZGi5UvTm7qNwh-bhKQcpu6Adle6jmVXx/view?usp=sharing)


https://github.com/user-attachments/assets/92fed726-4cac-4c90-b0ba-a17e73728827


---

## 🏆 Achievements

- **Top 15 Pan-India** — Unleash LLM Innovation Challenge, 1M1B Foundation
- **15+ real hospital users** validated the system in a live clinical setting
- **30% improvement** in response relevance across 100+ interactions

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">
  Built by <a href="https://github.com/godhulivyas-build">Godhuli Vyas</a>
  <br/>
  <sub>Top 15 Pan-India · Unleash LLM Innovation Challenge · 1M1B Foundation</sub>
</div>
