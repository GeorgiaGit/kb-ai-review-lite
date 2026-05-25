# Bento Style

A SharePoint list style inspired by bento boxes — each row is a horizontal card divided into labeled compartments (Document, Status, Progress, Deadline) with visible dividers between sections. Warm earth tones, subtle shadows, organized without being loud.

![preview](./assets/preview.png)

## What you get

- Design tokens for warm-toned status badges (burnt orange, olive green, slate)
- A horizontal compartment `rowFormatter` where each section has a tiny uppercase label above its content
- Progress percentage displayed large (20px) and centered in its compartment
- Overdue items get a red left-border accent — subtle, not aggressive

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the bento style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: ops teams, project managers, and content owners who need clear sectioning between metadata fields without flashy treatment.
**Tone**: organized, warm, earth-toned, considered — not loud.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-bento | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
