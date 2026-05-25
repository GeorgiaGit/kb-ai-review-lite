# Neobrutalism Style

A SharePoint list style built on thick black borders, saturated colors, uppercase text, and hard offset shadows. Every row becomes a two-panel card: a metadata sidebar on the left, main content on the right. Overdue items flip the shadow and border to red. Bold, graphic, impossible to ignore.

![preview](./assets/preview.png)

## What you get

- Design tokens for 3px solid black borders, hard 4px offset box-shadows, and saturated status colors
- A full `rowFormatter` card with a metadata sidebar (name, status badge, progress bar, deadline) and a main content panel
- ON TRACK / AT RISK indicator alongside the status badge
- Overdue items get red border + red shadow — an unmistakable signal that doesn't require reading the date

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the neobrutalism style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: internal comms, campaign sites, anything that needs to stop someone scrolling past.
**Tone**: loud, graphic, uppercase — impossible to ignore, intentionally not subtle.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-neobrutalism | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**