# Judging Session Prep

An interactive board for iGEM 2026 Team ReLeaf, built for the 20-minute judging session.

**Live page:** https://timmy97-tw.github.io/judging-session-prep/

## What this is

The scores are already in when the session starts. Those twenty minutes decide whether a
judge confirms what they read or starts doubting it, and the podium holds five people.

This board divides the whole project across six minds. The split follows the causal chain
of the system rather than the wet / dry / human-practices subteams, because judges walk the
chain and stop where the logic thins. Splitting by subteam guarantees a silent pause on any
cross-cutting question.

| | Mind | Owns |
|---|---|---|
| M1 | Plant & Stress Biology | Stress models, plant assays, application, readouts, thresholds |
| M2 | Protectant Design | LEA 14 and ACC deaminase, peptide design, MD, molecular weight cut-off |
| M3 | Gene Circuit & Cloning | MoClo, ccaS/ccaR, promoters, electroporation, Registry parts |
| M4 | Bioreactor & Hardware | Reactor DBTL, hollow fibre, photometer, LPA, containment |
| M5 | Human Practices & Regulation | Farmers, regulation, safety envelope, education, geospatial |
| M6 | Business & Entrepreneurship | Unit economics, spec floor, cost of goods, impact model, Taiwan market |

M5 asks whether this is responsible, legal and wanted. M6 asks whether it works, what it costs and how
much it changes. Regulation splits along that seam: M5 owns the research and the expert relationships,
M6 owns what the pathway costs in time and capital.

The business plan stands on five lines of the team's own data rather than published figures, and each
line comes from a different mind:

1. **It works** (M1) — the LPA dose–response curve and the plant rescue against four controls
2. **The spec floor** (M1, M2) — the lowest enzyme activity that still moves a plant readout
3. **The unit cost** (M4) — membrane, media, consumables, power draw, replacement cycle
4. **The impact number** (M5, M1) — the geospatial surface folded into the rescue data and the model
5. **The pathway and the market** (M5) — which statute applies, what it costs, what farmers spend today

Entrepreneurship carries no rubric of its own this year, so that work is scored inside project questions
1 and 3 and has to arrive as numbers.

Three chains run sideways through the board. **Map into numbers** takes the geospatial surface through the
stress model to a device count and a market size. **Device and cartridge** takes the reactor's build cost
and cartridge interval into the business model. **One chassis, many products** takes the swappable
cassette from a cloning decision to a product line. Trace any of them from an entry that carries it.

All five columns are populated in all three subteam rows. That is the point: no one on the podium gets to be
only a wet lab person, only a dry lab person, or only an HP person. Each mind needs a bench result, a
calculation and a conversation with an outside expert in the same head.

## Using it

- **Hover or click an entry** to read it in full in the strip below the board.
- **Trace a thread** to light the entries that share one number or decision across columns.
- **Click a judging question** to light the entries that answer it, with a coverage count per
  mind and a warning where coverage is thin.
- **Hover a column header** to watch one mind cut through all three subteam rows.
- **Download .xlsx** builds a four-sheet workbook from whatever is on screen, in the language you are
  reading. Pre-built copies sit in this repo as
  [`releaf-six-minds-en.xlsx`](releaf-six-minds-en.xlsx) and
  [`releaf-six-minds-zh.xlsx`](releaf-six-minds-zh.xlsx).
- **Full screen** puts the whole board on one screen for team review.
- **EN / 中文** toggles the entire page, English by default.

## Judging questions

Nine project questions build the score that decides Grand Prize, Finalist and Village
rankings. Three special-award rubrics cover the team's nominations: Measurement, Hardware and
Integrated Human Practices. Each judge's Gold vote is inferred from those same rubric scores,
so a weak third nomination is a Gold risk rather than only a lost award.

Question text is taken from the iGEM 2026 Judge Handbook (project questions p.31,
Hardware p.57, Integrated Human Practices p.65, Measurement p.68).

## The spreadsheet

Four sheets: the full matrix one row per entry, a per-mind coverage table, the 23 judge questions with
their lead minds, and the build list. Written client-side with no dependencies, so the file always
matches the page.

## Sources

Content is drawn from the team's own stakeholder engagement log, education log, business plan draft and
risk register. "What to build next" lists twelve pieces of work with the score each one moves, and
"Stress tests" records real contradictions found in those documents, so the team names them before a
judge does.

Every one of the 23 judge questions maps to a designed combination of entries, with the lead minds named.

## Development

A single self-contained `index.html`. No build step and no dependencies beyond Google Fonts.
Open it directly in a browser to work on it.
