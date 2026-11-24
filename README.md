# Study Material Portal

An interactive, self-contained study material portal and resource viewer for college coursework and technical subjects.

## 🌐 Live Hosted Site

The portal is hosted on GitHub Pages:
👉 **[https://chris-pereira-tech.github.io/study-material/](https://chris-pereira-tech.github.io/study-material/)**

---

## 📚 Overview

This repository hosts a fully bundled, interactive single-page study resource platform containing notes, assignments, lab tutorials, and reference documentation across multiple subject domains including:
- Data Warehousing & Mining (DWM)
- Computer Networks (CN)
- Theoretical Computer Science (TCS)
- Human-Computer Interaction (HCI)
- Security & Systems

## 🚀 Features

- **Self-Contained Bundle**: Everything is bundled within `index.html` with built-in asset unpacking.
- **Fast Client-Side Rendering**: Instant loading and search across modules.
- **Zero Configuration**: Ready to run directly in modern browsers or via GitHub Pages.

---

## 🛠️ GitHub Pages Hosting Configuration

This project is deployed to GitHub Pages. If configuring manually:

1. Navigate to **[Repository Settings > Pages](https://github.com/Chris-Pereira-tech/study-material/settings/pages)**.
2. Under **Build and deployment > Source**:
   - Select **GitHub Actions** (uses the automated workflow in `.github/workflows/deploy.yml`), OR
   - Select **Deploy from a branch** -> branch: `main` (or `gh-pages`), folder: `/ (root)`.
3. Save changes. GitHub Pages will build and deploy the site at `https://chris-pereira-tech.github.io/study-material/`.

---

## 💻 Local Preview

You can open `index.html` directly in any web browser, or serve it using a local HTTP server:

```bash
# Using Python
python -m http.server 8000

# Using Node / npx
npx serve .
```

Open `http://localhost:8000` in your browser.
