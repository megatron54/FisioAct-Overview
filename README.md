# FisioAct

**Physiotherapy activity tracking platform** — full-stack web and mobile application for physiotherapists and patients.

## Overview

FisioAct is a comprehensive platform that allows physiotherapists to create personalized exercise routines, track patient progress, and communicate efficiently. Patients receive guided exercise programs on their mobile devices with video demonstrations and adherence tracking.

## Features

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

This is a private project under active development. This repository serves as a public overview — source code is not publicly available.

## Contact

- [LinkedIn](https://www.linkedin.com/in/miguel-serra-ferrando)
