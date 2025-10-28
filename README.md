<p align="left">
  <img src="assets/heading-fullstack.svg" width="140%" style="max-width:780px;">
</p>

---

<p><sub><b>PPK Referral/Queue</b> — triage & referral rules · printable forms · audit trails  •  <b>HomeService Platform</b> — Go backend + Flutter mobile  •  automation (n8n)  •  <b>production-first</b> mindset</sub></p>
<p><sub><code>auth · users · notes · purchases · uploads · chores · weather · contractors · clinic-engine · referral-engine · automations(n8n)</code></sub></p>
<p><sub>Engineering: Docker · CI/CD · zero-downtime deploy · migrations guard · RBAC · JWT · logs · PostgreSQL (pgx)</sub></p>

<table width="100%" cellspacing="0" cellpadding="0">
  <tr>
    <td valign="top" width="68%">
      <h3>Tech Stack</h3>
      <p><img src="https://skillicons.dev/icons?i=go,php,ts,js,dart,python,c,cpp&perline=14" height="34"></p>
      <p><img src="https://skillicons.dev/icons?i=react,nextjs,vue,nuxtjs,flutter,tailwind,vite&perline=14" height="34"></p>
      <p><img src="https://skillicons.dev/icons?i=laravel,prisma,nodejs,express,nginx,docker,githubactions,jenkins&perline=14" height="34"></p>
      <p><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,firebase,aws&perline=14" height="34"></p>
      <p><img src="https://skillicons.dev/icons?i=linux,ubuntu,arch,arduino,postman&perline=14" height="34"></p>
      <p>
        <img src="https://skillicons.dev/icons?i=bash" height="34">
        <img src="https://skillicons.dev/icons?i=git" height="34">
        <img src="https://skillicons.dev/icons?i=github" height="34">
        <img src="https://skillicons.dev/icons?i=vim" height="34">
      </p>
    </td>
    <td valign="top" width="32%">
      <div style="display:flex; flex-direction:column; align-items:flex-end;">
        <img src="assets/makima-chainsaw-man.gif" width="240" style="border-radius:12px; margin-bottom:8px;">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iMookatayou&layout=compact&langs_count=8&theme=transparent&hide_border=true">
      </div>
    </td>
  </tr>
</table>

---

## About Me
**Full-stack & Systems Engineer** who builds production systems end-to-end: backend, mobile, and DevOps.  
I care about **clear domain models**, **boring-reliable infrastructure**, and **fast feedback loops**. I ship with tests, metrics, and guardrails so teams can move quickly **without** breaking patients’ workflows or users’ data.

> TH: ผมเป็นนักพัฒนาที่โฟกัส “เอาเข้าระบบจริง” มากกว่าพูดสวย ๆ — โครงสร้างข้อมูลต้องชัด, โค้ดอ่านง่าย, deploy ได้ซ้ำ ๆ, และแก้เหตุการณ์จริงในโรงพยาบาล/บ้านได้ทันเวลา

---

## What I’m Building
- **HomeService** — Go + pgx + Clean Architecture  
  Modules: `auth`, `users`, `notes`, `purchases`, `uploads`, `chores`, `weather`, `contractors`  
  <sub>Mobile: Flutter + Riverpod + GoRouter</sub>
- **PPK Pre-Service (Hospital)** — Next.js + Laravel + MySQL  
  `referral-engine`, `clinic-engine`, printable forms, and audit trails for clinical flows
- **Per-Service Management** — barrier token auth, Thai ID integrations, **gov-style UI**

---

## Engineering Principles
- **Production-first**: every feature must be observable, retry-safe, and ready to roll back.  
- **Small, composable modules**: clear interfaces (`service`, `repo`, `handler`) and testable boundaries.  
- **Explicit data contracts**: JSON shapes, migrations guard, and versioned APIs.  
- **Operational clarity**: metrics, logs, and playbooks over “tribal knowledge”.

> TH: ออกแบบให้ทีมอื่นเข้าใจง่าย แก้เหตุฉุกเฉินได้เร็ว และย้ายเครื่อง/สภาพแวดล้อมได้โดยไม่พัง

---

## Selected Modules (Specs)
- **Notes** — indexed search, pinning, SQL filters, repository pattern  
- **Purchases** — a pragmatic state machine:  
  `planned → ordered → bought → delivered`, with progress & audit  
- **Uploads** — file service + `files_before_write` trigger (guard naming, size, type)  
- **Referral Engine** — encoded rules for UTI / Cellulitis / Animal Bite → **clinic routing**  
- **Contractors** — geolocation + type filters + deep links (maps/call)

---

## DevOps & Infrastructure
- **Docker** multi-stage builds · **CI/CD** (GitHub Actions) · **zero-downtime** deploys  
- **PostgreSQL** with migrations guard · **RBAC** + **JWT** · structured **logging**  
- Reproducible environments (local → staging → prod), no surprises.

---

## Showcases
- **HomeService** — Go backend + Flutter mobile (modular domain; Riverpod + GoRouter on app side)  
- **PPK Form System** — Next.js + Laravel; printable forms; audit trails; EMR-friendly  
- **Surgical-OPD Registry** — Nuxt + MySQL; clean data capture + export paths  
- **Monitoring Dashboard** — Go + PostgreSQL; worker pipelines + alerting

---

## Architecture Notes
- **Backend shape** (per module):
