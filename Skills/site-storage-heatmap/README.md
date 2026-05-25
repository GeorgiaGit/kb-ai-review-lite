# Site Storage Heatmap

Generates an interactive HTML site map showing storage breakdown and hot/cold activity heatmap across all document libraries, lists, and site pages on a SharePoint site.

![preview](./assets/preview.png)

## What you get

- A site-wide summary with stacked horizontal bars showing hot/warm/cool/cold activity tiers across document libraries, lists, and site pages
- Per-library click-through drill-downs showing file count, total size, file type breakdown, and activity heatmap
- Storage breakdown by file type with percentage bars
- The file saved as `{FirstName}-Site-Storage-Heatmap.html` in a `storage heatmap` folder in the site's document library
- Automatic navigation to the saved file on completion

> **Open the HTML in a browser tab, not as a SharePoint preview.** SharePoint strips inline JavaScript from in-browser file previews, so the click-through drill-downs and modal only work after you download the file (or open it in a new tab from the document library).

## When to use

Ask Copilot:

- *"site storage heatmap"* / *"storage heatmap for this site"*
- *"show me what's hot and cold on this site"*
- *"site map with storage sizes"* / *"site map heatmap"*
- *"which libraries are taking the most space"* / *"where is the storage going"*
- *"what content is stale on this site"*

Best on a site you own or admin — the skill enumerates every library, list, and page library, so it needs broad read access to give a complete picture.

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| site-storage-heatmap | Joe Komban (Microsoft) &#124; [GitHub](https://github.com/JoeFranc) &#124; [LinkedIn](https://www.linkedin.com/in/kjoefrancis/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
