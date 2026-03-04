# Hey there 👋, I'm Jesus Oseguera

## Security Engineer & Systems Programmer | CS @ UNLV (Dec 2026)

I'm a CS student at UNLV focused on **security engineering** and **systems programming**, building offensive tooling, detection systems, and hardened backend infrastructure. My path into security started at DEF CON 2025, where I was the first to solve a Lockheed Martin-sponsored Aero Cyber Range challenge by deciphering a perspective-dependent pigpen cipher hidden in a corrupted document.

I don't just study attacks, I build both sides. I engineered a C2 framework with TLS-encrypted channels, SHA-256 challenge-response auth, and a Flask operator dashboard, then used what I learned about beacon intervals, heartbeat patterns, and encrypted socket signatures to write detection rules for a companion network IDS in Rust. Building both sides of the same attack surface is how I approach security engineering.

---

### 🔧 What I'm Building

- **[Network IDS](https://github.com/Oseguera12)** — Production-grade Rust IDS capturing raw packets via `pnet`, running 5 detection algorithms across L2/L3/L4 (port scanning, SYN floods, connection rate anomalies, malicious signatures, sliding window analysis), with a PostgreSQL-backed alert pipeline and queryable REST API via Axum
- **[Botnet Simulation & C2 Framework](https://github.com/LayerZeroUNLV/botnet)** — Multi-client C2 with Flask operator dashboard, TLS-wrapped sockets, SHA-256 challenge-response auth, heartbeat monitoring, per-session transcript logging, and a bidirectional file transfer protocol
- **MMO Backend Infrastructure** — Fully authoritative game server in Rust (Axum + WebSocket + PostgreSQL + Redis): JWT middleware on all REST routes, role-elevated GM routes, per-connection WebSocket auth handshakes, and all game logic executing server-side to eliminate client-authoritative attack surface
- **[DNS Enumeration Tool](https://github.com/Oseguera12/domain-name-system-enumeration-tool)** — Multi-threaded DNS recon tool processing 500–1,000 subdomains/min with DNSSEC validation, THREADPOOLEXECUTOR optimization, and automated security pattern matching

---

### 🏆 Competitions & Org

- **[Layer Zero](https://github.com/LayerZeroUNLV)** @ UNLV — Top 12% NCL Team (53/454), DOE CyberForce 2025 competitor
- Delivered workshops on SQL injection, malware RE, password cracking, and botnet construction to 20+ students
- Manages a production Discord bot for 500+ members with REST API integration, RBAC, and PostgreSQL audit logging

---

### 🛠️ Tech Stack

```
Languages:       Rust · Python · C++ · TypeScript · JavaScript · SQL
Frameworks:      Axum · Tokio · pnet · SQLx · Flask · Next.js · React · Discord.py
Tools:           Git · PostgreSQL · Redis · Docker · Nginx · WebSocket · REST APIs · Linux/Unix · AWS
Certifications:  AWS Solutions Architect Associate (SAA-C03) · AWS Cloud Practitioner
```

---

### 📬 Let's Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-jesusoseguera.dev-blue?style=flat-square)](https://jesusoseguera.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jesus--oseguera12-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/jesus-oseguera12)
[![GitHub](https://img.shields.io/badge/GitHub-Oseguera12-181717?style=flat-square&logo=github)](https://github.com/Oseguera12)
[![Email](https://img.shields.io/badge/Email-oseguera12@protonmail.com-8B89CC?style=flat-square&logo=protonmail)](mailto:oseguera12@protonmail.com)

> 🎯 Seeking **summer 2026 internships** and post-graduation roles in **security engineering** or **systems programming** — particularly at defense-relevant organizations. US citizen, eligible for security clearance. Open to remote and select onsite.
