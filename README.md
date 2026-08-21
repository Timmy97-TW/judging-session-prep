# Judging Session Prep

An interactive board for iGEM 2026 Team ReLeaf, built for the 20-minute judging session.

**Live page:** https://timmy97-tw.github.io/judging-session-prep/

## What this is

The scores are already in when the session starts. Those twenty minutes decide whether a
judge confirms what they read or starts doubting it, and the podium holds five people.

This board divides the whole project across five minds. The split follows the causal chain
of the system rather than the wet / dry / human-practices subteams, because judges walk the
chain and stop where the logic thins. Splitting by subteam guarantees a silent pause on any
cross-cutting question.

| | Mind | Owns |
|---|---|---|
| M1 | Plant & Stress Biology | Stress models, plant assays, application, readouts, thresholds |
| M2 | Protectant Design | LEA14 / ACCD / NaD1, peptide design, MD, molecular weight cut-off |
| M3 | Gene Circuit & Cloning | MoClo, ccaS/ccaR, promoters, electroporation, Registry parts |
| M4 | Bioreactor & Hardware | Reactor DBTL, hollow fibre, photometer, LPA, containment |
| M5 | Deployment & Human Practices | Geospatial, farmers, education, regulation, business |

Every column is populated in all three subteam rows. That is the test of whether the split holds.

## Using it

- **Hover or click an entry** to read it in full in the strip below the board.
- **Trace a thread** to light the entries that share one number or decision across columns.
- **Click a judging question** to light the entries that answer it, with a coverage count per
  mind and a warning where coverage is thin.
- **Full screen** puts the whole board on one screen for team review.
- **EN / 中文** toggles the entire page, English by default.

## Judging questions

Nine project questions build the score that decides Grand Prize, Finalist and Village
rankings. Three special-award rubrics cover the team's nominations: Measurement, Hardware and
Integrated Human Practices. Each judge's Gold vote is inferred from those same rubric scores,
so a weak third nomination is a Gold risk rather than only a lost award.

Question text is taken from the iGEM 2026 Judge Handbook (project questions p.31,
Hardware p.57, Integrated Human Practices p.65, Measurement p.68).

## Sources

Content is drawn from the team's own stakeholder engagement log, education log and business
plan draft. The "Known holes" and "Stress tests" sections record real gaps and real
contradictions found in those documents, so the team names them before a judge does.

## Development

A single self-contained `index.html`. No build step and no dependencies beyond Google Fonts.
Open it directly in a browser to work on it.
