# FisioAct

**Physiotherapy activity tracking platform** — full-stack web and mobile application for physiotherapists and patients.

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![JWT](https://img.shields.io/badge/Auth-JWT-black?style=flat&logo=jsonwebtokens)

> 📌 **This is a public overview repository.** FisioAct is a private, actively developed product built for a real client/business use case. The full source code, infrastructure, and patient-facing implementation are not publicly available; this README summarizes the platform's purpose, architecture, and stack for portfolio/review purposes. No real patient data, credentials, or proprietary code are included here.

## The Problem

Physiotherapists managing home-based rehabilitation face two recurring issues: patients frequently perform prescribed exercises incorrectly or inconsistently without supervision, and therapists lack visibility into adherence and recovery progress between in-person sessions. FisioAct addresses this by giving therapists a way to prescribe personalized, video-guided exercise routines and track patient compliance remotely, while patients get a simple mobile experience to follow their treatment plan at home.

## What It Does

- **Exercise Library** — Catalogued exercises with video demonstrations, muscle groups, and difficulty levels
- **Routine Builder** — Drag-and-drop interface for creating personalized treatment plans
- **Patient Dashboard** — Track adherence, pain levels, and recovery progress over time
- **Mobile App** — Native mobile experience for patients to follow routines at home
- **Real-time Messaging** — Secure communication between therapist and patient
- **Analytics** — Treatment effectiveness metrics and patient compliance reports

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend (Web) | React, TypeScript, Tailwind CSS |
| Frontend (Mobile) | React Native |
| Backend | Node.js, Express |
| Database | PostgreSQL |
| Auth | JWT-based authentication |
| Storage | Cloud object storage for media files |

## Architecture

```
┌──────────────────┐     ┌──────────────────┐
│   Web App        │     │   Mobile App     │
│   (React)        │     │ (React Native)   │
└────────┬─────────┘     └────────┬─────────┘
         │                        │
         └──────────┬─────────────┘
                    │
         ┌──────────▼─────────────┐
         │     REST API           │
         │   (Node.js/Express)    │
         └──────────┬─────────────┘
                    │
         ┌──────────▼─────────────┐
         │    PostgreSQL           │
         │    + Object Storage     │
         └────────────────────────┘
```

## Status

Private project under active development. This repository serves as a public overview only — source code, infrastructure, and any patient/client data are not publicly available.

## Autor

**Miguel Serra Ferrando** — Telecommunications Engineer
[GitHub](https://github.com/megatron54) · [LinkedIn](https://www.linkedin.com/in/miguel-serra-ferrando) · [Email](mailto:miguel.serra.ferrando@gmail.com)
