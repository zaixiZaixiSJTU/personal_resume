# Resume

> **Target roles:** AI application development / backend development / full-stack development internships  
> **GitHub:** [github.com/zaixiZaixiSJTU](https://github.com/zaixiZaixiSJTU)  
> Contact details and honors appear in the one-page PDF.

---

## Education

**Lei Chen** | Mechanical and Power Engineering, Shanghai Jiao Tong University | Class of 2024, expected 2028  
Relevant coursework: C++ Programming, Data Structures | CET-6: 488

---

## Technical Skills

| Category | Skills |
|----------|--------|
| **Languages** | Python, TypeScript, JavaScript, Rust, C# |
| **Backend & protocols** | FastAPI, asyncio, aiohttp, WebSocket, REST APIs, Nakama TypeScript Runtime, JSON Schema |
| **Frontend & clients** | React, Next.js, Tailwind CSS, Chakra UI, Unity 6, Tauri v2 |
| **AI applications** | LLM integration and per-agent model configuration, structured output, agent behavior design, prompt design |
| **Engineering** | Git, GitHub Actions, npm, ESLint, automated tests, technical writing, internationalization |

---

## Projects

### SJMCL — Minecraft Launcher Development

> *Open-source contributor | TypeScript, Next.js, Chakra UI, Tauri v2 | 2025–present*  
> [Upstream repository](https://github.com/UNIkeEN/SJMCL)

Contribute to a cross-platform Minecraft launcher, with work focused on content discovery, desktop integration, and clearer failure feedback.

- **Discover:** Contributed to the Discover experience and added community news sources and display behavior upstream ([PR #2031](https://github.com/UNIkeEN/SJMCL/pull/2031)).
- **Desktop integration:** Added operating-system file association for quick `.mrpack` import ([PR #1824](https://github.com/UNIkeEN/SJMCL/pull/1824)); contributed Markdown table rendering for extensions ([PR #1649](https://github.com/UNIkeEN/SJMCL/pull/1649)).
- **Error handling:** Improved Microsoft sign-in XSTS error messages so users can identify the failure more easily ([PR #1571](https://github.com/UNIkeEN/SJMCL/pull/1571)).

---

### astrbot_plugin_autoissue — Chat-to-GitHub Issue Plugin

> *Personal open-source project | Python, AstrBot, LLMs, GitHub API | 2026*  
> [Repository](https://github.com/zaixiZaixiSJTU/astrbot_plugin_autoissue)

Turns group-chat discussions into trackable GitHub Issues, reducing manual copying, summarization, and triage.

- **Message pipeline:** Extracts quoted and nested forwarded conversations, uses an LLM to produce a structured title and body, creates the Issue, and returns its link.
- **Per-group configuration:** Lets each chat group bind a different repository, with persistent settings and administrator commands.
- **Repository context:** Builds a knowledge cache from the target repository's README to give the LLM project context when drafting an Issue.

---

### MindWolf — AI Werewolf Game Prototype

> *Personal project | Python, FastAPI, WebSocket, React, TypeScript | 2026*  
> [Repository](https://github.com/zaixiZaixiSJTU/MindWolf)

An LLM-agent experiment built around a 12-player Werewolf game, using game state, role information, and model settings to generate player actions.

- **Agent model:** Maintains role information and belief-update logic for individual players, with eight deception-strategy prompts for speech and decisions.
- **Full-stack delivery:** Streams game events from a FastAPI backend over WebSocket to a React/TypeScript spectator interface with per-player model configuration.
- **Observability:** Records game events and model interactions for replay and future strategy experiments.

---

### Minecraft: Biome Rivals — Biome-Themed Card Game Prototype

> *Personal game prototype | Unity 6, C#, Nakama, TypeScript, JSON Schema | 2026*  
> [Repository](https://github.com/zaixiZaixiSJTU/mc_biome_rivals)

A Minecraft-biome-themed card battle project with a Unity client, a Nakama server-side rules core, and a shared protocol.

- **Authoritative rules:** Clients submit commands while the server resolves turns, deployment, combat, events, and snapshots; JSON Schema defines the client-server contract.
- **Testable prototype:** Built an offline playable demo, rule tests, and Unity EditMode validation. Gameplay rules, presentation, and network transport are separated for further development.

---

### astrbot_plugin_bugua — Plum Blossom I Ching and LLM Plugin

> *Personal open-source project | Python, borax, LLMs | 2026*  
> [Repository](https://github.com/zaixiZaixiSJTU/astrbot_plugin_bugua)

- Derives primary, mutual, and changed hexagrams from lunar time and user/topic inputs, then computes a base interpretation using Five Elements relationships.
- Can call AstrBot's LLM for a topic-specific written interpretation and shows the derivation so users can check the calculation.

---

### PubMedsoso-gui — PubMed Literature Search Desktop Tool

> *Fork extension | Python, tkinter, asyncio, aiohttp, SQLite | 2026*  
> [Repository](https://github.com/zaixiZaixiSJTU/PubMedsoso-gui)

- Added a tkinter GUI to the original command-line tool with parameter entry, live logs, and file selection.
- Improved PDF download interaction while retaining the upstream tool's asynchronous search, Excel export, and SQLite history features.

---

## Open Source and Additional Information

- Maintain the [awesome-SJMCL-extensions](https://github.com/zaixiZaixiSJTU/awesome-SJMCL-extensions) catalog and its multilingual documentation.
- Read and write technical documentation in Chinese and English; familiar with Issues, pull requests, code review, and open-source collaboration.
- Zhiyuan Scholarship; First Prize in the “Jiaoyan” campus project; member of the SJTU Minecraft Club.

---

> **Application note:** For AI application roles, feature AutoIssue and MindWolf. For client or game roles, give more space to SJMCL and Biome Rivals. The one-page version keeps the four strongest engineering examples.
