<div align="center">

# MERIDIAN FAMILY

### Five standalone Android apps. One connected offline-first suite.

**Local AI · Termux engineering · device operations · shared knowledge**

[![Android](https://img.shields.io/badge/Android-11%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![Offline first](https://img.shields.io/badge/offline--first-by_design-6046D8?style=for-the-badge)](https://github.com/kukirin-ui/meridian-showcase)
[![Termux](https://img.shields.io/badge/Termux-integrated-111111?style=for-the-badge&logo=gnubash&logoColor=white)](https://termux.dev/)
[![Current](https://img.shields.io/badge/latest-release-2.6.54--beta-blue?style=for-the-badge)](https://github.com/kukirin-ui/meridian-releases/releases/latest)

[**Download latest release**](https://github.com/kukirin-ui/meridian-releases/releases/latest) · [Showcase](https://github.com/kukirin-ui/meridian-showcase) · [Website](https://kukirin-ui.github.io/meridian-site/) · [Complete feature catalog](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/FEATURE-CATALOG.md)

</div>

---

## What is Meridian?

Meridian is a family of five Android applications designed to work independently or as one connected environment. Each app has a defined responsibility; Meridian Core provides shared services, typed communication and durable knowledge.

| App | Purpose | Latest APK |
|---|---|---|
| **Meridian Core** | ADB pairing/elevation bridge, family hub, shared data and Core-owned knowledge | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-core.apk) |
| **Meridian Chat** | Local GGUF models, optional BYOK providers, projects, memory, prompts, skills and recipes | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-chat.apk) |
| **Meridian Gaming** | Hardware telemetry, game profiles, task isolation, tuning and model benchmarks | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-gaming.apk) |
| **Meridian Parallel** | Termux console, files, plans, build tools, Doctor, Diagnose, Debugger, CodeGen and Sandbox | [Download](https://github.com/kukirin-ui/meridian-releases/latest/download/meridian-parallel.apk) |
| **NullCloud** | Read links, PDFs and text; summarize, extract, translate, check claims and save reads | [Download](https://github.com/kukirin-ui/meridian-releases/latest/download/meridian-nullcloud.apk) |

**Install Core first** for the connected family experience. The other four apps can also be used independently; some functions require Core, Termux, Termux:API, ADB pairing, device permissions or a configured model.

## See the apps

Real interface captures from the Meridian website. These show the product UI, not promotional mockups.

| Chat and Core | Gaming and Parallel |
|---|---|
| ![Chat home](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/chat-home.webp) | ![Gaming dashboard](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/gaming-dashboard.webp) |
| [Chat home](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/chat-home.webp) · [Core connected](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/core-connected.webp) · [Core pairing](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/core-pair.webp) | [Gaming tuning](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/gaming-advanced.webp) · [Parallel diagnosis](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/parallel-findings.webp) · [Verified repair](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/parallel-verified.webp) |

| NullCloud |
|---|
| ![NullCloud source reading](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/nullcloud-source.webp) |
| [Source reading](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/nullcloud-source.webp) · [Summary](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/nullcloud-summary.webp) · [Knowledge extraction](https://raw.githubusercontent.com/kukirin-ui/meridian-site/main/img/explore/nullcloud-facts.webp) |

[Explore the complete five-app showcase and feature catalog](https://github.com/kukirin-ui/meridian-showcase) · [Open the live website](https://kukirin-ui.github.io/meridian-site/)

---

## Quick install
1. Download the APKs you want from the latest release.
2. Install **Meridian Core** first.
3. Install Chat, Gaming, Parallel and NullCloud as needed.
4. Open Core and follow the Wireless debugging pairing guide if you need shell-level family actions.
5. Open Parallel and complete Termux connection setup for terminal, file, package and job features.
6. Verify downloads against the release's SHA256SUMS.txt.

**Requirement:** Android 11 or newer is the documented minimum. Device-specific features depend on OS, vendor firmware and permissions.

## What is inside

### Core — family hub and knowledge authority
- Wireless debugging pairing and shell-user helper on loopback, protected by a one-time token.
- Bound-service bridge for family apps; shared content provider and preferences.
- App check-ins, targeted command/result channels, event log and long-running work state.
- Typed, owner-scoped data ports with schema validation.
- Core-owned cards, lessons and shared knowledge.
- Deterministic model-free retrieval; multiple distinct successful solutions remain available.
- ICM context/method indexing; model output cannot promote itself to proven knowledge.

### Chat — local and online intelligence
- Local GGUF discovery/import/download, llama.cpp server connection and per-model settings.
- CPU, Vulkan GPU and split execution options; threads, affinity, context, GPU layers, batch, micro-batch, max reply, Flash Attention and KV-cache controls.
- Optional model mesh and Fixer / Helper / Judge roles.
- Optional BYOK providers, user model IDs/API keys, multiple seats, step/cost controls and privacy toggles.
- Projects, chat memory, instructions, prompts, attachments and Termux file access.
- Skill trees, skill cards, lessons, recipes, shared library and web search with citations.

### Gaming — device and performance workspace
- Battery, memory, CPU, GPU, hardware and system views.
- Live monitoring and shareable hardware reports.
- Security/network posture and device-care surfaces.
- Game detection, profiles, optional auto-add and watch mode.
- Task isolation with keep-lists and optional Samsung/Google extras handling.
- Heat-stop and advanced tuning controls where supported.
- llama.cpp benchmark controls for CPU/GPU/split backend, threads, affinity, layers, Flash Attention, KV cache, prompt/generation length, batch, repeats and history.

### Parallel — Termux workstation
- Console, command execution, sessions and long-running job state.
- File browser and project/file/folder operations.
- Searchable plan and command library.
- Build recipes and language/tool support for JavaScript/Node, Rust, Go, Ruby, PHP, Lua, Java, C/C++ and shell utilities.
- Package manager, compilers, Git, editors, file utilities and runtime/service recipes.
- Optional BYOK API configuration and user-defined scheduler.
- Meridian Doctor, Diagnose, fix recipes and source debugger.
- Multi-file CodeGen with file contracts, budget checks, Sandbox tests and repair workflow.
- Debian/Ubuntu via proot-distro, SSH/remote shell and local llama-server tooling.

### NullCloud — reading and research
- Web links, PDFs and pasted text.
- Summary, bullets, key points, facts, recipes, how-to steps, claim checks, simplification and translation.
- Follow-up questions and local reading library.
- Reuse Chat's model or configure a standalone local model.

## Privacy, signing and integrity
- Local inference is the default path; online providers are optional and require the user's own key and explicit enablement.
- All five APKs in a family release use the same certificate so Android can update installed packages consistently.
- Release tooling verifies each APK signature against the pinned SHA-256 certificate fingerprint before publication.
- Every release includes SHA256SUMS.txt.
- The private signing key and password remain with the owner and are not uploaded to GitHub.
- Core elevation is Android shell-user access through Wireless debugging, not root.
- Public issues are visible; never include passwords, API keys, tokens or private logs.

### Public family certificate fingerprint
SHA-256 18:58:EA:52:80:F2:7D:41:68:1B:73:DC:32:D7:AF:CD:69:39:21:DE:E2:97:B8:A3:8B:23:98:89:10:95:FA:B7

Always verify the APK and checksum against the release you are installing.

## Documentation and support
- [Complete implemented feature catalog](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/FEATURE-CATALOG.md)
- [System architecture](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/ARCHITECTURE.md)
- [Benchmarks and device measurements](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/BENCHMARKS.md)
- [Install and release procedure](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/INSTALL-AND-RELEASE.md)
- [Validation and boundaries](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/VALIDATION-AND-BOUNDARIES.md)
- [Public website](https://kukirin-ui.github.io/meridian-site/)
- [Report a problem](https://github.com/kukirin-ui/meridian-releases/issues)

Use **Report a problem** in an app's Settings to prepare an app/version/device report for review before sending.

## Project repositories
| Repository | Purpose |
|---|---|
| [Clean-Meridian](https://github.com/kukirin-ui/Clean-Meridian) | Private source, tests and build/release tooling |
| [meridian-releases](https://github.com/kukirin-ui/meridian-releases) | Public APK downloads and release notes |
| [meridian-showcase](https://github.com/kukirin-ui/meridian-showcase) | Product overview, architecture, feature catalog and benchmarks |
| [meridian-site](https://kukirin-ui.github.io/meridian-site/) | Public product website |

---
**Meridian Family © 2026 Alen Požun.** Component-level license and notice information is available in the apps and source repository.
