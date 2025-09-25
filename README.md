# Unity Medical Transportation — GitHub Pages Starter

This repo is prepped to deploy with **GitHub Pages**.

## Quick Deploy
1. Create a new repo on GitHub (e.g., `unitymt-website`), **Public**.
2. Upload these files (or push via Git) so `index.html` sits in the root of the repo's **main** branch.
3. In the repo: **Settings → Pages → Build and deployment → Source: `Deploy from a branch`**  
   - Branch: `main`  
   - Folder: `/root`  
4. Wait ~1 minute and open the Pages URL it shows (something like `https://USERNAME.github.io/unitymt-website/`).

## Custom Domain (www.unitymt.com)
- In **Settings → Pages → Custom domain**, enter `www.unitymt.com` and save. This will create a `CNAME` file (already included here).  
- In your DNS provider, set a **CNAME** record:  
  - **Host/Name:** `www`  
  - **Value/Target:** `USERNAME.github.io.` (replace USERNAME with your GitHub username)
- Optional: At your DNS provider, set the root domain `unitymt.com` to **redirect** to `www.unitymt.com` (most registrars offer URL forwarding).

> Tip: Using `www` avoids managing GitHub Pages A records for apex domains.

## Editing / Tweaks
- Edit files directly on GitHub (press `.` to open the web editor), or
- Use **GitHub Desktop** for easy drag‑and‑drop updates and commits, or
- Use **Codespaces** for full in‑browser dev.

## Local Preview (optional)
You can simply open `index.html` in your browser. No build step needed.

---
Generated: 2025-09-25 18:25:59
