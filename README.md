# Rip Aero — External Website

Source for the public website of Rip Aero, Inc.: **https://ripaero.space**

## How it works

- This is a **static site** (HTML/CSS/JS only, no server or database).
- It is hosted for free on **GitHub Pages**. Every commit to the `main` branch is published automatically, usually within 1–2 minutes.
- The domain `ripaero.space` is registered at Squarespace, and its DNS points to GitHub Pages.

## Files

| File | What it is |
|---|---|
| `index.html` | The homepage (currently the "Coming Soon" page with the rocket rip animation) |
| `CNAME` | Tells GitHub Pages to serve this site at `ripaero.space`. **Do not delete or edit it.** |
| `README.md` | This file. It is not shown on the website. |

## How to make a change

1. Click the file you want to change (e.g. `index.html`), then the ✏️ pencil icon.
2. Edit and click **Commit changes**. Write a short message describing what you changed.
3. Check the **Actions** tab. A green check means the change is live.
4. Open https://ripaero.space and hard-refresh (Ctrl/Cmd + Shift + R) to see it.

For bigger changes, commit to a new branch and open a pull request so another owner can review it before it goes live.

## Rules

- **Everything in this repo is public.** Never commit confidential material (equity, financials, technical data, passwords, API keys).
- Don't change the DNS records in Squarespace without checking with the team. The MX/TXT records there run company email (Google Workspace).
- Internal material goes on the internal Google Site, not here.
