# Financial Analysis vault — instructions for Claude

This folder is an Obsidian vault used for company and sector research with the
`equity-research` plugin skills (initiating-coverage, earnings-analysis,
earnings-preview, model-update, thesis-tracker, sector-overview,
idea-generation, catalyst-calendar, morning-note).

These rules apply every time one of those skills is used here. Where a skill's
own instructions say something different about output format, file names or
where files go, **these rules win**.

---

## 1. Before any analysis: look through the vault for leads

Before starting the research, search this whole vault (all folders and
subfolders, skipping `.obsidian/` and `.trash/`) for anything related to the
subject:

- the company name, ticker and former names
- its sector, competitors, suppliers, customers and main products
- earlier analyses in `companies/` and `sector/`
- other notes, clippings and spreadsheets that mention any of the above

Search both file names and file contents.

**How to use what you find:**

- Treat it as **leads, not as answers**. Do not copy the notes' content into
  the analysis or hand it back as findings. Use it to decide what to research
  more deeply and to make sure nothing relevant is missed: a risk noted
  earlier, a competitor, a past event, an open question, an idea to check.
- **Check it against current sources** before relying on it. Vault notes may
  be out of date or my own unverified opinions. When a note and a current
  source disagree, say so in the analysis.
- If an earlier analysis of the same company or sector exists, read it first.
  Build on it: say what changed, which earlier views still hold, and which
  don't.
- If the search finds nothing relevant, say so in one line and carry on.

Every analysis note ends with a short **"Leads from the vault"** section. It
lists the notes that shaped the research, each as a link with one line on what
it prompted you to look into. Leave it out if nothing was found.

---

## 2. Where analyses are saved

All output goes inside this vault. Create a folder when it doesn't exist yet.

| Kind of analysis | Folder |
|---|---|
| A single company (initiating-coverage, earnings-analysis, earnings-preview, model-update, thesis-tracker) | `companies/<Company name>/` |
| A sector (sector-overview) | `sector/<Sector name>/` |
| Several companies at once, not tied to one company or sector (idea-generation, catalyst-calendar, morning-note) | `market/` |

- **Company folder name:** the common name of the company, e.g.
  `companies/Apple/` or `companies/ASML/`, not `Apple Inc.` or a ticker.
  Before creating a folder, check whether one already exists under a slightly
  different spelling, ignoring case. If it does, reuse it.
- **Sector folder name:** a plain sector name, e.g. `sector/Semiconductors/` or
  `sector/Luxury Goods/`. Reuse an existing folder when the sector is the same.
- If a screen or a morning note focuses on just one sector, it may go in that
  sector's folder instead of `market/`.

---

## 3. File names

Every analysis is saved as Markdown (`.md`), named:

```
<skill name> <YYYY-MM-DD>.md
```

- `<skill name>` is the skill that was used, without the plugin prefix, e.g.
  `initiating-coverage`, `earnings-analysis`, `sector-overview`.
- `<YYYY-MM-DD>` is today's date at the time of the request.
- Examples:
  - `companies/Apple/earnings-analysis 2026-11-21.md`
  - `sector/Semiconductors/sector-overview 2026-11-21.md`
  - `market/morning-note 2026-11-21.md`
- **initiating-coverage** runs as 5 separate tasks, so add the task number:
  `initiating-coverage task1 2026-11-21.md` … `initiating-coverage task5 2026-11-21.md`.
- If a file with that name already exists, **never overwrite it**. Add a
  number: `earnings-analysis 2026-11-21 (2).md`.
- Do not use characters Windows forbids in names (`\ / : * ? " < > |`).

**Non-Markdown files.** Some skills also produce files such as an Excel model,
charts or a Word report. Do the following:

- Always write the analysis itself as the `.md` note described above. It is the
  main deliverable, even where the skill says the output is a `.docx` or
  `.xlsx`.
- Save the extra files in the same folder, with the same base name, e.g.
  `initiating-coverage task2 2026-11-21.xlsx`.
- Put charts in an `attachments/` subfolder of that same folder and embed them
  in the note with `![[file name.png]]`.
- Only create a Word or PowerPoint file when I ask for one.

---

## 4. Note format and Obsidian links

Start every note with YAML properties:

```yaml
---
skill: earnings-analysis
date: 2026-11-21
company: Apple          # leave out for sector or market notes
ticker: AAPL            # leave out if not relevant
sector: Consumer Electronics
tags: [equity-research, earnings-analysis]
---
```

**Links.** Link to other notes with Obsidian wikilinks wherever it helps a
reader move between related work:

- **Within the same company or sector:** link to the previous analysis, e.g.
  this earnings-analysis to the last one, model-update to the model it updates,
  thesis-tracker to its earlier versions. Add a line at the top:
  `Previous: [[companies/Apple/earnings-analysis 2026-08-02|Q3 earnings analysis]]`.
- **Company to sector:** a company analysis links to the latest note of its
  sector in `sector/`, and a sector note links to the company analyses that
  exist for the companies it discusses.
- **Competitors, suppliers, customers:** when one already has its own folder
  in `companies/`, link to its most recent analysis the first time it's
  mentioned.
- **Market notes:** screens, catalyst calendars and morning notes link to the
  company and sector notes for the names they mention, where those exist.
- **Other vault notes** used as leads (section 1) are linked in
  "Leads from the vault".

Use the full path inside the vault and a readable alias, so links stay
unambiguous: `[[companies/ASML/initiating-coverage task1 2026-11-21|ASML initiation]]`.
Only link where it adds something, not on every mention. Don't create empty
notes just to give a link a target.

---

## 5. General

- Get current figures from current sources: filings, company investor
  relations pages, web search. Cite sources with links and say how recent the
  data is.
- Say clearly what is a fact from a source, what is an estimate, and what is
  your own judgement.
- After saving, tell me the path of every file created.
