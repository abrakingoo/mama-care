# Mama Care – download site

A one-page static site for sharing the Mama Care Android APK, hosted on [Render](https://render.com).

## Files

- `index.html` – download page with install instructions
- `mama_care.apk` – the app (local only, git-ignored; published as a GitHub Release asset)
- `render.yaml` – Render Blueprint (static site, static site)

## Deploy on Render

1. In Render, choose **New → Blueprint** and pick this repo. Render reads `render.yaml` and creates the static site.
2. Share `https://<your-site>.onrender.com`. The download button links to the latest GitHub Release.

## Updating the app

Create a new GitHub Release and attach the new build as `mama_care.apk` (same file name, signed with the same key). The site's link always points to the latest release, so no redeploy is needed.
