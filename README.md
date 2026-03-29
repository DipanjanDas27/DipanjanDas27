<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=120&section=header" width="100%"/>

<br/>

```
██████╗ ██╗██████╗  █████╗ ███╗   ██╗     ██╗ █████╗ ███╗   ██╗    ██████╗  █████╗ ███████╗
██╔══██╗██║██╔══██╗██╔══██╗████╗  ██║     ██║██╔══██╗████╗  ██║    ██╔══██╗██╔══██╗██╔════╝
██║  ██║██║██████╔╝███████║██╔██╗ ██║     ██║███████║██╔██╗ ██║    ██║  ██║███████║███████╗
██║  ██║██║██╔═══╝ ██╔══██║██║╚██╗██║██   ██║██╔══██║██║╚██╗██║    ██║  ██║██╔══██║╚════██║
██████╔╝██║██║     ██║  ██║██║ ╚████║╚█████╔╝██║  ██║██║ ╚████║    ██████╔╝██║  ██║███████║
╚═════╝ ╚═╝╚═╝     ╚═╝  ╚═╝╚═╝  ╚═══╝ ╚════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═════╝ ╚═╝  ╚═╝╚══════╝
```

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=3000&pause=800&color=4FC3F7&center=true&vCenter=true&multiline=true&width=720&height=55&lines=Full+Stack+Developer+%E2%80%94+PERN+%C2%B7+MERN+%C2%B7+DevOps+%C2%B7+DSA;Node.js+%C2%B7+PostgreSQL+%C2%B7+React+%C2%B7+Redis+%C2%B7+Docker+%C2%B7+Open+to+SDE+Internships)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipanjan-das-65b023290/)
[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DipanjanDas27)
[![Email](https://img.shields.io/badge/Email-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dipanjandas2758@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/DipanjanDas27/)

</div>

<br/>

---

<br/>

## `> whoami`

```yaml
name        : Dipanjan Das
role        : Full Stack Developer
stacks      : PERN · MERN
focus       : Backend-heavy full stack development
interests   : System design, payment flows, DevOps, DSA
seeking     : SDE Internship Opportunities
contact     : dipanjandas2758@gmail.com
```

<br/>

I focus on the backend problems that don't show up in tutorials — concurrency, payment integrity, async side effects, and deployment pipelines that stay stable without manual intervention.

<br/>

---

<br/>

## `> ls ./projects`

<br/>

### ◆ &nbsp; Dwellio &nbsp;—&nbsp; Full-Stack Rental Management Platform

<div align="right">

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/DipanjanDas27/dwellio)&nbsp;[![Live](https://img.shields.io/badge/Live-Demo-4FC3F7?style=flat-square&logo=vercel&logoColor=black)](https://dwellio-five.vercel.app/)

</div>

Dual-portal rental platform — separate Tenant and Owner frontends backed by a single Express.js REST API.

<br/>

| What was built | Why it matters |
|---|---|
| Raw PostgreSQL transactions — no ORM | Atomic rental activation + auto-refund if DB fails after gateway success |
| Idempotency keys on payment & renewal endpoints | No double charges on network retries |
| `FOR UPDATE` row-level locking on property rows | Concurrent bookings can't race each other |
| Redis OTP with TTL-based expiry | Secure, stateless password reset |
| 3 `node-cron` jobs | Monthly rent records · overdue reminders · auto-termination on notice date |
| Docker Compose + Nginx + Certbot + GitHub Actions | Auto-deploy on every push to `main` |

<br/>

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

<br/>

---

<br/>

### ◆ &nbsp; Hospital Management System &nbsp;—&nbsp; MERN Stack

<div align="right">

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/DipanjanDas27/Hospital-Management)&nbsp;[![Live](https://img.shields.io/badge/Live-Demo-4FC3F7?style=flat-square&logo=vercel&logoColor=black)](https://patient-gilt.vercel.app/)

</div>

Multi-role hospital platform — Admin, Doctor, Patient — with structured backend architecture and live deployment.

<br/>

- **JWT auth** with protected routes and role validation enforced at the API layer
- **Database-level constraints** prevent appointment double-booking under concurrent requests
- Expiry and auto-cancellation logic in **cron jobs** — request cycle stays non-blocking
- Email notifications made **asynchronous** — no latency leaking into API responses
- Modular **MVC architecture** across appointments, records, and user management

<br/>

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

<br/>

---

<br/>

## `> cat tech_stack.json`

<br/>

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

<br/>

**Backend & Databases**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

<br/>

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

<br/>

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

<br/>

**Core Engineering Concepts**

```
Atomic Transactions   ·   Idempotency   ·   Row-Level Locking   ·   Async Job Queues
Payment Flow Design   ·   API Rate Limiting   ·   Cron Automation   ·   CI/CD Pipelines
```

<br/>

---

<br/>

## `> git log --graph --oneline`

<br/>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=DipanjanDas27&theme=algolia&no-frame=true&no-bg=true&margin-w=6&column=6" width="100%"/>

</div>

<br/>

<div align="center">

<img src="https://streak-stats.demolab.com?user=DipanjanDas27&theme=github-dark-blue&hide_border=true&background=0d1117&ring=4FC3F7&fire=4FC3F7&currStreakLabel=4FC3F7" width="58%"/>

</div>

<br/>

---

<br/>

## `> cat open_source.md`

<br/>

**Co-Lead — JGEC Winter of Code (JWOC) 2026**
&emsp;Mentored open-source contributors and co-led program execution for an annual OSS initiative.

<br/>

---

<br/>

<div align="center">

*Open to SDE Internship opportunities — let's build something that holds up.*

<br/>

[![Connect on LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dipanjan-das-65b023290/)
&nbsp;
[![Send a Mail](https://img.shields.io/badge/Send%20a%20Mail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dipanjandas2758@gmail.com)

<br/>
<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:161b22,100:0d1117&height=100&section=footer" width="100%"/>

</div>
