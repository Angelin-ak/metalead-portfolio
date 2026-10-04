# 🎯 MetaLeadIQ — Executive Project Portfolio & Pitch Presentation

This repository contains the standalone, single-page **Interactive Portfolio & Pitch Presentation Website** for **MetaLeadIQ: AI-Powered Lead Scoring & Omnichannel Prioritization System**.

- **Live Codebase Repository**: [https://github.com/athira-anil2327/MetaLeadIQ](https://github.com/athira-anil2327/MetaLeadIQ)
- **Project Lead**: Angelin Mathew (Architecture, ML Kinetics & Sales Operations)

---

## 🚀 How to Publish on GitHub Pages (10 Seconds)

1. Create a new repository on GitHub (e.g. `metaleadiq-portfolio` or `metaleadiq-pitch`).
2. Run these commands inside this folder:
   ```bash
   git init
   git add .
   git commit -m "feat: initial release of MetaLeadIQ interactive portfolio website"
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-NEW-REPO-NAME>.git
   git push -u origin main
   ```
3. In your new repository on GitHub:
   - Go to **Settings** $\rightarrow$ **Pages**.
   - Under **Build and deployment**:
     - **Source**: `Deploy from a branch`
     - **Branch**: `main`, Folder: `/ (root)`
   - Click **Save**.

Your portfolio website will immediately be live at:
👉 **`https://<YOUR-USERNAME>.github.io/<YOUR-NEW-REPO-NAME>/`**

---

## 📂 Repository Contents
- **`index.html`**: Complete, self-contained executive portfolio & pitch deck with:
  - **Dual Theme Engine**: Seamless instant switching between **Dark Executive Mode** and **Warm Light Studio Mode** (persisted in `localStorage`).
  - **Interactive Explainable UI Showcase**: 4 tabbed authentic screens with interactive pulsing radar hotspots (➊, ➋, ➌, ➍), dynamic architecture deep-dive panels, and panel defense talking points.
  - **Interactive 4-Stage Lead Lifecycle**: Step-by-step ingestion $\rightarrow$ Platt scoring $\rightarrow$ exponential decay $\rightarrow$ WhatsApp contact lock walkthrough.
  - **Live Mathematical Simulator**: Real-time scoring, Platt calibration, Wald 95% confidence intervals, and 1-click Contact Score Freezing.
  - **Interactive Viva Defense Categorizer**: Filter examiner questions by ML, Decay Kinetics, Security, or Architecture.
  - **MathJax LaTeX Equations**: Full mathematical formulations rendered at publication quality.
  - **Presenter Controls**: Navigate slides seamlessly using <kbd>→</kbd>, <kbd>Space</kbd>, <kbd>←</kbd>, and toggle progress with <kbd>P</kbd>.
- **Screenshots Included**:
  - `screenshot_dashboard.png`: Executive Dashboard & Leads Command Center.
  - `screenshot_queue.png`: Leads Priority Queue & Ingestion Hub (Webhooks, CSV, WhatsApp).
  - `screenshot_inbox.png`: Omnichannel Unified Inbox (WhatsApp Cloud API & Instagram DM).
  - `screenshot_insights.png`: Dynamic Lead Insights & Meta Performance Analytics.

---

## 🎯 Presenter Keyboard Controls
- **Next Section**: Press <kbd>→</kbd> or <kbd>Space</kbd> or <kbd>PageDown</kbd>
- **Previous Section**: Press <kbd>←</kbd> or <kbd>PageUp</kbd>
- **Toggle Presenter Counter Bar**: Press <kbd>P</kbd>
- **Close Modal / Lightbox**: Press <kbd>Esc</kbd>
- **⚡ Launch Live App Modal**: Dual launcher supporting Localhost (:5173), Public Cloud / Ngrok demo, live on-screen mobile QR code scanner, and custom URL persistence.
