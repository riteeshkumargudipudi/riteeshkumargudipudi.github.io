# 🚀 Gudipudi Riteesh Kumar — Developer Portfolio

A modern, responsive, high-performance developer portfolio website designed for **Gudipudi Riteesh Kumar**, final-year B.Tech Computer Science and Engineering undergraduate aspiring to be a **Software Engineer**.

---

## 🌟 Features Included

- **Modern Theming (Light / Dark Mode):**
  - Uses CSS `color-scheme` and standard `prefers-color-scheme` media queries.
  - Interactive theme toggle with persistent user choice in `localStorage`.
  - Anti-FOUC inline script to ensure smooth loading without theme flickers.
- **Hero & Identity:**
  - Dynamic status indicator (`Available for Software Engineering Roles`).
  - Interactive terminal/code showcase card highlighting core technical stack.
  - Direct links to GitHub, LinkedIn, Email, Phone, and Resume.
- **Skills Matrix:**
  - Languages (Python, Java, C, JavaScript, SQL).
  - AI & Multimodal Engineering (LLaMA, ConceptNet, Scikit-Learn, PyTorch).
  - Big Data & Databases (Apache Spark Advanced, MongoDB, Azure, OCI).
  - Tools & Workflows (Git, Maven, VS Code, Sockets, Kivy).
- **Featured Projects Showcase:**
  - Interactive category filtering (**All**, **AI & Machine Learning**, **Systems & Networking**).
  - Interactive Project Detail Modals for in-depth architectural breakdowns:
    1. **Visual Question Answering using LLaMA & ConceptNet** (Multimodal AI)
    2. **ChatterBox** (Real-Time Socket Application with Kivy GUI)
    3. **Heart Stroke Prediction using Hybrid ML Models** (with direct GitHub repo link)
    4. **DeepLure Saree & Apparel Recognition** (Computer Vision)
- **Verified Certifications Section:**
  - Oracle Cloud Infrastructure 2025 Generative AI Professional (Sept 09, 2025)
  - Microsoft Certified: Azure Data Scientist Associate
  - Apache Spark - Advanced (Feb 27, 2026)
  - MongoDB Certified (Dec 26, 2025)
- **Education Timeline:**
  - Amrita Vishwa Vidyapeetham, Amaravati (B.Tech CSE, 2023–2027)
  - SR Junior College (952/1000)
  - Dr. KKR’s Gowtham School (600/600 Perfect Score)
- **Contact & Interaction:**
  - One-click "Copy Email" with instant clipboard toast confirmation.
  - Interactive message form with instant mailto composition.
  - Built-in printable / downloadable Resume Viewer Modal.

---

## 💻 How to Run Locally

You can run this portfolio locally without any external dependencies!

### Option 1: Open Directly in Browser
Simply double-click `portfolio/index.html` or drag and drop it into Google Chrome, Microsoft Edge, Brave, or Firefox.

### Option 2: Run with Python Local Server
Open PowerShell in the `portfolio` directory and run:
```powershell
python -m http.server 8000
```
Then visit: `http://localhost:8000`

### Option 3: Run with Node.js
```powershell
npx serve .
```

---

## 🌐 Free 1-Click Hosting Guide

### Deploy to GitHub Pages (Recommended)
1. In your GitHub account ([github.com/riteeshkumargudipudi](https://github.com/riteeshkumargudipudi)), create a new public repository named:
   `riteeshkumargudipudi.github.io` (or `portfolio`)
2. Push all files inside this `portfolio/` folder into that repository.
3. In the repository settings, go to **Settings > Pages**.
4. Under **Build and deployment > Branch**, select `main` and `/ (root)`, then click **Save**.
5. Your live portfolio will be online at:
   `https://riteeshkumargudipudi.github.io/`

### Deploy to Vercel / Netlify
1. Connect your GitHub repository to [Vercel.com](https://vercel.com) or [Netlify.com](https://netlify.com).
2. Set Build Command to blank (static site) and publish directory to `./`.
3. Click **Deploy** — your site will be live on a fast global CDN with custom domain support.

---

## 📄 File Structure

```
portfolio/
├── index.html               # Main semantic HTML5 markup
├── style.css                # Modern responsive styling & light/dark tokens
├── script.js                # Dynamic interactions, modals, filtering & toast
├── README.md                # Project documentation and deployment guide
└── GITHUB_PROFILE_README.md # Ready-to-use GitHub Profile README
```
