# Taos Game Maker — Developer Documentation & Showcase Hub

Official public documentation and product showcase website for **Taos Game Maker**, the complete data-driven tactical JRPG framework and local No-Code web studio for **Godot 4.3+**.

Designed for instant deployment via **GitHub Pages** (pure static HTML5 + Vanilla CSS, zero build step).

---

## 🔗 Official Links & Resources

- **Engine Purchase (Gumroad):** [https://taosworld.gumroad.com/l/TaosGameMaker](https://taosworld.gumroad.com/l/TaosGameMaker) ($19.99)
- **Engine Purchase (itch.io):** [https://taosworld.itch.io/taosgamemaker](https://taosworld.itch.io/taosgamemaker) ($19.99)
- **Playable Demo Game (Echoes of Truth):** [https://taosworld.itch.io/echoesoftruth](https://taosworld.itch.io/echoesoftruth) (Free on Web, Windows & Android)
- **Engine Video Tour (YouTube):** [https://youtu.be/9ugIta7vTkQ](https://youtu.be/9ugIta7vTkQ)
- **Official Universe Community:** [https://www.sagaesferas.com/](https://www.sagaesferas.com/) (ES) | [https://en.sagaesferas.com/](https://en.sagaesferas.com/) (EN)
- **Contact & Developer Inquiries:** [taos@sagaesferas.com](mailto:taos@sagaesferas.com)

---

## 🚀 How to Publish on GitHub Pages (Step-by-Step)

Follow these simple steps to make your documentation site live worldwide:

### Step 1: Create a New GitHub Repository
1. Log in to your GitHub account.
2. Click **New Repository** (e.g., `taos-docs` or `taos-game-maker`).
3. Set visibility to **Public**.
4. Do not initialize with a README (this folder already has everything ready).

### Step 2: Push this Folder to GitHub
Open your terminal inside this `taos-docs-site/` folder and run:

```bash
git init
git add .
git commit -m "Initial commit: Taos Game Maker documentation and showcase hub"
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
git push -u origin main
```

### Step 3: Enable GitHub Pages in 30 Seconds
1. In your GitHub repository, navigate to **Settings** (top tab).
2. In the left sidebar, click **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**:
   - **Source:** Select `Deploy from a branch`.
   - **Branch:** Select `main` and folder `/ (root)`.
4. Click **Save**.
5. Wait ~60 seconds. GitHub will display your live site URL:  
   `https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/`

---

## 📁 Repository Structure

```text
taos-docs-site/
├── index.html           # Landing page with video embed, 4 pillars & showcase
├── getting-started.html # Requirements, 3-step setup & studio navigation
├── architecture.html    # 3-tier data pipeline & Godot view subsystem architecture
├── data-formats.html    # Truncated illustrative JSON data schemas (Enemies, Quests, Dialogues)
├── faq.html             # FAQ, commercial rights, royalty-free licensing & exports
├── styles.css           # Premium dark theme stylesheet (zero dependencies)
├── assets/
│   └── img/             # Official promotional artwork, banners and covers
└── README.md            # Deployment guide and repository overview
```

---

## 🛡️ Intellectual Property & Commercial License Notice

© 2026 Taos World. All rights reserved.

The **Taos Game Maker** proprietary source code, Godot 4 scripts (`.gd`), scene files (`.tscn`), resources (`.tres`), and local studio server implementation (`editor/serve.py`) are **NOT** hosted in this public repository. 

This repository exists strictly for public documentation, technical specifications, and product marketing. The complete commercial engine, full project template, and 45+ studio tools are available exclusively via [Gumroad](https://taosworld.gumroad.com/l/TaosGameMaker) and [itch.io](https://taosworld.itch.io/taosgamemaker). All games built with a valid commercial license are 100% royalty-free.
