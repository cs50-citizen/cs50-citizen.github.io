# Jack Deng (邓宇航) - Personal Portfolio Website

> Modern, high-performance personal portfolio website for Jack Deng — Full-Stack & AI Software Engineer (Ex-ByteDance, UQ Master of Computer Science).

---

## 🌐 Live Online

- **Current Live URL (Vercel)**: [https://rapid-neon-vwain8f.tmp.now](https://rapid-neon-vwain8f.tmp.now)
- **Claim & Bind to Your Vercel Account**: [Claim Deployment Link](https://vercel.com/claim-deployment?code=252e8101-7aae-428b-99ae-ee2322322639) *(Click to permanently attach to your Vercel account and set up a custom domain e.g. `jackdeng.dev`)*

---

## ✨ Key Features

1. **Bilingual Support (中英双语一键切换)**:
   - Full instant language toggle between English and Chinese (`EN` / `中文`) with zero page reloads.
   - Comprehensive translations across all sections (Summary, ByteDance experience, UQ coursework, AI projects, skills matrix).

2. **Ultra-Modern Tech Aesthetic**:
   - Dark mode default with high contrast, glassmorphism cards (`backdrop-blur-xl`), and animated gradient ambient glows.
   - Light / Dark theme toggle with state preservation.
   - Dynamic typing role animation ("Full-Stack Software Engineer", "AI & Agent Architect", "Ex-ByteDance Developer", "UQ CS Master").

3. **Featured Engineering Projects**:
   - **Enterprise RAG Knowledge Base & Intelligent Support Agent**: FastAPI, LangChain, pgvector, ChromaDB, Celery, React, Docker. Sub-second hybrid search and WebSocket/SSE streaming.
   - **LLM-Based Constraint-Aware Intelligent Trip Planning**: Master's Capstone with LangGraph and deterministic constraint satisfaction (Z3/OR-Tools), reducing violations from 34% to 0%.
   - **AI Job Application & Resume Tailor Engine**: Multi-tier automation agent generating ATS-optimized bilingual resumes and cover letters.
   - Interactive project details modal with architecture highlights and tech pills.
   - Dynamic category filter (`All`, `AI & Agents`, `Full-Stack`).

4. **Interactive Timeline**:
   - **ByteDance (字节跳动)** (2022.07 – 2024.06): High-concurrency microservices (100M+ DAU, 99.99% SLA), React/Next.js SSR optimization (-38% load time), Redis/PostgreSQL latency optimization (-45%).
   - **The University of Queensland (昆士兰大学)** (2024.07 – 2026.07): Master of Computer Science (Management), GPA 5.5/7.0.

5. **Direct Actions & Contacts**:
   - One-click copy email button with sleek toast notification (`yuhang.deng.ai@gmail.com`).
   - One-click resume download (`Jack_Deng_Resume.pdf`).
   - Direct LinkedIn, GitHub, and phone contact links.

---

## 🚀 Local Development

To run locally on your machine:

```bash
# Option 1: Python built-in server
python -m http.server 8080

# Option 2: Node.js serve
npx serve .
```

Open [http://localhost:8080](http://localhost:8080) in your browser.

---

## 📦 Permanent Deployment Options

### 1. Vercel (Recommended)
You can permanently link this website to your Vercel account by either:
1. Clicking your [Claim Link](https://vercel.com/claim-deployment?code=252e8101-7aae-428b-99ae-ee2322322639)
2. Or running in this folder:
   ```bash
   npx vercel login
   npx vercel --prod
   ```

### 2. GitHub Pages (Free Forever)
1. Initialize a git repository and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Jack Deng Personal Website"
   git branch -M main
   # Create a repo on github named cs50-citizen.github.io
   git remote add origin https://github.com/cs50-citizen/cs50-citizen.github.io.git
   git push -u origin main
   ```
2. In GitHub repository settings -> **Pages** -> Select `main` branch `/ (root)` -> Save. Your website will be permanently live at `https://cs50-citizen.github.io`!

