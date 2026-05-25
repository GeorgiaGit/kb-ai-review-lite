# Terminal Style

A SharePoint list style built like a dark-mode CLI dashboard. Dark cards with neon green and cyan text, a terminal prompt icon on each row, and status displayed as CLI-style output. Loved by developers and anyone who wants their SharePoint to look like a hacking scene.

![preview](./assets/preview.png)

## What you get

- Design tokens for a dark background palette with neon green, cyan, and amber status accents
- A `rowFormatter` with terminal prompt styling — each row reads like command output
- Status values rendered as CLI-style labels rather than visual badges
- Sharp corners, monospace-inspired typography, and zero decorative softness

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the terminal style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: developer teams, dev rel portals, engineering ops, and technical hubs — the people who feel at home in a CLI. Not a good fit for general staff or external-facing pages.
**Tone**: dark, neon, CLI-styled — a small inside joke for a technical audience.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-terminal | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**