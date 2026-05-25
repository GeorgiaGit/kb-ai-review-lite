# Blueprint Style

A SharePoint list style modeled on engineering drawings and technical spec sheets. Monochromatic blue palette, double-ring rubber-stamp status badges, and an ultra-compact card layout with a blue left-edge accent. The most information-dense style in the collection.

![preview](./assets/preview.png)

## What you get

- Design tokens for a monochromatic blue palette with double-ring badge treatment
- The most compact `rowFormatter` in the collection — spec-sheet density with a blue left edge
- Status badges styled as rubber-stamp rings — visually distinct from every other style
- Overdue is the only element that turns red — everything else stays in the blue system

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the blueprint style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: engineering teams, design ops, technical-spec libraries, anywhere the content already reads like a specification sheet.
**Tone**: precise, monochromatic blue, information-dense — every row a small drafting plate.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-blueprint | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**