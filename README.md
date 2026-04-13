# Chen Yue Liu — Academic Personal Website

A personal academic website for Chen Yue Liu, a PhD researcher in energy markets going on the job market. Built with Vue 3 + Vite, deployed to [chenyueliu.com](https://chenyueliu.com) via GitHub Pages.

## Tech Stack

- **Framework:** Vue 3 (Composition API, `<script setup>`)
- **Build tool:** Vite
- **Styling:** Custom CSS (no framework)
- **Deployment:** GitHub Pages via GitHub Actions
- **Domain:** chenyueliu.com

## Site Sections

| Section | Status | Notes |
|---|---|---|
| About / Biography | Placeholder | Needs real photo, name, bio, affiliation, CV link, social links |
| Job Market Paper | Placeholder | Needs real title, abstract, and PDF link |
| Working Papers | Partial | One real title, coauthor names still placeholder |
| Blog | Placeholder | Empty for now, can be filled later |
| Visitors | Live | ClustrMaps map + globe tracking real visitors |
| My Rabbit | Live | Interactive shape voting, backed by GitHub Gist |
| Publications | Hidden | Commented out, ready to enable when needed |
| Work in Progress | Hidden | Commented out, ready to enable when needed |
| Collaborative Research | Hidden | Commented out, ready to enable when needed |

## Features

### Rabbit Voting System
Visitors can vote on the shape of the rabbit (oval / hexagon / rectangle). Votes are stored in a **GitHub Gist** so counts are shared across all visitors and persist permanently — no external database needed.

- Gist ID stored in `.env.local` (gitignored, never pushed)
- For deployment, secrets are passed via GitHub Actions (`VITE_GIST_ID`, `VITE_GIST_TOKEN`)

### Visitor Map (ClustrMaps)
Two ClustrMaps widgets are embedded in the Visitors section:
- **Flat map** — world map with visitor location dots
- **Globe** — interactive 3D globe

Both are injected via `onMounted` (Vue does not execute `<script>` tags in templates directly). They track real visitors on the registered domain `chenyueliu.com`.

## Local Development

```sh
npm install
npm run dev
```

The dev server runs at `http://localhost:5173` (or next available port).

### Environment Variables

Create a `.env.local` file in the project root (this file is gitignored):

```
VITE_GIST_ID=your_gist_id
VITE_GIST_TOKEN=your_github_pat_with_gist_scope
```

## Deployment

Deployment is automatic — push to `main` and GitHub Actions builds and deploys to GitHub Pages.

The workflow is defined in `.github/workflows/deploy.yml`. It requires two repository secrets set in **Settings → Secrets and variables → Actions**:

- `VITE_GIST_ID` — the GitHub Gist ID used for rabbit vote storage
- `VITE_GIST_TOKEN` — a GitHub PAT with `gist` scope only

### Pushing from this machine

This repo belongs to the `yl159-Yiming` GitHub account. Since the default git credential on this machine is a different account, pushes require setting the remote URL with a PAT that has `repo` + `workflow` scope:

```sh
git remote set-url origin https://yl159-Yiming:<TOKEN>@github.com/yl159-Yiming/CYwebsite.git
git push
```

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Vue (Official)](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
