<img src="./assets/hero-tree.svg" alt="Nitish Kumar Kushwaha, full-stack engineer, under a tree in a night sky. Career trace: IIIT Ranchi B.Tech 2022 to 2026, Reelife and NexisparkX internships, and Software Developer 1 at Bigintsolutions since May 2026, covering payments, a learning platform, automations and a video editor." width="100%" />

<p align="center">
  <a href="https://www.linkedin.com/in/nitishkumar2026"><b>LinkedIn</b></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://leetcode.com/u/nitishkumarkushwaha/"><b>LeetCode</b></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="./Nitish_Kushwaha_Resume.pdf"><b>Resume</b></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="mailto:nitish.kumar.cse2026@gmail.com"><b>Email</b></a>
</p>

<br />

I build full-stack products and take them all the way to production: payment flows that handle real money, automations that remove manual work, and AI features that hold up when the model gets it wrong. Outside work I've solved `500+` LeetCode problems (rating `1799`, top 10%, `93-day` daily streak), and I'm Anthropic API certified in tool use, RAG, MCP, prompt caching and agent workflows.

## Experience

**Bigintsolutions**, Software Developer 1 &nbsp;<sub>May 2026 to now, remote</sub>

- Rebuilt [learn.approachable.dev](https://learn.approachable.dev) from a bare landing page (dashboard, video player, progress tracking) and built [approachable.dev](https://approachable.dev), the company marketing site, which brought its first corporate lead within 3 days of launch.
- Built the payment and billing flow from scratch: Razorpay across iOS and Android (every major method except Apple Pay) with IP-based country pricing, Cashfree as a backup gateway, and server-side price resolution so checkout amounts can't be changed from the client. It processed `Rs.2L+` across `34` payments in month one, with zero errors.
- Automated a Razorpay to Zoho Books invoice workflow so every successful payment raises a customer invoice, and built Zoho Flow and n8n automations for bulk and targeted emails and operations.
- Shipped `3` frontend features for the Haziram production app (`4,000+` workers, `200+` companies) and `1` admin-app feature.
- Owned Datadog monitoring and debugging across services; two of those investigations are written up below.
- Built a chat-based video editor that cut internal editing time from `6–8 hours` to `2–3 hours`.
- Delivered `600+` commits across `3` projects built from scratch and `1` existing project, in a 6-person team.

**NexisparkX Technologies**, MERN intern &nbsp;<sub>Apr to May 2026</sub><br />
Migrated a production database from Supabase to MongoDB with zero data loss, and built an admin dashboard for NX Solution's Smart Ecosystem platform.

**Reelife**, Full-stack intern &nbsp;<sub>Jun to Aug 2025</sub><br />
Delivered `10+` production React components and Node.js/Express API routes for an internal e-commerce platform.

## Featured projects

<a href="https://github.com/nitishkumarkushwaha21/Algonote"><img src="./assets/card-algonote.svg" alt="AlgoNote AI: DSA practice, notes, imports and revision in one IDE-style workspace. 3 microservices, 33 REST endpoints, 6 containers on AWS EC2." width="100%" /></a>

Interview prep usually lives across browser tabs, notes apps and spreadsheets. AlgoNote's backend is 3 microservices behind an API gateway on a 6-container Docker Compose stack on AWS EC2. The workspace has a Monaco editor, one-click LeetCode import, and a pipeline that turns a YouTube playlist into a revision sheet.

**[Code](https://github.com/nitishkumarkushwaha21/Algonote)** &nbsp;&nbsp; **[Live demo](http://algonote.duckdns.org/)**

<details>
  <summary><b>AlgoNote screenshots (6)</b></summary>
  <br />
  <p align="center">
    <img src="./assets/shots/algonote-1.png" alt="AlgoNote screenshot 1" width="49%" />
    <img src="./assets/shots/algonote-2.png" alt="AlgoNote screenshot 2" width="49%" />
  </p>
  <p align="center">
    <img src="./assets/shots/algonote-3.png" alt="AlgoNote screenshot 3" width="49%" />
    <img src="./assets/shots/algonote-4.png" alt="AlgoNote screenshot 4" width="49%" />
  </p>
  <p align="center">
    <img src="./assets/shots/algonote-5.png" alt="AlgoNote screenshot 5" width="49%" />
    <img src="./assets/shots/algonote-6.png" alt="AlgoNote screenshot 6" width="49%" />
  </p>
</details>

<br />

<a href="https://github.com/nitishkumarkushwaha21/n8n-job-hunter"><img src="./assets/card-jobhunter.svg" alt="n8n Job Hunter: an hourly workflow over 7 job sources with 23 nodes. Gemini screens, code decides." width="100%" /></a>

It pulls listings from YC, RemoteOK, We Work Remotely, Himalayas and company pages on Greenhouse, Lever and Ashby. A regex pass and a list of already-seen jobs remove misses before any AI call. Gemini screens the rest in batches of 12, but code makes the final decision, so a wrong model answer can't push a bad job through. Failed AI calls retry on the next run.

**[Code](https://github.com/nitishkumarkushwaha21/n8n-job-hunter)**

<br />

<a href="https://github.com/nitishkumarkushwaha21/vedaai-ai-question-maker"><img src="./assets/card-vedaai.svg" alt="VedaAI: LLM-generated question papers, generated on a BullMQ queue with live progress over Socket.IO, and PDF export." width="100%" /></a>

An LLM pipeline (OpenRouter, GPT-4o-mini) writes a structured, syllabus-aligned paper from the teacher's settings. Generation runs on a BullMQ and Redis job queue, and a background worker streams each job's progress (queued, processing, completed or failed) to the browser over Socket.IO.

**[Code](https://github.com/nitishkumarkushwaha21/vedaai-ai-question-maker)** &nbsp;&nbsp; **[Live demo](https://vedaai-ai-question-maker.vercel.app/)**

<details>
  <summary><b>VedaAI screenshots (3)</b></summary>
  <br />
  <p align="center">
    <img src="./assets/shots/veda-1.png" alt="VedaAI screenshot 1" width="49%" />
    <img src="./assets/shots/veda-2.png" alt="VedaAI screenshot 2" width="49%" />
  </p>
  <p align="center">
    <img src="./assets/shots/veda-3.png" alt="VedaAI screenshot 3" width="49%" />
  </p>
</details>

## Video walkthrough

<a href="https://drive.google.com/file/d/1mzQ_YsShtPqzAhd4a7Zeyl2s5pEsn8BQ/view?usp=sharing">
  <img src="./assets/explainer-poster.jpg" alt="Play the 1 minute 40 second explainer video" width="100%" />
</a>
<p align="center"><a href="https://drive.google.com/file/d/1mzQ_YsShtPqzAhd4a7Zeyl2s5pEsn8BQ/view?usp=sharing">Watch the 1:40 walkthrough of my work</a></p>

<!-- To play the video inline on GitHub: edit this file on github.com, drag the mp4 into the editor,
     and replace the two blocks above with the https://github.com/user-attachments/... link GitHub generates. -->

## Also built

<table>
  <tr>
    <td width="45%" valign="middle">
      <a href="https://freelancer-xi-nine.vercel.app/"><img src="./assets/shots/builtbywho-1.png" alt="BuiltByWho studio site in a browser window" width="100%" /></a>
    </td>
    <td width="55%" valign="top">
      <h3>BuiltByWho</h3>
      <p>A studio site for scoping and shipping client websites, with case studies (PULSE, Drishya Trails, Root &amp; Rise), services and a lead form. A React frontend talks to an Express and MongoDB API for projects, reviews and inquiries.</p>
      <p><a href="https://freelancer-xi-nine.vercel.app/"><b>Live site</b></a></p>
    </td>
  </tr>
</table>

<details>
  <summary><b>BuiltByWho screenshots (4)</b></summary>
  <br />
  <p align="center">
    <img src="./assets/shots/builtbywho-2.png" alt="BuiltByWho screenshot 2" width="49%" />
    <img src="./assets/shots/builtbywho-3.png" alt="BuiltByWho screenshot 3" width="49%" />
  </p>
  <p align="center">
    <img src="./assets/shots/builtbywho-4.png" alt="BuiltByWho screenshot 4" width="49%" />
    <img src="./assets/shots/builtbywho-5.png" alt="BuiltByWho screenshot 5" width="49%" />
  </p>
</details>

- **Vantage** (in progress): a real-estate management product in React, Python, PostgreSQL and Docker.
- **Notes extension**: notes with version history that cut repetitive form-filling from about 10 minutes to 1.
- **Telegram job finder**: pulls job posts from Telegram channels and turned a 3–4 hour manual search into about 30 minutes.

## Debugging notes

**A payment gateway that failed while our code was correct.** A Cashfree integration had to ship in a day, but test payments kept failing. I instrumented the API calls, then built a minimal HTML page that called Cashfree directly across API versions. That isolated the failure to the gateway itself. Cashfree confirmed it and fixed it the next day, with no change to our code.

**An AI onboarding chat that finished but never produced a profile.** Users completed the chat, yet their profiles were never generated. Lining up Datadog session replays, backend logs and MongoDB records traced it to concurrent session creation, inconsistent session IDs, and requests running past Heroku's 30-second limit. The fixes covered session consistency, concurrency, recovering saved AI data, and long-running requests.

What both taught me: shrink the system to a case you can reproduce, and find the failing boundary before changing any code.

## Stack

<img src="./assets/stack-layers.svg" alt="Tech stack by layer. Client: React, Next.js, TypeScript, Tailwind CSS, shadcn/ui, Zustand, Monaco. Services: Node.js, Express, Socket.IO, BullMQ, Zod, Clerk. Data: PostgreSQL, MongoDB, MySQL, Redis. Payments and ops: Razorpay, Cashfree, Zoho Books, Zoho Flow, Datadog. AI and automation: Anthropic API, MCP, RAG, Gemini, OpenRouter, n8n. Infrastructure: Docker, AWS EC2, Nginx, Vercel, Heroku, Git." width="100%" />

<br />

Away from the keyboard I captained IIIT Ranchi's basketball team in inter-IIIT tournaments and was vice head of the gaming society. The quickest way to reach me is [email](mailto:nitish.kumar.cse2026@gmail.com) or [LinkedIn](https://www.linkedin.com/in/nitishkumar2026).
