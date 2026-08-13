# CareConnect Frontend

This directory is planned to contain the frontend of **CareConnect**, a proposed voice-first rural healthcare platform.

The frontend will be designed around **simplicity, accessibility, regional-language voice interaction, and low digital literacy**.

---

## Frontend Goal

The primary interaction will be voice-based rather than text-heavy.

The intended user journey is:

```text id="6q2b5h"
🗣️ Speak in Regional Language
            ↓
       Voice Processing
            ↓
      Symptom Information
            ↓
         🚦 Triage
            ↓
      🏥 Care Connection
```

---

## Planned User Interfaces

### Patient Interface

The patient-facing interface is planned to provide:

* Simple home screen
* Language selection
* Voice-based health assessment
* Voice recording interface
* Symptom processing status
* Triage result
* Healthcare guidance
* Appointment booking
* Consultation access
* Emergency assistance

### ASHA Worker Interface

The ASHA dashboard is planned to provide:

* Patient registration
* Start voice assessment
* Patient history
* Structured symptom summary
* Triage result
* Referral management
* Appointment management
* Follow-up cases
* Offline case management

### Doctor Interface

A future healthcare-provider interface can include:

* Referral requests
* Patient summaries
* Consultation requests
* Audio/video consultation
* Follow-up information

---

## Planned Frontend Flow

```text id="7g6e8c"
Home
  ↓
Start Assessment
  ↓
Select Language
  ↓
🗣️ Voice Input
  ↓
Processing
  ↓
Symptom Summary
  ↓
🚦 Triage Result
  ↓
┌──────────────────┐
│ Emergency        │ → Healthcare Facility
│ Medical Review   │ → Doctor / PHC
│ Routine          │ → Follow-up
└──────────────────┘
```

---

## Planned Screens

```text id="0n2b0s"
frontend/
│
├── README.md
│
├── src/
│   ├── components/
│   │
│   ├── pages/
│   │   ├── Login
│   │   ├── Home
│   │   ├── Dashboard
│   │   ├── LanguageSelection
│   │   ├── VoiceAssessment
│   │   ├── SymptomSummary
│   │   ├── TriageResult
│   │   ├── Referral
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

### Voice First

The microphone/voice interaction should be the primary action.

### Regional Language

The interface is intended to support multiple regional languages.

### Simple Navigation

The UI should minimize:

* Typing
* Complex forms
* Medical terminology
* Unnecessary navigation

### Clear Triage Results

The result should be immediately understandable:

```text id="h8c6l2"
🔴 EMERGENCY
Seek immediate healthcare.

🟡 MEDICAL REVIEW
Connect with a doctor / PHC.

🟢 ROUTINE
Follow-up / routine care.
```

### Accessibility

The design will consider:

* Low digital literacy
* Elderly users
* Rural users
* Limited reading ability
* Small-screen devices
* Low-bandwidth environments

---
## Proposed Technology

### Frontend
- React
- JavaScript
- Tailwind CSS
- React Router
- Axios
- Browser MediaRecorder API — voice/audio capture

### Frontend Responsibilities
- Voice recording
- Language selection
- Patient interface
- ASHA dashboard
- Display symptom summary
- Display triage result
- Appointment and consultation interface
- Offline UI and local data handling

---

## Current Status

The frontend is currently **planned and documented as part of the CareConnect concept**.

Implementation will be developed in later stages of the project.
