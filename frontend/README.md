# CareConnect Frontend

The frontend of **CareConnect** provides a simple, accessible interface for patients, ASHA workers, and healthcare providers.

The interface is designed with a focus on **simplicity, accessibility, voice interaction, and low-bandwidth environments**.

---

## Main Interfaces

### ASHA Worker

* Login
* Dashboard
* Patient registration
* Symptom assessment
* Triage result
* Patient history
* Referrals
* Appointments
* Follow-ups

### Patient

* Home
* Symptom checker
* Voice/text symptom input
* Triage result
* Doctor consultation
* Appointments
* Health records
* Emergency assistance

### Doctor

* Referral requests
* Patient information
* Consultation
* Follow-up recommendations

---

## Frontend Flow

```text
Login
  ↓
Dashboard
  ↓
Patient Assessment
  ↓
Symptom Input
  ↓
Triage Result
  ↓
┌───────────────┐
│ Emergency     │ → Healthcare Facility
│ Medical Review│ → Doctor / PHC
│ Routine       │ → Follow-up
└───────────────┘
```

---

## Planned Screens

```text
frontend/
│
├── README.md
│
├── src/
│   ├── components/
│   ├── pages/
│   │   ├── Login
│   │   ├── Dashboard
│   │   ├── PatientAssessment
│   │   ├── TriageResult
│   │   ├── Appointments
│   │   └── Consultation
│   │
│   ├── services/
│   ├── assets/
│   └── App.jsx
│
└── public/
```

---

## Design Principles

* Simple navigation
* Large, accessible controls
* Minimal text where possible
* Voice-first interaction
* Regional-language support
* Mobile-first design
* Clear emergency indicators
* Low-bandwidth friendly interface

---

## Technology

* React
* JavaScript
* Tailwind CSS / CSS
* Axios
* React Router

---

## Demo

The frontend prototype demonstrates the complete CareConnect workflow from **symptom capture to triage and healthcare connection**.
