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

## 🧠 Engineering Mindset

> Build fast. Scale clean. Break nothing.

- ⚡ Performance-first (Core Web Vitals, Lighthouse)
- 🧩 Scalable architecture & clean abstractions
- 🔄 Developer Experience (DX) focused
- 🤖 Exploring AI-native development systems

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

### 🧠 Dynamic UI Generator (MCP UI PoC)

A **full-stack system for generating dynamic UI components in real-time** using schema-driven architecture and sandboxed rendering.

---

### 🏗️ Architecture

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
        M[MCP Server]
        G[UI Generator]
        D[(Data)]
    end

    F -->|Config| A
    A --> M
    M --> G
    G -->|HTML| A
    A --> R
    R --> I

    I <-->|PostMessage| R
    R -->|API Calls| A
    A --> D
```

---

### 🧠 Key Design Decisions

- **Iframe isolation** → safe execution of dynamic UI  
- **Schema-driven rendering** → flexible UI generation  
- **PostMessage bridge** → real-time communication  
- **Backend-driven UI** → no redeploy for UI updates  

---

### 🧠 How It Works Internally

The system follows a schema-driven pipeline where user input is sent to a backend service that generates UI definitions. These definitions are rendered inside an isolated iframe, and a PostMessage bridge enables communication between the rendered UI and the main React app, enabling real-time interaction without redeployment.

---

### 🔗 Links

- GitHub: https://github.com/iamadi11/mcp-ui-poc

---

### 🎯 Mouse Follow (UI Experiment)

A lightweight project exploring **interactive cursor-based animations**

- GitHub: https://github.com/iamadi11/mouse-follow  
- Live: https://mouse-follow-nine.vercel.app/

---

## 🧩 Problems I Solved

### ⚡ Dynamic UI Generation
- Problem: UI changes require deployments  
- Solution: Schema-driven system  
- Impact: Faster iteration  

---

### 📉 SLA Breach Reduction
- Problem: High SLA violations (~70%)  
- Solution: Real-time processing system  
- Impact: Reduced to ~15%  

---

### ⚡ Frontend Performance
- Problem: Slow load times  
- Solution: Optimization techniques  
- Impact: Better UX  

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
- Code automation & intelligent tooling
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
