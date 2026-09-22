# Nenil 🧠

**AI-Based Cognitive Gaming and Memory Assistance Platform for Elderly Dementia Patients in NER**

Smart India Hackathon 2026 — Problem Statement ID: **SIH26003**
Theme: MedTech / BioTech / HealthTech · Category: Software
Team: **Page Not Found**

---

## 📌 Overview

Nenil is a mobile application built for dementia patients and their caregivers in India's North Eastern Region (NER). It combines personalized cognitive games, daily routine assistance, and remote caregiver monitoring into a single, accessible platform — designed with elderly-first, low-digital-literacy, and low-connectivity users in mind.

## 🎯 Objectives

- Boost cognitive engagement through personalized cognitive activities
- Support independence in executing daily routines
- Enhance emotional recall using personalized family memories
- Enable remote monitoring for patient safety and care
- Deliver inclusive accessibility through multilingual support

## ✨ Features

### Core Patient Experience
- Language selection and patient PIN login
- Dynamic patient profile with a high-contrast landing dashboard
- Large touch targets and simplified navigation for elderly users
- Voice-first assistance using standard STT/TTS tools

### Cognitive & Safety Modules
| Module | Description |
|---|---|
| Family Photo Puzzle | Uploaded family images become memory games |
| Daily Routine Assistant | Prompts for medicines, hydration, activities, and appointments |
| Word Search Game | Adjustable difficulty based on performance |
| Regional Knowledge Quiz | Localized cultural trivia in the user's language |
| Location Monitoring | GPS tracking for patient safety |
| Direct Calling | One-touch patient-to-caregiver calling |
| Caregiver Login | Dedicated portal for remote monitoring and support |

### Innovation & Uniqueness
Adaptive cognitive gaming, emotional-memory personalization, cultural context, elderly-first AI, and a unified caregiver support system.

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Flutter + Riverpod |
| Backend | FastAPI |
| Database | PostgreSQL |
| Authentication | JWT |
| AI | Adaptive Cognitive Engine + STT/TTS |
| Device Integration | GPS, camera, native phone calling |
| Storage | Local offline cache with secure cloud sync |

> Designed for smartphone-based deployment with offline-friendly support in remote and low-connectivity regions.

## 🔄 System Flow

```
Elderly Patient
      │
      ▼
Voice / Touch Input ──► Family Photo Puzzles / Word Search / Regional Quizzes / Routine Reminders
      │
      ▼
Cognitive Activity + AI Engine
      │
      ▼
Local Progress Capture
      │
      ▼
Performance Analysis & Difficulty Adaptation
      │
      ▼
Secure Backend Sync ──► GPS Alerts / Direct Calling
      │
      ▼
Caregiver Dashboard
```

## 🧭 Methodology

1. Language selection and patient profile setup
2. Patient PIN and caregiver login
3. Cognitive games, adaptive difficulty, and daily routine assistant
4. Speech-to-Text and Text-to-Speech voice assistance
5. GPS monitoring and one-touch calling
6. Secure progress synchronization and caregiver insights

## ✅ Feasibility & Viability

- Flutter enables a practical cross-platform MVP from a single codebase
- FastAPI and PostgreSQL support modular APIs and caregiver records
- Open-source STT/TTS reduces dependency on expensive hardware
- GPS, camera, and calling are standard smartphone capabilities
- Local caching and background sync support remote, low-connectivity NER areas

**Pilot success measures:** activity completion · routine adherence · alert resolution · ease of use

### Challenges & Mitigation

| Risk | Mitigation |
|---|---|
| Elderly users may struggle with complex navigation | High contrast, large touch targets, voice prompts, minimal screens |
| Regional-language coverage/content quality may vary | Configurable language packs, validated with local users |
| Patient data requires strong privacy and consent controls | JWT, encryption, role-based access, consent-based sharing |
| GPS/network availability may be inconsistent | Show last synced location, preserve offline history |
| Clinical efficacy requires formal validation | Supervised pilots; Nenil positioned as support, not diagnosis |

## 🌍 Impact & Benefits

- **Cognitive & Emotional:** Personalized photo puzzles and repeatable stimulation exercises; voice interaction reduces digital-literacy barriers
- **Independence & Routine:** Daily prompts, high-contrast dashboard, regional language interaction
- **Caregiver & Safety:** Reduced supervision burden, GPS safety tracking, one-touch calling, continuity of care
- **Regional Value:** Culturally relevant quizzes and accessible smartphone-based support for remote NER families

**Expected Outcome:** A practical, inclusive digital companion supporting cognitive engagement, daily routines, emotional recall, and safer remote care for dementia patients in NER.

## 📚 Research & References

- National Programme for the Health Care of the Elderly (Govt. of India)
- LASI Study — Prevalence of Dementia in India
- National Digital Health Mission — Health Data Management Policy
- WHO — iSupport for Dementia Carers
- Health Technology Assessment for Digital Health in India
- Saragih et al. (2022) — Systematic Review & Meta-Analysis of RCTs on Serious Games for People with Dementia
- Zuo et al. (2024) — Effects of Electronic Serious Games on Older Adults with Alzheimer's Disease and MCI
- Abd-alrazaq et al. (2022) — Effectiveness of Serious Games for Improving Memory in Older Adults with Cognitive Impairment
- Woods et al. (2023), Cochrane Review — Cognitive Stimulation to Improve Cognitive Functioning in People with Dementia

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/<your-username>/nenil.git
cd nenil

# Backend setup
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend setup
cd frontend
flutter pub get
flutter run
```

## 📂 Project Structure

```
nenil/
├── frontend/          # Flutter app (patient + caregiver UI)
├── backend/           # FastAPI services
│   ├── auth/          # JWT authentication
│   ├── games/         # Cognitive game modules
│   ├── routines/       # Daily routine assistant
│   └── monitoring/     # GPS & caregiver sync
├── docs/              # Documentation, research references
└── README.md
```

## 👥 Team

**Team Name:** Page Not Found
**Problem Statement:** SIH26003 — AI-Based Cognitive Gaming and Memory Assistance Platform for Elderly Dementia Patients in NER

