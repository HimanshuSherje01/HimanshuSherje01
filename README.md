<div align="center">

<img src="./assets/profile/profile-banner.svg" width="100%" alt="Header Banner" />

<br/><br/>

<sub><b>BACKEND ENGINEERING · AI/RAG · SYSTEMS</b></sub>

# HIMANSHU SHERJE

*Building reliable backend systems, asynchronous pipelines, and intelligent applications.*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-sherje/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/Himanshu_sherje01/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:himanshusherje9@gmail.com)

<br/>

<sub><a href="#01--about">`01 About`</a> &nbsp;·&nbsp; <a href="#02--focus">`02 Focus`</a> &nbsp;·&nbsp; <a href="#03--featured-projects">`03 Projects`</a> &nbsp;·&nbsp; <a href="#04--technical-stack">`04 Stack`</a> &nbsp;·&nbsp; <a href="#05--experience--leadership">`05 Experience`</a> &nbsp;·&nbsp; <a href="#06--education--achievements">`06 Education`</a> &nbsp;·&nbsp; <a href="#07--contact">`07 Contact`</a></sub>

</div>

<br/>

---

### `01 / ABOUT`
## Engineering systems, not just interfaces.

<table width="100%">
  <tr>
    <td width="65%" valign="top">
      Backend-focused CSBS student building scalable APIs, asynchronous background workflows, and AI/RAG applications. Experienced in decoupling compute-heavy jobs using Redis queues, structuring document and relational stores, and integrating local LLM pipelines over vector indexes.
      <br/><br/>
      Currently contributing as a <b>Backend Engineering Intern</b> at <b>Incubein Foundation</b>.
    </td>
    <td width="35%" valign="top">
      <sub>CURRENT STATUS</sub><br/>
      • <b>Intern</b> · Incubein Foundation<br/>
      • <b>B.Tech CSBS</b> · SVPCET '28 (CGPA 7.52)<br/>
      • <b>Diploma CE</b> · GP Yavatmal (81.66%)<br/>
      • <b>Location</b> · Nagpur, India
    </td>
  </tr>
</table>

---

### `02 / FOCUS`
## Core Architectural Pillars

<table>
  <tr>
    <td width="33.3%" valign="top">
      <sub>01 / BACKEND</sub>
      <h4>Distributed & REST APIs</h4>
      • REST endpoints & WebSockets<br/>
      • Asynchronous Redis/Upstash queues<br/>
      • MongoDB, PostgreSQL & MySQL<br/>
      • Schema design & query handling
    </td>
    <td width="33.3%" valign="top">
      <sub>02 / AI & RAG</sub>
      <h4>Retrieval & Embeddings</h4>
      • Dynamic PDF ingestion & chunking<br/>
      • 384-dimensional embeddings<br/>
      • MongoDB Atlas Vector Search<br/>
      • Local Ollama / Qwen2.5 3B inference
    </td>
    <td width="33.3%" valign="top">
      <sub>03 / DELIVERY</sub>
      <h4>Reliability & Security</h4>
      • Helmet.js HTTP protection<br/>
      • node-cron workflow automation<br/>
      • Payloads optimized for 2G networks<br/>
      • Playwright automated E2E testing
    </td>
  </tr>
</table>

---

### `03 / FEATURED PROJECTS`
## Selected Engineering Work

### 03.1 · APSM
**Cross-Platform Analytics & Publishing Engine**

`Node.js` `Express` `MongoDB` `Redis` `Upstash` `Helmet`

```text
[ 4 Social Platforms ] ──── [ < 20s Multi-Post ] ──── [ Redis/Upstash Task Queues ]
```

- **Modular Backend Architecture**: Engineered backend services handling publishing pipelines across 4 platforms in **under 20 seconds**.
- **Asynchronous Task Queues**: Decoupled multi-platform upload and publishing workloads using non-blocking Redis and Upstash queues.
- **Defensive API Hardening**: Enforced HTTP security headers with Helmet and automated recurring backend sync jobs via `node-cron`.

<details>
  <summary><sub><b>VIEW ARCHITECTURE DETAILS</b></sub></summary>
  <br/>
  <ul>
    <li>Engineered to prevent request timeouts by delegating social publishing payloads to asynchronous background workers.</li>
    <li>Maintains decoupled status handling across social network rate limits and endpoint responses.</li>
  </ul>
</details>

<br/>

[ View Repository → ](https://github.com/sudeep042006/APSM)

---

### 03.2 · Contexta
**AI Document Intelligence Assistant**

`React` `Node.js` `MongoDB` `RAG` `Ollama` `Qwen2.5 3B` `Atlas Vector Search`

```text
PDF Ingest ──> Chunking ──> 384-dim Embed ──> Atlas Vector Search ──> Ollama / Qwen2.5 ──> Grounded Answer
```

- **Vector Processing Pipeline**: Dynamic PDF text parsing and sliding-window chunking producing **384-dimensional dense vector embeddings**.
- **Atlas Vector Similarity**: High-dimensional vector indexing and k-NN query execution against MongoDB Atlas with user document isolation.
- **Local Inference & Grounding**: Context-augmented answer generation via local **Qwen2.5 3B** with verifiable **page-level citations**.

<details>
  <summary><sub><b>VIEW RAG PIPELINE DETAILS</b></sub></summary>
  <br/>
  <ul>
    <li>Runs completely on local inference via Ollama to ensure zero external API token costs and data privacy.</li>
    <li>Constrains generative model outputs to verified document segments to minimize hallucinations.</li>
  </ul>
</details>

<br/>

[ View Repository → ](https://github.com/HimanshuSherje01/Contexta)

---

### 03.3 · KrishiSetu
**Smart Agriculture Mobile Application**

`React Native` `Node.js` `MongoDB` `Socket.io` `Playwright`

```text
[ ~2s Load Time on 2G ] ──── [ Real-time Socket.io ] ──── [ Role-Based Access Control ]
```

- **Engineered for Low Connectivity**: Tuned data routing and payload footprint to deliver **~2-second initial screen load times on 2G networks**.
- **Real-Time Event Channels**: Established persistent Socket.io channels for low-latency market advisories and instant broadcasts.
- **Quality & Authorization**: Protected endpoints using role-based authentication and automated critical user journeys with **Playwright**.

<details>
  <summary><sub><b>VIEW MOBILITY DETAILS</b></sub></summary>
  <br/>
  <ul>
    <li>Architected specifically for low-end devices and volatile rural cellular connections.</li>
    <li>Validates end-to-end user onboarding, submissions, and status updates through automated test runners.</li>
  </ul>
</details>

<br/>

[ View Repository → ](https://github.com/HimanshuSherje01/Krishi-Setu)

---

### `04 / TECHNICAL STACK`
## System Architecture & Technologies

| Domain | Technologies & Infrastructure |
| :--- | :--- |
| **Languages** | `C++` · `C` · `Java` · `Python` · `JavaScript` · `SQL` |
| **Backend** | `Node.js` · `Express.js` · `FastAPI` · `Redis` · `REST APIs` · `WebSockets` |
| **Databases** | `MongoDB` · `PostgreSQL` · `MySQL` · `Supabase` |
| **AI / Vector** | `RAG Pipelines` · `384-dim Embeddings` · `Atlas Vector Search` · `Ollama` · `Gemini API` · `Twilio` |
| **DevOps & Tools** | `Docker` · `Git` · `GitHub Actions` · `Upstash` · `Vercel` · `Render` · `Helmet` · `Playwright` |
| **Core** | `Data Structures & Algorithms` · `OOP` · `DBMS` · `System Design` · `Automation` |

---

### `05 / EXPERIENCE & LEADERSHIP`
## Work & Leadership

```text
2026 — PRESENT
│
├── Backend Engineering Intern · Incubein Foundation
│   • Contributing to a 7-member team engineering asynchronous backend services for APSM.
│   • Built Redis job processing queues, integrated Helmet API security, and node-cron jobs.
│   Stack: Node.js · Express · Redis · MongoDB · Helmet · node-cron
│
2024 — 2025
│
└── Event Management Head & Treasurer · COSA, GP Yavatmal
    • Coordinated logistics, budgeting, and operations for university technical competitions.
    • Managed department finances, fiscal accounting, and execution across student teams.
```

---

### `06 / EDUCATION & ACHIEVEMENTS`
## Academics & Milestones

<table width="100%">
  <tr>
    <td width="55%" valign="top">
      <sub>ACADEMIC BACKGROUND</sub>
      <h4>Computer Science & Engineering</h4>
      • <b>B.Tech in CSBS</b><br/>
      &nbsp;&nbsp;SVPCET, Nagpur · <i>2024 – 2028</i> · <b>CGPA 7.52</b><br/><br/>
      • <b>Diploma in Computer Engineering</b><br/>
      &nbsp;&nbsp;Government Polytechnic Yavatmal · <i>2021 – 2024</i> · <b>81.66%</b>
    </td>
    <td width="45%" valign="top">
      <sub>COMPETITIVE MILESTONES</sub>
      <h4>Recognition & Practice</h4>
      • 🥈 <b>2nd Runner-Up</b> — IIIT Nagpur Hackathon<br/>
      &nbsp;&nbsp;<i>Placed among 40+ engineering teams</i><br/><br/>
      • 🧩 <b>100+ Problems Solved</b> — LeetCode<br/>
      &nbsp;&nbsp;<i>Data Structures, Graphs & Dynamic Programming</i>
    </td>
  </tr>
</table>

<br/>

<sub>CURRENTLY EXPLORING</sub><br/>
`System Design` · `Distributed Systems` · `AI Engineering` · `RAG` · `Vector Search` · `Docker` · `CI/CD`

---

<div align="center">

### `07 / CONTACT`
## Let's build something useful.

*Available for backend engineering opportunities, scalable systems, and RAG architectures.*

<br/>

[![Email](https://img.shields.io/badge/Email-himanshusherje9%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:himanshusherje9@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-sherje/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/Himanshu_sherje01/)

<br/><br/>

<sub>HIMANSHU SHERJE · NAGPUR, MAHARASHTRA, INDIA</sub>

</div>
