# Figma Clean Style

A SharePoint list style that looks like a polished Figma component library. Each card has a thin status-colored stripe across the top, clean data layout below, and subtle self-colored borders. Polished, professional, and immediately recognizable as intentional design.

![preview](./assets/preview.png)

## What you get

- Design tokens with per-status accent colors used across the top stripe, border, and badge
- A `rowFormatter` with a colored header bar that shifts hue based on the item's status value
- Clean typographic hierarchy below the stripe — name, metadata row, progress bar
- A style that pairs well with modern SharePoint intranets and communication sites

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the figma-clean style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: designers, product teams, and anyone whose first reaction to a list should be "this looks deliberately designed."
**Tone**: polished, restrained, component-library precision — no flourish, no decoration.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-figma-clean | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**