# Fernando Magalhães

**Full-Stack Developer focused on Infrastructure and DevOps | TypeScript, NestJS, Next.js, PostgreSQL, Docker, GitHub Actions | I build applications and the pipelines, environments and monitoring that keep them running in production**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fernando-magalhães-a82378274/)
[![E-mail](https://img.shields.io/badge/E--mail-Fernando.apmagalhaes@hotmail.com-D14836?style=flat&logo=maildotru&logoColor=white)](mailto:Fernando.apmagalhaes@hotmail.com)

---

## About

I write the feature and I also own what happens after the merge: the build, the deploy, the migration, the rollback plan and the alert when something goes wrong.

On the application side I work with NestJS, Prisma and PostgreSQL on the server and Next.js and React on the client. On the infrastructure side I containerize services with Docker, deploy them to cloud environments with separate dev and production stages, and gate every change behind CI. Most of what I build is used daily by internal teams and by the public, so security, observability and repeatable releases go into every delivery from the start.

I'm studying Analysis and Systems Development (ADS) at Faculdade Descomplica.

---

## Infrastructure and DevOps

- **Containerized NestJS and Next.js services** with multi-stage Docker builds, slim base images and health endpoints, deployed to Railway with separate dev and production environments
- **Built CI pipelines in GitHub Actions** with lint, type checking, tests and a dependency-audit gate that blocks critical vulnerabilities from reaching production
- **Enforced a `feat → dev → main` release flow** in CI, branch protection and pre-push hooks, so nothing reaches production without passing the same checks locally and remotely
- **Defined a database migration policy** (when migrations run on deploy and when they are applied by hand) and wrote runbooks for deploy, release, rollback and failed migrations
- **Audited cloud services for cost and security**, finding secrets shared between environments, credentials exposed in a front-end bundle and outdated framework versions with critical advisories, and drove the fixes
- **Migrated object storage between S3 buckets** without touching application data, by keeping only relative keys in the database and switching environment configuration
- **Integrated infrastructure monitoring** by reading the Zabbix API into operational dashboards with host maps and alerts, and ran Zabbix and GLPI locally in Docker for safe testing
- **Hardened APIs** with configurable trust proxy, Helmet and CSP, rate limiting per account and IP, short-secret warnings and token revocation on logout
- **Automated the local environment** with scripts that start the whole multi-service stack against a local PostgreSQL and Redis, plus seed scripts for repeatable test data

---

## Full-stack development

- **Built a single sign-on service** shared by several applications, with session revocation, magic links, password recovery, per-application role inheritance and a Redis-backed token denylist
- **Replaced polling with a real-time support chat** using Server-Sent Events and Redis pub/sub
- **Integrated a help desk with external ticketing systems** through webhooks, syncing status, messages and internal notes both ways
- **Shipped a public selection process**: registration with e-mail verification, exam scheduling, waitlist, ranking with official tie-break rules and generated PDF guides
- **Turned an admin dashboard into an installable PWA** with web push notifications
- **Wrote route contract tests** that fail when an endpoint is left unprotected, and an end-to-end auth suite covering cookies, CSRF, refresh and rate limiting

---

## Tech stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Infrastructure and DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat&logo=amazons3&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat&logo=zabbix&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Back end and data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Front end**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Testing**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

---

## GitHub activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Fer-Magalhaes&show_icons=true&count_private=true&include_all_commits=true&hide_rank=true&theme=radical&hide_border=true" alt="GitHub stats" />
  <img height="170" src="https://streak-stats.demolab.com?user=Fer-Magalhaes&theme=radical&hide_border=true" alt="GitHub streak" />
</p>

---

## Contact

Hiring for a full-stack, back-end or DevOps role? Send the role and the stack to [Fernando.apmagalhaes@hotmail.com](mailto:Fernando.apmagalhaes@hotmail.com) or message me on [LinkedIn](https://www.linkedin.com/in/fernando-magalhães-a82378274/).
