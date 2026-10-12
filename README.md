<div align="center">

  <!-- Hero Banner -->
  <a href="https://outletking.co.kr" target="_blank">
    <img src="./assets/hero.svg" alt="Hey! I'm Allan" width="920" />
  </a>

  <br/><br/>

  <!-- Typing Subtitle -->
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Full-Stack+%26+AI+Engineer;NestJS+%E2%80%A2+GraphQL+%E2%80%A2+MongoDB+%E2%80%A2+Redis+%E2%80%A2+BullMQ;Next.js+%E2%80%A2+React+%E2%80%A2+TypeScript;Gemini+AI+%E2%80%A2+SSE+Streaming+%E2%80%A2+Job+Queues;From+data+model+to+production+deploy"
    alt="Typing SVG"
  />

  <br/>

  <!-- At a glance -->
  <p align="center">
    <img src="https://img.shields.io/badge/Seoul,_South_Korea-0EA5E9?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Seoul, South Korea" />
    <img src="https://img.shields.io/badge/Full--Stack_%26_AI_Engineer-7C3AED?style=for-the-badge&logo=stackblitz&logoColor=white" alt="Full-Stack &amp; AI Engineer" />
    <img src="https://img.shields.io/badge/5+_Years_in_Production-16A34A?style=for-the-badge&logo=rocket&logoColor=white" alt="5+ years in production" />
    <img src="https://img.shields.io/badge/EN_·_KR_·_RU_·_UZ-F59E0B?style=for-the-badge&logo=googletranslate&logoColor=white" alt="Languages: English, Korean, Russian, Uzbek" />
  </p>

  <!-- Core stack -->
  <p align="center">
    <img src="https://skillicons.dev/icons?i=ts,nestjs,graphql,nextjs,react,mongodb,redis,docker,nginx&theme=dark&perline=10" alt="Core stack" />
  </p>

  <!-- Badges Row -->
  <p align="center">
    <a href="https://outletking.co.kr" target="_blank">
      <img src="https://img.shields.io/badge/Outlet%20King-outletking.co.kr-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Outlet King" />
    </a>
    <a href="https://www.cafena-coffee.com" target="_blank">
      <img src="https://img.shields.io/badge/Cafena-cafena--coffee.com-B45309?style=for-the-badge&logo=buymeacoffee&logoColor=white" alt="Cafena" />
    </a>
    <a href="mailto:solijonov.azamat9507@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

</div>

---

### 👨‍💻 Summary

```yaml
engineer:
  name: "Azamat Solijonov"
  title: "Full-Stack & AI Engineer"
  experience: "5+ years building and running production web applications"
  location: "Seoul, South Korea 🇰🇷"
  backend:
    - "Node.js, TypeScript, NestJS (monorepo), Express, GraphQL (Apollo, code-first), REST"
    - "MongoDB, Mongoose, Redis, BullMQ, WebSocket, Server-Sent Events"
  integrations:
    - "Kakao Login and Google sign-in (OAuth 2.0 / OpenID Connect, server-side code exchange)"
    - "Kakao Maps (store locator with geocoded addresses)"
  ai:
    - "Google Gemini API (text + image models)"
    - "AI stylist with 3-model failover on error or an 8 s timeout"
    - "AI fitting room: asynchronous image jobs on BullMQ + Redis"
    - "Live job progress over Server-Sent Events, per-visitor rate limiting"
  frontend:
    - "React, Next.js, Apollo Client, Redux, Tailwind CSS, MUI, SCSS, i18next (EN / KR / RU)"
  devops:
    - "Linux, Nginx, PM2, Docker, DigitalOcean, scripted deploys with rollback"
  current_role: "Full-Stack Engineer (main developer) @ Outlet King"
  languages: "Uzbek, Russian, Korean (TOPIK 4), English"
```

- 🧩 **End-to-end ownership:** I take a product from data model to production — API, frontend, infrastructure and the deploy scripts that ship it.
- ⚡ **GraphQL backends on NestJS:** Code-first Apollo APIs with JWT guards (required, role-based, optional), strict input validation and MongoDB aggregation pipelines.
- 🤖 **LLM features in production:** A Gemini AI stylist with 3-model failover on error or an 8 s timeout, and an AI fitting room running as BullMQ jobs on Redis with live SSE progress and per-visitor rate limiting.
- 🔐 **Social login and maps:** Kakao Login and Google sign-in over OAuth 2.0, with the one-time code exchanged on the server so the client secret never reaches the browser and redirect URIs checked against an allow-list; a Kakao Maps store locator where the map and the shop list follow each other.
- 🎨 **Frontend systems:** Next.js apps with their own MUI + SCSS design system, dark / light themes, three languages and real-time WebSocket notifications.
- ☁️ **Self-managed infrastructure:** Nginx reverse proxy, PM2, UFW, Redis, nightly batch jobs and scripted deploys with automatic rollback on DigitalOcean.

---

### 💼 Experience

| Period | Company | Role | Work |
|---|---|---|---|
| 2024.07 – 2026.01 | **Neuracode** · remote, international team | Full-Stack Engineer | NestJS / Express services with REST and GraphQL, JWT / OAuth 2.0 / RBAC, WebSocket, Redis caching, React / Next.js frontends |
| 2023.07 – 2024.06 | **IdeaSoft** · Uzbekistan, remote | Full-Stack Developer | E-commerce and business applications with React, TypeScript and Redux Toolkit on Node.js / Express / MongoDB |
| 2022.06 – 2023.06 | **IT Brick** · Uzbekistan | Full-Stack Developer | MERN-stack web applications: responsive React UIs, REST APIs with JWT auth, MongoDB data models |
| 2021.02 – 2022.05 | **FortoPro** · Uzbekistan | Frontend Developer | Frontend of the fpg.uz IT equipment store: catalog, brand pages, product listings and responsive layouts |

---

### 🚀 Featured Projects

<table>
  <thead>
    <tr>
      <th width="30%">Project</th>
      <th width="50%">Architecture & Capabilities</th>
      <th width="20%">Status / Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <b>👑 Outlet King</b><br/>
        <sub>Fashion Outlet Marketplace</sub>
      </td>
      <td>
        Production marketplace running in English, Korean and Russian. ~28k lines of TypeScript across a <b>NestJS monorepo</b> (API + batch worker) and a <b>Next.js</b> app: 19 modules, 57 GraphQL queries and mutations, 12 MongoDB models. Gemini AI stylist and an asynchronous AI fitting room on BullMQ + Redis with SSE progress. Kakao and Google social login, Kakao Maps store locator. 25 pages, 78 components.
      </td>
      <td>
        <a href="https://outletking.co.kr" target="_blank"><code>outletking.co.kr</code> ↗</a><br/>
        <code>Production</code><br/>
        Main developer
      </td>
    </tr>
    <tr>
      <td>
        <b>☕ Cafena</b><br/>
        <sub>Coffee Marketplace</sub>
      </td>
      <td>
        Full-stack marketplace on Node.js / Express and React: search, reviews, orders, franchise directory and real-time updates over Socket.IO. 9 Mongoose schemas, React + Redux + MUI client, server-rendered admin panel for shops and advertising. Gemini AI ordering assistant that assembles an order from the live menu within the visitor's budget, with prices and totals computed in code. Deployed with Docker, Nginx and PM2.
      </td>
      <td>
        <a href="https://www.cafena-coffee.com" target="_blank"><code>cafena-coffee.com</code> ↗</a><br/>
        <code>Production</code><br/>
        <code>Private repository</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>🛒 E-commerce Storefronts</b><br/>
        <sub>Frontend · 2021 – 2024</sub>
      </td>
      <td>
        Production e-commerce storefronts. Frontend architecture with React, TypeScript and Redux on REST backends: catalogs, filtering, product pages, multi-currency pricing and responsive layouts.
      </td>
      <td>
        <a href="https://fpg.uz" target="_blank"><code>fpg.uz</code> ↗</a><br/>
        <a href="https://tovar.uz" target="_blank"><code>tovar.uz</code> ↗</a><br/>
        <a href="https://olcha.uz" target="_blank"><code>olcha.uz</code> ↗</a><br/>
        <a href="https://us-appliance.com" target="_blank"><code>us-appliance.com</code> ↗</a>
      </td>
    </tr>
    <tr>
      <td>
        <b>🏢 Nestar</b><br/>
        <sub>Real-Estate Marketplace</sub>
      </td>
      <td>
        Real-estate marketplace with a NestJS monorepo backend and a Next.js 14 frontend using Apollo Client, MUI and i18next.
      </td>
      <td>
        <a href="https://github.com/Azamat9507/nestar-next"><code>nestar-next</code> ↗</a>
      </td>
    </tr>
    <tr>
      <td>
        <b>🍽️ Burak</b><br/>
        <sub>Restaurant Ordering Service</sub>
      </td>
      <td>
        REST backend on Node.js, Express and TypeScript with MongoDB: members, product catalogue, orders, JWT auth and a server-rendered EJS admin panel for the restaurant.
      </td>
      <td>
        <a href="https://github.com/Azamat9507/burak"><code>burak</code> ↗</a>
      </td>
    </tr>
  </tbody>
</table>

---

### 🛠️ Technical Stack

<br/>

<table>
  <tr>
    <td width="22%" align="center"><b>🤖 AI & Queues</b></td>
    <td>
      <img src="https://img.shields.io/badge/Google_Gemini-0f172a?style=for-the-badge&logo=googlegemini&logoColor=8e75c2" alt="Gemini" />
      <img src="https://img.shields.io/badge/BullMQ_Queues-0f172a?style=for-the-badge&logo=redis&logoColor=f87171" alt="BullMQ" />
      <img src="https://img.shields.io/badge/SSE_Streaming-0f172a?style=for-the-badge&logo=nestjs&logoColor=e0234e" alt="SSE" />
      <img src="https://img.shields.io/badge/Socket.IO-0f172a?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.IO" />
    </td>
  </tr>
  <tr>
    <td width="22%" align="center"><b>🔐 Auth & Maps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Kakao_Login-0f172a?style=for-the-badge&logo=kakaotalk&logoColor=ffcd00" alt="Kakao Login" />
      <img src="https://img.shields.io/badge/Google_Sign--In-0f172a?style=for-the-badge&logo=google&logoColor=4285f4" alt="Google Sign-In" />
      <img src="https://img.shields.io/badge/Kakao_Maps-0f172a?style=for-the-badge&logo=kakao&logoColor=ffcd00" alt="Kakao Maps" />
      <img src="https://img.shields.io/badge/JWT-0f172a?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
    </td>
  </tr>
  <tr>
    <td width="22%" align="center"><b>💻 Languages</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=ts,js,html,css,sass&theme=dark" alt="Languages" />
    </td>
  </tr>
  <tr>
    <td width="22%" align="center"><b>⚡ Backend & Data</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=nestjs,nodejs,express,graphql,apollo,mongodb,redis&theme=dark" alt="Backend" />
    </td>
  </tr>
  <tr>
    <td width="22%" align="center"><b>🎨 Frontend</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=nextjs,react,redux,tailwind,materialui,bootstrap&theme=dark" alt="Frontend" />
    </td>
  </tr>
  <tr>
    <td width="22%" align="center"><b>☁️ DevOps</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=linux,nginx,docker,git,github&theme=dark" alt="DevOps" />
      <img src="https://img.shields.io/badge/PM2-0f172a?style=for-the-badge&logo=pm2&logoColor=2b037a" alt="PM2" />
      <img src="https://img.shields.io/badge/DigitalOcean-0f172a?style=for-the-badge&logo=digitalocean&logoColor=0080ff" alt="DigitalOcean" />
    </td>
  </tr>
  <tr>
    <td width="22%" align="center"><b>🧪 Tools</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=postman,vscode,figma&theme=dark" alt="Tools" />
    </td>
  </tr>
</table>

---

### 📬 Connect

<div align="center">

  <a href="https://outletking.co.kr" target="_blank">
    <img src="https://img.shields.io/badge/OUTLET%20KING-LIVE%20SITE-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Outlet King" />
  </a>
  &nbsp;
  <a href="https://www.cafena-coffee.com" target="_blank">
    <img src="https://img.shields.io/badge/CAFENA-LIVE%20SITE-B45309?style=for-the-badge&logo=buymeacoffee&logoColor=white" alt="Cafena" />
  </a>
  &nbsp;
  <a href="mailto:solijonov.azamat9507@gmail.com">
    <img src="https://img.shields.io/badge/GMAIL-EMAIL%20ME-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,100:2563EB&height=110&section=footer" alt="" width="100%" />
