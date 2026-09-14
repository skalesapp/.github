<div align="center">

# 🦎 Skales

**A local-first AI harness for Windows, macOS, Linux, Android & iOS**

![Team Skales](https://skales.app/team_s.png)

**Double-click. Run. Done.** No Docker. No terminal. No signup.

<p>
  <a href="https://skales.app"><img src="https://img.shields.io/badge/skales.app-10b981?style=for-the-badge&labelColor=0D1117" alt="Website"></a>
  <a href="https://docs.skales.app"><img src="https://img.shields.io/badge/Documentation-0D1117?style=for-the-badge" alt="Docs"></a>
  <a href="https://github.com/skalesapp/skales"><img src="https://img.shields.io/badge/GitHub_Repo-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
  <a href="https://x.com/skalesapp"><img src="https://img.shields.io/badge/@skalesapp-0D1117?style=for-the-badge&logo=x&logoColor=white" alt="Twitter"></a>
</p>

<p>
  <a href="https://github.com/skalesapp/skales/releases/latest"><img src="https://img.shields.io/github/v/release/skalesapp/skales?style=for-the-badge&labelColor=0D1117&color=10b981" alt="Latest Release"></a>
  <a href="https://github.com/skalesapp/skales/blob/main/LICENSE"><img src="https://img.shields.io/badge/Licence-Proprietary-0D1117?style=for-the-badge" alt="Licence"></a>
  <a href="https://github.com/skalesapp/skales/stargazers"><img src="https://img.shields.io/github/stars/skalesapp/skales?style=for-the-badge&labelColor=0D1117&color=10b981" alt="Stars"></a>
</p>

Desktop **12.8.4** · Mobile **2.8.4**

</div>

---

## 🧭 What Skales is

Skales is a **harness**, not a wrapper. A wrapper puts a chat window in front of
someone else's API. A harness is the part that makes a model actually do things:
the agent loop, the tool layer, the context and memory handling, the provider
abstraction, and the per-model tuning that keeps tool calls landing across models
that behave nothing alike.

Concretely, that is **257 tools** on one turn budget, **26 providers** behind one
interface, a bundled local inference server, and a profile layer that adjusts
sampling and tool naming per model family. The chat window is the surface. The
harness is the product.

Local-first by default. Your data stays in `~/.skales-data` on your machine.
Bring your own keys, or run with no key at all. No Docker. No terminal. No signup.

Built from **6 to 60+** — usable by a kid, approved by a grandmother. Mainstream
surface, power-user depth underneath.

> *"From every tool I've tested in this space, I haven't found one that delivers intelligence without complexity, a companion instead of a tool, or value without hype. Skales has the foundation to tell that story."*
> — [@v33-kind](https://github.com/v33-kind), Community Contributor

---

## 📦 Projects

| Repo | What | Licence |
|------|------|---------|
| [**skales**](https://github.com/skalesapp/skales) | Desktop harness (Windows, macOS, Linux) | Proprietary |
| [**skales mobile**](https://play.google.com/store/apps/details?id=app.skales.mobile) | [Android](https://play.google.com/store/apps/details?id=app.skales.mobile) + [iOS](https://apps.apple.com/us/app/skales/id6763328966) — both live | Proprietary |
| [**devkit**](https://github.com/skalesapp/devkit) | CLI, developer docs, examples | MIT |
| [**wordpress**](https://github.com/skalesapp/wordpress) | WordPress Connector Plugin | MIT |
| [**plugins**](https://github.com/skalesapp/plugins) | Community plugin registry | MIT |
| [**llm-profiles**](https://github.com/gonemedia/llm-profiles) | Per-model tuning profiles for reliable tool calling | MIT |
| [**api-connectors**](https://github.com/gonemedia/api-connectors) | Keyless REST connector templates | MIT |

---

## 🖥️ Skales Local — the model runs on your machine

Skales ships its own **llama.cpp server** and starts it itself. One process,
a directory of models, hot-swapping between them. No Ollama install, no Docker,
no terminal — the download button is the whole setup.

The catalogue holds **55 downloadable assets**: **18 local LLMs**, their vision
projectors, and the rest of the stack that makes a machine self-sufficient —

- 🖼️ **Image generation on device** via stable-diffusion.cpp — DreamShaper 8 LCM, Stable Diffusion 1.5, Z-Image Turbo, FLUX.2 klein
- 🎙️ **Speech to text on device** via Whisper
- 🔊 **Text to speech on device** — Piper voices run through sherpa-onnx, in eight languages

Everything above works with **no API key and no network call**.

Prefer a hosted model? **Skales IQ** is a free trial tier that answers instantly
with fast open models and no key at all, so a fresh install is useful before you
have signed up for anything. It is capped; when it runs out, Skales tells you and
points at the place to add your own key.

---

## ✨ What it does

🧰 **257 tools** — files, shell, git, browser, email, calendar, messaging, documents, images, memory, and the rest, loaded on the same turn

🌍 **26 providers** — OpenAI, Anthropic, Google, Groq, DeepSeek, xAI, Mistral, Together, MiniMax, Moonshot, GLM, Qwen, Hunyuan, GigaChat, Nvidia NIM, Cloudflare, Hugging Face, OpenRouter, Atlas Cloud, and the local ones: Ollama, LM Studio, Unsloth Desktop, Skales Local, plus any OpenAI-compatible endpoint

💻 **Code** — an agentic coding surface with a 3-panel diff GUI, session history and undo

🏢 **Organization** — build an AI company with departments, specialized agents and team leaders

🤖 **Agents** — custom agents with opt-in per-agent memory: each finished task leaves a lesson the next run reads back

🎛️ **Cockpit** — goals, tasks and schedule in one screen, with a background heartbeat that works the queue every few minutes

🦁 **Lio AI** — block-based code builder for newcomers, generating HTML/CSS/JS/Python into a sandboxed preview

🎨 **Studio & Flow** — design, image, video, voice and music generation, with Brand Kit and PowerPoint/Word/PDF export

📝 **WordPress lives in the chat** — 47 tools behind the connector, so posts, pages, media and settings are just things you ask for

🌐 **Built-in browser** — the agent navigates, clicks and extracts

🖥️ **Computer use** — screenshot, click, type, scroll

📅 **Planner + calendar sync** — Google, Apple, Outlook

🧠 **Memory + dreaming** — persistent memory with 3-phase overnight consolidation

🗣️ **12 languages** — EN, DE, ES, FR, RU, PT, KO, ZH, JA, VI, HR, TR

---

## 👁️ Iris

The voice inside Skales has a name and a face. **Iris** opens in her own
frameless window — wake word, listening, speaking — and carries on the same
session as the chat you handed to her, while the rest of Skales stays where it
was. She ships today, marked Beta.

Iris Orbit becomes its own product later: [irisorbit.com](https://irisorbit.com)

---

## 📜 Licence and brand

Skales is **proprietary software**. It is licensed, not sold. It is not open
source, it is not source-available, and it will not become either.

Private individuals, students, teachers and non-commercial educational
institutions use Skales **free of charge**.

Companies, businesses and public bodies need a written commercial licence;
SaaS, hosting, bundling, white-labelling and resale need a written contract.
Ask at [request@skales.app](mailto:request@skales.app).

Run Skales as it is published: no modified copies, no bypassing its integrity,
attestation or authentication mechanisms, no operating it as a component,
backend or agent engine of another program, no reselling or brokering access to
it, and no claiming to be a partner, reseller or co-developer of Skales. The
current licence is **version 1.1 of 14 September 2026**, published at
[skales.app/licence](https://skales.app/licence/).

The name **Skales**, the logo and the icon stay with their author. You may refer
to Skales by name to describe, review or link to the unmodified original
software; a modified or rebranded copy must not carry the name or the logo.

📄 [LICENSE](https://github.com/skalesapp/skales/blob/main/LICENSE) · ™ [TRADEMARK.md](https://github.com/skalesapp/skales/blob/main/TRADEMARK.md) · ✍️ [request@skales.app](mailto:request@skales.app)

Published builds are signed and identify themselves. A build that is not in our
own release record is not one of ours, whatever it is called.

---

<div align="center">

Made by [Mario Simic](https://mariosimic.at) in Vienna 🇦🇹

</div>
