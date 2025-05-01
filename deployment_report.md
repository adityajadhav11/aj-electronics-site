# Scalable Static Website with S3 + GitHub Actions (No Custom Domain)

## 📌 Project Objective

Deploy a static website to AWS S3 using GitHub Actions for automated deployment — without using a custom domain. The site is hosted on the AWS Free Tier and is publicly accessible.

## 🛠️ Tools Used

- **AWS S3 (Free Tier)** – Static website hosting
- **GitHub Actions** – CI/CD workflow to auto-deploy on push
- **HTML, CSS, JavaScript** – For the static site content

## 🌐 Live Website

[http://aj-electronics.s3-website-us-east-1.amazonaws.com](http://aj-electronics.s3-website-us-east-1.amazonaws.com)

## ⚙️ GitHub Actions CI/CD Workflow

A GitHub Actions workflow is set up to automatically deploy the site to the S3 bucket whenever changes are pushed to the main branch.

File: `.github/workflows/deploy.yml`

## 📁 Folder Structure

/ ├── index.html ├── styles.css ├── script.js ├── .github/ │ └── workflows/ │ └── deploy.yml └── README.md


## ✅ Status

- [x] Static website created
- [x] GitHub repo initialized and pushed
- [x] GitHub Actions workflow set up
- [x] Website deployed to AWS S3
- [x] Verified live website (HTTP only, no custom domain)

## 🖼 Screenshot

See `deployment_screenshot.png` for a proof of deployment.

## 📅 Deployment Date

May 1, 2025
