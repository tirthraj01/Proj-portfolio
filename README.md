# 🚀 Mine Portfolio Website

A **modern, minimal, and beginner-friendly** portfolio template built with vanilla HTML, CSS, and JavaScript. Designed for Second Year Engineering (SE) students who want a professional online presence — **no frameworks, no npm, no complexity**.

> ✏️ **Edit one file (`data.js`) and your portfolio is ready.**

![Light Mode](https://img.shields.io/badge/theme-light-f0f0f0?style=flat-square)
![Dark Mode](https://img.shields.io/badge/theme-dark-0a0a0a?style=flat-square&labelColor=0a0a0a)
![Responsive](https://img.shields.io/badge/responsive-yes-c8ff00?style=flat-square)
![No Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen?style=flat-square)

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎯 **One-File Customization** | Edit only `data.js` to personalize everything |
| 🌙 **Dark Mode** | Toggle with auto-save (remembers your preference) |
| 📱 **Fully Responsive** | Looks great on mobile, tablet, and desktop |
| 🎬 **Smooth Animations** | Scroll reveals, parallax, hover effects (inspired by [landonorris.com](https://landonorris.com)) |
| ⚡ **Preloader** | Stylish loading screen with animated progress bar |
| 🖱️ **Custom Cursor** | Interactive dot + ring cursor on desktop |
| 📌 **Sticky Navbar** | Frosted glass effect with active section highlighting |
| 🔤 **Marquee** | Scrolling skill names between sections |
| 📦 **Zero Dependencies** | No npm, no frameworks, no build step |

---

## 📁 Project Structure

```
portfolio/
├── index.html   ← Page structure (don't edit)
├── style.css    ← Styling (don't edit)
├── script.js    ← Logic & animations (don't edit)
└── data.js      ← ✅ YOUR DATA — Edit this file!
```

---

## 📄 Sections

- **Hero** — Name + tagline + call-to-action buttons
- **About Me** — Bio + highlight cards (location, university, branch, year)
- **Skills** — Grid with animated progress bars
- **Projects** — Cards with descriptions, tech tags, and hover effects
- **Education** — Timeline with degree, institution, and dates
- **Contact** — Email link + social media buttons

---

## 🛠️ How to Use

### Step 1: Download or Clone

```bash
git clone https://github.com/YOUR_USERNAME/portfolio.git
cd portfolio
```

Or simply download the ZIP and extract it.

### Step 2: Edit `data.js`

Open `data.js` in any text editor (VS Code recommended) and replace the placeholder values:

```js
const portfolioData = {
  // 🧑 Change your name
  name: "Your Name Here",
  tagline: "Your Tagline Here",

  // 📖 Write about yourself
  about: {
    description: "A short bio about yourself...",
    highlights: [
      { label: "Location", value: "Your City" },
      { label: "University", value: "Your University" },
      // ...
    ],
  },

  // 🛠️ List your skills (level: 1-5)
  skills: [
    { name: "HTML & CSS", level: 4 },
    { name: "JavaScript", level: 3 },
    // ...
  ],

  // 🚀 Add your projects
  projects: [
    {
      title: "Project Name",
      description: "What it does...",
      tags: ["HTML", "CSS", "JS"],
      liveLink: "https://...",
      codeLink: "https://github.com/...",
    },
    // ...
  ],

  // 🎓 Your education
  education: [
    {
      degree: "B.E. in Computer Engineering",
      institution: "Your University",
      duration: "2024 – 2028",
      description: "CGPA: 8.5 / 10",
    },
    // ...
  ],

  // 🌐 Your contact info
  contact: {
    email: "you@email.com",
    socialLinks: [
      { platform: "GitHub", url: "https://github.com/you", icon: "github" },
      { platform: "LinkedIn", url: "https://linkedin.com/in/you", icon: "linkedin" },
      // ...
    ],
  },

  // 🎨 Customize the accent color
  theme: {
    accentColor: "#c8ff00",
  },
};
```

### Step 3: Preview Locally

```bash
# Option A: Python (pre-installed on Mac/Linux)
python3 -m http.server 8080
# → Open http://localhost:8080

# Option B: VS Code Live Server
# Install "Live Server" extension → right-click index.html → "Open with Live Server"

# Option C: Direct open
# Double-click index.html in your file manager
```

### Step 4: Deploy to GitHub Pages (Free!)

```bash
# 1. Create a new repo on GitHub (e.g., "portfolio")

# 2. Push your code
git init
git add .
git commit -m "My portfolio 🚀"
git branch -M main
git remote add origin https://github.com/ChinmayIngle26/Portfolio.git
git push -u origin main

# 3. Enable GitHub Pages
#    → Repo Settings → Pages → Source: "main" branch → Save

# 4. Your site is live at:
#    https://YOUR_USERNAME.github.io/portfolio/
```

---

## 🎨 Customization Tips

### Change the accent color

In `data.js`, modify the `theme` section:

```js
theme: {
  accentColor: "#c8ff00",       // Try: "#6366f1" (purple), "#f43f5e" (pink), "#06b6d4" (cyan)
  accentColorDark: "#a8d900",   // A slightly darker shade for hover effects
},
```

### Supported social icons

Use these icon names in `contact.socialLinks`:

`github` · `linkedin` · `twitter` · `instagram` · `email` · `codepen` · `youtube`

### Add more projects

Just add another object to the `projects` array:

```js
{
  title: "My New Project",
  description: "What it does...",
  tags: ["React", "Firebase"],
  liveLink: "https://myproject.com",   // Use "#" if no live demo
  codeLink: "https://github.com/...",  // Use "#" if no repo
},
```

---

## 🧩 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Custom properties, Grid, Flexbox, animations |
| **Vanilla JS** | DOM manipulation, Intersection Observer, localStorage |
| **Google Fonts** | Inter + Space Grotesk typography |

---

## 📝 FAQ

**Q: Do I need Node.js or npm?**
No! This is pure HTML/CSS/JS. Just open `index.html` in a browser.

**Q: Can I use this for my actual portfolio?**
Absolutely! It's designed for exactly that. Just edit `data.js` with your info.

**Q: How do I add a custom domain?**
After deploying to GitHub Pages, go to Settings → Pages → Custom Domain and add your domain.

**Q: The animations feel slow/fast. How do I adjust?**
In `style.css`, look for the `--transition-*` variables at the top and tweak the duration values.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Built with ♥ for the GDG community
</p>
