# Glassmorphism Style

A SharePoint list style built around floating surfaces and negative space. Soft diffused shadows, barely-visible borders, 16px rounded corners, pill-shaped badges, and generous padding. Looks like a modern SaaS dashboard — not SharePoint.

![preview](./assets/preview.png)

## What you get

- Design tokens for soft shadows, pill badges, and a single-column floating card layout
- A `rowFormatter` where content stacks vertically — name, metadata row, full-width thin progress bar
- Overdue treatment is whispered ("overdue" in lowercase italic), not shouted
- The opposite of Neobrutalism — no hard borders, no offsets, no uppercase

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the glassmorphism style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: leadership dashboards, marketing sites, modern SaaS-style hubs where SharePoint shouldn't look like SharePoint.
**Tone**: soft, floaty, generous whitespace — the opposite of dense and gridded.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-glassmorphism | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
