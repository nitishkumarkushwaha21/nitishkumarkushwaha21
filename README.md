<div align="center">

<img src="./assets/tree-top-full.jpg" alt="Tree banner" width="100%" />

# Nitish Kumar Kushwaha

**Full-Stack Engineer · Production Software & Applied AI**

I take products from idea to production — learning platforms, payments, automation, and AI-backed tools — with clean UX and reliable backends.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nitishkumar2026-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitishkumar2026)
[![LeetCode](https://img.shields.io/badge/LeetCode-1799%20·%20Top%2010%25-F59E0B?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/nitishkumarkushwaha/)
[![Resume](https://img.shields.io/badge/Resume-View%20PDF-EA580C?style=for-the-badge&logo=readthedocs&logoColor=white)](./Nitish_Kushwaha_Resume.pdf)
[![Email](https://img.shields.io/badge/Email-Contact-16A34A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nitish.kumar.cse2026@gmail.com)

</div>

---

## Explainer

<div align="center">

A 1 min 40 sec walkthrough of my work — learning platforms, payments, and full-stack products.

<!-- To play the video inline on GitHub: edit this file on github.com, drag the mp4 into the editor,
     and replace this whole block with the https://github.com/user-attachments/... link GitHub generates. -->
<a href="https://drive.google.com/file/d/1mzQ_YsShtPqzAhd4a7Zeyl2s5pEsn8BQ/view?usp=sharing">
  <img src="./assets/explainer-poster.jpg" alt="Play the Nitish Kumar Kushwaha explainer video" width="100%" />
</a>

[![Watch the explainer](https://img.shields.io/badge/▶-Watch%20the%20explainer-7C3AED?style=for-the-badge)](https://drive.google.com/file/d/1mzQ_YsShtPqzAhd4a7Zeyl2s5pEsn8BQ/view?usp=sharing)

</div>

---

## About Me

- `Software Developer 1` at Bigintsolutions (May 2026 – Present); previously interned at NexisparkX Technologies and Reelife
- B.Tech in Computer Science and Engineering, IIIT Ranchi (`2022 – 2026`, CGPA `7.83`)
- LeetCode: `500+` problems, rating `1799` (Top 10%), `50+` contests, `93-day` POTD streak
- Anthropic API Certified — tool use, RAG, MCP, prompt caching, and agent workflows; I build with AI coding tools every day

> I like building products that reduce friction, simplify messy workflows, and make complex systems feel intuitive.

---

## Experience

### Bigintsolutions — Software Developer 1
`May 2026 – Present` · Remote

- Rebuilt [learn.approachable.dev](https://learn.approachable.dev) from a bare landing page (dashboard, video player, progress tracking) and built [approachable.dev](https://approachable.dev), the company marketing site — first corporate lead within 3 days of launch.
- Built the payment and billing flow from scratch: Razorpay across iOS and Android (every major method except Apple Pay) with IP-based country pricing, Cashfree as a backup gateway, and server-side price resolution so checkout amounts can't be changed from the client. Processed `Rs.2L+` revenue and `34` payments in month 1, with zero errors.
- Automated a Razorpay → Zoho Books invoice workflow so every successful payment raises a customer invoice, and built Zoho Flow and n8n automations for bulk and targeted emails and operational workflows.
- Shipped `3` frontend features for the Haziram production app (`4,000+` workers, `200+` companies) and `1` admin-app feature.
- Owned Datadog monitoring and debugging across services (see [Debugging Notes](#debugging-notes)).
- Built a chat-based video editor that cut internal video-editing time from `6–8 hours` to `2–3 hours`.
- Delivered `600+` commits across `3` projects built from scratch and `1` existing project, in a 6-person team.

### NexisparkX Technologies — MERN Stack Intern
`April 2026 – May 2026` · Remote

- Migrated a production database from Supabase to MongoDB with zero data loss, and built an admin dashboard for NX Solution’s Smart Ecosystem platform.

### Reelife Private Limited — Full Stack Developer Intern
`June 2025 – August 2025` · Remote

- Delivered `10+` production-ready React components and Node.js/Express REST API routes for an internal e-commerce platform, and debugged failures in Postman to improve reliability.

---

## Featured Projects

### AlgoNote AI

<table>
  <tr>
    <td width="54%" valign="top">
      <p><strong>Built to solve the fragmented interview-prep workflow by combining DSA practice, note-taking, imports, and personalized revision into one workspace.</strong></p>
      <p>Architected a microservices backend across 3 services with an API Gateway on a 6-service Docker Compose stack (AWS EC2), exposing 33 REST endpoints. The product side is an IDE-style workspace with a Monaco editor, one-click LeetCode import, and a YouTube-to-revision-sheet pipeline.</p>
      <p><strong>Tech Stack</strong><br />
      <code>React</code> <code>Vite</code> <code>Tailwind CSS</code> <code>Monaco Editor</code> <code>Node.js</code> <code>Express</code> <code>PostgreSQL</code> <code>MongoDB</code> <code>Clerk</code> <code>Docker</code></p>
      <p><strong>Links</strong><br />
      <a href="https://github.com/nitishkumarkushwaha21/Algonote">Repository</a> • <a href="http://algonote.duckdns.org/">Live Demo</a></p>
    </td>
    <td width="46%" align="center">
      <img src="./images/algonote-1.png" alt="AlgoNote AI preview" width="100%" />
    </td>
  </tr>
</table>

<details>
  <summary><strong>More Screenshots</strong></summary>
  <br />
  <p align="center">
    <img src="./images/algonote-2.png" alt="AlgoNote screenshot 2" width="32%" />
    <img src="./images/algonote-3.png" alt="AlgoNote screenshot 3" width="32%" />
    <img src="./images/algonote-4.png" alt="AlgoNote screenshot 4" width="32%" />
  </p>
  <p align="center">
    <img src="./images/algonote-5.png" alt="AlgoNote screenshot 5" width="32%" />
    <img src="./images/algonote-6.png" alt="AlgoNote screenshot 6" width="32%" />
  </p>
</details>

---

### n8n Job Hunter

<table>
  <tr>
    <td width="46%" align="center">
      <img src="./assets/n8n-job-hunter-flow.svg" alt="n8n Job Hunter pipeline: collect, pre-filter, deduplicate, AI screen, rules in code, notify" width="100%" />
    </td>
    <td width="54%" valign="top">
      <p><strong>Built to stop manually checking a dozen job boards every day — an hourly pipeline that finds fresher software roles and emails only the real matches.</strong></p>
      <p>A 23-node n8n workflow pulls new listings from YC, RemoteOK, We Work Remotely, Himalayas, and company pages on Greenhouse, Lever, and Ashby. A cheap regex pass and a Google Sheets "seen" list filter out misses and duplicates before any AI call; Gemini then screens the rest in batches for fit, experience, and salary in ₹. The final decision is made by code, not the model, and failed AI calls retry on the next run.</p>
      <p><strong>Tech Stack</strong><br />
      <code>n8n</code> <code>JavaScript</code> <code>Google Gemini API</code> <code>Google Sheets API</code> <code>Gmail SMTP</code> <code>Docker</code></p>
      <p><strong>Links</strong><br />
      <a href="https://github.com/nitishkumarkushwaha21/n8n-job-hunter">Repository</a></p>
    </td>
  </tr>
</table>

---

### VedaAI Assessment Creator

<table>
  <tr>
    <td width="54%" valign="top">
      <p><strong>Built so teachers can configure question types, marks, and difficulty, then generate a structured, syllabus-aligned paper through an LLM pipeline (OpenRouter, GPT-4o-mini).</strong></p>
      <p>The strongest engineering part was an async job queue (BullMQ, Redis) with a background worker that streams real-time progress — queued, processing, completed, or failed — to the client over Socket.IO, plus direct PDF export.</p>
      <p><strong>Tech Stack</strong><br />
      <code>Next.js</code> <code>TypeScript</code> <code>Node.js</code> <code>Express</code> <code>MongoDB</code> <code>Redis</code> <code>BullMQ</code> <code>Socket.IO</code> <code>Clerk</code></p>
      <p><strong>Links</strong><br />
      <a href="https://github.com/nitishkumarkushwaha21/vedaai-ai-question-maker">Repository</a> • <a href="https://vedaai-ai-question-maker.vercel.app/">Live Demo</a></p>
    </td>
    <td width="46%" align="center">
      <img src="./images/veda-1.png" alt="VedaAI preview" width="100%" />
    </td>
  </tr>
</table>

<details>
  <summary><strong>More Screenshots</strong></summary>
  <br />
  <p align="center">
    <img src="./images/veda-2.png" alt="VedaAI screenshot 2" width="48%" />
    <img src="./images/veda-3.png" alt="VedaAI screenshot 3" width="48%" />
  </p>
</details>

---

## More Projects

| Project | What it is | Stack |
| --- | --- | --- |
| **[BuiltByWho](https://freelancer-xi-nine.vercel.app/)** | Studio site for scoping and shipping client websites — case studies (PULSE, Drishya Trails, Root &amp; Rise), services, and a lead form backed by an API for projects, reviews, and inquiries | React, Vite, Node.js, Express, MongoDB |
| **Vantage** *(in progress)* | Real-estate management product | React, Python, PostgreSQL, Docker |
| **Notes extension** | Browser notes with version history — cut repetitive form-filling from about 10 minutes to 1 | JavaScript |
| **Telegram job finder** | Pulls job posts from Telegram channels — cut a 3–4 hour manual search to about 30 minutes | Automation |

<details>
  <summary><strong>BuiltByWho screenshots</strong></summary>
  <br />
  <p align="center">
    <img src="./images/builtbywho-1.png" alt="BuiltByWho screenshot 1" width="32%" />
    <img src="./images/builtbywho-2.png" alt="BuiltByWho screenshot 2" width="32%" />
    <img src="./images/builtbywho-3.png" alt="BuiltByWho screenshot 3" width="32%" />
  </p>
  <p align="center">
    <img src="./images/builtbywho-4.png" alt="BuiltByWho screenshot 4" width="32%" />
    <img src="./images/builtbywho-5.png" alt="BuiltByWho screenshot 5" width="32%" />
  </p>
</details>

---

## Debugging Notes

**A payment gateway that failed with correct code.** A Cashfree integration had to ship in a day, but test payments kept failing even though the application code looked right. I instrumented the API calls, then built a minimal HTML page that called Cashfree directly across API versions. That isolated the failure to the gateway itself; Cashfree confirmed and fixed it the next day, with no changes to our code.

**AI onboarding that finished but produced no profile.** Users completed the onboarding chat, yet their profiles never generated. Correlating Datadog session replays, backend logs, and MongoDB data traced it to concurrent session creation, inconsistent session IDs, and requests exceeding Heroku's 30s timeout — which drove fixes for session consistency, concurrency, recovering saved AI data, and long-running requests.

> My rule from both: reduce the system to a reproducible case and find the failing boundary before changing code.

---

## Skills

<div align="center">

### Languages

![JavaScript](https://img.shields.io/badge/JavaScript-1E293B?style=for-the-badge&logo=javascript&logoColor=FACC15)
![TypeScript](https://img.shields.io/badge/TypeScript-1E293B?style=for-the-badge&logo=typescript&logoColor=38BDF8)
![C++](https://img.shields.io/badge/C++-1E293B?style=for-the-badge&logo=cplusplus&logoColor=60A5FA)
![Python](https://img.shields.io/badge/Python-1E293B?style=for-the-badge&logo=python&logoColor=A78BFA)
![SQL](https://img.shields.io/badge/SQL-1E293B?style=for-the-badge&logo=postgresql&logoColor=93C5FD)

### Frontend

![React](https://img.shields.io/badge/React-0F172A?style=for-the-badge&logo=react&logoColor=67E8F9)
![Next.js](https://img.shields.io/badge/Next.js-0F172A?style=for-the-badge&logo=nextdotjs&logoColor=ffffff)
![Vite](https://img.shields.io/badge/Vite-0F172A?style=for-the-badge&logo=vite&logoColor=C084FC)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=22D3EE)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-0F172A?style=for-the-badge&logo=shadcnui&logoColor=ffffff)
![Zustand](https://img.shields.io/badge/Zustand-0F172A?style=for-the-badge&logo=react&logoColor=F59E0B)

### Backend

![Node.js](https://img.shields.io/badge/Node.js-111827?style=for-the-badge&logo=nodedotjs&logoColor=4ADE80)
![Express](https://img.shields.io/badge/Express-111827?style=for-the-badge&logo=express&logoColor=F8FAFC)
![Socket.IO](https://img.shields.io/badge/Socket.IO-111827?style=for-the-badge&logo=socketdotio&logoColor=ffffff)
![BullMQ](https://img.shields.io/badge/BullMQ-111827?style=for-the-badge&logo=redis&logoColor=F87171)
![Zod](https://img.shields.io/badge/Zod-111827?style=for-the-badge&logo=zod&logoColor=C4B5FD)
![Clerk](https://img.shields.io/badge/Clerk-111827?style=for-the-badge&logo=clerk&logoColor=F8FAFC)
![Nginx](https://img.shields.io/badge/Nginx-111827?style=for-the-badge&logo=nginx&logoColor=4ADE80)

### Databases and Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-172554?style=for-the-badge&logo=postgresql&logoColor=93C5FD)
![MongoDB](https://img.shields.io/badge/MongoDB-172554?style=for-the-badge&logo=mongodb&logoColor=4ADE80)
![MySQL](https://img.shields.io/badge/MySQL-172554?style=for-the-badge&logo=mysql&logoColor=7DD3FC)
![Redis](https://img.shields.io/badge/Redis-172554?style=for-the-badge&logo=redis&logoColor=F87171)
![Docker](https://img.shields.io/badge/Docker-172554?style=for-the-badge&logo=docker&logoColor=38BDF8)
![AWS](https://img.shields.io/badge/AWS%20EC2-172554?style=for-the-badge&logo=amazonaws&logoColor=FBBF24)
![Vercel](https://img.shields.io/badge/Vercel-172554?style=for-the-badge&logo=vercel&logoColor=ffffff)
![Git](https://img.shields.io/badge/Git-172554?style=for-the-badge&logo=git&logoColor=FB7185)
![Postman](https://img.shields.io/badge/Postman-172554?style=for-the-badge&logo=postman&logoColor=FB923C)

### Payments, Automation, Monitoring, and AI

![Razorpay](https://img.shields.io/badge/Razorpay-1C1917?style=for-the-badge&logo=razorpay&logoColor=3395FF)
![Cashfree](https://img.shields.io/badge/Cashfree-1C1917?style=for-the-badge)
![Zoho](https://img.shields.io/badge/Zoho%20Books%20%26%20Flow-1C1917?style=for-the-badge&logo=zoho&logoColor=F87171)
![n8n](https://img.shields.io/badge/n8n-1C1917?style=for-the-badge&logo=n8n&logoColor=EA4B71)
![Datadog](https://img.shields.io/badge/Datadog-1C1917?style=for-the-badge&logo=datadog&logoColor=A78BFA)
![Gemini](https://img.shields.io/badge/Gemini%20API-1C1917?style=for-the-badge&logo=googlegemini&logoColor=8AB4F8)
![Anthropic](https://img.shields.io/badge/Anthropic_API-1C1917?style=for-the-badge&logo=anthropic&logoColor=D4A574)
![MCP](https://img.shields.io/badge/MCP-1C1917?style=for-the-badge&logo=anthropic&logoColor=F8FAFC)

</div>

---

## 🔭 Currently

| Area | What I'm doing |
|------|----------------|
| 🏗️ Building | Production work at Bigintsolutions — learning platform, payments, invoicing, automation, and monitoring |
| 🧪 Side project | Vantage, a real-estate management product (React, Python, PostgreSQL, Docker) |
| 🏀 Beyond code | Captained the IIIT Ranchi basketball team; Vice Head of the Gaming Society (`3+` events, `100+` participants) |

<div align="center">

<sub>Reach me at <a href="mailto:nitish.kumar.cse2026@gmail.com">nitish.kumar.cse2026@gmail.com</a> or on <a href="https://www.linkedin.com/in/nitishkumar2026">LinkedIn</a>.</sub>

</div>
