# Semantic Field Cartographer

A 2D table of things and their qualities, folded onto a 3D graph you can fly
through. Your AI does the judging, the folding, and the piloting.

## Install

Tell your coding agent (Claude Code, Codex, or similar):

> **read this: https://github.com/prairielabs/semantic-field-cartographer/blob/main/HARNESSED_AGENT_READ_THIS.md**

The installer is written in [Scissortail](https://github.com/prairielabs/scissortail) and is addressed to the model. It acquires the folder, reads its program, serves the field, and seats itself as the judge.

## Use

1. Open this folder in Claude Code, Codex, or any similar agent.
2. Say: **"make me [some set of things] by [three qualities]"** —
   e.g. *top 20 GDP countries by freedom, prosperity, military strength*.
3. The model builds the map, opens it at `http://localhost:8322`, and tells
   you what it found.

## Flying

Drag to look · **WASD** or arrows move · **wheel** glides forward (**hold Shift**
for 4× speed) · **Space/Shift** rise and sink · **R** or double-click returns
home · **F** immersive · grid detail top-right · click column headers to sort ·
hover any point for its profile · edit any cell or weight — the map answers
live. Motion has mass: the camera eases into a look and coasts to a stop, and
it feels the same at any frame rate. Touch works: one finger looks.
Optional controls: **light** toggles the palette; **octants** region tints, **legend**
red/green standings per construct, **nums** axis marks.

That's everything. Ask the model for the next matter.

## Credit

The 3D visualization approach was inspired by **AutoWiki**, a project by
**Tom Pagnozzi** (GitHub link coming soon).

TikTok [@aibasics](https://tiktok.com/@aibasics) ·
Instagram [@ai_basics](https://instagram.com/ai_basics) ·
YouTube [@ai_basics](https://youtube.com/@ai_basics) ·
X [@ai_basics](https://x.com/ai_basics) ·
tom@summersafe.ai

## License

MIT © 2026 Prairie Labs, Inc.
