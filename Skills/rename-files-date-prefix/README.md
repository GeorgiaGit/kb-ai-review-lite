# Rename Files with Date Prefix

Renames all files in a SharePoint document library — including files in subfolders — to prefix them with their created date in `yyMMdd` format (e.g., `251203-Status Report.pdf`). Always shows a preview before committing any changes.

![preview](./assets/preview.png)

## What you get

- All files prefixed with their created date in `yyMMdd` format (2-digit year, 2-digit month, 2-digit day)
- A preview table showing current names, new names, folder paths, and status before any changes are made
- Automatic skip for files already prefixed with a 6-digit date — no double-prefixing
- Recursive processing across all subfolders
- Graceful error handling — one failure does not stop the rest of the batch

## When to use

Ask Copilot:

- *"prefix all files with their created date"*
- *"add date prefixes to files"* / *"add date prefix to filenames"*
- *"rename files with date prefix"* / *"prefix filenames with yyMMdd"*
- *"prefix files in this library with their created date"*

Best on a library where you want files to sort chronologically by name. Files already prefixed with a 6-digit date are detected and skipped — the skill is safe to re-run.

## SharePoint Skill

| Solution | Author(s) |
| --- | --- |
| rename-files-date-prefix | Leon Armston &#124; [GitHub](https://github.com/LeonArmston) &#124; [LinkedIn](https://www.linkedin.com/in/leonarmston/) |

## Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | May 2026 | Initial Release |

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
