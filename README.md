<div align="center">

# 🚀 3D Developer Portfolio

A stunning, immersive **3D developer portfolio** built with modern web technologies. Featuring interactive 3D models, smooth GSAP animations, and a sleek dark-themed design — this portfolio is designed to leave a lasting impression.

</div>

---

## 🎬 Showcase

### 📸 Screenshot

<div align="center">
  <img src="showcase/Screenshot 2026-02-25 132533.png" alt="3D Portfolio Screenshot" width="100%" />
</div>

### 🎥 Demo Video

<div align="center">
  <video src="https://github.com/user-attachments/assets/placeholder" controls width="100%">
    Your browser does not support the video tag.
  </video>
</div>

> **Note:** The full demo video is available in the [`showcase/product.mp4`](showcase/product.mp4) file.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [License](#license)

---

## 🤖 About the Project

This is a **3D minimalistic developer portfolio** website that showcases a developer's skills, projects, experience, and contact information in a visually captivating way. Unlike traditional flat portfolios, this one leverages **Three.js** and **React Three Fiber** to render interactive 3D scenes directly in the browser — creating an experience that stands out.

The portfolio is broken into distinct sections:

- **Hero** — A dynamic 3D hacker room scene that reacts to mouse movements, accompanied by animated floating 3D models (cube, rings, React logo, target).
- **About** — A bento-grid layout with personal info, a 3D globe showing location, tech stack icons, and a quick email-copy feature.
- **Projects** — An interactive project carousel where live demos play inside a 3D computer model, with seamless project switching.
- **Clients** — Testimonials from satisfied clients highlighting collaboration and results.
- **Work Experience** — A timeline of professional milestones with animated 3D character reactions on hover.
- **Contact** — A functional email form powered by **EmailJS** for direct outreach from visitors.
- **Footer** — A clean footer with social media links.

---

## 🔋 Features

- 🖥️ **Immersive 3D Hero Section** — Interactive hacker room scene with mouse-tracking, surrounded by animated mini-models
- 📊 **Bento Grid About Section** — Personal info, 3D globe, tech stack icons, and one-click email copy
- 🎞️ **Dynamic Project Showcase** — Live project demos inside a 3D computer model with smooth transitions
- 🏢 **Interactive Experience Timeline** — Hover over milestones to trigger 3D character animations
- 💬 **Client Testimonials** — Dedicated section for client reviews and feedback
- 📧 **Contact Form** — Functional email form integrated with EmailJS
- 🌗 **Dark Theme** — Sleek, modern dark-themed design throughout
- 📱 **Fully Responsive** — Optimized for all devices — desktop, tablet, and mobile
- 🎭 **GSAP Animations** — Smooth, performant animations using GSAP and `@gsap/react`
- ⚡ **Vite Powered** — Lightning-fast development and build times

---

## ⚙️ Tech Stack

| Technology            | Purpose                               |
| --------------------- | ------------------------------------- |
| **React 18**          | UI framework & component architecture |
| **Three.js**          | 3D rendering engine                   |
| **React Three Fiber** | React renderer for Three.js           |
| **React Three Drei**  | Useful helpers & abstractions for R3F |
| **GSAP**              | High-performance animations           |
| **Tailwind CSS**      | Utility-first styling                 |
| **EmailJS**           | Contact form email delivery           |
| **Vite**              | Build tool & dev server               |
| **react-globe.gl**    | Interactive 3D globe component        |
| **react-responsive**  | Responsive breakpoint hooks           |

---

## 🤸 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (v18+)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/3d-portfolio.git
   cd 3d-portfolio
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the project root:

   ```env
   VITE_APP_EMAILJS_USERID=your_emailjs_user_id
   VITE_APP_EMAILJS_TEMPLATEID=your_emailjs_template_id
   VITE_APP_EMAILJS_RECEIVERID=your_emailjs_receiver_id
   ```

   Get your credentials from [EmailJS](https://www.emailjs.com/).

4. **Run the development server**

   ```bash
   npm run dev
   ```

5. **Open in browser**

   Navigate to [http://localhost:5173](http://localhost:5173)

---

## 📁 Project Structure

```
3d-portfolio/
├── public/                 # Static assets (3D models, textures, images)
├── showcase/               # Showcase media (screenshot, demo video)
├── src/
│   ├── components/         # Reusable 3D & UI components (Cube, Rings, etc.)
│   ├── constants/          # App data (projects, experiences, nav links)
│   ├── hooks/              # Custom React hooks
│   ├── sections/           # Page sections (Hero, About, Projects, etc.)
│   ├── App.jsx             # Root application component
│   ├── index.css           # Global styles & Tailwind utilities
│   └── main.jsx            # Entry point
├── index.html              # HTML template
├── tailwind.config.js      # Tailwind CSS configuration
├── vite.config.js          # Vite configuration
└── package.json            # Dependencies & scripts
```

---

## 📜 License

This project is open source and available for personal use and learning purposes.

---

<div align="center">
  <p>Built with ❤️ using React, Three.js, and GSAP</p>
</div>
