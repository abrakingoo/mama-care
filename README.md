# Mama Care – download site

A one-page static site for sharing the Mama Care Android APK, hosted on [Render](https://render.com).

## Files

- `index.html` – download page with install instructions
- `mama_care.apk` – the app
- `render.yaml` – Render Blueprint (static site, serves the APK with the right download headers)

## Deploy on Render

1. In Render, choose **New → Blueprint** and pick this repo. Render reads `render.yaml` and creates the static site.
2. Share `https://<your-site>.onrender.com` (the page) or `https://<your-site>.onrender.com/mama_care.apk` (direct download).

## Updating the app

Replace `mama_care.apk` with the new build (same file name, signed with the same key), commit and push. Render redeploys automatically.
