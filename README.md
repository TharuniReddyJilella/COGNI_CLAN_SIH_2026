# 🧠 COGNI_CLAN – AI-Powered Cognitive Gaming & Memory Assistance Platform

> **SIH26003 | Smart India Hackathon 2026**

**COGNI_CLAN** is an AI-powered cognitive gaming and memory assistance platform designed to support **elderly users experiencing memory and cognitive difficulties** through engaging, personalized, and accessible cognitive activities.

The platform combines **cognitive games, AI-based performance analysis, personalized recommendations, and caregiver monitoring** to create a supportive digital environment for cognitive engagement.

---

## 🎯 Problem Statement

**Problem Statement ID: SIH26003**

Elderly individuals experiencing cognitive decline may face difficulties with:

- Memory retention
- Attention and concentration
- Problem-solving
- Language and communication
- Spatial awareness
- Executive functioning

Existing digital solutions may not provide sufficient personalization, continuous performance tracking, caregiver involvement, or support for users with limited connectivity.

COGNI_CLAN addresses these challenges through an interactive and personalized cognitive assistance platform.

---

## 💡 Our Solution

COGNI_CLAN provides a collection of cognitive games designed around different cognitive abilities.

The system records user performance and uses the collected information to generate a **personalized cognitive profile**.

Based on the user's interaction and performance, the platform can provide:

- Cognitive performance insights
- Personalized game recommendations
- Progress tracking
- Areas requiring additional attention
- Caregiver-oriented information

The platform is designed with **elderly-friendly interaction, accessibility, multilingual support, and low-connectivity environments** in mind.

---

## ✨ Key Features

### 🎮 1. Cognitive Games

The platform includes games targeting multiple cognitive abilities:

| Cognitive Area | Purpose |
|---|---|
| 🧠 Memory | Tests recall and retention |
| 🎯 Attention | Measures focus and concentration |
| 🧩 Problem Solving | Evaluates logical thinking |
| 🗣️ Language | Supports language and word-based activities |
| 📍 Spatial | Tests spatial awareness |
| ⚙️ Executive Functions | Evaluates planning and decision-making |

---

### 🤖 2. AI-Based Performance Analysis

User interactions and game performance can be analyzed to identify patterns in cognitive performance.

The system can consider factors such as:

- Accuracy
- Response time
- Score
- Game history
- Repeated performance
- Cognitive category performance

This information contributes to the user's cognitive profile.

---

### 👤 3. Personalized Cognitive Profile

Each user can have an individual profile containing their performance across different cognitive areas.

Example:

```text
Memory          █████████░  90%
Attention       ███████░░░  70%
Problem Solving ████████░░  80%
Language        ██████░░░░  60%
Spatial         ████████░░  80%
Executive       ███████░░░  70%
```

This allows the system to identify areas where the user may need more cognitive engagement.

---

### 📊 4. Progress Tracking

The platform can track cognitive performance over time.

Users and caregivers can observe:

- Previous scores
- Recent performance
- Improvement trends
- Game completion
- Cognitive-area performance

---

### 👨‍👩‍👧 5. Caregiver Dashboard

A caregiver-oriented dashboard can provide a simplified view of the user's activity and progress.

It can help caregivers understand:

- Recent activity
- Game performance
- Cognitive-area trends
- Areas requiring attention
- Overall engagement

> **Important:** COGNI_CLAN is intended as a **cognitive assistance and engagement platform**, not as a medical diagnostic system.

---

### 🌐 6. Low-Connectivity Support

The platform is designed with environments having limited or unreliable internet connectivity in mind.

Potential offline-first capabilities include:

- Locally available cognitive games
- Local performance storage
- Synchronization when connectivity becomes available

---

### 🌍 7. Multilingual & Accessible Design

The platform aims to make cognitive activities accessible to elderly users by supporting:

- Simple navigation
- Large and clear interface elements
- Easy-to-understand instructions
- Regional language support
- Elderly-friendly interaction patterns

---

## 🏗️ System Workflow

```text
                 ┌─────────────────────┐
                 │      User / Elderly │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Cognitive Games   │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Performance Data    │
                 │ Score / Time / etc. │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ AI Performance      │
                 │ Analysis            │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Cognitive Profile   │
                 └──────────┬──────────┘
                            │
                  ┌─────────┴─────────┐
                  ▼                   ▼
        ┌──────────────────┐  ┌──────────────────┐
        │ Personalized     │  │ Caregiver        │
        │ Recommendations  │  │ Dashboard        │
        └──────────────────┘  └──────────────────┘
```

---

## 🧠 Cognitive Assessment Approach

The platform focuses on multiple cognitive dimensions instead of relying on a single score.

A conceptual performance model can combine:


Cognitive Performance
        │
        ├── Memory
        ├── Attention
        ├── Problem Solving
        ├── Language
        ├── Spatial Ability
        └── Executive Function
```

Game results can be aggregated to build a broader picture of the user's interaction and performance.

---

## 🛠️ Technology Stack

### Frontend
- HTML
- CSS
- JavaScript
- Responsive UI components

### Backend
- Python
- Flask / applicable backend services

### AI / Machine Learning
- Python
- Machine Learning algorithms
- Performance analysis
- Recommendation logic

### Data Processing
- Pandas
- NumPy

### Development Tools
- Visual Studio Code
- Git
- GitHub

### Deployment
- Web-based deployment

> Technologies may vary depending on the implementation of individual modules.

---

## 🏗️ Project Structure

cogni-care/
│
├── ai/
│   ├── data/
│   │   └── generate_dataset.py
│   │
│   ├── explainability/
│   │   └── explainer.py
│   │
│   ├── inference/
│   │   └── predict.py
│   │
│   ├── models/
│   │   └── cognicare_transformer/
│   │       ├── model.pt
│   │       └── model_config.json
│   │
│   ├── preprocessing/
│   │   └── preprocess.py
│   │
│   └── training/
│       └── train_transformer.py
│
├── backend/
│   ├── app/
│   │   ├── ai/
│   │   ├── routes/
│   │   ├── auth.py
│   │   ├── config.py
│   │   ├── database.py
│   │   ├── main.py
│   │   ├── models.py
│   │   ├── schemas.py
│   │   └── security.py
│   │
│   ├── auth.py
│   └── requirements.txt
│
├── data/
│
├── frontend/
│
├── tests/
│
├── .gitignore
├── README.md
└── requirements.txt

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Tharuni-23/COGNI_CLAN-SIH-2026.git
```

### 2. Navigate to the Project

```bash
cd COGNI_CLAN-SIH-2026
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

If the project uses Flask:

```bash
python app.py
```

Then open the local URL shown in the terminal.

---

## 🔬 Future Enhancements

The project can be further enhanced with:

- Advanced machine-learning-based personalization
- Voice-based interaction
- More regional languages
- Improved offline synchronization
- Long-term cognitive performance analytics
- Additional cognitive games
- Adaptive difficulty levels
- Enhanced caregiver notifications
- Secure cloud synchronization
- Integration with wearable devices
- Research-oriented cognitive analytics

---

## ⚠️ Disclaimer

COGNI_CLAN is designed for **cognitive engagement, assistance, and performance tracking**.

It is **not intended to diagnose dementia, Alzheimer's disease, or any other medical condition**.

Any cognitive performance information should be interpreted appropriately and, where necessary, discussed with qualified healthcare professionals.

---

## 🏆 Smart India Hackathon 2026

**Hackathon:** Smart India Hackathon 2026  
**Problem Statement:** SIH26003  
**Team:** COGNI_CLAN  

The project focuses on applying **AI, cognitive gaming, personalization, and accessible technology** to support elderly users and their caregivers.

---

## 👥 Team

**Team Name:** COGNI_CLAN

Our team worked collaboratively on:

- Problem analysis
- UI/UX design
- Cognitive game development
- AI/ML implementation
- Backend development
- Testing
- Documentation
- Hackathon presentation

---
### Prototype

PROTOTYPE VIDEO LINK

(GOOGLE DRIVE): https://drive.google.com/file/d/1P-VajfIOFjAAYKHIOj_o0tVi4PGcciwj/view?usp=sharing


YOUTUBE LINK:https://youtu.be/_2TKmQUc_iI?si=FmrjI2EjbpbEc8nH

---


**COGNI_CLAN — Making cognitive engagement more accessible, personalized, and meaningful.**