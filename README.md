# South Asian Historical Documentary VideoExpress

An adaptation of the historical documentary workflow for South Asian history, society and culture. Each request produces a detailed Markdown episode packet with research notes, narration, scene-by-scene image prompts and matching image-to-multishot VideoExpress prompts for manual production.

The workflow is designed for stories about history, society and culture in ancient and medieval India: trade routes, cities, temples, courts, crafts, foodways, languages, migration, belief and everyday life.

## What this adaptation changes

- Two presentation modes: an uploaded on-screen narrator who appears in every frame, or a faceless documentary mode.
- One locked male or female narrator voice throughout the episode.
- A five-minute maximum by default.
- A `World Lock` for architecture, clothing, materials, light and geography in each period.
- Source-first research notes, claim labels and a “what we know / what we infer” pass.
- Visual reconstructions are clearly framed as reconstructions; they do not pretend to be recovered footage.
- Each episode has its own navigation from research brief → storyboard → prompt pack → edit checklist → export.

## Quick start

1. Open [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) in a browser-capable assistant.
2. Request a documentary topic, place, period or question. The defaults are up to 5 minutes, 16:9 and a selected male or female narrator with a clear Indian English accent.
3. Provide source links or notes when available.
4. Receive one detailed `.md` packet. Generate the images and then paste the following multishot video prompts into VideoExpress manually.

## Episode principles

Historical claims should be traceable. Separate primary evidence, scholarly interpretation and creative reconstruction. Avoid invented quotations, false certainty, modern stereotypes and “walking through” scenes presented as literal evidence. Prefer ordinary people and material culture alongside rulers and monuments.

## Files

| File | Purpose |
|---|---|
| [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) | Copy-ready assistant prompt |
| [PLAYBOOK.md](PLAYBOOK.md) | Full production workflow |
| [PROMPT_COMPACT.md](PROMPT_COMPACT.md) | Compact project instructions |
| [docs/research-and-ethics.md](docs/research-and-ethics.md) | Evidence, uncertainty and representation rules |
| [docs/visual-language.md](docs/visual-language.md) | Period reconstruction and camera language |
| [examples/README.md](examples/README.md) | Episode packet format |
| [templates/episode-output.md](templates/episode-output.md) | Required Markdown output structure |

## License and attribution

This repository is an adaptation of [Realistic Consistent Character Videos](https://github.com/ai-playbooks/realistic-consistent-character-videos). Preserve upstream attribution and check the upstream license before redistributing or publishing modified copies.
