<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=3000&pause=1000&color=FFFFFF&center=true&vCenter=true&width=600&lines=Pedro+Henrique;Backend+Engineer;Distributed+Systems" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-h-aab8a514b)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:henriquesilvamoura81@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PedroHMour)

</div>

---

I build backend systems that don't go down.
Distributed queues, resilient APIs, horizontal scale.
Node.js · TypeScript · PostgreSQL · Redis · Docker

---

## Featured Project

**[Distributed Job Queue Engine](https://github.com/PedroHMour/distributed-job-queue)** — production-grade async job processing built from scratch

| What | How |
|---|---|
| Zero job loss | Postgres persisted before Redis enqueue. Redis down = still 202 OK |
| Horizontal scale | docker compose up --scale worker=3 — no config changes, no port conflicts |
| Smart concurrency | Email ×10 (I/O bound) · Image ×2 (CPU bound) · Report ×5 (mixed) |
| Full audit trail | Every transition logged: PENDING → ACTIVE → COMPLETED / RETRYING / DEAD |
| Dead Letter Queue | Failed jobs archived with complete failure history for manual review |
| Graceful shutdown | SIGTERM pauses workers, drains in-flight jobs, closes connections cleanly |

`Node.js` `TypeScript` `Fastify` `BullMQ` `Redis` `PostgreSQL` `Prisma` `Docker` `Zod`

---

## Stack

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Infrastructure**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PedroHMour&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&hide_title=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=PedroHMour&layout=compact&theme=github_dark&hide_border=true&langs_count=6&hide_title=true" height="150"/>
</div>
