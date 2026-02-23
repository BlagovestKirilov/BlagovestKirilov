# Hey, I'm Blagovest 👋

Java backend developer building real-world applications with **Spring Boot**, **PostgreSQL**, and modern deployment pipelines.

I enjoy turning ideas into production-ready systems — from real-time multiplayer games and live TV streaming to vehicle management platforms and social apps.

---

## 🛠 Tech Stack

**Languages & Frameworks:** Java · Spring Boot · Spring Security · Spring Data JPA · Spring WebSocket (STOMP)

**Databases & Caching:** PostgreSQL · MySQL · Redis · H2

**Infrastructure:** Docker · Docker Compose · Nginx · AWS EC2 · GitHub Actions CI/CD

**Integrations & Tools:** FFmpeg · AWS S3 · Expo Push Notifications · Liquibase · Swagger/OpenAPI · MapStruct · Lombok

---

## 🚀 Projects

### [🃏 SantaseService](https://github.com/BlagovestKirilov/santase-service)
[deck.bg](https://deck.bg) — a real-time online multiplayer platform for **Santase** (Sixty-Six), the popular Bulgarian two-player trick-taking card game.

- Real-time gameplay via **WebSockets (STOMP + SockJS)** with full rule enforcement
- Matchmaking queue, inactivity handling, and turn timers
- **Elo-based ranking system** with placement phase and tier progression (Bronze → Legend)
- JWT auth, Liquibase migrations, rate-limited Nginx reverse proxy
- **CI/CD**: GitHub Actions → Docker Hub → AWS EC2
- **Stack**: Java 25 · Spring Boot 4 · PostgreSQL · Docker · Nginx · Virtual Threads

---

### [📺 WolfTV](https://github.com/BlagovestKirilov/WolfTV)
A live TV streaming backend that records and re-streams channels via **HLS** using FFmpeg.

- Dynamic M3U8 playlist generation with automatic segment cleanup
- **Redis-backed** concurrent watch session enforcement with heartbeat TTL
- Subscription system with plan management and stacking
- Multi-device login with device tracking and blocking
- Scheduled FFmpeg health checks and automatic stream recovery
- **Stack**: Java 21 · Spring Boot 3 · PostgreSQL · Redis · FFmpeg · Docker · AWS EC2

---

### [🚗 CarMate](https://github.com/BlagovestKirilov/CarMate)
A REST API for Bulgarian vehicle owners to manage and monitor their cars — insurance, vignettes, technical reviews, obligations, expenses, and trip sheets.

- Integrates with **Bulgarian government APIs** (BG Toll, Guarantee Fund, GTP) for automated document status checks
- Daily scheduled jobs for document expiry detection and **Expo push notifications** (bilingual: BG/EN)
- PDF trip sheet generation with **iTextPDF** and email delivery
- Email confirmation flows, Swagger UI documentation
- **Stack**: Java 17 · Spring Boot 3 · PostgreSQL · Spring WebFlux · iTextPDF

---

### [📸 PhotoApp](https://github.com/BlagovestKirilov/PhotoApp)
A full-stack social photo-sharing web application with server-rendered UI.

- Photo uploads to **AWS S3** with likes, comments, and reporting system
- Friend requests, real-time chat, in-app notifications
- Community pages with photo galleries and discovery suggestions
- Admin panel for content moderation, user bans, and report review
- **Stack**: Java 17 · Spring Boot 3 · Thymeleaf · MySQL · AWS S3

---

### [🍽 MenuCraft](https://github.com/BlagovestKirilov/MenuCraft)
A full-stack application for venues to manage menu templates and generate filled PDF menus.

- PDF generation via **Apache PDFBox** using AcroForm field mapping
- Menu generation history with regeneration support
- **Facebook Page integration** — OAuth flow for publishing posts directly to venue pages
- Role-based access (Admin / Company) with JWT auth
- **Stack**: Java 25 · Spring Boot 4 · React (Vite) · PostgreSQL

---

## 📫 Get in Touch

- **GitHub**: [github.com/BlagovestKirilov](https://github.com/BlagovestKirilov)
- **Email**: blagovestkirilov1@gmail.comhttps://www.linkedin.com/in/blagovestkirilov/
- **LinkedIn**: [linkedin.com/BlagovestKirilov](https://www.linkedin.com/in/blagovestkirilov/)
