# 🌐 Pranav Ingole — Personal Portfolio Website

A fully responsive personal portfolio website built with **HTML5**, **CSS3**, **Bootstrap 5**, and **Vanilla JavaScript**. Designed to showcase skills, data science projects, professional certifications, and contact information.

---

## 📌 About the Developer

**Pranav Rajesh Ingole** — Aspiring Data Scientist based in Nagpur, Maharashtra, India.

- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/pranav-ingole-0225392aa)
- 💡 Passionate about transforming raw data into meaningful insights
- 🎯 Focused on Power BI, SQL, Python, and MS Excel

---

## ✨ Features

- **Responsive Design** — Works seamlessly on mobile, tablet, and desktop using Bootstrap 5 grid
- **Fixed Navigation Bar** — Smooth scroll to all sections
- **Hero Section** — Circular profile photo with gradient background, LinkedIn & Hire Me CTAs
- **Animated Skill Bars** — Visual progress indicators for key tools
- **Project Cards** — Hover-lift cards for each data science project
- **Certificate Gallery** — 6 real certificate thumbnails with titles
- **Contact Form** — Client-side validated form with success message via JavaScript
- **No Backend Required** — Fully static, open directly in any browser

---

## 🛠️ Tech Stack

| Technology       | Version | Purpose                             |
|------------------|---------|-------------------------------------|
| HTML5            | —       | Page structure & semantic markup    |
| CSS3             | —       | Custom styles, transitions, layout  |
| JavaScript (ES6) | —       | Form handling & DOM interaction     |
| Bootstrap        | 5.3.2   | Responsive grid & UI components     |
| Font Awesome     | 6.5.0   | Social & UI icons                   |

---

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Main single-page HTML file
├── style.css               # Custom stylesheet
├── script.js               # JavaScript (contact form handler)
│
└── assets/                 # All static images
    ├── profile.jpg         # Developer profile photo (studio shot)
    ├── 1.jpeg              # Certificate: AI Origins & Foundations (NXTGEN)
    ├── 2.jpg               # Certificate: Getting Started with AI (IBM)
    ├── 3.jpg               # Certificate: Project Management 101 (Simplilearn)
    ├── 4.jpg               # Certificate: Journey to Cloud (IBM SkillsBuild)
    ├── 5.jpg               # Certificate: RAG with LangChain (IBM SkillsBuild)
    └── 6.jpg               # Certificate: Earn it! Accept it! Share it! (IBM)
```

---

## 📄 Sections

### 🏠 Home (Hero)
- Profile photo with circular white border
- Name: **Pranav Ingole**
- Tagline: *Aspiring Data Scientist | Power BI | SQL*
- Buttons: LinkedIn (external link) & Hire Me (scrolls to contact)
- Background: `linear-gradient(135deg, #e0e4e8, #471499)`

### 👤 About Me
- Personal bio covering passion for data science, Python, analytics tools, and career goals

### 📊 Skills

| Skill    | Proficiency |
|----------|-------------|
| Python   | 95%         |
| MS Excel | 90%         |
| Power BI | 85%         |
| SQL      | 80%         |

### 💼 Projects

| Project                    | Description                                                  |
|----------------------------|--------------------------------------------------------------|
| Student Management System  | Manages student records, attendance, and academic details    |
| IPL Data Analysis          | Predicts winning teams using cricket match data              |
| Zomato Data Analysis       | Analyzes Zomato online food delivery data and trends         |

### 🏆 Certificates

| # | Certificate | Issuer | Completion Date |
|---|-------------|--------|-----------------|
| 1 | AI101 — AI Origins & Foundations | NXTGEN Intelligence Academy | 17 Dec 2025 |
| 2 | Getting Started with Artificial Intelligence | IBM SkillsBuild | 07 Aug 2025 |
| 3 | Project Management 101 | Simplilearn SkillUp | 08 Jan 2026 |
| 4 | Journey to Cloud: Envisioning Your Solution | IBM SkillsBuild | 07 Aug 2025 |
| 5 | Lab: Retrieval Augmented Generation with LangChain | IBM SkillsBuild | 07 Aug 2025 |
| 6 | Earn it! Accept it! Share it! | IBM SkillsBuild | 07 Aug 2025 |

### 📬 Contact
- Form fields: Name, Email, Message
- On submit: prevents page reload, shows *"Message sent successfully!"*, resets form fields

---

## 🚀 Getting Started

### No Installation Needed

This is a static website — no build tools, no package managers, no server required.

### Option 1 — Open directly
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Option 2 — Local development server (recommended)
```bash
# Python (no install needed)
python -m http.server 8000
# Visit: http://localhost:8000

# OR Node.js
npx serve .
# Visit: http://localhost:3000
```

> ⚠️ Some browsers block local image loading when opening via `file://`. Use a local server to avoid this.

---

## 🎨 Customization Guide

| What to Change       | Where to Edit                                           |
|----------------------|---------------------------------------------------------|
| Profile photo        | Replace `assets/profile.jpg`                            |
| Name & tagline       | `index.html` → `#home` section                         |
| About text           | `index.html` → `#about` section `<p>` tag              |
| Skill percentages    | `index.html` → `style="width: X%"` in `#skills`        |
| Project descriptions | `index.html` → `.project-card` blocks                  |
| Certificate images   | Replace `assets/1.jpeg` through `assets/6.jpg`          |
| Certificate titles   | `index.html` → `<h6>` tags in `#certificates`          |
| Navbar color         | `style.css` → `.navbar { background: #134084; }`       |
| Hero gradient        | `style.css` → `.hero-section { background: ... }`      |
| Footer color         | `style.css` → `footer { background: #0d6efd; }`        |
| LinkedIn URL         | `index.html` → `<a href="...">` in hero section        |

---

## 🌍 Deployment

### GitHub Pages
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
# Enable GitHub Pages: Settings → Pages → Deploy from main branch
```

### Netlify (Drag & Drop)
1. Go to [netlify.com](https://netlify.com)
2. Drag the entire project folder onto the dashboard
3. Your site is live instantly with a free URL

### Vercel
```bash
npx vercel
```

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

*Built with ❤️ by Pranav Rajesh Ingole — Nagpur, Maharashtra, India*
