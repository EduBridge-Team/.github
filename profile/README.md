<div align="center">

# EduBridge

### Inclusive education. Connected support. Smarter learning.

**EduBridge** is a bilingual Arabic/English education and accessibility platform designed to connect children, parents, teachers, specialists, institutions, and ministries in one unified ecosystem.

[![Website](https://img.shields.io/badge/Website-edubridge.win-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://edubridge.win)
[![Platform](https://img.shields.io/badge/Platform-Web%20%2B%20Mobile-7C3AED?style=for-the-badge)](https://github.com/EduBridge-Team/EduBridge)
[![GitHub](https://img.shields.io/badge/GitHub-EduBridge--Team-181717?style=for-the-badge&logo=github)](https://github.com/EduBridge-Team)

</div>

---

## About EduBridge

EduBridge helps coordinate the educational journey of children who need personalized learning and accessibility support.

Instead of separating parents, teachers, specialists, institutions, and administrators into disconnected systems, EduBridge brings them together around one shared student experience.

The platform combines:

- Personalized education
- Accessibility and adaptation support
- Parent–teacher–specialist collaboration
- Student progress tracking
- Lessons and homework
- Educational and medical documentation
- Identity and professional verification
- Notifications and communication
- AI-assisted guidance through **Noor**
- Arabic and English experiences across web and mobile

---

## Noor AI

**Noor** is EduBridge's intelligent assistant.

Noor is designed to help users navigate the platform, understand information, and receive context-aware educational guidance while respecting role permissions and platform boundaries.

The assistant is integrated into the EduBridge experience rather than operating as a separate chatbot.

---

## Who EduBridge Is For

| Role | Experience |
|---|---|
| **Parents** | Follow their children's learning, lessons, homework, progress, and support |
| **Teachers** | Manage lessons, homework, student progress, and classroom-related records |
| **Specialists** | Follow assigned students, evaluations, adaptations, and weekly progress |
| **Institutions** | Coordinate educational services and organizational workflows |
| **Ministries** | Access higher-level educational oversight and reporting capabilities |
| **Administrators** | Manage users, verification, platform operations, and governance |

---

## Core Platform Areas

### Learning

- Lessons
- Homework
- Student files
- Progress tracking
- Teacher reports
- Certificates
- Educational content

### Accessibility & Support

- Student adaptations
- Specialist follow-up
- Evaluations
- Accessibility-aware experiences
- Support for diverse learning needs

### Collaboration

- Parent–teacher communication
- Specialist coordination
- Notifications
- Shared student context
- Role-aware access

### Trust & Safety

- Identity verification
- Specialist credential verification
- Private sensitive-document handling
- Backend-enforced authorization
- Security headers and edge protections
- Rate limiting and hardened production deployment

---

## Technology

<div align="center">

### Backend

![Laravel](https://img.shields.io/badge/Laravel_13-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.4-777BB4?logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_17-4169E1?logo=postgresql&logoColor=white)

### Web & Mobile

![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)

### Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?logo=caddy&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?logo=oracle&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

</div>

---

## Architecture

```text
Users
  │
  ├── Web — React + Vite
  └── Mobile — Flutter
          │
          ▼
      Cloudflare
          │
          ▼
        Caddy
          │
          ▼
   Laravel REST API
          │
          ├── PostgreSQL
          ├── Object Storage
          └── Noor AI Services
```

EduBridge is deployed as a containerized production stack with Cloudflare at the edge and Oracle Cloud infrastructure behind it.

---

## Accessibility First

Accessibility is not treated as an optional feature.

EduBridge is built around the idea that educational software should adapt to the learner and their support network.

That includes:

- Personalized student adaptations
- Role-specific interfaces
- Mobile-first experiences
- Arabic RTL support
- English LTR support
- Clear navigation
- Accessible educational workflows
- Support for specialized education contexts

---

## Security & Reliability

EduBridge follows a production-oriented security model with:

```text
Authentication      → JWT and server-side validation
Authorization       → API-enforced role permissions
Network security    → Cloudflare + restricted origin
Transport security  → HTTPS + HSTS
Browser security    → CSP and hardened response headers
Data protection     → Private sensitive-document storage
Abuse protection    → Edge and application rate limiting
Delivery            → CI/CD checks and deployment smoke tests
```

---

## Main Repository

The core EduBridge platform is maintained in:

### [EduBridge-Team/EduBridge](https://github.com/EduBridge-Team/EduBridge)

The repository contains the Laravel API, React web application, Flutter mobile application, deployment configuration, security tooling, and technical documentation.

---

## Production

<div align="center">

### [edubridge.win](https://edubridge.win)

**Building a more connected and inclusive educational experience.**

</div>

---

<div align="center">

## EduBridge

**Every learner deserves an experience built around their needs.**

<sub>Education · Accessibility · Collaboration · AI</sub>

</div>
