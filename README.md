# Võ Hưng Yên

<p align="left">
<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <style>
    @keyframes glass-shimmer {
      0% { opacity: 0.1; transform: translateX(-100%) skewX(-15deg); }
      50% { opacity: 0.3; transform: translateX(100%) skewX(-15deg); }
      100% { opacity: 0.1; transform: translateX(-100%) skewX(-15deg); }
    }
    @keyframes text-breathing {
      0%, 100% { opacity: 0.8; }
      50% { opacity: 1; transform: translateY(-1px); }
    }
    .bg-container { fill: #09090b; }
    .glass-panel {
      fill: url(#glass-gradient);
      stroke: rgba(255, 255, 255, 0.08);
      stroke-width: 1.5;
    }
    .shimmer-line {
      fill: #38bdf8;
      animation: glass-shimmer 8s cubic-bezier(0.4, 0, 0.2, 1) infinite;
      transform-box: fill-box;
      transform-origin: center;
    }
    .title-text {
      font: bold 38px 'Satoshi', 'Geist', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      fill: #ffffff;
      letter-spacing: -1.5px;
    }
    .subtitle-text {
      font: 500 15px 'Geist', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      fill: #94a3b8;
      letter-spacing: 0.5px;
    }
    .accent-mark { fill: #38bdf8; font-weight: bold; }
    .terminal-signal {
      font: 12px 'JetBrains Mono', 'Fira Code', Consolas, 'Liberation Mono', monospace;
      fill: #38bdf8;
      animation: text-breathing 3s infinite;
    }
  </style>
  <defs>
    <linearGradient id="glass-gradient" x1="0" y1="0" x2="800" y2="200" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#1f4e79" stop-opacity="0.12"/>
      <stop offset="100%" stop-color="#09090b" stop-opacity="0.02"/>
    </linearGradient>
    <linearGradient id="glow-mesh" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#1f4e79" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#38bdf8" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <!-- Background Base -->
  <rect width="800" height="200" class="bg-container" rx="12"/>
  <circle cx="720" cy="60" r="140" fill="url(#glow-mesh)" />
  <!-- Glassmorphism Container with Physical Refraction -->
  <rect x="15" y="15" width="770" height="170" rx="10" class="glass-panel" />
  <rect x="15" y="15" width="100" height="170" class="shimmer-line" opacity="0.1"/>
  <!-- Typography Context -->
  <text x="50" y="85" class="title-text">VÕ HƯNG YÊN</text>
  <text x="50" y="120" class="subtitle-text">Software Engineer <tspan class="accent-mark">//</tspan> Backend Engineering <tspan class="accent-mark">//</tspan> Architecture</text>
  <text x="50" y="155" class="terminal-signal">[$] active_baseline_configuration: verified_</text>
</svg>
### System Status // Profile
<p align="left">
  Final-year Software Engineering student architecting end-to-end full-stack web, mobile, and AI-assisted systems. Focused on modern backend engineering, concurrent data pipelines, and cloud-native application deployment.
</p>

* **Current Focus:** High-concurrency architectures, distributed caching optimization, and automated LLM orchestration.
* **Education:** Software Engineering Student at HUFLIT (Expected Graduation: 2027).
* **Target Position:** Software Engineer Intern / Backend Developer Intern / Full Stack Developer Intern.
* **Deployment Matrix:** [my-portfolio-web-ex66.onrender.com](https://my-portfolio-web-ex66.onrender.com)

---

### Core Architecture // Technology Stack

**Languages & Frameworks**  
[![Core Skills](https://skillicons.dev/icons?i=cs,dotnet,nodejs,express,react,ts,js,java,html,css,tailwind,bootstrap&theme=dark)](https://skillicons.dev)

**Data, Infrastructure & Cloud Ecosystem**  
[![Infra Skills](https://skillicons.dev/icons?i=postgres,mysql,svg,docker,githubactions,redis,vercel,figma,postman&theme=dark)](https://skillicons.dev)

---

### Hardened Production Systems // Selected Projects

> **System 01 // ReqSimulator — Requirement Engineering Platform**
> * **Context:** Graduation Thesis | Microservices Architecture
> * **Tech Stack:** ASP.NET Core 9 • FastAPI • PostgreSQL • TypeScript • Gemini AI
> * **Design Engineering:** Engineered a decoupled three-service distributed system. Developed asynchronous communication channels and integrated generative AI orchestration layers to evaluate industry requirement coverage via semantic similarity vectors. Enforced security using JWT validation and granular role-based authorization (RBAC).
> * **Access:** [Live Production Application](https://kltn-chi.vercel.app)

---

> **System 02 // HungYenAirline — Flight Booking Engine**
> * **Context:** Cross-Platform Client Infrastructure
> * **Tech Stack:** ASP.NET Core 8 • SQL Server • Android Native • VNPAY API
> * **Design Engineering:** Applied `RowVersion` optimistic concurrency control directly within the data persistence layer to mitigate multi-user database race conditions during seat allocation. Maintained a shared backend API supporting both responsive web layers and native mobile clients.
> * **Access:** [Web Client Repository](https://github.com/voy32103-code/HungYenAirline_web) | [Android Native Repository](https://github.com/voy32103-code/HungYenAirline-Android)

---

> **System 03 // WebCRM — Enterprise Management Dashboard**
> * **Context:** Full-Stack Internal Workflow Automation
> * **Tech Stack:** React • Node.js • Express.js • PostgreSQL • Gemini AI
> * **Design Engineering:** Formulated clean relational schemas and analytical endpoints. Architected data-dense enterprise dashboards supporting asymmetric Kanban matrices and tabular visualization modules. Integrated context-aware generative pipelines for automated lead scoring.
> * **Access:** [Live Dashboard Presentation](https://webcrm-landing-page.vercel.app) | [Source Code](https://github.com/voy32103-code/WebCRM)

---

> **System 04 // Digital Tech Portfolio & Core Systems**
> * **Context:** Real-time Dynamic Platform
> * **Tech Stack:** ASP.NET Core • PostgreSQL • Redis • SignalR • QuestPDF
> * **Design Engineering:** Integrated Redis distributed caching layers to abstract database load under intensive traffic. Built real-time event broadcasting components via SignalR and handled asynchronous server-side PDF document generation using QuestPDF.
> * **Access:** [Live Application](https://my-portfolio-web-ex66.onrender.com) | [Source Code](https://github.com/voy32103-code/Personal-Dashboard)

---

> **System 05 // HairSalonDuyen Landing Page**
> * **Context:** Responsive Interface & UI Automation
> * **Tech Stack:** React • TailwindCSS • Selenium WebDriver
> * **Design Engineering:** Constructed high-fidelity frontend presentations with structured atomic component reusability. Authored automated end-to-end integration test suites to programmatically validate client UI workflow reliability.
> * **Access:** [Live Presentation](https://hairsalonduyen.vercel.app)

---

### System Telemetry // Metrics

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=voy32103-code&show_icons=true&theme=dark&title_color=38bdf8&text_color=94a3b8&icon_color=38bdf8&bg_color=09090b&border_color=1e293b&border_radius=8&count_private=true" alt="Core Profile Statistics" height="155px"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=voy32103-code&layout=compact&theme=dark&title_color=38bdf8&text_color=94a3b8&icon_color=38bdf8&bg_color=09090b&border_color=1e293b&border_radius=8" alt="Language Utilization Matrix" height="155px"/>
</p>

<p align="left">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=voy32103-code&theme=dark&title_color=38bdf8&text_color=94a3b8&icon_color=38bdf8&bg_color=09090b&border_color=1e293b&border_radius=8" alt="Commit Streak Telemetry" height="150px" />
</p>

---

### Gateways // Connect

<p align="left">
  <a href="mailto:voy32103@gmail.com">
    <img src="https://img.shields.io/badge/Endpoint-voy32103%40gmail.com-1f4e79?style=flat-square&logo=gmail&logoColor=ffffff&labelColor=09090b" alt="Email Endpoint" />
  </a>
  <a href="tel:+84355161941">
    <img src="https://img.shields.io/badge/Signal-(%2B84)%20355%20161%20941-1f4e79?style=flat-square&logo=phone&logoColor=ffffff&labelColor=09090b" alt="Communication Signal" />
  </a>
</p>
