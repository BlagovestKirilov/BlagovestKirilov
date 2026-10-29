# Hey, I'm Blagovest 👋

Java backend developer building real-world applications with **Spring Boot**, **PostgreSQL**, and modern deployment pipelines — and the **React** frontends that sit on top of them.

I enjoy turning ideas into production-ready systems — from real-time multiplayer games and live TV streaming to vehicle management platforms and social apps.

🌐 **[My Personal Page](https://blagovestkirilov.github.io/BlagovestKirilovPersonalPage/)**

---

## 🛠 Tech Stack

**Languages & Frameworks:** Java · Spring Boot · Spring Security · Spring Data JPA · Spring WebSocket (STOMP) · Node.js (Express)

**Frontend:** React · TypeScript · Vite

**Databases & Caching:** PostgreSQL · MySQL · Redis · H2

**Infrastructure:** Docker · Docker Compose · Nginx · AWS EC2 · Fly.io · GitHub Actions CI/CD · Prometheus · Grafana

**Integrations & Tools:** FFmpeg · AWS S3 · Expo Push Notifications · Liquibase · Swagger/OpenAPI · MapStruct · Lombok

---

## 🚀 Projects

### ♠️ [deck.bg](https://deck.bg)
A real-time online multiplayer platform for traditional Bulgarian games — **Santase** (Sixty-Six), the two-player trick-taking card game, and **Tabla**, Bulgarian backgammon.

**Repositories:** [deck.bg-backend](https://github.com/BlagovestKirilov/deck.bg-backend) · [deck.bg-frontend](https://github.com/BlagovestKirilov/deck.bg-frontend)

- Real-time gameplay via **WebSockets (STOMP + SockJS)** with full rule enforcement
- Matchmaking queue, inactivity handling, and turn timers
- **Elo-based ranking system** with placement phase and tier progression (Bronze → Legend)
- **React + TypeScript frontend** (Vite), talking to the backend over REST and STOMP
- JWT auth, Liquibase migrations, rate-limited Nginx reverse proxy
- **CI/CD**: GitHub Actions → Docker Hub → AWS EC2, for both the backend and the frontend
- **Stack**: Java 25 · Spring Boot 4 · React · TypeScript · PostgreSQL · Docker · Nginx · Virtual Threads

---

### 📡 [StreamVault IPTV](https://streamvault.fly.dev/configure)
An addon that brings live TV into **Stremio** and **Nuvio** from an **Xtream Codes** account or an **M3U playlist** — on PC, Android, iOS, and TV.

**Repository:** [StreamVault](https://github.com/BlagovestKirilov/StreamVault)

- <!--installs-->3K+<!--/installs--> installs, 25K+ streams played, and 30K+ channel searches since May 2026
- TV guide (**EPG**) showing what's on now and next, for Xtream Codes sources
- **Catch-up** — watch recorded programmes from the past days, by programme or by hour
- Channel search that works across Latin and Cyrillic, plus category filters
- Connection test before installing, so bad credentials are caught early
- Large playlists are streamed and parsed instead of loaded whole; settings stored encrypted
- Monitoring with **Prometheus** and **Grafana**
- **CI/CD**: GitHub Actions → Docker → Fly.io
- **Stack**: Node.js · Express · Docker · Fly.io · Prometheus · Grafana · Jest

---

### 🍽 [MenuCraft](https://github.com/BlagovestKirilov/MenuCraft)
A full-stack application for venues to manage menu templates and generate filled PDF menus.

- PDF generation via **Apache PDFBox** using AcroForm field mapping
- Menu generation history with regeneration support
- **Facebook Page integration** — OAuth flow for publishing posts directly to venue pages
- Role-based access (Admin / Company) with JWT auth
- **Stack**: Java 25 · Spring Boot 4 · React (Vite) · PostgreSQL
- Only Admins can register new companies for now!

---

### 📺 [WolfTV](https://github.com/BlagovestKirilov/WolfTV)
A live TV streaming backend that records and re-streams channels via **HLS** using FFmpeg.

- Dynamic M3U8 playlist generation with automatic segment cleanup
- **Redis-backed** concurrent watch session enforcement with heartbeat TTL
- Subscription system with plan management and stacking
- Multi-device login with device tracking and blocking
- Scheduled FFmpeg health checks and automatic stream recovery
- **Stack**: Java 21 · Spring Boot 3 · PostgreSQL · Redis · FFmpeg · Docker · AWS EC2

---

### 🚗 [CarMate](https://github.com/BlagovestKirilov/CarMate)
A REST API for Bulgarian vehicle owners to manage and monitor their cars — insurance, vignettes, technical reviews, obligations, expenses, and trip sheets.

- Integrates with **Bulgarian government APIs** (BG Toll, Guarantee Fund, GTP) for automated document status checks
- Daily scheduled jobs for document expiry detection and **Expo push notifications** (bilingual: BG/EN)
- PDF trip sheet generation with **iTextPDF** and email delivery
- Email confirmation flows, Swagger UI documentation
- **Stack**: Java 17 · Spring Boot 3 · PostgreSQL · Spring WebFlux · iTextPDF

---

### 📸 [PhotoApp](https://github.com/BlagovestKirilov/PhotoApp)
A full-stack social photo-sharing web application with server-rendered UI.

- Photo uploads to **AWS S3** with likes, comments, and reporting system
- Friend requests, real-time chat, in-app notifications
- Community pages with photo galleries and discovery suggestions
- Admin panel for content moderation, user bans, and report review
- **Stack**: Java 17 · Spring Boot 3 · Thymeleaf · MySQL · AWS S3

---

## 📫 Get in Touch

- 💻 GitHub: https://github.com/BlagovestKirilov
- 🔗 LinkedIn: https://www.linkedin.com/in/blagovestkirilov/
- 📧 Email: blagovestkirilov1@gmail.com
