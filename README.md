# Scalable Static Website Deployment with S3 + Cloudflare + GitHub Actions

This project demonstrates how to host and auto-deploy a static website using:

- **Amazon S3 (Free Tier)** for storage and static website hosting
- **Cloudflare (Free)** for HTTPS and global CDN
- **GitHub Actions** for continuous deployment on every commit

## 🔧 Tools Used

- HTML / CSS / JS (Static Website)
- AWS S3
- Cloudflare
- GitHub Actions

## 📁 Folder Structure

/ (root) ├── index.html ├── styles.css ├── script.js └── .github/workflows/deploy.yml


## 🚀 How It Works

- Website code is pushed to GitHub.
- GitHub Actions workflow (`deploy.yml`) syncs the contents to the S3 bucket.
- Cloudflare is used for SSL and CDN, connected to a custom domain (optional).
- Any change to the `main` branch triggers automatic deployment.

## 🔗 Live Website

[Click here to view the site](https://www.ajelectronics.site/)
