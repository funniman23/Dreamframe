# Dreamframe

A simple image generator built on the [Pollinations.ai](https://pollinations.ai) API. Type a prompt, get an image.

[![Built With pollinations.ai](https://img.shields.io/badge/Built%20With-pollinations.ai-orange?style=flat-square)](https://pollinations.ai)

## Live demo

[funniman23.github.io/Dreamframe](https://funniman23.github.io/Dreamframe/)

## What's in it

- Text-to-image generation via Pollinations.ai
- BYOP auth — users connect their own Pollinations account, app runs at $0
- Model selection: Flux, Turbo, Flux Realism, Anime, 3D
- Output sizes: square, landscape, portrait
- One-click image download
- Single HTML file, no build step, no dependencies

## Running it locally

```bash
git clone https://github.com/funniman23/Dreamframe.git
cd Dreamframe
open index.html
```

Or just double-click the file.

## How the API works

Every image request is a plain URL:

```
https://image.pollinations.ai/prompt/{your prompt}?model=flux&width=1024&height=1024
```

Full docs at [pollinations.ai](https://pollinations.ai).

## Stack

Vanilla HTML, CSS, and JavaScript. Nothing else.

## Built with

[<img src="https://pollinations.ai/p/pollinations_ai_logo_white_text?width=200&height=50&nologo=true" alt="pollinations.ai Logo" height="30">](https://pollinations.ai)

## License

MIT
