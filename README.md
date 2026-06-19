<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16,18,20&height=200&section=header&text=Rajit%20Dakhane&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20AI%20Builder%20%7C%20DefTech%20Enthusiast&descAlignY=58&descSize=18" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=A78BFA&center=true&vCenter=true&multiline=false&width=700&lines=Backend+Engineer+%40+Innox+IT+Solutions;Building+AI-powered+production+systems;Published+Researcher+%7C+Geopolitics+%2B+AI;Full+Stack+%7C+Spring+Boot+%7C+FastAPI+%7C+Next.js;Shipping+real+things+that+go+to+production.)](https://git.io/typing-svg)

<br/>

![BE Computer Engineering](https://img.shields.io/badge/BE%20Computer%20Engineering-Sinhgad%20Institute%20of%20Technology-7C3AED?style=flat-square&logo=graduation-cap&logoColor=white)
![UGC Published](https://img.shields.io/badge/UGC%20Published-IDEAL%20Journal%20No.%2047026-5B21B6?style=flat-square&logo=bookstack&logoColor=white)
![Location](https://img.shields.io/badge/Manmad%2C%20Maharashtra-India-6D28D9?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![LinkedIn](https://go-skill-icons.vercel.app/api/icons?i=linkedin)](https://linkedin.com/in/rajit0311)
[![Gmail](https://go-skill-icons.vercel.app/api/icons?i=gmail)](mailto:rajitdakhane007@gmail.com)
[![GitHub](https://go-skill-icons.vercel.app/api/icons?i=github)](https://github.com/rd-007)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=rd-007&style=flat-square&color=7C3AED&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/rd-007?style=flat-square&color=5B21B6&label=Followers&logo=github)
![Stars](https://img.shields.io/github/stars/rd-007?style=flat-square&color=4C1D95&label=Total+Stars&logo=github)

</div>

---

## `Who am I `

```
Software engineer who builds things that ship.
Not portfolio pieces. Production systems.
```

Backend-first by instinct, full-stack by necessity. I'm a final-year CS student at Sinhgad Institute of Technology, currently writing APIs at Innox IT Solutions that go live in a real world solutions.

On the side, I build AI-powered products. Not wrappers. The Smart Task Prioritizer uses K-Means clustering, burnout detection, and energy-aware scheduling — built with a proper two-service architecture, secured end-to-end, deployed on real infra. The multi-input AI assistant routes text, images, and documents through NVIDIA NIM APIs with proper fallback logic and server-side key handling.

Published researcher too. My paper on AI in global diplomacy — *Algorithmic Diplomacy: AI in Global Power Politics* — came out in a UGC-listed peer-reviewed journal in March 2026. Turns out geopolitics and gradient descent have more in common than people think.

DefTech follower. ICSE alumnus. Builder of things that actually work.

**Open to:** Backend / Full-Stack engineering roles · AI/ML product engineering · Research collaborations · Open source

---

## Tech Stack

<div align="center">

**Languages**

![My Skills](https://go-skill-icons.vercel.app/api/icons?i=java,python,typescript,js,html&theme=dark)

**Frontend**

![My Skills](https://go-skill-icons.vercel.app/api/icons?i=nextjs,react,tailwind,vite&theme=dark)

**Backend & Databases**

![My Skills](https://go-skill-icons.vercel.app/api/icons?i=spring,fastapi,nodejs,postgres,redis,supabase,prisma,maven&theme=dark)

**Cloud, DevOps & Tooling**

![My Skills](https://go-skill-icons.vercel.app/api/icons?i=aws,docker,vercel,railway,render,git,postman,notion,figma&theme=dark)

</div>

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:---|:---:|:---|
| Machine Learning | Intermediate | Scikit-Learn, K-Means clustering, classification pipelines |
| AI API Integration | Advanced | NVIDIA NIM APIs — Llama 3.1, Nemotron VL, Nemotron Parse |
| AI Product Engineering | Advanced | End-to-end AI services, FastAPI backends, prompt engineering |
| Predictive Systems | Intermediate | Burnout detection, habit pattern analysis, energy scheduling |
| AI in Geopolitics | Research | Published paper: surveillance, cyber strategy, predictive intelligence |
| Security-first AI | Intermediate | Rate limiting, IDOR checks, CSP headers, XSS sanitization |

</div>

---

## Featured Projects

<details>
<summary><b>⬡ &nbsp; Smart Task Prioritizer</b> &nbsp;—&nbsp; AI-Powered Productivity Platform</summary>

<br/>

An AI productivity platform built with a clean two-service split: Next.js 16 on the frontend, Python FastAPI handling all the intelligence. Not a monolith pretending to be scalable — an actual architecture decision made on purpose.

The AI layer runs priority scoring, energy-aware scheduling, K-Means habit clustering, and burnout detection through Scikit-Learn. Security isn't an afterthought — it runs through the whole stack. Sliding-window rate limits per IP, Clerk Auth middleware on every protected route, IDOR checks before every database write, Prisma transactions where consistency matters, CSP and Permissions-Policy headers on the way out.

<div align="center">

| Attribute | Details |
|:---|:---|
| **Stack** | Next.js 16, Python FastAPI, Supabase PostgreSQL, Prisma, Clerk Auth, Scikit-Learn |
| **Deployment** | Vercel (frontend) · Render non-root Docker container (AI service) |
| **AI Capabilities** | Priority scoring, K-Means habit clustering, burnout detection, energy-aware scheduling |
| **Security** | Sliding-window rate limiting, IDOR checks, Clerk middleware, CSP headers, Prisma transactions |
| **Observability** | Sentry (error tracking) · PostHog (analytics) |
| **Repository** | [![GitHub](https://img.shields.io/badge/View%20Repo-7C3AED?style=flat-square&logo=github&logoColor=white)](https://github.com/rd-007/Smart-Task-Prioritizer) |

</div>

</details>

<br/>

<details>
<summary><b>⬡ &nbsp; AI-Powered Multi-Input Assistant</b> &nbsp;—&nbsp; Vision, Chat & Document Intelligence</summary>

<br/>

A React 19 frontend backed by a Node.js server-side proxy that routes text, images, and documents through NVIDIA NIM APIs. Llama 3.1 handles chat, Nemotron VL handles vision, Nemotron Parse handles PDF and DOCX extraction. Three models, one clean interface, properly abstracted.

Client-side file processing where possible, fallback logic where it isn't. AbortController and 30-second timeouts keep things from hanging. API keys stay server-side. Per-IP rate limiting at 20 req/min. XSS sanitization on rendered output. localStorage persistence with blob-stripping to stay within quota limits.

<div align="center">

| Attribute | Details |
|:---|:---|
| **Stack** | React 19, Node.js, NVIDIA NIM APIs (Llama 3.1 · Nemotron VL · Nemotron Parse) |
| **Deployment** | Vercel with serverless functions for server-side API key handling |
| **Capabilities** | Text chat, image understanding (vision), PDF & DOCX document extraction |
| **Security** | Server-side key storage, per-IP rate limiting, XSS sanitization, blob-stripped localStorage |
| **Resilience** | AbortController, 30-second timeouts, multi-model fallback logic |
| **Repository** | [![GitHub](https://img.shields.io/badge/View%20Repo-7C3AED?style=flat-square&logo=github&logoColor=white)](https://github.com/rd-007/AI-Assistant) |

</div>

</details>

---

## Experience

### Spring Boot Development Intern &nbsp;·&nbsp; Innox IT Solutions LLP
`January 2026 – Present` &nbsp;·&nbsp; Pune, India

Building backend systems for a real subscription-based Delivery Management System. The code goes to production. The APIs serve actual users.

- Built RESTful APIs using Spring Boot, PostgreSQL, and layered MVC architecture for a live delivery management platform
- Developed billing and order management modules with recurring subscription logic and transactional integrity through Spring Data JPA
- Implemented role-based authentication, documented APIs via Swagger UI, and collaborated on React Native mobile integration using structured Git workflows

![Spring Boot](https://go-skill-icons.vercel.app/api/icons?i=spring)
![PostgreSQL](https://go-skill-icons.vercel.app/api/icons?i=postgresql)
![Spring Data JPA](https://go-skill-icons.vercel.app/api/icons?i=springdatajpa)
![Swagger](https://go-skill-icons.vercel.app/api/icons?i=swagger)
![JWT](https://go-skill-icons.vercel.app/api/icons?i=jwt)
![Git](https://go-skill-icons.vercel.app/api/icons?i=git)
![Maven](https://go-skill-icons.vercel.app/api/icons?i=maven)

---

## Achievements

<div align="center">

| Recognition | Details |
|:---:|:---|
| 📄 UGC-Listed Publication | *Algorithmic Diplomacy: AI in Global Power Politics* · IDEAL Journal No. 47026 · Vol. XIV, Issue II · March–August 2026 · pp. 102–109 |
| 🏢 Production Internship | Writing backend APIs at Innox IT Solutions that serve real users in a live delivery management system |
| 🤝 Technical Team Member | Association of Computer Engineering Students (A.C.E.S) · July 2023 – April 2024 |
| 🌐 Full-Stack AI Platform | Built and deployed a two-service AI productivity platform with ML clustering, burnout detection, and enterprise-grade security |
| 🔗 Multi-Model AI System | Integrated Llama 3.1, Nemotron VL, and Nemotron Parse into a single production-deployed assistant |

</div>

---

## Certifications

<div align="center">

**AWS**

[![AWS Solutions Architecture](https://go-skill-icons.vercel.app/api/icons?i=aws)](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/pmnMSL4QiQ9JCgE3W/kkE9HyeNcw6rwCRGw_pmnMSL4QiQ9JCgE3W_XW8ifayk5re49fcfv_1742682222678_completion_certificate.pdf)


**APIs & Tooling**

[![Postman](https://go-skill-icons.vercel.app/api/icons?i=postman)](https://badges.parchment.com/public/assertions/JslYt71sSoax9pXjrNF1HQ)

</div>

---

## Coding Profiles

<div align="center">

[![LeetCode](https://go-skill-icons.vercel.app/api/icons?i=leetcode)](https://leetcode.com/u/geek_rsd/)
[![HackTheBox](https://go-skill-icons.vercel.app/api/icons?i=hackthebox)](https://profile.hackthebox.com/profile/019edd2a-38bf-7074-adff-5ecab390e487)
[![HackerRank](https://go-skill-icons.vercel.app/api/icons?i=hackerrank)](https://www.hackerrank.com/profile/rajitdakhane007)
[![Stack Overflow](https://go-skill-icons.vercel.app/api/icons?i=stackoverflow)](https://stackoverflow.com/users/30432953)

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.shion.dev/api?username=rd-007&theme=midnight-purple&hide_border=true&include_all_commits=false&count_private=false&show_icons=true&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD&bg_color=0D1117" height="165" alt="GitHub Stats" />
&nbsp;&nbsp;
<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=rd-007&theme=midnight-purple&hide_border=true&include_all_commits=false&count_private=false&layout=compact&title_color=A78BFA&text_color=C4B5FD&bg_color=0D1117" height="165" alt="Top Languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=rd-007&theme=midnight-purple&hide_border=true&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD&background=0D1117&stroke=5B21B6&dates=6D28D9" alt="GitHub Streak" />

</div>

---

## GitHub Trophies

<div align="center">

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=rd-007&theme=dracula&no-frame=true&no-bg=true&margin-w=6&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=rd-007&bg_color=0D1117&color=A78BFA&line=7C3AED&point=C4B5FD&area=true&area_color=5B21B6&hide_border=true&radius=6)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rd-007/rd-007/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rd-007/rd-007/output/github-snake.svg" />
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/rd-007/rd-007/output/github-snake-dark.svg" />
</picture>

</div>

---

## Current Focus

```yaml
status:
  role: Spring Boot Development Intern @ Innox IT Solutions
  location: Pune / Manmad, Maharashtra, India

learning:
  - Java Spring ecosystem (advanced patterns, reactive programming)
  - AI/ML engineering for production systems
  - System design and distributed architecture

building:
  - Backend APIs for a live delivery management platform
  - AI-powered tools with real ML models (not just wrappers)
  - Security-conscious, production-grade full-stack systems

exploring:
  - DefTech and AI in geopolitical strategy
  - Cloud-native architectures on AWS
  - Agentic AI systems and LLM orchestration

open_to:
  - Backend / Full-Stack engineering internships & roles
  - AI/ML product engineering opportunities
  - Open source collaboration on meaningful projects
  - Research partnerships at the AI × policy intersection
```

---

## Connect

<div align="center">

[![Gmail](https://go-skill-icons.vercel.app/api/icons?i=gmail)](mailto:rajitdakhane007@gmail.com)
[![LinkedIn](https://go-skill-icons.vercel.app/api/icons?i=linkedin)](https://linkedin.com/in/rajit0311)
[![GitHub](https://go-skill-icons.vercel.app/api/icons?i=github)](https://github.com/rd-007)
[![X](https://go-skill-icons.vercel.app/api/icons?i=x)](https://x.com/rajitsd96)
[![Discord](https://go-skill-icons.vercel.app/api/icons?i=discord)](https://discord.gg/vjQvzch3h)
[![Instagram](https://go-skill-icons.vercel.app/api/icons?i=instagram)](https://instagram.com/@being_rsd)

</div>

---

<div align="center">

*Code is like humor. When you have to explain it, it's bad.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,16,18,20&height=120&section=footer&animation=fadeIn" width="100%" />

</div>
