# Dreamframe

A simple image generator built on the [Pollinations.ai](https://pollinations.ai) API. Type a prompt, get an image.

## Live demo

[funniman23.github.io/dreamframe](https://funniman23.github.io/Dreamframe/)

## What's in it

- Text-to-image generation via Pollinations.ai
- Model selection: Flux, Turbo, Flux Realism, Anime, 3D
- Output sizes: square, landscape, portrait
- One-click image download
- Single HTML file, no build step, no dependencies

## Running it locally

```bash
git clone https://github.com/funniman23/dreamframe.git
cd dreamframe
open index.html
```

Or just double-click the file.

## How the API works

Every image request is a plain URL:

```
https://image.pollinations.ai/prompt/{your prompt}?model=flux&width=1024&height=1024
```

No API key required. Full docs at [pollinations.ai](https://pollinations.ai).

## Stack

Vanilla HTML, CSS, and JavaScript. Nothing else.

## License

MIT
