<div align="center">

# 🔄 EduLoop
### *Learn · Earn · Teach*
**Every child learns. Every student earns. Together they lift the next one.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,15,22,25&height=120&section=header&text=EduLoop%20Ecosystem&fontSize=28&fontColor=ffffff&animation=fadeIn" width="100%"/>

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100%2B-teal?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15%2B-blue?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Claude LLM](https://img.shields.io/badge/Claude-LLM_API-orange?style=for-the-badge&logo=anthropic&logoColor=white)](https://anthropic.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 📌 01 / The Problem
> **Talent is everywhere. Access isn’t.**

Traditional educational models suffer from structural bottlenecks that leave millions behind:
1. **📉 Poor children cannot study:** Families lack money for tuition, courses, or personal tutors—leaving raw ability to go to waste.
2. **💸 Students need income:** Capable college students want and need financial independence while studying.
3. **🧠 Knowledge goes unused:** Advanced college students possess valuable knowledge but lack a trusted, structured way to teach and get paid.

---

## 💡 02 / The Solution
**Two sides. One unbreakable loop.**

```
 ┌──────────────┐     Enrolls free/sponsored     ┌─────────────────┐
 │ Low-Income   │ ─────────────────────────────> │ College Student │
 │ Learner      │ <───────────────────────────── │ Tutor           │
 └──────────────┘     Teaches at very low fee    └─────────────────┘
         ▲                                                │
         │─────────────── 10% Funds New Seats ────────────┘
```

### 🔄 How the Loop Works
1. **Enroll:** A child from a low-income family joins via a free or sponsored seat.
2. **Learn:** A relatable college student-tutor teaches at an ultra-low fee.
3. **Teach:** Tutors run live interactive sessions and doubt-clearing blocks.
4. **Earn:** Tutors earn money while studying, and **10% of every session fee directly funds new free seats**, scaling the ecosystem organically!

#### 💰 Example Breakdown: ₹99 Learning Session
* **Tutor:** $\approx$ ₹69 (Direct income for college students)
* **Platform:** $\approx$ ₹19 (Maintenance & infrastructure)
* **Impact Fund:** $\approx$ ₹11 (Founds new sponsored seats for underprivileged kids)
* *Child pays **₹0** on sponsored seats!*

---

## 🤖 03 / Agent Architecture
EduLoop runs on a powerful **multi-agent orchestration engine** backed by real tools and human supervision:

| Agent | Core Functionality | Integrated Tools & APIs |
| :--- | :--- | :--- |
| **Orchestrator Agent** | Understands requests, routes tasks, maintains session states & rules. | Core Router Engine |
| **1. Matching Agent** | Pairs learners with the best-fit tutor by subject, language, & schedule. | Tutor Search, Scoring Rules, **Google Calendar API** |
| **2. Verification Agent** | Vets tutors through subject quizzes and scored demo lessons. | Quiz Generator, Rubric Scorer, **Claude LLM API** |
| **3. Learning Agent** | Answers doubts, builds low-data notes & quizzes, updates skill passports. | Content Store, Quiz Engine, **Claude LLM API** |
| **4. Safety & Payout Agent** | Flags risky interactions, logs chats, splits fees (69/19/10), executes payouts. | Rules Engine, Ledger, **UPI / Razorpay API** |
| **5. Impact Agent** | Transforms usage data into aggregated, privacy-safe metrics for sponsors. | SQL Analytics, Report Builder, **WhatsApp Business API** |

> *Shared Layer:* PostgreSQL (Profiles, sessions, ledger, passport)  
> *Human-in-the-Loop:* Admin approval for tutor verification, safety flags, and payouts.

---

## 🛠️ 04 / Tech Stack
Our architecture is lean, modular, and built for rapid deployment across low-bandwidth environments:

* **Backend:** Python + FastAPI (High-performance REST APIs & agent microservices)
* **Database:** PostgreSQL (Relational management for profiles, sessions, and financial ledgers)
* **Agent Layer:** Claude LLM API (Advanced tool calling for orchestration and learning guidance)
* **Channels:** WhatsApp Integration + Low-data Web App (Accessible on low-cost mobile devices)
* **Live Classes:** Google Meet + Google Calendar API (Seamless scheduling without heavy app installations)
* **Payments:** UPI / Razorpay (Automated fee splitting and instant tutor payouts)

---

## 📊 05 / Impact Metrics
We measure **true learning outcomes**, not vanity metrics:
* **Access:** Number of sponsored seats utilized & children onboarded.
* **Learning:** Completion rates and quiz performance improvements.
* **Earning:** Tutor payout volume and student retention rates.
* **Sustainability:** Cost per completed course to keep the loop self-funding.

### 🛡️ Safeguards Protecting the Impact
* **Tutor Quality:** Strict subject checks, demo lessons, and peer reviews.
* **Child Safety:** Mandatory parent consent, robust privacy controls, safe chat filters, and session logs.
* **Financial Fairness:** Transparent fee splits, refund policies, and scholarship rules.
* **Privacy First:** Only aggregated analytics are published to protect every child's privacy.

---

## 🗺️ 06 / Roadmap & Next Steps

### 🔄EduLoop 30-Day Execution Roadmap
* **Week 1: Validate** (Talk to 15 learners, 10 tutors)   :active, 0, 7
* **Week 2: Pilot** (Onboard 5 tutors, teach 10 learners) : 7, 14
* **Week 3: Measure** (Track attendance & completion)     : 14, 21
* **Week 4: Build** (Onboard sponsors, launch MVP)        : 21, 30
    
* **Now (Manual Pilot):** Forms, live classes, manually verified tutors via WhatsApp.
* **MVP:** Automated profiles, bookings, payouts, and user dashboards.
* **Later (Smart Learning):** Autonomous agent matching and adaptive practice modules.
* **Scale:** Partnerships with schools, NGOs, alumni networks, and corporate sponsors.

---

## 👥 Meet Team NEXUS

| Name | Role | Student ID / Branch |
| :--- | :--- | :--- |
| **Priyanshu Singh** | Team Leader | `26GCEBELVLSI001` |
| **Pritansh Srivastava** | Core Member | `26GCEBCSAIML007` |
| **Deewansh Yadav** | Core Member | `26GCEREN054` |
| **Shubham Katiyar** | Core Member | `26GCEBCSAIML001` |

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,15,22,25&height=80&section=footer&text=Lift%20the%20next%20one!&fontSize=22&fontColor=ffffff" width="100%"/>
</div>
