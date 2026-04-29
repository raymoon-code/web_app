# Moonray Landing Page

This repository contains the static HTML files for the **Moonray** landing page and legal documents. It is designed to be deployed using **Dokploy**.

## 🌐 Live URLs
- **Main Website:** [https://moonray.store](https://moonray.store)
- **Terms of Service:** [https://moonray.store/term](https://moonray.store/term)
- **Privacy Policy:** [https://moonray.store/privacy](https://moonray.store/privacy)

## 📁 Project Structure
The project uses a folder-based structure to ensure "pretty URLs" (clean paths without the `.html` extension):

- `index.html`: The main landing page.
- `/term/index.html`: Terms of Service content (accessible via `/term`).
- `/privacy/index.html`: Privacy Policy content (accessible via `/privacy`).

## 🚀 Deployment Guide
This project is hosted as a **Static Application** on Dokploy:

1. **Build Type:** Set to `Static`.
2. **Repository:** Connected to this GitHub repo.
3. **Container Port:** `80`.
4. **Domain Configuration:** Pointed to `www.moonray.store` with a path of `/`.

## 🛠 Maintenance
To update the website, simply commit and push your changes to the `main` branch. If **Auto Deploy** is enabled in Dokploy, the changes will reflect live within a few moments.

---
*Maintained by Raymoon Code*
