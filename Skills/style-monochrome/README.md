# Monochrome Style

A SharePoint list style built entirely in a single slate hue. The progress percentage is the dominant visual element — displayed large on the left — with all other metadata stacked beside it. Clean, corporate, tonal. Works in any context where saturated color would feel out of place.

![preview](./assets/preview.png)

## What you get

- Design tokens using a single slate palette with tonal variations for status and progress
- A `rowFormatter` where the large progress number anchors the left side and metadata stacks to its right
- Status badges differentiated by tint depth rather than color — cohesive, not flat
- A style that integrates seamlessly with SharePoint's default chrome without clashing

## Using this style

This is a **style token skill** — it provides design tokens and a reference `rowFormatter`, but does not apply them on its own. Pair it with the [list-styling](../list-styling/) skill, which reads the tokens from this skill and adapts the row template to your library's actual columns.

Typical flow:

1. Install both this skill and [list-styling](../list-styling/) into your SharePoint Skills library.
2. From a Copilot agent, ask: *"Style this library using the monochrome style."*

Looking for sample content to try it on? The [list-styling demo](../list-styling/demo/) ships with ten short Word documents and the exact `Status`, `Progress`, and `Deadline` column setup the row template expects.

## When to use this style

**Audience**: corporate, finance, legal, and executive views where saturated color would feel out of place.
**Tone**: tonal, restrained, percentage-led — a single slate hue doing all the work.

## Demo video

[![Watch the video](https://img.youtube.com/vi/34aAsN12s80/hqdefault.jpg)](https://www.youtube.com/watch?v=34aAsN12s80)

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| style-monochrome | Zach Rosenfield &#124; [GitHub](https://github.com/zrosenfield) &#124; [LinkedIn](https://www.linkedin.com/in/zrosenfield/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**