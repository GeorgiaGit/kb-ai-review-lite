# List Styling — Demo Content

Demo content for the [list-styling](../) skill. Use these sample files and column setup to set up an end-to-end demo of the skill against a SharePoint document library.

## What's included

The `sample-files/` folder contains 10 short Word documents on SharePoint Skills topics, including:

- Introduction to SharePoint Skills
- Best Practices on SharePoint Skills
- Authoring Custom SharePoint Skills
- Styling SharePoint Lists with Skills
- Cleaning Up SharePoint Libraries
- Reconciling Invoices and POs
- Classifying Files with SharePoint Skills
- Organizing Document Libraries
- Visualizing Site Storage Heatmaps
- The Review Council Pattern

Each file is a one-pager — content is illustrative only. The variety of titles gives the styled view enough rows to look realistic without bloating the library.

## Setup

1. Create or open a SharePoint document library.
2. Upload all files from `sample-files/` into the library.
3. Add the following three columns to the library so the row template has Status, Progress, and Deadline roles to render. Internal names matter — match them exactly:

   | Display name | Internal name | Type      | Configuration                                                                                          |
   | ------------ | ------------- | --------- | ------------------------------------------------------------------------------------------------------ |
   | Status       | `Status`      | Choice    | Choices: `Not Started`, `In Progress`, `In Review`, `Complete`, `Blocked`. Default: `Not Started`.     |
   | Progress     | `Progress`    | Number    | Min `0`, Max `100`. Show as percentage off (the row template formats it). Default: `0`.                |
   | Deadline     | `Deadline`    | Date only | Friendly format off. No default value.                                                                 |

   To add a column: library settings → **Add column** → pick the type → set the display name to match the table → save. If SharePoint auto-generates a different internal name (because the display name was edited later), recreate the column with the correct name from the start.

4. Populate the new columns with a mix of values across the uploaded files — for example, set a few items to `In Progress` with `Progress` 40–80 and a `Deadline` in the past so the overdue treatment is visible.
5. Install the [list-styling](../) skill into your SharePoint Skills library.
6. Install one or more style token skills you want to try (for example [style-neobrutalism](../../style-neobrutalism/), [style-bento](../../style-bento/), [style-pastel](../../style-pastel/)).
7. From a Copilot agent, ask: *"Style this library using the neobrutalism style."* (substitute whichever style you installed).

## What to expect

The agent will:

- Read the library schema and map your `Status`, `Progress`, and `Deadline` columns to the style template's role placeholders
- Generate a full `rowFormatter` JSON that recomposes each row into the style's signature card layout
- Generate column formatters for any columns not handled by the row template
- Tell you to create a new view named after the style (e.g., "Neobrutalism") and paste the JSON via **Format current view → Advanced mode**
- Leave your default "All Documents" view untouched

The result should hit the skill's bar: *"I can't believe that's SharePoint."*
