<!-- ====== EMERALD × BLACK • Pro Dev Profile (2-column, no frames) ====== -->

<h2><u>Hi There I'm a Full-Stack Developer</u></h2>

<!-- Header Summary -->
<p><sub>PPK Referral/Queue → triage & referral rules, printable forms, audit trails • HomeService Platform → Go backend + Flutter mobile • automation(n8n) • production-first mindset</sub></p>
<p><sub><code>auth · users · notes · purchases · uploads · chores · weather · contractors · clinic-engine · referral-engine · automations(n8n)</code></sub></p>
<p><sub>Engineering: Docker • CI/CD • zero-downtime deploy • migrations guard • RBAC • JWT • logs • PostgreSQL(pgx)</sub></p>

<br/>

<!-- ========== TWO COLUMNS (no borders) ========== -->
<table width="100%">
  <tr>
    <!-- ===== LEFT (Main) ===== -->
    <td width="66%" valign="top">

<h3>Tech Stack</h3>
<p>
  <!-- ↑ เพิ่มขนาดจากเดิม height=26 เป็น 32 -->
  <img src="https://skillicons.dev/icons?i=go,postgres,redis,nginx,docker,githubactions,linux,ubuntu,arch,php,laravel,ts,js,react,nextjs,flutter,dart,tailwind,prisma&perline=18" height="32" />
</p>
<sub><code>Go (Chi, pgx, Zap)</code> · <code>PostgreSQL</code> · <code>Redis</code> ·
<code>Laravel 12 (PHP 8.3)</code> · <code>Next.js 15 / React 19</code> ·
<code>Flutter (Riverpod, GoRouter)</code> · <code>Tailwind</code> ·
<code>JWT / RBAC</code> · <code>Nginx</code> · <code>Docker</code> ·
<code>GitHub Actions</code> · <code>n8n automations</code></sub>

<br/>

<h3>What I'm Building</h3>

- <b>HomeService</b> — Go + pgx + Clean Architecture → modules:
  <code>auth</code>, <code>users</code>, <code>notes</code>, <code>purchases</code>,
  <code>uploads</code>, <code>chores</code>, <code>weather</code>, <code>contractors</code>; Flutter app (Riverpod + GoRouter)
- <b>PPK Pre-Service (Hospital)</b> — Next.js + Laravel + MySQL → <i>referral-engine / clinic-engine</i>,
  printable PPK forms, Thai ID integrations, audit trails
- <b>Per-Service Management</b> — screening-group permission, barrier token auth, government-style UI

<br/>

<h3>Selected Modules (Specs)</h3>

- <b>Notes</b> — list/search/pin, SQL filters, repo pattern, GIN-index ready  
- <b>Purchases</b> — state machine: <code>planned → ordered → bought → delivered</code>, amount estimate/paid, itemized entries, file attachments  
- <b>Uploads</b> — <code>POST /uploads</code> (JWT + multipart), trigger <code>files_before_write</code> เติม filename/mime/bytes/url  
- <b>Referral Engine (PPK)</b> — UTI/Cellulitis/Animal-bite rules, clinics <code>muang</code>/<code>surg</code>/<code>uro</code>, Tue/Thu morning gating (TH time)  
- <b>Contractors</b> — geolocation banner/permission flow (Geolocator), type filters, deep-link Maps/Call

<br/>

<h3>DevOps</h3>

- Docker multi-stage, offline composer cache, entrypoint migrations/seeds  
- CI/CD (GitHub Actions): build/test/lint/deploy, migrations guard, zero-downtime  
- Observability: Zap logging, request IDs; Security: JWT, RBAC, CORS/Nginx

<br/>

<h3>Showcases</h3>

- <b>Homeservice</b> — Go + PostgreSQL + Clean Arch (modulesด้านบน)  
- <b>PPK-Form</b> — Next.js + Laravel + printable forms + referral rules  
- <b>Surgical-OPD-Registry</b> — Nuxt + MySQL  
- <b>Monitoring-Dashboard-Starter</b> — Go + Postgres

<br/>

<h3>Snippets I Reuse</h3>

- Go: <code>Repo</code> interfaces + <code>Service{ Now func() }</code> for deterministic tests  
- Flutter: Riverpod <code>Notifier</code> (LocationController: lastKnown/current/stream/manual), debounced search, GoRouter guards  
- Laravel: request validation + model casts (QuestionResult)  
- Next.js: route handlers + Prisma/Drizzle; edge-safe token gate

<br/>

<h3>Contact</h3>
<sub>
Portfolio: <a href="https://imookatayou.github.io">imookatayou.github.io</a> ·
Email (personal): <a href="mailto:jetsribumrung@gmail.com">jetsribumrung@gmail.com</a> ·
Email (work): <a href="mailto:fenyyei@gmail.com">fenyyei@gmail.com</a>
</sub>

    </td>

    <!-- ===== RIGHT (Sidebar) ===== -->
    <td width="34%" valign="top">

<!-- รูปมาคิมะ + เว้นระยะเท่า ๆ กัน -->
<p>
  <img src="assets/makima-chainsaw-man.gif" width="240" alt="makima" style="margin-bottom:10px;" />
</p>

<!-- Most Used Languages: ย้ายมาใต้รูป + เล็กลงด้วยการซ่อน title ของการ์ด -->
<sub><b>Most Used Languages</b></sub>
<p>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iMookatayou&layout=compact&langs_count=10&hide_title=true" width="100%" alt="langs"/>
</p>

<!-- เว้นช่องเล็กน้อยไม่ให้ติด -->
<p></p>

<h3>Stats</h3>
<p>
  <img src="https://github-readme-stats.vercel.app/api?username=iMookatayou&show_icons=true&hide_title=true&include_all_commits=true&count_private=true" width="100%" alt="stats"/>
</p>

<!-- เว้นช่องก่อน WakaTime -->
<p></p>

<h3>WakaTime</h3>
<p>
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=YOUR_WAKATIME&layout=compact&hide_title=false" width="100%" alt="wakatime"/>
</p>

<h3>Badges</h3>
<p>
  <img alt="Build" src="https://img.shields.io/badge/Build-Actions-success?logo=githubactions" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-ready-blue?logo=docker" />
  <img alt="Clean Architecture" src="https://img.shields.io/badge/Clean%20Architecture-on-emerald" />
  <img alt="Go" src="https://img.shields.io/badge/Go-ship-00ADD8?logo=go" />
</p>

<h3>Anime Corner</h3>
<sub>Rendered via Anilist on metrics (optional).</sub>

    </td>
  </tr>
</table>

<br/>

<!-- Notes:
- ใช้สองคอลัมน์เต็มความกว้าง ไม่มีกรอบ
- รูปมาคิมะ, Most Used, Stats, WakaTime เว้นระยะเท่า ๆ กันด้วย <p></p> และ margin-bottom
- Tech Stack ขยายเป็น height=32 เพื่อให้อ่านง่ายขึ้น
-->
