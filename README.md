# 🎂 Birthday Website

A surprise birthday website. Push to GitHub and enable GitHub Pages to host for free.

## How to deploy

1. Create a new **public** repo on GitHub (e.g. `happy-birthday`)
2. Push this folder:
```bash
cd birthday-site
git init
git add .
git commit -m "happy birthday 🎉"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/happy-birthday.git
git push -u origin main
```
3. Go to repo → **Settings → Pages → Source: main branch / root** → Save
4. Your site will be live at `https://YOUR_USERNAME.github.io/happy-birthday/`
5. Generate a QR code for that URL at [qr-code-generator.com](https://www.qr-code-generator.com)
