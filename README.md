<h1 align="center">Ibnu Habib Ridwansyah</h1>

<p align="center">
  <strong>Systems & Full-Stack Software Engineer</strong><br>
  Undergraduate Informatics Engineering at <a href="https://www.pens.ac.id/">Politeknik Elektronika Negeri Surabaya (PENS)</a>
</p>

<p align="center">
  Architecting high-performance native utilities, local-first applications, and open-data infrastructure for Indonesia.
</p>

<p align="center">
  <a href="https://www.ibnuhabib.web.id"><img src="https://img.shields.io/badge/Portfolio-ibnuhabib.web.id-0969da?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ibnuhabib/"><img src="https://img.shields.io/badge/LinkedIn-ibnuhabib-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mail@ibnuhabib.web.id"><img src="https://img.shields.io/badge/Email-mail@ibnuhabib.web.id-59636e?style=flat-square&logo=minutemailer&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=prodhokter&style=flat-square&color=0969da&label=Profile+Views" alt="Profile Views" />
</p>

---

### 🇮🇩 Open Data Infrastructure for Indonesia

Architect and maintainer of **[api-datasets-indonesia](https://github.com/prodhokter/api-datasets-indonesia)**: a production, high-throughput, read-only REST API daemon (built in Go & PostgreSQL) and curated repository serving **850,000+ official records** normalized from Indonesian government and state databases.

- **Public Production Endpoint**: [`api.ibnuhabib.web.id`](https://api.ibnuhabib.web.id) *(Zero API key required • CORS-enabled • Sub-50ms latency)*
- **Data Collections**:

| Dataset Repository | Records | Official Primary Source | Coverage |
| :--- | :---: | :--- | :--- |
| **[dataset-sekolah-indonesia](https://github.com/prodhokter/dataset-sekolah-indonesia)** | `547,019` | Dapodik, Kemendikbudristek | All formal educational institutions + Top 1000 LTMPT ranks |
| **[dataset-kbbi-indonesia](https://github.com/prodhokter/dataset-kbbi-indonesia)** | `209,868` | KBBI V / Badan Pengembangan Bahasa | Complete lexical entries, parts of speech, 1,453 standard word pairs |
| **[dataset-wilayah-indonesia](https://github.com/prodhokter/dataset-wilayah-indonesia)** | `91,599` | Kepmendagri No. 100.1.1-6117 (2025) | 38 provinces, 514 regencies/cities, 7,285 districts, 83,762 villages |
| **[dataset-program-studi-indonesia](https://github.com/prodhokter/dataset-program-studi-indonesia)** | `4,971` | SNPMB Kemendikbud | University degree programs with quotas, applicant demand & passing rates |
| **[dataset-perguruan-tinggi-indonesia](https://github.com/prodhokter/dataset-perguruan-tinggi-indonesia)** | `143` | SNPMB Kemendikbud | State universities (PTN) with capacity statistics and program distribution |

---

### 🛠️ Featured Systems & Engineering

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/prodhokter/segmenta">Segmenta</a></h4>
      <p><em>Modern, lightweight, privacy-respecting download accelerator & media grabber.</em></p>
      <ul>
        <li><strong>Core Engine</strong>: Asynchronous Rust core (Tokio, Reqwest, Rusqlite) paired with Tauri v2 and Svelte 5.</li>
        <li><strong>Dynamic Slicing</strong>: Concurrent 1–32 parallel HTTP <code>Range</code> stream chunking with token-bucket bandwidth governing.</li>
        <li><strong>Media Grabber</strong>: Native HLS (<code>.m3u8</code>) stream parser/muxer accompanied by a Manifest V3 companion browser extension.</li>
      </ul>
      <p><code>Rust</code> <code>Tauri v2</code> <code>Svelte 5</code> <code>SQLite</code> <code>Manifest V3</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/prodhokter/anti-distract">AntiDistract</a></h4>
      <p><em>Local-first deep focus enforcement desktop suite with edge vision intelligence.</em></p>
      <ul>
        <li><strong>Architecture</strong>: Python desktop suite built with PyQt6 and an OpenCV edge inference pipeline.</li>
        <li><strong>Biometric Focus</strong>: Real-time user presence and posture detection running entirely on-device with zero telemetry.</li>
        <li><strong>Interception</strong>: Low-level DNS and hosts-level site distraction blocker paired with a focus session state engine.</li>
      </ul>
      <p><code>Python</code> <code>PyQt6</code> <code>OpenCV</code> <code>Local-First</code> <code>Cross-Platform</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/prodhokter/api-datasets-indonesia">API Datasets Indonesia</a></h4>
      <p><em>Public, read-only RESTful API engine serving normalized national datasets.</em></p>
      <ul>
        <li><strong>Backend Engine</strong>: High-throughput Go REST daemon with connection-pooled PostgreSQL queries.</li>
        <li><strong>Query Performance</strong>: B-tree & trigram indexed search across 850k+ records with sub-50ms response times.</li>
        <li><strong>Zero-Friction</strong>: Publicly deployed infrastructure with automated health probes and open access.</li>
      </ul>
      <p><code>Go</code> <code>PostgreSQL</code> <code>REST API</code> <code>Docker</code> <code>Cloudflare</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/prodhokter/pens-kp-bot">PENS KP Bot</a></h4>
      <p><em>Automated headless bot for PENS student internship logbook synchronization.</em></p>
      <ul>
        <li><strong>Authentication Flow</strong>: Headless session lifecycle manager negotiating Central Authentication Service (CAS) SSO.</li>
        <li><strong>State Engine</strong>: Automated log entry generation, payload validation, and submission to Online MIS CAS.</li>
        <li><strong>Reliability</strong>: Retry strategies, structured logging, and network failure tolerance.</li>
      </ul>
      <p><code>Python</code> <code>Automation</code> <code>CAS SSO</code> <code>Session State</code></p>
    </td>
  </tr>
</table>

---

### 💻 Technical Arsenal

```
Systems & Core       :: Rust, Go, Python, C#, C++, TypeScript
Frontend & Desktop   :: Svelte 5, React, Next.js, Tauri v2, Flutter, PyQt6, Tailwind CSS
Databases & Storage  :: PostgreSQL, Supabase, SQLite, Redis, Cloudflare D1 / KV
Infrastructure & CI  :: Docker, Linux, GitHub Actions, Cloudflare Workers, Nginx
```

---

### 📈 Activity & Telemetry

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=prodhokter&show_icons=true&hide_border=true&bg_color=00000000&title_color=f0f6fc&text_color=9198a1&icon_color=4493f8" />
        <img width="100%" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=prodhokter&show_icons=true&hide_border=true&bg_color=00000000&title_color=1f2328&text_color=59636e&icon_color=0969da" />
      </picture>
    </td>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=prodhokter&layout=compact&hide_border=true&bg_color=00000000&title_color=f0f6fc&text_color=9198a1&icon_color=4493f8" />
        <img width="100%" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prodhokter&layout=compact&hide_border=true&bg_color=00000000&title_color=1f2328&text_color=59636e&icon_color=0969da" />
      </picture>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=prodhokter&hide_border=true&background=00000000&ring=4493f8&fire=f0883e&currStreakLabel=4493f8&sideLabels=9198a1&dates=9198a1&currStreakNum=f0f6fc" />
        <img width="100%" alt="Streak stats" src="https://streak-stats.demolab.com?user=prodhokter&hide_border=true&background=00000000&ring=0969da&fire=bc4c00&currStreakLabel=0969da&sideLabels=59636e&dates=59636e&currStreakNum=1f2328" />
      </picture>
    </td>
  </tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prodhokter/prodhokter/output/snake-dark.svg" />
  <img width="100%" alt="Contribution Graph Snake Animation" src="https://raw.githubusercontent.com/prodhokter/prodhokter/output/snake-light.svg" />
</picture>

---

<p align="center">
  <sub>Surabaya, Indonesia • <a href="https://www.ibnuhabib.web.id">ibnuhabib.web.id</a></sub>
</p>
