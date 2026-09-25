# 🚀 Adarsh Singh — Personal Portfolio Website

A premium, modern, highly responsive portfolio website designed for **Adarsh Singh**, a first-year B.Tech student specializing in **Data Science & Artificial Intelligence / Machine Learning**, and **CMO @ WYNKO**.

Built with a dark futuristic aesthetic, glassmorphism, cyan/violet glowing accents, interactive particle canvas, project filtering, and responsive mobile architecture.

---

## 🌟 Highlights & Features

- **Futuristic Dark Aesthetic**: Midnight navy & space-black base (`#050814`) with cyan (`#06b6d4`), violet (`#8b5cf6`), and neon accents.
- **Hero Section**:
  - Catchphrase: *«“Building skills, creating projects, and turning ideas into real-world solutions.”»*
  - Interactive status badges: First-year B.Tech DS & AI/ML + CMO @ WYNKO.
  - CTAs for **View My Work** and **Let's Connect**.
  - Direct links to **LinkedIn**, **GitHub**, **Instagram**, and **Email**.
  - Interactive holographic dev card displaying specialization, tooling, and current venture.
- **Interactive Particle Background**: Zero-dependency HTML5 canvas rendering floating constellation nodes with cursor repulsion and attraction.
- **About Me**:
  - Narrative bridging analytical data science with entrepreneurial product building.
  - 4 Highlight Pillars: First-Year B.Tech, AI/ML & Data Science, Startup & Products, Creative & Tech.
  - Animated stat counters for college milestones.
- **Featured Projects & WYNKO Spotlight**:
  - **WYNKO — Focus • Study • Together**:
    - Focus Sessions, App Blocking, Group Study, Study Challenges, Study Communities, WYNKOINS Rewards.
    - Role Highlight: **CMO @ WYNKO**.
    - Interactive deep-dive modal preview and live UI mockup card.
  - **NeuroPredict**: Student study habits & academic score forecasting model.
  - **PulseAI**: Tech discussion sentiment and NLP trend analyzer.
  - **CampusFlow**: Engineering resource repository for first-year peers.
  - Category filters: *All Projects*, *Startups & Products*, *AI & Machine Learning*, *Web & Tools*.
  - Reserved placeholder card for future projects.
- **Currently Building**:
  - Dedicated spotlight for **WYNKO** with early access waitlist form, live registrant counter, and pulsing status beacon.
- **Skills (Categorized & Interactive)**:
  - **Technical**: Data Science, Artificial Intelligence, Machine Learning, Python, Basic Web Development.
  - **Creative & Professional**: Canva, Presentation Design, Content Creation, Digital Marketing, Branding, Social Media Strategy.
- **My Journey (Interactive Timeline)**:
  - Chronological roadmap: *Schooling → Class 12 (Science) → B.Tech (Data Science & AI/ML) → Hands-on Projects → Startup Building (CMO @ WYNKO) → Future Goals*.
- **Achievements & Highlights**:
  - Easy-to-update grid showcasing leadership, certifications, collegiate hackathons, and design expertise.
- **Contact & Connect**:
  - Direct connection cards for LinkedIn (`adarsh-singh-a04066251`), Email, and GitHub.
  - One-click **Copy Email** button with instant toast notification.
  - Interactive contact form with client-side validation and feedback.
- **Extra Utility**:
  - Sticky glassmorphic navbar with active section scrollspy.
  - Scroll progress bar at top of screen.
  - Mobile slide-out drawer menu.
  - Back-to-top floating button.

---

## 📁 File Structure

```text
adarsh-portfolio/
├── index.html        # Main semantic HTML5 markup & sections
├── styles.css        # Custom styles, glassmorphism, animations & glowing effects
├── app.js            # Particle canvas, interactions, modals, filtering & form toast
└── README.md         # Documentation & deployment guide
```

---

## ⚡ How to Run Locally

You can run this portfolio immediately with zero installation required:

### Option 1: Direct Browser Opening
Simply double-click `index.html` or drag and drop it into Chrome, Edge, Brave, or Firefox.

### Option 2: Python Local Server
Open PowerShell or your terminal in this directory:
```bash
python -m http.server 3000
```
Then visit `http://localhost:3000` in your web browser.

### Option 3: Node.js / npx serve
```bash
npx serve .
```

---

## ✏️ How to Personalize & Update

1. **LinkedIn Profile**:
   The LinkedIn link is already configured to:
   `https://www.linkedin.com/in/adarsh-singh-a04066251`

2. **GitHub & Instagram Handles**:
   Search for `https://github.com` and `https://instagram.com` in `index.html` and replace them with your exact usernames.

3. **Email**:
   Search for `adarsh.singh.tech@gmail.com` in `index.html` and `app.js` to change to your preferred university or personal email.

4. **Adding New Projects**:
   Duplicate any `<div class="project-card ...">` block in `index.html` under the `#projects` section and update the `data-category` attribute (`startup`, `ai-ml`, `web`).

---

## 🌐 Deploying to the Web (Free & Fast)

### Option A: GitHub Pages
1. Push this folder to a GitHub repository named `adarsh-singh-portfolio` or `username.github.io`.
2. Go to **Settings** > **Pages**.
3. Under **Branch**, select `main` and `/root`.
4. Click **Save**. Your site will be live at `https://<username>.github.io/`!

### Option B: Vercel or Netlify
1. Drag and drop the `adarsh-portfolio` folder directly into [Netlify Drop](https://app.netlify.com/drop) or import from GitHub on [Vercel](https://vercel.com).
2. It will deploy within 10 seconds.
