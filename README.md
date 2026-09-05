# Yash Raj - Personal Portfolio Website

<div align="center">

  <!-- Live Demo & Stats Badges -->
  <a href="https://yash-raj-portfolio-website-neon.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-yash--raj--portfolio-00dfa2?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" />
  </a>
  <a href="https://github.com/Yashraj413/Yash-Raj-Portfolio-Website">
    <img src="https://img.shields.io/github/stars/Yashraj413/Yash-Raj-Portfolio-Website?style=for-the-badge&color=ffd700&logo=github" alt="GitHub Stars" />
  </a>
  <a href="https://github.com/Yashraj413/Yash-Raj-Portfolio-Website/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-ISC-blue?style=for-the-badge" alt="License" />
  </a>

  <br/><br/>

  <!-- Tech Stack Badges -->
  <img src="https://img.shields.io/badge/Three.js-r128-black?style=flat-square&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/GSAP-3.12.2-88CE02?style=flat-square&logo=greensock&logoColor=white" alt="GSAP" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Node.js-Serverless-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Resend-Email%20API-000000?style=flat-square&logo=resend&logoColor=white" alt="Resend" />
  <img src="https://img.shields.io/badge/Vercel-Hosted-black?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />

  <br/><br/>

  <p align="center">
    <strong>A modern, interactive developer portfolio featuring a WebGL 3D starfield canvas, GSAP scroll-triggered choreography, glassmorphic UI design, and a secure serverless contact backend.</strong>
  </p>

  <p align="center">
    <a href="https://yash-raj-portfolio-website-neon.vercel.app/"><strong>Explore Live Demo »</strong></a>
    &nbsp;•&nbsp;
    <a href="https://github.com/Yashraj413/Yash-Raj-Portfolio-Website/issues">Report Bug</a>
    &nbsp;•&nbsp;
    <a href="https://github.com/Yashraj413/Yash-Raj-Portfolio-Website/issues">Request Feature</a>
  </p>

</div>

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Portfolio Sections](#-portfolio-sections)
- [Tech Stack & Architecture](#-tech-stack--architecture)
- [Project Directory Structure](#-project-directory-structure)
- [Local Development Setup](#-local-development-setup)
- [Environment Variables](#-environment-variables)
- [Deployment Guide](#-deployment-guide)
- [Contact & Connect](#-contact--connect)
- [License](#-license)

---

## 🌟 Overview

This repository contains the source code for the personal portfolio of **Yash Raj** - Software Developer specializing in Full-Stack Engineering, AI/ML, and Data Analytics.

Designed with a cosmic dark-mode theme, the application delivers an immersive user experience through a **Three.js WebGL particle field**, **dynamic camera parallax**, **GSAP timeline reveals**, and **fluid interactive micro-animations**. The contact form utilizes a secure **Vercel Serverless Function** integrated with the **Resend API**, ensuring zero exposure of private API credentials in client-side code.

---

## ✨ Key Features

- 🌌 **Interactive 3D WebGL Starfield**: Thousands of particle nodes rendered via Three.js with dynamic camera tracking responding to mouse movements and viewport shifts.
- ⚡ **GSAP ScrollTrigger Choreography**: Staggered entrance animations, section reveals, and smooth element transformations.
- 🖱️ **Custom Magnetic Cursor System**: Reactive trailing cursor dot and outline with magnetic snapping on interactive elements.
- 🎴 **3D Perspective Tilt Cards**: Dynamic card tilt physics calculated in real-time according to mouse cursor coordinates.
- ⏳ **Timeline Progress Indicator**: Scroll-synchronized milestone path highlighting education and work history.
- ⌨️ **Terminal-Style Typewriter**: Auto-cycling role titles in the hero section displaying core technical disciplines.
- 🛡️ **Secure Serverless Contact Form**: Protected endpoint via Node.js `/api/submit` communicating over HTTPS with the Resend API.
- 🎨 **Glassmorphic Cyber Aesthetic**: High-contrast dark palette, subtle backdrop blurs, neon gradient borders, and responsive grid layouts.
- 📱 **100% Fully Responsive**: Pixel-perfect viewing across mobile, tablet, laptop, and ultra-wide displays.
- 🔍 **Search Engine Optimized (SEO)**: Pre-configured OpenGraph metadata, Twitter Cards, canonical URL tags, and dynamic sitemap.

---

## 📂 Portfolio Sections

| Section | Description |
| :--- | :--- |
| **Hero** | High-impact greeting, dynamic role typewriter, CTAs to resume and contact form, and social links. |
| **About Me** | Background summary, technical philosophies, quick stats, and core focus areas. |
| **Work Experience** | Chronological career timeline detailing engineering roles, responsibilities, and achievements. |
| **Education** | Academic background, institutions, degree honors, and coursework. |
| **Projects** | Featured software projects with tech stack tags, GitHub repositories, and live demo links. |
| **Technical Skills** | Categorized skill chips (Languages, Frameworks, AI/ML & Data, Cloud & Developer Tools). |
| **Certifications** | Verified professional credentials and industry certifications with modal previews. |
| **Achievements** | Competitive coding milestones, hackathon awards, and recognitions. |
| **Coding Profiles** | Direct links to LeetCode, GitHub, LinkedIn, and developer platforms. |
| **Contact Form** | Async contact portal with client validation, loading state, and serverless email delivery. |

---

## 🛠️ Tech Stack & Architecture

### **Frontend & Visuals**
- **Markup & Structure:** HTML5 (Semantic, SEO-optimized)
- **Styling:** Vanilla CSS3 (Custom properties, CSS Grid, Flexbox, Glassmorphism backdrop filters)
- **Programming Language:** Vanilla JavaScript (ES6+ Modules)
- **3D Graphics:** [Three.js](https://threejs.org/) (r128)
- **Motion & Animations:** [GSAP](https://greensock.com/gsap/) (3.12.2) + [ScrollTrigger](https://greensock.com/scrolltrigger/)
- **Iconography & Fonts:** [Font Awesome 6](https://fontawesome.com/), [Devicon](https://devicon.dev/), [Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)

### **Backend & APIs**
- **Serverless Runtime:** Node.js Vercel Function (`api/submit.js`)
- **Email Delivery Service:** [Resend API](https://resend.com/)
- **Analytics & Observability:** [@vercel/analytics](https://vercel.com/analytics), [@vercel/speed-insights](https://vercel.com/speed-insights)

---

## 📁 Project Directory Structure

```text
Yash_Raj-Personal-Portfolio-Website/
│
├── index.html                   # Core HTML markup, SEO tags, & semantic structure
├── style.css                    # Design system, CSS variables, glassmorphism, responsive queries
├── script.js                    # UI interactivity, typewriter effect, tilt cards, contact form
├── 3d_background.js             # Three.js WebGL particle field & GSAP animation sequences
│
├── api/
│   └── submit.js                # Vercel serverless function handling contact form submissions
│
├── portfolio_assets/            # Media assets
│   ├── YR_Favicon.jpg           # Portfolio favicon and meta preview image
│   ├── Yash_Profile.png         # Author portrait
│   ├── Yash_Raj_Resume.pdf      # Downloadable resume PDF
│   └── *.webp, *.jpg, *.png     # Company, university, and certification badges
│
├── package.json                 # Project configuration, scripts, and dependencies
├── .gitignore                   # Files and directories ignored by Git version control
├── robots.txt                   # Search crawler directives
├── sitemap.xml                  # Search engine URL indexing structure
└── README.md                    # Project documentation
```

---

## 🚀 Local Development Setup

Follow these steps to run the portfolio on your local machine:

### **1. Prerequisites**
- [Node.js](https://nodejs.org/) (v18.0.0 or higher recommended)
- [npm](https://www.npmjs.com/) (bundled with Node.js)
- [Git](https://git-scm.com/)

### **2. Clone the Repository**
```bash
git clone https://github.com/Yashraj413/Yash-Raj-Portfolio-Website.git
cd Yash-Raj-Portfolio-Website
```

### **3. Install Dependencies**
```bash
npm install
```

### **4. Run Local Server**
Start a local static development server:
```bash
npm run dev
# or
npm run serve
```

Open your browser and navigate to:
```
http://localhost:3000
```

> **Note on Contact Form Locally:**  
> The contact form (`/api/submit`) executes as a Vercel Serverless Function. To test the backend API locally, install the Vercel CLI via `npm i -g vercel` and run `vercel dev`.

---

## ⚙️ Environment Variables

To enable the contact form to dispatch messages to your inbox via the Resend API, configure the following environment variables in your hosting provider (or `.env.local` when using Vercel CLI):

| Variable | Description | Example |
| :--- | :--- | :--- |
| `RESEND_API_KEY` | Secret API key generated from [Resend](https://resend.com/api-keys) | `re_123456789_abcdefg...` |
| `RECEIVER_EMAIL` | Target email address where contact messages should arrive | `your-email@example.com` |

---

## 🌐 Deployment Guide

### **Deploying on Vercel (Recommended)**

1. **Push to GitHub**:
   Ensure all files are pushed to your GitHub repository:
   ```bash
   git add .
   git commit -m "Update portfolio assets and documentation"
   git push origin main
   ```

2. **Import into Vercel**:
   - Log in to your [Vercel Dashboard](https://vercel.com/dashboard).
   - Click **"Add New..."** > **"Project"**.
   - Select your repository `Yash-Raj-Portfolio-Website` and click **Import**.

3. **Configure Environment Variables**:
   - In the project configuration screen, navigate to **Environment Variables**.
   - Add `RESEND_API_KEY` with your Resend API secret.
   - Add `RECEIVER_EMAIL` with your destination email address.

4. **Deploy**:
   - Click **"Deploy"**.
   - Once deployed, your site will be live at `https://your-project-name.vercel.app`.

---

## 👨‍💻 Contact & Connect

**Yash Raj**  
*Software Developer | Full-Stack • AI/ML • Data*

- 🌐 **Portfolio:** [yash-raj-portfolio-website-neon.vercel.app](https://yash-raj-portfolio-website-neon.vercel.app/)
- 💼 **LinkedIn:** [/in/yash-raj-7225b3212](https://linkedin.com/in/yash-raj-7225b3212)
- 🐙 **GitHub:** [@Yashraj413](https://github.com/Yashraj413)
- ⚡ **LeetCode:** [@Yashraj012](https://leetcode.com/u/Yashraj012/)
- 📧 **Email:** [yashraj41323@gmail.com](mailto:yashraj41323@gmail.com)

---

## 📄 License

This project is licensed under the [ISC License](LICENSE).  
Feel free to star ⭐ this repository if you find it helpful!

<div align="center">
  <sub>© 2026 Yash Raj. Built with precision and passion.</sub>
</div>
