<div align="center">

<img src="https://raw.githubusercontent.com/pollinations/pollinations/main/assets/logo.svg" alt="pollinations.ai logo" width="120" />

# Dreamframe

### The best way to test your Pollinations API key.

A full-featured, single-file playground for [pollinations.ai](https://pollinations.ai) . Images, video, voice, and music generation. Paste your API key and start creating.

[![Built with Pollinations](https://img.shields.io/badge/Built%20with-Pollinations-8a2be2?style=for-the-badge&logo=data:image/png;base64,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&logoColor=white&labelColor=6a0dad)](https://pollinations.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge)](https://funniman23.github.io/Dreamframe/)

**[→ Open Live Demo](https://funniman23.github.io/Dreamframe/)**

</div>

---

## What is Dreamframe?

Dreamframe is a zero-dependency, single-HTML-file playground for the [pollinations.ai](https://pollinations.ai) API. It lets developers and creators test every major Pollinations model images, video, voice, and music, without writing a line of code. Enter your API key, pick a model, type a prompt, generate.

---

<div align="center">

![Dreamframe showcase](showcase.gif)

</div>

## Features

| Mode | What it does | Models |
|---|---|---|
| **Image** | Text → image | Flux Schnell, Turbo, Flux Realism, Flux Anime, Flux 3D, Flux 2 Dev, Dirtberry, Dirtberry Pro, Z-Image Turbo, Imagen 4, Grok Imagine, Klein, GPT Image 1 Mini + all 💎 paid tiers |
| **Video** | Text → video clip | Grok Video, LTX-2, Seedance Lite, Wan 2.6, Veo 3.1 Fast, Seedance Pro, Pruna p-video |
| **Voice** | Text → spoken audio | ElevenLabs v3 (20+ voices), Qwen3 TTS |
| **Music** | Text → music | ElevenLabs Music, Suno v5 |

### Also included

- **Prompt Enhancer** — AI-rewrites your prompt via `openai-fast` for richer results
- **Random prompt** — 15 hand-picked cinematic prompts to spark ideas
- **Style quick-tags** — one-click append: cinematic, anime, 3D render, watercolor, etc.
- **Negative prompt** — collapsible negative prompt field
- **Seed control** — lock seeds for reproducibility, shuffle for variety
- **Session gallery** — every generation saved; lightbox preview, one-click download, reuse prompt
- **Pollen Cost Calculator** — live estimator across all media types with per-tier sufficiency indicators
- **BYOP** — your `sk_` or `pk_` key stored in `sessionStorage` only, never transmitted elsewhere
- **Zero dependencies** — one `.html` file, no build step, no npm, no framework

---

## Running locally

```bash
git clone https://github.com/funniman23/Dreamframe.git
cd Dreamframe
open index.html
```

Or double-click `index.html`. That's it.

---

## Getting a Pollinations API key

1. Go to [enter.pollinations.ai](https://enter.pollinations.ai)
2. Sign in with GitHub
3. Create a Secret key (`sk_…`) or App key (`pk_…`)
4. Paste it into the **Enter API key** modal in Dreamframe

---

## API endpoints used

```
# Image & Video
GET  https://gen.pollinations.ai/image/{prompt}
     ?model=flux&width=1024&height=1024&seed=42&referrer=dreamframe&key=sk_...

# TTS & Music (OpenAI-compatible)
POST https://gen.pollinations.ai/v1/audio/speech
     { "input": "...", "model": "elevenlabs", "voice": "aria" }

# Prompt Enhancement
GET  https://gen.pollinations.ai/text/{prompt}
     ?model=openai-fast&referrer=dreamframe&key=sk_...
```

Full API reference → [APIDOCS.md](https://github.com/pollinations/pollinations/blob/main/APIDOCS.md)

---

## Pollen cost reference

| Type | Model | Rate |
|---|---|---|
| Image | Flux Schnell | 0.001 p / img |
| Image | Z-Image Turbo | 0.002 p / img |
| Image | Flux Kontext 💎 | 0.04 p / img |
| Video | Grok Video ⚠️ | 0.003 p / sec |
| Video | Veo 3.1 Fast 💎 | 0.150 p / sec |
| Voice | ElevenLabs v3 | 0.18 p / 1K chars |
| Music | ElevenLabs Music | 0.005 p / sec |

Full pricing at [enter.pollinations.ai](https://enter.pollinations.ai)

---

## License

MIT

---

<div align="center">
  <a href="https://pollinations.ai">
    <img src="https://raw.githubusercontent.com/pollinations/pollinations/main/assets/logo.svg" alt="Powered by pollinations.ai" width="72" />
  </a>
  <br/><br/>
  <sub>Built with <a href="https://pollinations.ai">pollinations.ai</a> — Free & Open AI API</sub>
</div>
