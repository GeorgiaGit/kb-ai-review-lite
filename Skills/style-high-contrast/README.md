# High Contrast Style

A SharePoint list style designed for maximum readability and accessibility. Large bold text, thick borders, alternating dark/light band rows, and a heavy left accent bar make every row easy to scan — useful for users who need high contrast or simply want no ambiguity in the UI.

![preview](./assets/preview.png)

## What you get

- Design tokens optimized for WCAG contrast requirements — large text, thick borders, unambiguous status colors
- A `rowFormatter` with wide horizontal band rows and a dominant left accent bar
- Status badges with heavy weight and large font size — readable at a glance
- Alternating row shading that remains legible even without color perception

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the high-contrast style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: accessibility-first scenarios, low-vision users, public-display screens, and anyone who needs the UI to leave zero ambiguity.
**Tone**: blunt, oversized, AAA-contrast — readability is the design.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-high-contrast | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
