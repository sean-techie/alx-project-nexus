# Lite-Link URL Shortener

## Overview
Lite-Link is a modern URL shortening web application built with **Next.js, TypeScript, and TailwindCSS**.  
The app allows users to convert long URLs into short, shareable links through a simple and responsive interface.

This project demonstrates real-world frontend engineering practices including modern project structure, reusable components, and production-ready tooling.

---

##  User Stories — Lite-Link URL Shortener Project Nexus 

### User Story 1 — Instant Link Sharing Experience

**As Everest **, a busy digital professional who frequently shares content online,  
**I want to** paste a long URL into a simple interface and instantly receive a shortened, easy-to-copy link with basic tracking information,  
**so that** I can share clean, professional-looking links across social media, messaging apps, and emails while confidently knowing how often my links are being accessed.

**Impact / Transformation**  
Before using the app, Everest struggled with messy, lengthy URLs that looked unprofessional and were hard to share. With Lite-Link URL, Everest can now generate polished short links in seconds, improving the appearance of shared content and saving valuable time.

---

###  User Story 2 — Link Performance & Control Experience

**As Vee**, a content creator who shares multiple links across platforms,  
**I want to** access an admin link where I can view click counts, generate QR codes, and customize my short URLs,  
**so that** I can better understand engagement and manage my links more effectively without needing technical expertise.

**Impact / Transformation**  
Previously, Vee had no visibility into how shared links were performing. With Lite-Link URL, Vee gains simple analytics and control, enabling smarter decisions about what content resonates and how to share it more effectively.


## Features
- Shorten long URLs using an external API
- Client-side validation and error handling
- Copy shortened links easily
- Responsive mobile-first design
- Clean and scalable Next.js project structure

---

## Tech Stack
- **Framework:** Next.js (App Router)
- **Language:** TypeScript, JavaScript
- **Styling:** TailwindCSS
- **Tooling:** ESLint, PostCSS, npm

---

## Project Structure

lite-link/
├── public/
├── src/
│ ├── app/
│ │ ├── layout.tsx
│ │ ├── page.tsx
│ │ └── globals.css
│ └── components/
│ └── Navbar.tsx
├── tailwind.config.ts
├── postcss.config.mjs
├── next.config.mjs
├── tsconfig.json
└── package.json


---

## Key Concepts Demonstrated
- **Next.js App Router:** layouts, pages, and scalable structure  
- **Component-Based Architecture:** reusable UI (Navbar component)  
- **TailwindCSS:** responsive, mobile-first styling  
- **TypeScript:** safer, type-checked development  
- **Project Tooling:** modern configuration and environment-ready setup  

---

## Major Learnings
- Structuring production-ready Next.js apps
- Integrating TailwindCSS with PostCSS
- Organizing scalable frontend projects
- Writing reusable and maintainable components
- Understanding modern frontend tooling

---

## Challenges & Solutions
- **Next.js Structure:** Learned App Router and layout system  
- **Tailwind Setup:** Configured Tailwind, PostCSS, and global styles  
- **Project Organization:** Implemented a clean folder structure  


## Benefits:
- Easier navigation of codebase
- Separation of UI, pages, and assets
- Industry-standard organization

---

###  Responsive and Accessible UI Foundations
Even at this stage, the app is built with:
- Mobile-first layout
- Semantic HTML
- Accessible navigation structure

This sets the foundation for future feature expansion.

---

## Getting Started
```bash
git clone https://github.com/yourusername/lite-link.git
npm install
npm run dev

## Contributing
This project was developed collaboratively as part of the **ALX ProDev Frontend Engineering Program**.

We welcome feedback and suggestions to improve the project.

### Contributors
- **Reseanne Rampou**
- **Vincent Odume**


License

Part of the ALX ProDev Frontend Engineering Program

Last Updated: February 2026
