# Pastel Style

A SharePoint list style using soft candy colors and inverted badges. Each card has a tinted left panel that matches the item's status hue, with warm pastel tones throughout. Friendly, approachable, and a strong visual contrast to the corporate defaults.

![preview](./assets/preview.png)

## What you get

- Design tokens for soft pastel status colors with inverted badge treatment (light background, dark text)
- A `rowFormatter` with a status-hued left panel that shifts color based on the item's current status
- Rounded corners and gentle shadows — approachable rather than aggressive
- A style that works well on team sites, project trackers, and any context where warmth matters

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the pastel style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: HR, people teams, community sites, onboarding hubs, and any internal space that should feel welcoming.
**Tone**: warm, candy-colored, approachable — corporate defaults softened, not abandoned.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-pastel | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**