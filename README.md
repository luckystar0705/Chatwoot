# Chatwoot

<img src="./.github/screenshots/header.png#gh-light-mode-only" width="100%" alt="Chatwoot header (light)"/>
<img src="./.github/screenshots/header-dark.png#gh-dark-mode-only" width="100%" alt="Chatwoot header (dark)"/>

---

**Chatwoot** is a modern, open-source customer support platform — a self-hosted alternative to Intercom, Zendesk, and Salesforce Service Cloud.

<p>
  <a href="https://codeclimate.com/github/chatwoot/chatwoot/maintainability"><img src="https://api.codeclimate.com/v1/badges/e6e3f66332c91e5a4c0c/maintainability" alt="Maintainability"></a>
  <img src="https://img.shields.io/circleci/build/github/chatwoot/chatwoot" alt="CircleCI Build">
  <a href="https://hub.docker.com/r/chatwoot/chatwoot/"><img src="https://img.shields.io/docker/pulls/chatwoot/chatwoot" alt="Docker pulls"></a>
  <img src="https://img.shields.io/github/commit-activity/m/chatwoot/chatwoot" alt="Commits per month">
  <a href="https://chatwoot.crowdin.com/chatwoot"><img src="https://badges.crowdin.net/e/37ced7eba411064bd792feb3b7a28b16/localized.svg" alt="Crowdin"></a>
  <a href="https://discord.gg/cJXdrwS"><img src="https://img.shields.io/discord/647412545203994635" alt="Discord"></a>
  <a href="https://status.chatwoot.com"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchatwoot%2Fstatus%2Fmaster%2Fapi%2Fchatwoot%2Fuptime.json" alt="Uptime"></a>
</p>

---

## Quick demo

<img src="./.github/screenshots/dashboard.png#gh-light-mode-only" width="100%" alt="Chatwoot dashboard (light)"/>
<img src="./.github/screenshots/dashboard-dark.png#gh-dark-mode-only" width="100%" alt="Chatwoot dashboard (dark)"/>

---

## Key features

### Core
- Omnichannel inbox: website live chat, email, Facebook, Instagram, Twitter, WhatsApp, Telegram, Line, SMS.
- Help Center: publish articles, FAQs, and guides.
- Reporting & analytics: conversation logs, agent metrics, CSAT, downloadable reports.

### Productivity & collaboration
- Private notes, mentions, labels, canned responses.
- Auto-assignment, business hours, auto-responders.
- Keyboard shortcuts, command bar, custom views and filters.
- Agent capacity management, teams, and automation rules.

### Integrations
- Lucid ORM and dashboard apps (embed internal tools).
- Slack, Dialogflow, Shopify, Google Translate, Linear.
- Webhooks and developer-friendly APIs.

### Enterprise & extensibility
- Captain — AI assistant for automated replies and summarization. Read more: https://chwt.app/captain-docs
- Multi-language support, custom attributes, and role-based access.
- Deploy options: Docker, Heroku one-click, DigitalOcean Kubernetes, and more.

---

## How it works (example flow)
1. Sales managers sign up on the web portal and create organizations.
2. Managers invite agents via email.
3. Agents record and upload audio; recordings are transcribed and analyzed (AssemblyAI + langgraph.js).
4. Managers view aggregated analysis and historical reports in the dashboard.

---

## Background & target use-cases
Chatwoot is built for teams that require full control of customer data, want to integrate AI for support workflows, and prefer a self-hosted, extensible platform.

---

## Documentation & translation
- Full docs: https://chatwoot.com/help-center  
- Translation: https://translate.chatwoot.com — read the translation guide at https://www.chatwoot.com/docs/contributing/translating-chatwoot-to-your-language

---

## Deployment

### Heroku (one-click)
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/chatwoot/chatwoot/tree/master)  
See environment variables: https://www.chatwoot.com/docs/environment-variables

### DigitalOcean (Kubernetes)
<a href="https://marketplace.digitalocean.com/apps/chatwoot?refcode=f2238426a2a8"><img src="https://www.deploytodo.com/do-btn-blue.svg" alt="Deploy to DigitalOcean" width="200"></a>

For other deployment methods, visit: https://chatwoot.com/deploy

---

## Security
Report vulnerabilities via the repository's `SECURITY.md`. See `./SECURITY.md` for details.

---

## Contributing & community
Join us on Discord: https://discord.gg/cJXdrwS. Contributors and sponsors are listed at https://www.chatwoot.com/docs/contributors.

---

## License
Chatwoot © 2017–2025, Chatwoot Inc — MIT License.

