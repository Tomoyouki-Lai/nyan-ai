![Image](https://github.com/user-attachments/assets/351a0f07-69d1-463b-8d6d-fb90e445ee17)
[English](README.md) | [繁中](readmes/README.zh-Hant.md) | [简中](readmes/README.zh-Hans.md)

# 🐾 Nyan AI – AI Assistant Sharing Platform

> Using AI is no longer just your business — it’s for everyone.

**Nyan AI** is an AI assistant sharing platform that combines **anime-style virtual characters** with a **shareable task script system (Nyan Cards)**, built around the idea of **community co-creation**.
Users don’t need to write complicated prompts — simply click on a **Nyan Card** to let AI **“understand, execute, and share” web tasks** with ease.

---

## 🆚 Nyan AI vs. Traditional Web Agents

| Feature                           | 🐌 Traditional Web Agent                            | 🚀 Nyan AI                                                     |
| --------------------------------- | --------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| **Ease of Use**                   | High skill barrier; requires prompt crafting        | Low; prompts are pre-written by contributors                                                   |
| **Cost**                          | High; each run consumes large compute resources     | Low; with task caching & sharing                                                               |
| **Time**                          | Slow; re-analyzes from scratch (5–10 min)           | Fast; reuses shared task scripts (≤30 sec)                                                     |
| **Success Rate**                  | Medium; depends on skill & AI efficiency (\~50–70%) | High; pre-validated by the community                                                           |
| **Virtual Character Interaction** | None                                                | Yes; built-in catgirl interactions for an immersive experience |
| **Sharing**                       | Almost none                                         | Yes; visualized tasks & one-click sharing                                                      |
| **Customization**                 | None                                                | Yes; open-source workflows & character styles                                                  |
| **Reward Mechanism**              | None                                                | Yes — Nyan Card creators can add a “Meow Magic Points” (Meow Points) reward system as needed |
| **User Participation**            | None (B2C tool)                                     | Yes; B2C2C community sharing model                                                             |
| **Marketing Potential**           | None                                                | Yes; viral-friendly with social sharing                                                        |
| **Language Support**              | Primarily English                                   | 16 languages, with localized character voices                                                  |

---

## 🌟 What is a Nyan Agent?

> Your loyal companion, personal butler, and intelligent assistant in the digital world.

The Nyan Agent offers **two operation modes** — *Chat Mode* and *Work Mode* — that you can switch between anytime:

**Chat Mode**:

* Casual conversation, jokes, and fun interactions for a friendly companion experience.
* Proactively offers suggestions or related topics based on your conversation.

**Work Mode**:

* Automatically detects and recommends suitable Nyan Cards, which you can approve to launch instantly.
* Or manually start any Nyan Card (double-click) for full control.

---

## 🎴 What is a Nyan Card?

> More than just a tool — it’s a bridge for **communication, promotion, and co-creation**.

A Nyan Card is a micro AI assistant for customized tasks — visualized and shareable web task scripts to make your workflows smarter and more fun.

### ✨ Key Features

* 🧩 **Drag-and-Drop Builder** — Easily create task flows
* 🧠 **AI Instant Parsing** — Auto-executes tasks to save time
* 🧑‍💻 **Actions-to-Card** — Convert your actions into open-source Nyan Cards
* 🗂 **Multimedia Guidance** — Embed character voices and prompts
* 📤 **Easy Sharing** — Send Nyan Cards to friends or communities

### 📥 How to Get Nyan Cards

1. **From the Official Nyan AI Card Marketplace**
   Drag any card you like from the marketplace onto your Nyan character to save it to your collection.
2. **Import a `.json` Card File Privately**
   Create or exchange `.json` cards privately; drag them onto the Nyan character to load them securely.
   Cards can be shared via DMs, communities, or cloud services.

---

## 💡 Nyan Card Use Cases

> Try, share, and remix our demo Nyan Cards — available in the `template` folder of this repo.

* **Personal Companion** — Emotional interaction, reminders → `cat_girl_template.json`
* **Guidance & Rewards** — Directs users through multi-step tasks with rewards → `guidance_rewards_template.json`
* **Service Introduction** — Customer support, feature walkthroughs → `customer_support_template.json`
* **Product Showcase** — Present features, specs, tutorials → `product_showcase_template.json`
* **Search** — Locate info like places, content, prices → `shopping_search_template.json`
* **Shopping** — Selection, comparison, checkout guidance → *(coming soon...)*
* **Form Filling** — Registration, reservations, surveys → *(coming soon...)*
* **Games** — Interactive challenges and competitions → *(coming soon...)*

…and your ideas!

---

## 🚀 Getting Started

You can install Nyan AI in two ways:

1. **From this GitHub repo (Developer Mode)**

   * Click `Code` → `Download ZIP` and unzip
   * Open Chrome Extensions page (`chrome://extensions/`)
   * Enable *Developer Mode*, then *Load unpacked extension* and select the folder

2. **From the [Chrome Web Store](https://chrome.google.com/webstore/xxx)**

After installation:

* Sign in with your Google account
* Click the Nyan AI icon to open the menu
* Enter your free LLM API key (get one from OpenRouter, Google AI Studio, OpenAI, etc.)
* Switch it ON — a cute catgirl will appear in the bottom-left corner of your screen, ready to assist!

> Make AI cute, intuitive, and shareable!

* 👉 **Chrome Extension**: [Chrome Web Store](https://chrome.google.com/webstore/nyan-ai)
* 👉 **Discord Community**: [Nyan AI Forum](https://discord.gg/S63V44n3)
* 👉 **Official Site**: [https://nyan-ai.app](https://nyan-ai.app)

---

## ⚠️ Chrome Extension & AI Notes

* If idle for too long, reload the page to keep it running smoothly.
* Chrome may block autoplay audio unless you interact with the page first.
* First launch may take longer to prepare.
* Different LLMs have different personalities — the same catgirl may behave differently on different models.

---

## ❓ FAQ

* **Q: Why does the catgirl disappear on a new page?**
  A: Chrome Web Store security policy! If you install from source, she can appear instantly.

* **Q: Can I use it without writing prompts?**
  A: Absolutely! Just use shared Nyan Cards & characters — no prompt writing required.

* **Q: How do I run a Nyan Card?**
  A: Open the menu → double-click the card → watch her get to work!

* **Q: Can I create my own Nyan Cards or characters?**
  A: Yes! Share your creations with the community ❤️

  👉 See [docs/](./docs/) for the full guide.

* **Q: Is my LLM API key safe?**
  A: Yes — it’s stored locally in `chrome.storage.local` and never uploaded to our servers. All LLM requests go directly from your browser to your chosen provider.

---

## 📌 Roadmap

We’re building a smarter, cuter, more autonomous Nyan AI. Key future plans:

### 🤖 AI Capabilities

* **Long-term Memory** — Persistent personality & cross-task memory
* **User Profiling** — Learn preferences to tailor responses & recommendations
* **Advanced Live2D Engine** — More detailed movements, expressions, and TTS sync

### 🎴 Smart Nyan Card Management

* **Smart Search & Install** — Auto-search/install/activate cards (with permission)
* **Scheduled Card Runs** — Daily, weekly, or specific-time automation
* **Multi-Card Chaining** — Run multiple cards in sequence for complex workflows
* **AI Web Automation (Playwright-powered)** — Full browser task automation built into the Nyan Card generator
* **Model Context Protocol (MCP)** — Integrate cards with online services & tools for flexible cross-module execution

### 🔐 Personalization & Web3

* **Catgirl Crypto Wallet** — For signing cards, managing character assets, and future in-app economy (with permission)

---

## 🛠️ Tech Stack & Architecture

Event-driven, modular Chrome extension for *AI Vibe Coding*:

* **Core Interaction**: Live2D + PixiJS for smooth character animations
* **State Management**: `chrome.storage.local` for reactive decoupling
* **NLU**: `nluProcessor.js` for lightweight intent parsing
* **Task Engine**: State-machine workflow execution in `background.js`
* **Backend**: Firebase (Auth, Realtime DB, Storage) — serverless & highly available
* **AI Vibe Coding Philosophy**: Flat file structure for accessibility by non-engineers

---

## 🐾 Developer Guide

* Licensed under [Apache-2.0](./LICENSE)
* Supports custom characters, themes, and workflows
* Contributions welcome — join us in creating Nyan Cards & characters!

---

## 🧠 AI Vibe Coding — Building the Future with AI

We’re not just coding traditionally — we’re **co-creating with AI**.

Whether you are:

* 🤖 Prompt engineer / LLM power user
* ✨ UI/UX designer with big ideas
* 🧑‍💻 JavaScript / front-end dev
* 😺 Catgirl fan & creative spirit

If you love **AI + Web Interaction** or **AI Vibe Coding**, join our Discord and collaborate!

👉 [Join Discord](https://discord.gg/S63V44n3)

---

## 📜 License

This project is licensed under **Apache-2.0**.
Free to use, modify, and share — please retain original attribution.

---

Generative AI is still in its early stages. While powerful, it may produce unexpected or misleading outputs. Always verify results. Do not use for legal, medical, or advisory purposes.
