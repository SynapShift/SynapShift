# Hi, I'm SynapShift

**AI Product Manager · Building AI applications and interactive products**

I build AI applications, desktop utilities, and web products, taking ideas through design, implementation, and deployment.

[WorkLog Demo](https://worklog-5gb.pages.dev) · [Projects](#featured-projects) · [Open Source](#open-source-contributions)

## Open Source Contributions

| Project | Change | Pull request | Status |
| --- | --- | --- | --- |
| [daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | Bound market-data calls with timeouts and fallback handling | [#2345](https://github.com/ZhuLinsen/daily_stock_analysis/pull/2345) | Merged |
| [Ollama](https://github.com/ollama/ollama) | Allow empty-state comparison requests for vllm-d3 models | [#19173](https://github.com/ollama/ollama/pull/19173) | Open |
| [mypy](https://github.com/python/mypy) | Prevent dmypy crashes when reusing namespace-package caches | [#22009](https://github.com/python/mypy/pull/22009) | Open |
| [Happy-LLM](https://github.com/datawhalechina/happy-llm) | Clarify feedforward network directionality | [#221](https://github.com/datawhalechina/happy-llm/pull/221) | Open |
| [llm_interview_note](https://github.com/wdndev/llm_interview_note) | Correct the Skip-Gram definition and diagram | [#41](https://github.com/wdndev/llm_interview_note/pull/41) | Open |

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

<p>
  <a href="https://synapshift.github.io/garden-wardens/"><img width="49%" alt="Garden Wardens battle with plant defenders and animated enemies" src="https://raw.githubusercontent.com/SynapShift/garden-wardens/main/assets/gameplay-battle.png"></a>
  <a href="https://synapshift.github.io/garden-wardens/"><img width="49%" alt="Garden Wardens hand-painted garden and start screen" src="https://raw.githubusercontent.com/SynapShift/garden-wardens/main/assets/gameplay-preview.png"></a>
</p>

*Live battle and the hand-painted garden — click either image to play in the browser.*

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

**Product Concepts**

`consumer product thinking` · `mobile-first UX` · `local-first storage` · `image/data management` · `usage insights`

**Stack**

TypeScript, React, Vite, IndexedDB, localStorage, Cloudflare Pages

## Toolkit

**AI & Product** · LLM APIs, prompt design, evaluation, workflow design

**Frontend** · TypeScript, JavaScript, React, Expo Web, Vite

**Desktop** · Electron

**Backend & Deployment** · Python, Node.js, Cloudflare Pages, Pages Functions, D1
