# Pawan Selotkar — Portfolio Website 🚀

A modern, animated portfolio website showcasing my work as an **AI-First Full Stack Developer** and **Vibe Coder**. Built with React, TypeScript, Three.js, and GSAP with smooth scroll animations powered by Lenis.

## 🌐 Live Demo

(https://portfolio-pawan-eta.vercel.app/)

## ✨ Features

- **3D Interactive Tech Stack** — Floating spheres with physics simulation using React Three Fiber and Rapier
- **Smooth Scroll Animations** — Powered by Lenis and GSAP ScrollTrigger
- **Text Split Animations** — Custom text splitter with character and word-level GSAP animations
- **Responsive Design** — Fully optimized for desktop, tablet, and mobile
- **Loading Screen** — Animated loading progress with interactive marquee
- **Project Showcase** — 8 projects with GitHub and live demo links
- **Contact Section** — Direct links to email, GitHub, LinkedIn, and Instagram

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Frontend** | React, TypeScript, HTML, CSS |
| **3D Graphics** | Three.js, React Three Fiber, React Three Drei, Rapier Physics |
| **Animations** | GSAP, ScrollTrigger, Lenis Smooth Scroll |
| **Build Tool** | Vite |
| **Deployment** | Vercel |
| **AI Tools** | Prompt Engineering, Gemini API, AI Integration |

## 📁 Project Structure

```
├── public/
│   ├── images/          # Project screenshots and tech stack textures
│   └── models/          # 3D model files and HDR environments
├── src/
│   ├── components/      # React components (Landing, About, Work, Contact, etc.)
│   │   ├── Character/   # 3D character scene
│   │   ├── styles/      # Component-specific CSS
│   │   └── utils/       # Animation utilities (initialFX, splitText)
│   ├── utils/           # Text splitter utility
│   ├── context/         # Loading context provider
│   ├── config.ts        # All portfolio content and configuration
│   ├── App.tsx          # Main app component
│   └── main.tsx         # Entry point
├── index.html
├── vite.config.ts
├── tsconfig.json
└── package.json
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/pawan1812/Portfolio_pawan.git

# Navigate to project directory
cd Portfolio_pawan

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be running at `http://localhost:5173/`

### Build for Production

```bash
npm run build
```

The production build will be output to the `dist/` folder.

## 📋 Projects Showcased

| # | Project | Description | Links |
|---|---------|-------------|-------|
| 1 | **Nexora** | AI-powered legal platform with case classification and advocate matching | [Live](https://nexora-olive.vercel.app/) · [GitHub](https://github.com/Pa18wan/Nexora) |
| 2 | **SmartAlloc** | Resource allocation web and mobile app with dashboard | [GitHub](https://github.com/pawan1812/SmartAlloc-Web-Mobile-application-) |
| 3 | **Hirable_x** | Career intelligence platform with AI resume analysis | [Live](https://hirable-x.vercel.app/) · [GitHub](https://github.com/pawan1812/Hirable_x) |
| 4 | **MindWell** | Mental health web and mobile app with mood tracking | [GitHub](https://github.com/pawan1812/MindWell-Mobile-Web-Application-) |
| 5 | **FoodieHub** | Food ordering system with admin panel and cart | [GitHub](https://github.com/pawan1812/FoodieHub) |
| 6 | **ProLearn** | E-learning platform with course management | [GitHub](https://github.com/pawan1812/ProLearn-EducationHUB) |
| 7 | **AI Voice Assistant** | Python-based AI assistant with speech recognition | [GitHub](https://github.com/Pa18wan/AIVoiceAssistant) |
| 8 | **Focus Mode** | Browser productivity tool with distraction blocker | [GitHub](https://github.com/pawan1812/Focus-Mode) |

## 🎓 About Me

- **Name:** Pawan Selotkar
- **Education:** MCA (Pursuing) at IICC, RTMNU Nagpur | B.Com (CA) from DAIMSR, Nagpur (CGPA: 8.14)
- **Role:** AI-First Full Stack Developer and Vibe Coder
- **Location:** Nagpur, India

### Connect with me

- 🐙 GitHub: [Pa18wan](https://github.com/Pa18wan) · [pawan1812](https://github.com/pawan1812)
- 💼 LinkedIn: [pawan-selotkar-18dec2004](https://www.linkedin.com/in/pawan-selotkar-18dec2004/)
- 📸 Instagram: [pawan_182004](https://www.instagram.com/pawan_182004/)
- 📧 Email: pawanselotkar18@gmail.com

## 🚀 Deploy on Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub
3. Click **"Add New Project"** → Import `Portfolio_pawan`
4. Vercel auto-detects Vite. Verify settings:
   - **Framework Preset:** Vite
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
5. Click **Deploy** — done!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
