# 🚀 Deepak Harish — Portfolio

A modern, single-file personal portfolio website built with pure HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies — just one file.

![Status](https://img.shields.io/badge/status-live-brightgreen) ![HTML](https://img.shields.io/badge/built%20with-HTML%2FCSS%2FJS-ff6b35) ![Deploy](https://img.shields.io/badge/deployed%20on-Vercel-black)

---

## ✨ Features

- 🎬 **Loading screen** — Animated progress bar intro on page load
- ⌨️ **Typing animation** — Hero label cycles through role titles automatically
- 🗂️ **Project filter** — Filter projects by tech tag (React, JavaScript, Node.js, etc.)
- ✨ **Scroll reveal** — Sections animate in as you scroll
- ↑ **Scroll to top** — Fixed button appears after scrolling down
- 🍞 **Toast notifications** — Slide-in success/error feedback on form submit
- 🌙 **Dark / Light theme** — Toggle with localStorage persistence
- 📱 **Fully responsive** — Optimised for mobile, tablet, and desktop
- 🖱️ **Custom cursor** — Animated orange dot + ring (desktop only)
- 📬 **Contact form** — Powered by EmailJS, delivered to your inbox

---

## 🗂️ Project Structure

```
portfolio/
└── portfolio.html   ← Everything is in this one file
```

That's it. No `node_modules`, no `package.json`, no build step.

---

## 🚀 Deploying to Vercel

### Step 1 — Push to GitHub

Create a new GitHub repository and upload `portfolio.html`:

```bash
git init
git add portfolio.html
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Step 2 — Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and click **Add New Project**
2. Import your GitHub repository
3. Leave all settings as default — Vercel auto-detects it as a static site
4. Click **Deploy**

Your portfolio will be live at `https://your-repo-name.vercel.app` in under a minute.

---

## 📬 EmailJS Setup

The contact form uses [EmailJS](https://emailjs.com) to send emails without a backend.

The following credentials are already configured in `portfolio.html`:

| Key | Value |
|---|---|
| Service ID | `service_408z7nb` |
| Template ID | `template_qnxngeo` |
| Public Key | `jS9pIzOuO10XVVMw1` |

To update them, search for `emailjs.init(` inside the file and replace the values.

---

## 🖼️ Profile Photo

The profile photo loads directly from the public GitHub repository — no local file needed:

```
https://raw.githubusercontent.com/deepakharish17/DEEPAK-HARISH-MURALI-PORTFOLIO-REACT/main/public/deepak.jpeg
```

If you ever change the photo, update this URL in the two `<img>` tags inside `portfolio.html`.

---

## 🎨 Customisation

All content is in the `<script>` section near the bottom of the file.

| What to change | Where to find it |
|---|---|
| Projects list | `const PROJECTS = [...]` |
| Name, email, phone | Search for `harishdeepak35` / `8778658798` |
| Social links (GitHub, LinkedIn, Twitter) | Search for `social-link` in the HTML |
| Typing phrases | `const phrases = [...]` |
| Theme colours | CSS variables at the top (`:root`) |
| Resume link | Search for `drive.google.com` |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, responsive layout |
| Vanilla JavaScript | Interactivity, scroll spy, filter, typing |
| [EmailJS](https://emailjs.com) | Contact form (no backend) |
| [Google Fonts](https://fonts.google.com) | Syne + DM Mono |
| Vercel | Hosting & deployment |

---

## 📄 License

This project is personal and not open-sourced. All rights reserved © 2025 Deepak Harish.
