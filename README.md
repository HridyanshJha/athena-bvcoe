# ATHENA: Glitch Gallery – Official Website

Welcome to the official repository of **ATHENA**, the Technical and Gaming Society of **Bharati Vidyapeeth College of Engineering (BVCOE)**. This project is a modern, fully responsive, and scalable web platform that showcases our events, achievements, and community spirit.

🌐 **Live Website**: [ATHENA BVCOE](https://athena-tech-bvcoe.netlify.app)
 **🏛️ College Website:**: [BVCOE Official Site](https://bvcoend.ac.in/)              
 
 Steps To follow:-*BVCOE Official Site → Life@BVCOE → Student Chapter Cell → Technical Society → ATHENA*

---

## 📌 Project Overview

ATHENA's online presence is designed to reflect our energy and innovation. The **Glitch Gallery** is a futuristic, interactive, and minimal web application that serves as a central hub for:

- 🎮 Gaming tournaments & leaderboards
- 🧠 Tech symposiums & hackathons
- 📰 Event registrations and updates
- 🏆 Display of society achievements
- 📸 Media gallery of past events

---

## 🧠 Tech Stack

| Technology    | Role                                     |
|---------------|------------------------------------------|
| Vite          | Lightning-fast build tool and dev server |
| TypeScript    | Type-safe JavaScript                     |
| React         | Component-based UI library               |
| Tailwind CSS  | Utility-first CSS for rapid styling      |
| shadcn/ui     | Accessible and customizable UI components|
| PostCSS       | Modern CSS transformations               |
| EmailJs       | For Backend to get Applications          |

---

## ⚙️ Local Development Setup

> Ensure **Vscode** and **npm** are installed.

```sh
# 1. Clone the repository
git clone <YOUR_REPO_URL>

# 2. Navigate into the directory
cd athena-glitch-gallery

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

Open http://localhost:5173 to preview the project locally.

## 🗂 Project Structure
```sh
ATHENA-GLITCH-GALLERY/
│
├── public/                         # Static public assets
│   └── assets/
│       ├── images/
│       │   ├── athena-logo.png     # Athena official logo (public reference)
│       │   └── suman_maam.jpg      # Image asset
│
├── src/                            # Main source folder (React + TypeScript)
│   ├── assets/
│   │   └── images/                 # Local images used inside components
│   │       ├── athena-logo.png
│   │       └── suman_maam.jpg
│   │
│   ├── components/                 # All reusable UI and layout components
│   │   ├── ui/                     # ShadCN-inspired modular UI components
│   │   │   ├── accordion.tsx
│   │   │   ├── alert.tsx
│   │   │   ├── button.tsx
│   │   │   ├── ... (etc)          # Includes input, modal, table, toast, etc.
│   │   │   └── use-toast.ts       # Custom toast utility
│   │   │
│   │   ├── Footer.tsx             # Website footer
│   │   ├── Hero.tsx               # Main landing section
│   │   ├── Logo.tsx               # Athena logo component
│   │   ├── Navbar.tsx             # Navigation bar
│   │   ├── PastEvents.tsx         # Display past events
│   │   ├── PastTeamMembers.tsx    # Alumni team members showcase
│   │   ├── TeamSection.tsx        # Current team members section
│   │   └── UpcomingEvents.tsx     # Events scheduled in the future
│   │
│   ├── hooks/                     # Custom React hooks
│   │   ├── use-mobile.tsx         # Mobile screen hook
│   │   └── use-toast.ts           # Toast management logic
│   │
│   ├── lib/
│   │   └── utils.ts               # Utility/helper functions
│   │
│   ├── pages/                     # Pages directory (if using routing)
│   │
│   ├── App.css                    # App-level custom styles
│   ├── App.tsx                    # Main App component
│   ├── index.css                  # Tailwind base/global styles
│   ├── main.tsx                   # React DOM rendering entry
│   └── vite-env.d.ts              # Vite TypeScript environment declarations
│
├── components.json                # Dynamic component registry (optional)
├── index.html                     # Main HTML shell used by Vite
├── tailwind.config.ts            # Tailwind configuration
├── vite.config.ts                # Vite configuration for build and dev
├── tsconfig.json                 # Root TypeScript configuration
├── tsconfig.app.json             # App-specific TypeScript config
├── tsconfig.node.json            # Node-related TypeScript config
├── eslint.config.js              # Linting and code rules
├── postcss.config.js             # PostCSS plugin configuration
├── package.json                  # Project dependencies and scripts
├── package-lock.json             # Dependency lockfile
├── .gitignore                    # Files and folders ignored by Git
├── README.md                     # Project documentation
└── SECURITY.md                   # Security policies

```
🔄 Deployment
This project is deployed using Netlify for seamless CI/CD and fast global delivery.

To deploy manually:

Build your project:
```sh
npm run build
```
Upload the dist/ folder to Netlify or any static host of choice.

## 🔐 Security & Maintenance
Security protocols and best practices are followed as per standard front-end guidelines.
Refer to SECURITY.md for issue reporting and responsible disclosure.
Regular dependency updates are performed to prevent vulnerabilities.


## 📊 Application Flowchart:
```sh
              ┌───────────────┐
              │   Homepage    │
              └──────┬────────┘
                     │
           ┌─────────▼──────────┐
           │  Event Gallery     │
           └─────────┬──────────┘
                     │
          ┌──────────▼─────────┐
          │ Registration Forms │
          └──────────┬─────────┘
                     │
             ┌───────▼────────┐
             │ Leaderboards   │
             └───────┬────────┘
                     │
            ┌────────▼─────────┐
            │ Past Highlights  │
            └──────────────────┘
```

🌟 Key Features
⚡ Lightning-fast performance with Vite

🎨 Elegant UI powered by Tailwind CSS & shadcn/ui

📱 Mobile-First Design for full responsiveness

🧩 Modular Component Architecture

🛡️ Security Compliance and accessibility-focused

🚀 Continuous Deployment on Netlify

---
## 📄 License

This project is licensed under the [MIT License](LICENSE).
