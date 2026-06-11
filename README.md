# 👋 Hi, I'm Aditya Raj
### 💻 Software Development Engineer | Frontend Specialist | React Ecosystem Expert
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=iamadi11&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

## 🚀 About Me
I'm a **Software Development Engineer with ~4.5 years of experience** building scalable, high-performance systems.
- ⚡ Currently at **Cashfree Payments** — working on **risk & fraud systems**
- 📊 Systems handling **millions of transactions/month**
- 🧠 Reduced SLA breaches from **70% → 15%**
- 🏗️ Built **real-time rule engine for fraud detection**
- 🌍 Experience across **Fintech, Healthcare, Travel**

---

## 🛠️ Tech Stack

### **Frontend**
![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC?style=for-the-badge&logo=typescript&logoColor=white)

### **Backend**
![Node.js](https://img.shields.io/badge/Node.js-%23339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-%23404d59?style=for-the-badge&logo=express&logoColor=white)

---

## 🚀 Featured Projects

### ⚙️ Eidos — Abstraction Layer for Service Workers
> *Describe intent. The runtime figures out how.*

An **npm-published OSS library** that replaces Service Worker boilerplate with a declarative 2-line API. No cache strategy config, no retry logic, no SW file to write.

```ts
// before: ~40 lines of Workbox config
// after:
const products = resource('/api/products', { offline: true })
const createOrder = action(orderApi.create, { reliability: 'neverLose' })
```

- **5 kB gzip** — zero runtime dependencies
- `neverLose` actions persist to IndexedDB and replay automatically on reconnect
- Full React hooks API (`useEidosStatus`, `useEidosQueue`, `useEidosQueueStats`)

**Links:** [GitHub](https://github.com/iamadi11/eidos) · [Playground](https://playground-iamadi11s-projects.vercel.app) · [npm](https://www.npmjs.com/package/@sweidos/eidos)

---

### 🧠 Dynamic UI Generator (MCP UI PoC)
A **full-stack system that turns any API endpoint into a UI** — fetch data, an LLM picks components from a registered design system, render via MCP UI in a sandboxed iframe.

```mermaid
flowchart TB
    U[User Interaction] --> F
    subgraph Frontend_React_Vite
        F[UI Builder]
        R[Dynamic Renderer]
        I[Iframe Renderer]
    end
    subgraph Backend_Node_Express
        A[API Layer]
        DS[Data Source - SSRF guard]
        P[ui-compose-kit Planner]
        L[LLM Adapters - Claude/GPT/Gemini]
        T[Design System - glass/shadcn/material]
        M[MCP UI Resource]
    end
    E[(External API)]
    F -->|endpoint + instructions| A
    A --> DS
    DS <--> E
    DS --> P
    P <--> L
    P --> T
    T --> M
    M -->|HTML resource| A
    A --> R
    R --> I
    I <-->|PostMessage| R
```

- **Iframe isolation** → safe execution of dynamic UI
- **Multi-LLM planner** → Claude, GPT, Gemini adapters (`ui-compose-kit`)
- **Pluggable design systems** → glass, shadcn, Material themes
- **PostMessage bridge** → real-time communication
- **Backend-driven UI** → no redeploy for UI updates

**Links:** [GitHub](https://github.com/iamadi11/mcp-ui-poc) · [Live](https://mcp-ui-poc.vercel.app/)

---

### 🎯 Mouse Follow (UI Experiment)
A lightweight project exploring **interactive cursor-based animations**

**Links:** [GitHub](https://github.com/iamadi11/mouse-follow) · [Live](https://mouse-follow-nine.vercel.app/)

---

## 📈 GitHub Stats

<p align="center">
  <img height="170em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=iamadi11&show_icons=true&theme=tokyonight&hide_border=true"/>
  <img height="170em" src="https://streak-stats.demolab.com?user=iamadi11&theme=tokyonight&hide_border=true"/>
  <img height="170em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=iamadi11&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## 🤖 Currently Exploring
- AI-powered dev systems (MCP, Cursor)
- OSS library development & npm publishing
- Frontend architecture at scale

---

## 🌐 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/adityaraj11/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Aditya-blue?logo=linkedin&logoColor=white&style=for-the-badge"/>
  </a>
  <a href="https://github.com/iamadi11" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-iamadi11-black?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://connectaditya.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=vercel"/>
  </a>
</p>

---

## ⚡ Fun Fact
I like building systems that **scale silently but impact massively** 🚀
