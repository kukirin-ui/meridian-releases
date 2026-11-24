<div align="center">

# MERIDIAN FAMILY

### Five Android apps. One mind. Built and run on a phone.

**Local AI · Termux engineering · device intelligence · shared knowledge that learns from its own work**

Meridian turns an Android phone into an AI workstation. Core is the family's mind: one memory for all five apps, trust that only evidence raises, and the one app that always runs, opening each of the others when there is work for it. Every verified result is shared, and every model, local or online, learns from it.

**Current release: 3.0.00** · Android 11 or newer · no root

<br/>

[**⬇ DOWNLOAD ALL FIVE APPS**](https://github.com/kukirin-ui/meridian-releases/blob/main/download-all.html) · [Latest release](https://github.com/kukirin-ui/meridian-releases/releases/latest) · [What's new](https://kukirin-ui.github.io/meridian-site/whatsnew.html)
[Website](https://kukirin-ui.github.io/meridian-site/) · [Feature showcase](https://github.com/kukirin-ui/meridian-showcase) · [Architecture](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/ARCHITECTURE.md) · [Report an issue](https://github.com/kukirin-ui/meridian-releases/issues)

</div>

---

## The suite

| **CORE** | **CHAT** | **GAMING** | **PARALLEL** | **NULLCLOUD** |
|:---:|:---:|:---:|:---:|:---:|
| The family's mind | Local AI | Device performance | Termux workstation | Research & reading |
| Memory, trust, upkeep | 14 job adapters | Smart gaming | Programs, written and tested | Studio |

| App | What it is for | Latest APK |
|---|---|---|
| **Meridian Core** | One library and memory for the family, the Trust Ledger, the Caretaker, the Translator, and the ADB helper that changes system settings without root | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-core.apk) |
| **Meridian Chat** | Models on the phone with llama.cpp, or your own provider key; job adapters, Me mode, Teacher mode, Model Lab and Storage | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-chat.apk) |
| **Meridian Gaming** | Live clocks and hardware readings, Clock profiles, heat guard, and Smart gaming: the least power that still holds the game | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-gaming.apk) |
| **Meridian Parallel** | Termux console and files, Forge, programs written with their tests and proven in the Sandbox, Diagnose, Recipe Compiler and Repro Lab | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-parallel.apk) |
| **NullCloud** | Read links, PDFs and text; Studio learns topics, scrapes sites and writes from sources only | [Download](https://github.com/kukirin-ui/meridian-releases/releases/latest/download/meridian-nullcloud.apk) |

**Install Core first** for the connected family. Each of the other four also works on its own; some features need Core, Termux, Termux:API, Wireless debugging pairing, device permissions or a configured model.

---

## New in 3.0.00

- **Core is the family's mind.** One library and one memory in one database, ranked by what really worked on this phone; trust rises only with evidence and every change is on the Trust Ledger, a verifiable hash chain.
- **Every app's verified work is shared.** Commands that ran, files that passed their check, fixes the Sandbox proved and programs whose tests passed are kept in Core, and every model gets the closest verified work as an example before it answers.
- **Core opens the apps for their work.** Only Core runs all the time; work between apps goes through Core, which opens the app that gets it and closes it again afterwards.
- **Any model can have a program built.** Parallel writes it with its tests, runs them in its Sandbox, repairs what fails and saves the working program in Termux.
- **14 job adapters** on one local model, **Teacher mode** (an online model's passing fix teaches the local one), **Me mode**, **tools for local models** measured as reliable, and **Model Lab**.
- **Forge**, **Recipe Compiler**, **Repro Lab**, **NullCloud Studio**, **Smart gaming**, **Theme Studio** and **Looks and Effects**.
- **The Caretaker, Constitution, Proof Engine and Survival Mode**, the **internet switch** with Hard offline, **Core · Translator** (Croatian and English on the phone), and updates for the whole family from any app's drawer.

The complete list is in the [3.0.00 release notes](https://github.com/kukirin-ui/meridian-releases/releases/tag/v3.0.00).

---

## Quick install

1. Open the [latest release](https://github.com/kukirin-ui/meridian-releases/releases/latest) or the [all-apps download page](https://github.com/kukirin-ui/meridian-releases/blob/main/download-all.html).
2. Install **Meridian Core** first, then Chat, Gaming, Parallel and NullCloud as you need them.
3. In Core, follow the Wireless debugging pairing guide for system-level features.
4. In Parallel, connect Termux for the console, files, packages and builds.
5. Check each APK against the release's `SHA256SUMS.txt`.

Later updates: any Meridian app's drawer shows what is missing or behind and updates it in one tap.

---

## What is inside

### Core · the family's mind
- One library for the family: documents, recipe cards, proven fixes, lessons, learned cards and the shared record of verified work, searched and ranked by evidence.
- Learning Kernel: results from every app teach which answers, fixes and models work on this phone.
- Trust Ledger: every change of trust in a verifiable hash chain; trust remembers the phone and Android version it was earned on.
- A read-only shared view of Core's knowledge for every app, checked before it is trusted.
- Opens the app a piece of work belongs to and closes it again, so only Core and the app on screen use memory.
- Caretaker: upkeep while charging and idle; file clean-up always asked first.
- Constitution, Proof Engine (a proof before consequential actions, verified after) and Survival Mode.
- Core · Translator: Croatian and English on the phone, on Mozilla's engine.
- Wireless debugging pairing and an ADB shell-user helper on loopback, protected by a one-time token. Shell-user access, not root.
- The family's internet master switch, Theme Studio, the Reasoner, and settings shared by all five apps.

### Chat · models on the phone
- Local GGUF models through llama.cpp in Termux; CPU, Vulkan GPU or split; every llama-server option, llama.cpp built from source, Vulkan drivers and presets.
- 14 job adapters on one base model: Python, C/C++, shell, web, JVM, Rust/Go, a Termux fixer and worker, a judge, recipe cards, Android, local models, networking and conversation.
- Me mode: commands run at once, files are checked in a sandbox and backed up first, destructive actions wait for a tap.
- Teacher mode: an online model fixes what a local model could not, and the fix trains the local adapter.
- Tools for local models that the Model Lab measured as reliable with tools.
- Model Lab: live speed test and tests checked by code; the Store for GGUF models with this phone's measurements.
- Optional online providers with your own keys; Chat holds the keys for the whole family.
- Projects, memory, instructions, prompts, attachments, Storage, web search with citations, and training data exported per adapter.

### Gaming · device performance
- Live clocks for every CPU cluster and the GPU, battery, memory and hardware views, shareable reports.
- Clock profiles, heat guard, Release RAM and task isolation, every value read back.
- Smart gaming: per-game posture, the Sweet Spot Finder, the chip's efficiency fingerprint, a throttle forecast, a frame-time recorder and an exact restore.

### Parallel · the Termux workstation
- Console with sessions, files, plans and build recipes for Python, Node, Rust, Go, C/C++, Java, Ruby, PHP, Lua and shell.
- Forge: from an idea to a proven product, with an architecture review, a security review of every line, README, FORGE.json and checksums.
- Programs on request from any app and any model: written with their tests, proven in the Sandbox, repaired, saved in Termux.
- Doctor, Diagnose (the cause by method, one verified fix at a time), the Debugger, the Recipe Compiler and the Repro Lab.
- Debian and Ubuntu through proot-distro, SSH and local llama-server tooling.

### NullCloud · research and reading
- Links, PDFs and pasted text: summaries, steps, facts, claim checks, translation and follow-up questions; no size caps.
- Studio: learn a topic from ranked sources into Core's library, scrape a page or a site with robots.txt respected, and write from sources only.
- Reads only the public web, checked on every redirect.

---

## Privacy, signing and integrity

- Models run on the phone by default. Online providers are optional, use your own key and are switched on by you.
- The internet switch: one per app and a master switch in Core; Hard offline drops all internet traffic of the Meridian apps and Termux.
- Each app's page runs only its own scripts; Core's own screen cannot be opened by other apps.
- All five APKs in a release are signed with the same certificate, verified against the pinned fingerprint before publication, and every release includes `SHA256SUMS.txt`.
- The private signing key and its password stay with the owner and are never uploaded.
- Public issues are visible to everyone: never include passwords, API keys, tokens or private logs.

### Family certificate fingerprint
```
SHA-256 18:58:EA:52:80:F2:7D:41:68:1B:73:DC:32:D7:AF:CD:69:39:21:DE:E2:97:B8:A3:8B:23:98:89:10:95:FA:B7
```

---

## Documentation and support

- [Feature catalog](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/FEATURE-CATALOG.md)
- [Architecture](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/ARCHITECTURE.md)
- [Benchmarks and device measurements](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/BENCHMARKS.md)
- [Install and release procedure](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/INSTALL-AND-RELEASE.md)
- [Validation and boundaries](https://github.com/kukirin-ui/meridian-showcase/blob/main/docs/VALIDATION-AND-BOUNDARIES.md)
- [Website](https://kukirin-ui.github.io/meridian-site/) · [What's new](https://kukirin-ui.github.io/meridian-site/whatsnew.html)
- [Report a problem](https://github.com/kukirin-ui/meridian-releases/issues), or use **Report a problem** in any app's Settings to prepare a report you review before sending.

## Repositories

| Repository | Purpose |
|---|---|
| [meridian-releases](https://github.com/kukirin-ui/meridian-releases) | Signed APKs, checksums and release notes |
| [meridian-showcase](https://github.com/kukirin-ui/meridian-showcase) | Product overview, architecture, feature catalog and benchmarks |
| [meridian-site](https://kukirin-ui.github.io/meridian-site/) | The website |
| Clean-Meridian (private) | Source, tests and build and release tooling |

---
**Meridian Family © 2026 Alen Požun** · [X / @termuxSolutions](https://x.com/termuxSolutions) · [XDA](https://xdaforums.com/m/termuxsolutions.13482532/)
Component licences and notices are in the apps.
