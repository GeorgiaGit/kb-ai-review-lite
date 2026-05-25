# Retro Memphis Style

A SharePoint list style channeling 80s and 90s Memphis design — bright contrasting colors, colored hard shadows, and a bold status-colored top banner on each card. The progress percentage is displayed large below the banner. Playful, energetic, and nothing like SharePoint.

![preview](./assets/preview.png)

## What you get

- Design tokens for bright saturated colors, colored box-shadows, and a stacked vertical card layout
- A `rowFormatter` with a status-colored top banner strip and large progress number below it
- Hard offset shadows tinted to match the status color — the shadow IS part of the design
- A deliberately opposite layout from the sidebar-based styles — everything stacks vertically

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the retro style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: creative teams, events, internal campaigns, and any moment that earns a nostalgic wink.
**Tone**: playful Memphis design — loud, energetic, and proudly not corporate.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-retro | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**