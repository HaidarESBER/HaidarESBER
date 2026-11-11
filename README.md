<p align="center">
  <img src="assets/hero.svg" alt="Haidar Esber. Player 1. Class: full-stack and AI tooling. Guild: EFREI Paris. Mode: alternance. I build systems, and break them." width="900">
</p>

<p align="center">
  <a href="https://haidaresber.github.io"><img src="https://img.shields.io/badge/Portfolio-haidaresber.github.io-2ea44f?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/haidaresber"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.npmjs.com/package/ecobrowser"><img src="https://img.shields.io/npm/v/ecobrowser?style=for-the-badge&logo=npm&label=npm%20ecobrowser&color=cb3837" alt="ecobrowser on npm"></a>
</p>

> 💾 **SAVE-DATA NOTICE.** Most of my repositories are **private** (client work, coursework, infrastructure and security labs). This profile is a small, curated selection of what I can show publicly. I'm happy to walk through private work in a conversation.

<h2 align="center">MAIN MENU</h2>

<table align="center">
  <tr><td>▶ <a href="#quest-log"><b>QUEST LOG</b></a></td><td>what I've built (click a quest to open it)</td></tr>
  <tr><td>▶ <a href="#side-quests"><b>SIDE QUESTS</b></a></td><td>smaller public projects</td></tr>
  <tr><td>▶ <a href="#inventory"><b>INVENTORY</b></a></td><td>the stack I work with</td></tr>
  <tr><td>▶ <a href="#locked-chest"><b>LOCKED CHEST</b></a></td><td>what lives in my private repos</td></tr>
  <tr><td>▶ <a href="#continue"><b>CONTINUE?</b></a></td><td>how to reach me</td></tr>
</table>

---

## Quest log

<sub>Click a quest to expand it. Every quest links to the real repository.</sub>

<details>
<summary>🛒 <b>QUEST 1: nuage-commerce</b> &nbsp;·&nbsp; <i>full-stack e-commerce, live in production</i></summary>

<br>

A French-language store for premium chichas, with a storefront, an admin back office and a pipeline that sources products automatically.

- **Storefront and checkout:** Next.js 16, React 19, TypeScript, Supabase, Stripe
- **Automated sourcing:** scraping, AI curation, review translation and image processing, run by scheduled cron jobs
- **Also:** MDX blog, AI support chatbot, analytics, transactional email, PWA, 435 commits, Vitest tests

🔗 [Repository](https://github.com/HaidarESBER/nuage-commerce) · 🌐 [Live shop](https://chichanuage.com)

</details>

<details>
<summary>🤖 <b>QUEST 2: ai-browser</b> &nbsp;·&nbsp; <i>published on npm as <code>ecobrowser</code></i></summary>

<br>

An AI-native browser framework, "the AI's hands and eyes on the web", shipped as a TypeScript library **and** an MCP server.

- **Structured, no-pixel perception** of pages, with incremental diffs and a live view
- **Verified, self-healing actions:** every action checks its own result, and retries are guarded
- **MCP server with 22 tools** you can add to Claude Code in one line

```bash
npm install ecobrowser
claude mcp add ecobrowser -- npx -y ecobrowser-mcp
```

[![npm](https://img.shields.io/npm/v/ecobrowser?logo=npm&color=cb3837)](https://www.npmjs.com/package/ecobrowser) [![downloads](https://img.shields.io/npm/dm/ecobrowser?logo=npm&color=cb3837)](https://www.npmjs.com/package/ecobrowser)

📦 [**ecobrowser on npm**](https://www.npmjs.com/package/ecobrowser) · 🔗 [Repository](https://github.com/HaidarESBER/ai-browser)

</details>

<details>
<summary>🔍 <b>QUEST 3: privasearch</b> &nbsp;·&nbsp; <i>private AI search, fully self-hosted</i></summary>

<br>

Search that stays on your machine: SearXNG for results, Ollama for the model, and RAG so every answer is **cited**.

- **Stack:** React, Node.js, Docker Compose, SearXNG, Ollama
- **Flow:** results stream in first, then the cited answer streams after them
- **Why:** private by design: a local model, self-hosted search and no third-party AI API

🔗 [Repository](https://github.com/HaidarESBER/privasearch)

</details>

<details>
<summary>🎨 <b>QUEST 4: privasvg</b> &nbsp;·&nbsp; <i>Rust → WebAssembly, 100% in the browser</i></summary>

<br>

Turns raster images into clean SVG without uploading anything.

- **Pipeline:** AI background removal → manual retouch → 2x/4x upscale → vectorize (Rust compiled to WebAssembly)
- **Bulk mode:** convert up to 50 images into one ZIP
- **Privacy:** everything runs client-side

🔗 [Repository](https://github.com/HaidarESBER/privasvg) · 🌐 [Live demo](https://haidaresber.github.io/privasvg/)

</details>

<details>
<summary>📱 <b>QUEST 5: claude-whatsapp-notify</b> &nbsp;·&nbsp; <i>drive Claude Code from your phone</i></summary>

<br>

Approve or deny commands, send prompts and talk to your open Claude Code sessions from WhatsApp.

- **Remote approvals, live sessions, images, files and voice notes** (transcribed locally with Whisper)
- **Guest mode** for group chats: a locked-down Claude with web search only
- **Security model documented:** authenticated local API, rate-limited pairing, and approvals that refuse to hide a long command's tail

🔗 [Repository](https://github.com/HaidarESBER/claude-whatsapp-notify)

</details>

<details>
<summary>📰 <b>QUEST 6: majalpost</b> &nbsp;·&nbsp; <i>Arabic-first, right-to-left news platform</i></summary>

<br>

A news and media platform for Lebanese affairs, built RTL-first.

- **Monorepo:** Next.js frontend, Express/MongoDB REST API, shared TypeScript types
- **Features:** admin dashboard, roles (admin, editor, contributor, user), media uploads, comments, contributor applications
- **CI** on every push

🔗 [Repository](https://github.com/HaidarESBER/majalpost) · 🌐 [Live site](https://majalpost.vercel.app)

</details>

<details>
<summary>🎵 <b>QUEST 7: nowplaying</b> &nbsp;·&nbsp; <i>an always-on screen for what you're listening to</i></summary>

<br>

A Spotify "now playing" display with synced lyrics, installable as a PWA on iPhone and Android. Vanilla JavaScript, no dependencies, with a demo mode that plays sample songs.

🔗 [Repository](https://github.com/HaidarESBER/nowplaying) · 🌐 [Live demo](https://haidaresber.github.io/nowplaying/)

</details>

## Side quests

- 🏋️ [**sports**](https://github.com/HaidarESBER/sports): community workout planner built with Next.js
- 🔬 [**microscope-3d-render**](https://github.com/HaidarESBER/microscope-3d-render): a Blender render presented as an interactive web preview · [demo](https://haidaresber.github.io/microscope-3d-render/)
- 🏠 [**3D room portfolio**](https://haidaresber.github.io): an interactive WebGL portfolio · [source](https://github.com/HaidarESBER/haidaresber.github.io)

## Inventory

|  | Items |
|---|---|
| ⚔️ **Languages** | TypeScript · JavaScript · Rust |
| 🛡️ **Frontend** | React · Next.js · Vite |
| 🧪 **Backend** | Node.js · Express |
| 🗃️ **Data** | Supabase · MongoDB |
| 🐳 **Ops** | Docker · GitHub Actions |
| 🧠 **AI** | MCP · Ollama · Whisper · RAG |

## Locked chest

<details>
<summary>🔒 <b>Open to see what's in my private repositories</b></summary>

<br>

Most of my work isn't public. The private repos contain:

- **Cloud infrastructure** on Azure with Terraform
- **Docker CI/CD pipelines** with PostgreSQL
- **Python** tooling: job-search automation and federated-learning research
- **A Symfony application-security lab**, plus a deliberately vulnerable app for training
- **Websites and web apps built for clients**
- Coursework and group projects from EFREI

Want to see any of it? Ask and I'll walk you through it.

</details>

## Continue?

<details>
<summary>🎮 <b>Enter the cheat code</b> &nbsp;<sub>(↑ ↑ ↓ ↓ ← → ← → B A)</sub></summary>

<br>

Cheat code accepted. Here is how to reach me:

- 🌐 Portfolio: [haidaresber.github.io](https://haidaresber.github.io)
- 💼 LinkedIn: [in/haidaresber](https://www.linkedin.com/in/haidaresber)
- 💻 GitHub: [@HaidarESBER](https://github.com/HaidarESBER)

</details>

<p align="center"><sub>▶ PLAYER 1 · EFREI PARIS · <a href="https://github.com/HaidarESBER?tab=repositories">browse all public repositories</a></sub></p>
