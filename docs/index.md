# CGDD — Learn Hub

Welcome! This is the **central place** for my AI & Data Science content:
clean, reproducible, and focused on real-world practice.

> ✅ Goal for today: put this page online at **https://learn.cgdd.ai**.  
> Later, we’ll add sections (Roadmap, Projects, Templates) one by one.

---

## Quick start

??? tip "1) Preview locally"
    ```bash
    conda activate cgdd-hub
    mkdocs serve
    ```
    Open **http://127.0.0.1:8000** — if you see this page, you’re good.

??? tip "2) Publish with GitHub Pages (free + HTTPS)"
    ```bash
    git init
    git add .
    git commit -m "init site"
    git branch -M main
    git remote add origin https://github.com/YOUR-GITHUB-USERNAME/learn-hub.git
    git push -u origin main

    mkdocs gh-deploy --force
    ```
    Test the provisional URL:  
    `https://YOUR-GITHUB-USERNAME.github.io/learn-hub/`

??? tip "3) Point your subdomain (DNS)"
    In your domain’s DNS (cgdd.ai), create a **CNAME**:

    - **Host/Name:** `learn`  
    - **Target/Value:** `YOUR-GITHUB-USERNAME.github.io`  
    - **TTL:** automatic

    > Subdomains are free. Avoid duplicate records for `learn`.

??? tip "4) Custom domain + HTTPS in GitHub"
    In **GitHub → Settings → Pages** of your repo:

    - **Custom domain:** `learn.cgdd.ai` → **Save**  
    - Enable **Enforce HTTPS** once available

---

## What you’ll find here (soon)

- **Roadmap** — A practical path from Foundations → Modeling → Validation → Deployment.  
- **Projects** — Reproducible case studies with notebooks and clear metrics.  
- **Core Guides** — Metrics (RMSE/MAE), validation, regularization, leakage.  
- **Templates** — Checklists, model/data cards, and notebook skeletons.  

We’ll add these sections gradually so you can follow the structure as it grows.

---

## Add your first new page (when ready)

1. Create a file: `docs/roadmap.md`
   ```md
   # Roadmap
   Start here. Foundations → Modeling → Validation → Deployment.
