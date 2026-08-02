# 🚀 Interactive AI/ML Portfolio & Embedded CMS Engine

A modern, responsive, single-page interactive portfolio and content management system built with **Vanilla JavaScript**, **HTML5**, **CSS3**, and **Firebase**. 

Designed specifically for AI/ML engineers and developers, this project allows you to showcase your projects, skills, education, and experience while managing all content in real time via a built-in admin dashboard.

---

## ✨ Features

- 👤 **Interactive Profile & Hero**:
  - Dynamic typewriter effect cycling through custom roles.
  - Interactive photo hover card featuring quick facts and a biometric scanline effect.
  - Live client-side HTML5 canvas image cropping and compression.

- 🛠 **Embedded Admin CMS (`Ctrl + Shift + A` / `#admin`)**:
  - Built-in WYSIWYG administrative panel—no external backend required.
  - Live data binding: changes render immediately on the page as you edit.
  - Export and import JSON backup files (`portfolio-backup.json`).

- ⚡ **Firebase & Offline Storage Support**:
  - Synchronizes content with **Firebase Realtime Database** and **Firebase Auth**.
  - Includes automated fallback to browser `localStorage` when offline or in local mode.

- ⌨️ **Command Palette (`Ctrl + K`)**:
  - Keyboard-driven modal navigation allowing visitors to search sections and jump instantly.

- 📄 **PDF Resume Viewer & Case Studies**:
  - In-app PDF viewer modal for resumes with download support.
  - Interactive Case Study popups detailing project *Problems*, *Approaches*, and *Results*.

- ✉️ **Contact Form Integration**:
  - Integrated contact form ready for **Formspree** API endpoints.

- 🎨 **Modern Design System**:
  - Built with custom CSS variables, flexbox, CSS grid, glassmorphism backdrop filters, cursor radial spotlight highlights, and responsive layouts.

---

## 🛠 Tech Stack

- **Frontend**: HTML5, Vanilla JavaScript (ES6+), CSS3 (Custom Variables, Flexbox/Grid, Glassmorphism)
- **Database & Auth**: Firebase Realtime Database & Firebase Authentication (v10 Compat SDK)
- **Form Handling**: Formspree API
- **Fonts & Icons**: Google Fonts (Inter), inline SVGs

---

## 🚀 Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/portfolio-cms.git
   cd portfolio-cms
