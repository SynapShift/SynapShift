# Hi, I'm SynapShift

**AI Product Manager · Building AI-native products and original interactive experiences**

`LLM` · `Agent` · `Memory` · `Evaluation` · `Product Prototyping` · `Creative Coding`

I turn real-world problems and playful ideas into working products. My work spans AI workflows, context and memory design, evaluation, privacy-aware experiences, and original interactive prototypes.

## Featured Projects

### WorkLog

**AI-powered work memory and reflection system**

WorkLog turns fragmented daily notes into structured work records, project progress, risks, reviews, reports, and career evidence.

[Live Demo](https://worklog-5gb.pages.dev) · [GitHub Repo](https://github.com/SynapShift/worklog)

**What it does**

- Structures daily work, todos, risks, notes, life records, goals, ideas, and reports.
- Generates AI reviews for daily records, weekly progress, projects, and reports.
- Aggregates records into project dashboards with progress, risks, follow-ups, and archived states.
- Supports weekly reports, project reviews, stage summaries, and custom reporting periods.
- Keeps model API keys local while allowing optional Cloudflare D1 sync for user records.

**AI / Product Concepts**

`AI review` · `work memory` · `structured records` · `report generation` · `multi-model support` · `local-first UX` · `privacy boundary`

**Stack**

React Native Web / Expo, JavaScript, Cloudflare Pages Functions, D1, PWA

---

### Garden Wardens

**An original hand-painted garden defense game for the web**

[Play Online](https://synapshift.github.io/garden-wardens/) · [GitHub Repo](https://github.com/SynapShift/garden-wardens)

Garden Wardens is a five-lane tower-defense experiment built around a living garden, day-and-night strategy, changing weather, plant fusion, automation tools, and animated enemies.

**What it explores**

- Combines hand-painted art direction with responsive WebGL gameplay.
- Uses plant fusion, energy automation, mystery rewards, and global upgrades to create strategy beyond straightforward placement.
- Treats motion, combat feedback, onboarding, difficulty, and desktop usability as product-design problems—not just implementation details.
- Ships as an open-source browser game with a playable GitHub Pages build.

**Product / Game Concepts**

`game UX` · `systems design` · `progressive onboarding` · `feedback & animation` · `difficulty balancing` · `open-source iteration`

**Stack**

JavaScript, Phaser, WebGL, Vite, GitHub Pages

---

### Tonicue

**A cross-platform desktop break reminder for screen-heavy work**

[GitHub Repo](https://github.com/SynapShift/screen-break-reminder)

Tonicue runs quietly in the background, distinguishes active work from idle, lock, and sleep states, and delivers small always-on-top reminders without interrupting the user's flow.

**What it demonstrates**

- Windows tray and macOS menu-bar background behavior.
- Active screen-time tracking with idle, lock, and sleep handling.
- Guided rest flows, snooze and focus modes, local statistics, and local-only settings.
- Installable preview builds for Windows and macOS Apple Silicon.

**Stack**

Electron, JavaScript, HTML, CSS, electron-builder

---

### English Reader

**Personal learning product for focused English reading**

English Reader is a responsive web reader for reading English books page by page, looking up words inline, and collecting vocabulary cards.

[Live Demo](https://english-reader-public-demo.pages.dev/) · [GitHub Repo](https://github.com/SynapShift/english-reader)

**What it does**

- Provides page-by-page reading across mobile and desktop.
- Lets readers tap words for inline lookup without breaking the reading flow.
- Collects vocabulary cards with examples for later review.
- Supports browser-local PDF, TXT, and Markdown import.
- Keeps the public frontend separate from private account, sync, upload, and dictionary services.

**Product Concepts**

`learning workflow` · `reader UX` · `vocabulary capture` · `local file import` · `public/private boundary`

**Stack**

TypeScript, React, Vite, pdf.js, Cloudflare Pages

---

### My Wardrobe

**Mobile-first digital wardrobe and outfit tracking app**

My Wardrobe is a personal consumer product for organizing clothes, creating outfits, recording wear history, and understanding wardrobe usage.

[Live Demo](https://my-wardrobe-5l1.pages.dev) · [GitHub Repo](https://github.com/SynapShift/my-wardrobe)

**What it does**

- Manages clothes with photos, categories, seasons, colors, tags, brands, sizes, price, and notes.
- Creates outfit combinations and connects outfits back to individual clothing items.
- Records daily wear history and shows usage, recent wear, cost per wear, and wardrobe insights.
- Stores data locally by default with JSON, CSV, and image export paths.
- Includes an optional Cloudflare D1/R2/Pages Functions architecture for future cloud sync.

**Product Concepts**

`consumer product thinking` · `mobile-first UX` · `local-first storage` · `image/data management` · `usage insights`

**Stack**

TypeScript, React, Vite, IndexedDB, localStorage, Cloudflare architecture

## AI Product Focus

| Area | What I'm exploring |
| --- | --- |
| Agents | Tool use, workflows, agent UX, and human handoff points |
| Memory | Short-term and long-term memory, retrieval, user control, and deletion/correction flows |
| Evaluation | Prompt/model comparison, regression checks, quality criteria, and product reliability |
| Context | Context construction, information prioritization, and task-specific compression |
| FinTech AI | AI-native financial product experiences with compliance, risk, and trust boundaries |
| Product Systems | From user problem discovery to prototype, architecture, launch, and iteration loops |

## Currently Building

- **Building**: WorkLog AI capability upgrades around memory, review quality, and evidence generation.
- **Shipping**: Garden Wardens gameplay, animation, difficulty, and visual-feedback improvements through rapid playtest-driven iteration.
- **Exploring**: AI Prompt / Skill / Eval Studio for comparing prompts, models, and workflow outputs.
- **Planned**: Agent Memory Lab for experimenting with user-visible memory, retrieval, and correction.

## Currently Learning

- LLM fundamentals and Transformer/GPT internals
- Agent systems, tool use, and context engineering
- LLM evaluation and reliability practices
- PyTorch fundamentals for understanding model behavior more deeply

## Toolkit

**Product & AI**

LLM APIs, prompt engineering, AI evaluation, agent workflows, memory UX, privacy boundaries

**Build**

TypeScript, React, JavaScript, Python, Node.js, Vite, Expo Web

**Infra**

Cloudflare Pages, Pages Functions, D1, R2 architecture, IndexedDB, localStorage, local-first product design

## Project Map

| Category | Repositories | Portfolio role |
| --- | --- | --- |
| Flagship Products | [worklog](https://github.com/SynapShift/worklog) | Main AI product portfolio project |
| Product Experiments | [garden-wardens](https://github.com/SynapShift/garden-wardens), [screen-break-reminder](https://github.com/SynapShift/screen-break-reminder), [english-reader](https://github.com/SynapShift/english-reader), [my-wardrobe](https://github.com/SynapShift/my-wardrobe), [AI-Sentiment-Analysis-Display](https://github.com/SynapShift/AI-Sentiment-Analysis-Display) | Original products, games, and prototypes, ordered by portfolio signal |
| Learning / Research | [AI-Monthly-Insights](https://github.com/SynapShift/AI-Monthly-Insights) | AI industry tracking and learning-oriented tooling |
| Forks / References | `dify`, `happy-llm`, `self-llm`, `llm_interview_note`, `daily_stock_analysis`, `freeCodeCamp`, `LlamaIndex-Tutorials`, `newspaper` | References and study materials, not presented as original products |

## How I Build

I care about products that make AI useful in real workflows: clear user problems, explicit data boundaries, working prototypes, measurable quality, and interfaces that help people understand and control AI behavior.
