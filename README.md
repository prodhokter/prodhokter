<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,14,24,30&height=220&section=header&text=Ibnu%20Habib%20Ridwansyah&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Systems%20%26%20Full-Stack%20Software%20Engineer&descAlignY=60&descSize=19" alt="Header Banner" />
</div>

<p align="center">
  <a href="https://www.ibnuhabib.web.id"><img src="https://img.shields.io/badge/Portfolio-ibnuhabib.web.id-0284C7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ibnuhabib/"><img src="https://img.shields.io/badge/LinkedIn-ibnuhabib-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mail@ibnuhabib.web.id"><img src="https://img.shields.io/badge/Email-mail@ibnuhabib.web.id-6366F1?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Surabaya-Indonesia-10B981?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=prodhokter&style=for-the-badge&color=EC4899&label=Profile+Views" alt="Profile Views" />
</p>

<p align="center">
  <em>Undergraduate Informatics Engineering at <a href="https://www.pens.ac.id/">Politeknik Elektronika Negeri Surabaya (PENS)</a></em><br>
  <strong>Architecting high-performance native engines, local-first applications, and public data infrastructure.</strong>
</p>

---

### 🇮🇩 Indonesian Open Data Infrastructure

<p>
  Architect and maintainer of <strong><a href="https://github.com/prodhokter/api-datasets-indonesia">api-datasets-indonesia</a></strong>: a production, high-throughput, read-only RESTful API daemon and open repository serving <strong>850,000+ official records</strong> normalized from Indonesian ministries and academic databases.
</p>

<p>
  <a href="https://api.ibnuhabib.web.id"><img src="https://img.shields.io/badge/Live_API-api.ibnuhabib.web.id-10B981?style=flat-square&logo=fastapi&logoColor=white" alt="Live Endpoint" /></a>
  <img src="https://img.shields.io/badge/Indexed_Records-850%2C000%2B-6366F1?style=flat-square&logo=databricks&logoColor=white" alt="Indexed Records" />
  <img src="https://img.shields.io/badge/Latency-%3C50ms-0284C7?style=flat-square&logo=speedtest&logoColor=white" alt="Latency" />
  <img src="https://img.shields.io/badge/Auth-Zero_Key_Required-F59E0B?style=flat-square" alt="Zero Key" />
</p>

| Dataset | Volume | Primary Upstream Source | Scope & Utility | Status |
| :--- | :---: | :--- | :--- | :---: |
| **[dataset-sekolah-indonesia](https://github.com/prodhokter/dataset-sekolah-indonesia)** | `547,019` | Dapodik, Kemendikbudristek | All formal national schools + Top 1000 LTMPT national rankings | ![Active](https://img.shields.io/badge/Live-10B981?style=flat-square) |
| **[dataset-kbbi-indonesia](https://github.com/prodhokter/dataset-kbbi-indonesia)** | `209,868` | KBBI V / Badan Bahasa | Complete lexical dictionary, parts of speech, 1,453 word pairs | ![Active](https://img.shields.io/badge/Live-10B981?style=flat-square) |
| **[dataset-wilayah-indonesia](https://github.com/prodhokter/dataset-wilayah-indonesia)** | `91,599` | Kepmendagri 100.1.1-6117 (2025) | 38 provinces, 514 regencies, 7,285 districts, 83,762 villages | ![Active](https://img.shields.io/badge/Live-10B981?style=flat-square) |
| **[dataset-program-studi-indonesia](https://github.com/prodhokter/dataset-program-studi-indonesia)** | `4,971` | SNPMB Kemendikbud | University degree programs, admissions quotas & historical passing rates | ![Active](https://img.shields.io/badge/Live-10B981?style=flat-square) |
| **[dataset-perguruan-tinggi-indonesia](https://github.com/prodhokter/dataset-perguruan-tinggi-indonesia)** | `143` | SNPMB Kemendikbud | State universities (PTN) with capacity statistics and faculty breakdowns | ![Active](https://img.shields.io/badge/Live-10B981?style=flat-square) |

---

### 🛠️ Featured Systems & Engineering

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/prodhokter/segmenta">Segmenta</a>
      </h3>
      <p>
        <a href="https://github.com/prodhokter/segmenta"><img src="https://img.shields.io/badge/GitHub-Segmenta-181717?style=flat-square&logo=github&logoColor=white" /></a>
        <img src="https://img.shields.io/badge/Dual_License-MIT%20%2F%20Apache_2.0-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Architecture-Rust%20%2B%20Tauri-orange?style=flat-square" />
      </p>
      <p><em>High-throughput, privacy-respecting download accelerator and streaming media extractor.</em></p>
      <ul>
        <li><strong>Multi-Connection Slicing</strong>: Concurrent 1–32 parallel HTTP <code>Range</code> stream chunking with token-bucket bandwidth governing.</li>
        <li><strong>Media Grabber</strong>: Native HLS (<code>.m3u8</code>) stream parser/muxer paired with a Manifest V3 companion browser extension.</li>
        <li><strong>Low Footprint</strong>: Asynchronous Rust core (Tokio, Reqwest, Rusqlite) driving a responsive Svelte 5 desktop GUI.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black" />
        <img src="https://img.shields.io/badge/Tauri_v2-24C8D8?style=flat-square&logo=tauri&logoColor=white" />
        <img src="https://img.shields.io/badge/Svelte_5-FF3E00?style=flat-square&logo=svelte&logoColor=white" />
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/prodhokter/anti-distract">AntiDistract</a>
      </h3>
      <p>
        <a href="https://github.com/prodhokter/anti-distract"><img src="https://img.shields.io/badge/GitHub-AntiDistract-181717?style=flat-square&logo=github&logoColor=white" /></a>
        <img src="https://img.shields.io/badge/Cross_Platform-Win%20%7C%20Mac%20%7C%20Linux-success?style=flat-square" />
        <img src="https://img.shields.io/badge/Privacy-100%25_Local--First-blueviolet?style=flat-square" />
      </p>
      <p><em>Local-first deep focus productivity suite with biometric edge computing.</em></p>
      <ul>
        <li><strong>Biometric Vision Engine</strong>: Real-time user presence and posture detection with OpenCV edge inference (zero telemetry).</li>
        <li><strong>Kernel/Hosts Interception</strong>: Low-level DNS and hosts-level distraction blocker synchronized with Pomodoro cycles.</li>
        <li><strong>Gamified Retention</strong>: Virtual garden state machine tracking continuous focus streaks locally.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white" />
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
        <img src="https://img.shields.io/badge/Local--First-059669?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/prodhokter/api-datasets-indonesia">API Datasets Indonesia</a>
      </h3>
      <p>
        <a href="https://github.com/prodhokter/api-datasets-indonesia"><img src="https://img.shields.io/badge/GitHub-API_Datasets-181717?style=flat-square&logo=github&logoColor=white" /></a>
        <a href="https://api.ibnuhabib.web.id"><img src="https://img.shields.io/badge/Live_API-api.ibnuhabib.web.id-10B981?style=flat-square&logo=fastapi&logoColor=white" /></a>
      </p>
      <p><em>Production RESTful engine serving normalized national datasets with zero auth friction.</em></p>
      <ul>
        <li><strong>High-Throughput Daemon</strong>: Go HTTP service connected to a query-optimized PostgreSQL cluster.</li>
        <li><strong>Fast Retrieval</strong>: B-tree & trigram indexed search resolving queries across 850k+ records in sub-50ms.</li>
        <li><strong>Resilient Architecture</strong>: Containerized deployment with automated health checks and Cloudflare edge caching.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/prodhokter/pens-kp-bot">PENS KP Bot</a>
      </h3>
      <p>
        <a href="https://github.com/prodhokter/pens-kp-bot"><img src="https://img.shields.io/badge/GitHub-pens--kp--bot-181717?style=flat-square&logo=github&logoColor=white" /></a>
        <img src="https://img.shields.io/badge/Automation-CAS_SSO-orange?style=flat-square" />
      </p>
      <p><em>Automated headless bot for PENS student internship logbook compliance and submission.</em></p>
      <ul>
        <li><strong>Auth State Negotiation</strong>: Automated session lifecycle management interacting with Central Authentication Service (CAS) SSO.</li>
        <li><strong>Payload Validation</strong>: Structured daily log formulation, schema verification, and automated Online MIS submission.</li>
        <li><strong>Fault-Tolerant Engine</strong>: Exponential backoff retries, session renewal, and structured execution audits.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Automation-E11D48?style=flat-square" />
        <img src="https://img.shields.io/badge/CAS_SSO-D97706?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### 💻 Technical Arsenal

<div align="center">

#### Systems & Core Programming
<p>
  <img src="https://img.shields.io/badge/Rust-DEA584?style=for-the-badge&logo=rust&logoColor=black" alt="Rust" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
</p>

#### Frontend & Native Desktop
<p>
  <img src="https://img.shields.io/badge/Svelte_5-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte 5" />
  <img src="https://img.shields.io/badge/Tauri_v2-24C8D8?style=for-the-badge&logo=tauri&logoColor=white" alt="Tauri v2" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt6" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

#### Databases, Caching & Cloud Storage
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Cloudflare_D1-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare D1" />
</p>

#### DevOps, Edge & Infrastructure
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
</p>

</div>

---

### 📊 Activity & Telemetry

<table>
  <tr>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=prodhokter&theme=tokyonight" />
        <img width="100%" alt="GitHub Stats Card" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=prodhokter&theme=default" />
      </picture>
    </td>
    <td width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=prodhokter&theme=tokyonight" />
        <img width="100%" alt="Languages Chart" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=prodhokter&theme=default" />
      </picture>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=prodhokter&theme=tokyonight&hide_border=false" />
        <img width="100%" alt="Streak Stats" src="https://streak-stats.demolab.com?user=prodhokter&theme=default&hide_border=false" />
      </picture>
    </td>
  </tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prodhokter/prodhokter/output/snake-dark.svg" />
  <img width="100%" alt="Contribution Graph Snake Animation" src="https://raw.githubusercontent.com/prodhokter/prodhokter/output/snake-light.svg" />
</picture>

---

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=30,24,14,2&height=100&section=footer" alt="Footer Wave" />
  <p><sub>Surabaya, Indonesia • <a href="https://www.ibnuhabib.web.id">ibnuhabib.web.id</a> • Engineered with Precision</sub></p>
</div>
