# Echoes of the Script — OpenLab

A peer-review toolkit for ancient script research. Log a claim, tie it to evidence, and run two independent checks — so conclusions are testable, not just plausible.

## What is this?

When researchers study ancient inscriptions (Egyptian hieroglyphs, undeciphered scripts, etc.), it's easy for claims to go unchecked. Someone says "this symbol means X" — but where's the evidence trail? Who verified it?

This toolkit gives you a **Falsifiability Sheet**: a one-page structured form that forces you to:

- State **one narrow, testable claim** about one artifact
- Record the **provenance and context** (where it came from, what collection it's in)
- Log **which evidence you actually consulted** (sign lists, object descriptions, etc.)
- Rate your **confidence** for each component separately
- Flag any **AI-assisted analysis** with a green/yellow/red traffic light
- Run **two independent peer reviews** (R1 verifies the evidence trail, R2 stress-tests for gaps)
- Record a **definitive outcome**: Confirmed, Revise, Defer, or Unproven

The goal: no claim gets published without a traceable evidence trail and independent review.

## Who is this for?

- Researchers and academics working with ancient texts and inscriptions
- Students learning epigraphic or paleographic methods
- Anyone who wants to apply structured, falsifiable reasoning to artifact analysis

## Quick start (2 minutes)

### 1. Read the quick-start guide

Open [`quickstart/Quick_Start_Falsifiability_Sheet_v5_TOP_R2_RULE.pdf`](quickstart/Quick_Start_Falsifiability_Sheet_v5_TOP_R2_RULE.pdf) — a one-page overview of the entire workflow and all field labels.

### 2. Download a template

Go to [`templates/`](templates/) and grab:

- **Blank Sheet** — start from scratch with your own artifact and claim
- **R2-ready Sheet** — pre-formatted for the second-rater review phase

### 3. See a worked example

Check [`worked-examples/`](worked-examples/) for a fully completed sheet using Ramesses II material, so you can see exactly what a finished entry looks like.

### 4. Try it yourself

Pick one artifact you're already familiar with (ideally well-understood material like Egyptian). Fill in the sheet following the 12-step workflow in the quick-start guide. This calibrates you on the process before tackling contested or undeciphered scripts.

## The 12-step workflow

| Step | What you do |
|------|-------------|
| 1 | Pick **one artifact** and write **one testable claim** (one sentence) |
| 2 | Fill in **CISI/context**: provenance, period, object type, museum ID, stable URL or DOI |
| 3 | Record **ORI** (reading direction) — if unknown, mark N/A; don't guess |
| 4 | Record **OVR** (overlay/alignment) — mark N/A if not used |
| 5 | Check only the **evidence types you actually used** |
| 6 | Set **confidence** separately for each component: T/R, P/A/O, ORI, G/OVR |
| 7 | Write **1-3 prep notes** justifying your confidence (short, factual, citeable) |
| 8 | If you used AI, paste output into **AI comments** and rate it: **G** (supported) / **Y** (incomplete) / **R** (contradicted) |
| 9 | **R1 review**: first reviewer verifies the evidence trail |
| 10 | **R2 review**: second reviewer stress-tests contradictions, alternatives, or gaps |
| 11 | Log **outcome**: Confirmed / Revise / Defer / Unproven — if reviewers disagree, log both |
| 12 | **Publish** the completed sheet (PDF) with back-links to source records |

**Lean workflow option:** A LIGHT pass logs traceability and provisional confidence. A FULL pass adds R1/R2 reviews (required for anything public-facing).

## Glossary

| Term | Meaning |
|------|---------|
| **CISI** | Collection/Institution + stable identifier (e.g., museum ID) |
| **ORI** | Orientation/reading direction (L-to-R, R-to-L, or N/A) |
| **OVR** | Overlay/alignment choice used to map a hypothesis; N/A if not used |
| **T/R** | Transcription/reading confidence |
| **P/A/O** | Category call confidence (Person/Animal/Object) |
| **G / G-OVR** | Glyph-first mode: confidence in glyph ID and/or overlay placement |
| **R1** | First independent peer check — verifies the evidence trail |
| **R2** | Second independent peer check — stress-tests contradictions and gaps |
| **AI G/Y/R** | AI risk traffic light: Green (supported), Yellow (incomplete), Red (contradicted) |
| **Out of scope** | Damaged/unclear artifacts or claims not responsibly testable with available evidence |

## Submit your work

1. Read the [Zenodo record abstract](https://zenodo.org/records/18518231) — it explains how community submission works
2. Complete your R2 (second-rater) check
3. Submit your finished sheet to the Zenodo community using the instructions in the abstract

## Repository structure

```
quickstart/       → One-page quick-start guide (PDF)
templates/        → Blank sheet + R2-ready sheet (PDFs)
worked-examples/  → Ramesses II fully worked example (PDF)
```

## License

[Mozilla Public License 2.0](LICENSE)

Created by Michael Grasa. Falsifiability Sheet content is CC BY 4.0 (where applicable).
