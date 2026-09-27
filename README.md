# 🎓 ABES Hub — Official Event Management Platform

> **The heartbeat of ABES Engineering College, Ghaziabad**  
> A modern, responsive web application for managing and discovering campus events — from Aarohan to hackathons, all in one beautiful place.

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![LocalStorage](https://img.shields.io/badge/Data-LocalStorage-6c5ce7?style=for-the-badge)

[Live Demo](#-getting-started) · [Report Bug](https://github.com/AniruddhaGupta03/College-event/issues) · [Request Feature](https://github.com/AniruddhaGupta03/College-event/issues)

</div>

---

## 📖 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Admin Credentials](#-admin-credentials)
- [Project Structure](#-project-structure)
- [Customization Guide](#-customization-guide)
- [Browser Support](#-browser-support)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Credits](#-credits)
- [License](#-license)

---

## 🏫 About

**ABES Hub** is the official digital event platform for [ABES Engineering College, Ghaziabad](https://www.abes.ac.in) — a premier institute affiliated to Dr. A.P.J. Abdul Kalam Technical University (AKTU), Lucknow.

Built as a single-page application, it connects **6000+ ABESians** across 8 departments (CSE, IT, ECE, EE, ME, CE, MBA, MCA) with **150+ events per year**, including the flagship techno-cultural fest **Aarohan**.

### 🎯 Why ABES Hub?
- ✅ **Zero setup** — Just open `index.html` in any browser.
- ✅ **No backend required** — All data is seamlessly stored in the browser's `localStorage`.
- ✅ **Fully responsive** — Works beautifully on mobile, tablet, and desktop.
- ✅ **Production-ready UI** — Modern glassmorphism design with real photography.
- ✅ **ABES-specific** — Pre-loaded with real clubs, events, and campus data.

---

## ✨ Features

### 👨‍🎓 Student Side
| Feature | Description |
|---------|-------------|
| 🏠 **Home Page** | Hero section with typing animation, live stats counter, and featured event spotlight. |
| 📅 **Events Listing** | Browse all events with real-time search and category filters. |
| 🎟️ **Event Cards** | Displays name, date, time, venue, description, organizing club, and registration count. |
| 📝 **Registration** | Modal form capturing name, ABES email, phone, department, year, and roll number. |
| ❤️ **Save Favorites** | Heart any event to save it for later (persisted locally). |
| 🎯 **Clubs Section** | Discover 8+ active clubs — IEEE, CodeChef, E-Cell, Robotics, etc. |
| 📸 **Photo Gallery** | Masonry grid with a lightbox viewer (keyboard navigation supported). |
| 💬 **Testimonials** | Auto-rotating carousel of real ABESian stories. |
| 👥 **Team Section** | Meet the faculty advisors and student organizers. |
| ❓ **FAQ Accordion** | Smooth expand/collapse for common questions. |
| 📬 **Newsletter** | Email subscription form with validation. |
| ⏰ **Live Countdown** | Ticking timer to the featured event (e.g., Aarohan 2026). |

### 🛠 Admin Side
| Feature | Description |
|---------|-------------|
| 🔐 **Secure Login** | Protected admin panel with credential verification. |
| 📊 **Dashboard Stats** | Visual counters for total events, upcoming events, registrations, and categories. |
| ➕ **Add Events** | Full form with name, date, time, venue, category, club, and description. |
| ✏️ **Edit Events** | Update any event details instantly. |
| 🗑️ **Delete Events** | Remove events with a confirmation prompt (cascades to registrations). |
| ⭐ **Featured Flag** | Mark any event as the home-page spotlight. |
| 👥 **View Registrations** | Comprehensive table with all student data per event. |
| 🔍 **Search & Filter** | Filter registrations by name, email, roll number, or specific event. |

### 🎨 Interactive Elements
- 🌊 Scroll progress bar
- ⬆️ Back-to-top button
- 🎬 Scroll-reveal animations
- 🔢 Animated number counters
- 💫 Typing effect in the hero section
- 🖼️ Lightbox gallery with keyboard navigation
- 🎠 Auto-rotating testimonials
- 🍞 Toast notifications for user feedback
- 📱 Mobile-friendly hamburger menu

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Structure** | HTML5 (Semantic) |
| **Styling** | CSS3 (Custom Properties, Flexbox, Grid, Animations) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Data Storage** | Browser `localStorage` |
| **Typography** | Google Fonts (Poppins, Space Grotesk) |
| **Images** | Unsplash (hotlinked, no local assets needed) |
| **Build Tools** | None — single file, zero dependencies |

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge).
- No Node.js, no npm, no server required!

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/AniruddhaGupta03/College-event.git

# 2. Navigate to the folder
cd College-event

# 3. Open in your browser
# Option A: Double-click index.html
# Option B: Use a local server (optional, for better performance)
python -m http.server 8000
# Then visit http://localhost:8000