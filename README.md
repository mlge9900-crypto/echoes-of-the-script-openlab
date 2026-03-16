# Echoes of the Script — OpenLab

**A repeatable review workflow for ancient-script claims — including AI-assisted claims — built to make evidence traceable, testable, and reviewable.**

| | |
|---|---|
| **Status** | Prototype — actively maintained |
| **Current Version** | v1.0-alpha |
| **License** | [MPL-2.0](LICENSE) (code) · CC BY 4.0 (sheet content) |
| **Founder** | Michael Grasa |
| **Contact** | mlge9900@gmail.com |
| **Zenodo** | [https://zenodo.org/records/18518231](https://zenodo.org/records/18518231) |
| **Support** | [Fractured Atlas](https://fundraising.fracturedatlas.org/echoes-of-the-script-public-decoding-pop-ups) |

---

## The problem

Claims about ancient scripts can spread quickly, especially when AI is involved.
But many of those claims are hard to check. A reader often cannot tell:

- what evidence was used,
- what image or object was examined,
- what was inferred versus directly observed,
- whether another reviewer checked the claim,
- or whether AI was treated as evidence instead of just input.

This project exists to slow that problem down and make claims easier to inspect.

## What this is

This repository houses a **repeatable verification workflow** for evaluating claims about ancient writing and related heritage material.

It includes:

- a structured one-page review sheet (the **Falsifiability Sheet**),
- worked examples showing completed sheets,
- a two-reviewer workflow with defined roles,
- field labels and a glossary,
- and a method for recording how AI tools were used without letting them act as authority.

This is **not** a tool that asks people to trust AI.
It is a workflow that asks people to **document claims clearly, review them carefully, and separate evidence from interpretation**.

## How it works

The workflow is simple at a high level:

**claim → fill sheet → reviewer 1 → reviewer 2 → outcome**

In practice, that means:

1. A researcher identifies one artifact and writes one testable claim about it.
2. The supporting evidence is recorded — which sources were checked, which were not.
3. The object, image, or inscription is described with provenance (museum, collection ID, stable URL).
4. The researcher notes what is directly visible versus inferred, and rates confidence separately for each component.
5. AI output, if used, is logged as input and rated: supported, incomplete, or contradicted.
6. A first reviewer verifies the evidence trail (not just the conclusion).
7. A second reviewer checks independently, stress-testing for contradictions and gaps.
8. The final outcome is recorded: **Confirmed**, **Revise**, **Defer**, or **Unproven**.

The result is a single auditable page. Anyone can pick it up and see what was claimed, what was checked, what the reviewers found, and whether the claim held.

## Example output

A completed Falsifiability Sheet for a Ramesses II cartouche (British Museum EA1006). One claim, one artifact, both peer reviews recorded, outcome: Confirmed.

![Completed Falsifiability Sheet — Ramesses II cartouche, British Museum EA1006](assets/ramesses-ii-example.png)

[Download the full worked-example PDF](worked-examples/Falsifiability_Sheet_v5vai2_RamessesII_WorkedExample.pdf)

## How ChatGPT fits into this workflow

AI tools such as ChatGPT, Claude, or Gemini may be used inside this workflow, but their role is limited.

**AI can:**
- suggest interpretations,
- summarize visible patterns,
- offer possible readings,
- help generate comparison ideas,
- support structured note-taking.

**AI cannot:**
- act as final authority,
- replace reviewer judgment,
- raise confidence by itself,
- count as evidence on its own.

The key rule is: **AI is logged input, not authority.**

In practice, that means: paste the AI's output into the "AI comments" section of the sheet, then rate it using a traffic light:

- **Green:** AI output is supported by the physical evidence and published sources.
- **Yellow:** AI output is plausible but incomplete — evidence doesn't fully confirm or deny it.
- **Red:** AI output is contradicted by the evidence, or makes unsupported leaps.

Both peer reviewers see the AI output and can check whether it was rated fairly.

The real question is never just "Did you use AI?"
The real question is: **"Does the evidence support what the AI suggested?"**

## Quick start

1. **See what a finished sheet looks like** — open [`worked-examples/`](worked-examples/) for a completed Ramesses II sheet with both peer reviews and a final outcome.
2. **Read the one-page guide** — open [`quickstart/`](quickstart/) for every step and field label on one page, with a glossary on the right.
3. **Download a template** — go to [`templates/`](templates/) and grab:
   - **Blank Sheet** — start from scratch with your own artifact and claim
   - **Second-reviewer Sheet** — pre-formatted for someone doing the second peer review
4. **Compare** the claim, evidence, reviewer notes, and outcome across the example and the blank.
5. **Try the workflow on one small case** — start with well-understood material (e.g., Egyptian hieroglyphs) to learn the form before tackling contested or undeciphered scripts.

## Who this is for

- Humanities researchers working with ancient texts and inscriptions
- Epigraphers and paleographers
- Historians evaluating contested or AI-generated readings
- Digital humanities scholars incorporating AI into artifact analysis
- Grant reviewers looking for structured verification methods
- Public-interest AI researchers studying how AI claims are audited
- Pilot partners interested in stress-testing the method on real material

## The full workflow (12 steps)

| Step | What you do |
|------|-------------|
| 1 | Pick **one artifact** and write **one testable claim** (one sentence) |
| 2 | Fill in **context**: where it's from, what period, what collection/museum, catalog ID, stable URL or DOI |
| 3 | Record **reading direction** (left-to-right, right-to-left, or mark N/A if unknown — don't guess) |
| 4 | Record **overlay/alignment choice** if you used one to map your hypothesis; mark N/A if not used |
| 5 | Check only the **evidence types you actually consulted** (sign list, object description, provenance record, etc.) |
| 6 | Set **confidence separately** for each component: transcription/reading, category (person/animal/object), reading direction, glyph/overlay |
| 7 | Write **1–3 prep notes** justifying your confidence ratings (short, factual, citeable) |
| 8 | If you used AI: paste the output into **AI comments** and rate it Green / Yellow / Red (see above) |
| 9 | **Peer review 1**: a reviewer verifies your evidence trail (not just your conclusion) |
| 10 | **Peer review 2**: a second reviewer stress-tests for contradictions, alternatives, or gaps |
| 11 | Log **outcome**: Confirmed / Revise / Defer / Unproven — if reviewers disagree, log both |
| 12 | **Publish** the completed sheet (PDF) with back-links to source records |

**Lean option:** A LIGHT pass logs traceability and provisional confidence (good for early-stage work). A FULL pass adds both peer reviews (required for anything public-facing).

## Field labels (glossary)

The sheet uses short labels to fit on one page. Here's what they mean:

| On the sheet | What it means |
|---|---|
| **CISI** | Collection/Institution + stable identifier (e.g., "British Museum EA1006") |
| **ORI** | Orientation — the reading direction you chose (left-to-right, right-to-left, or N/A) |
| **OVR** | Overlay — an alignment or mapping you applied to test your hypothesis; N/A if not used |
| **T/R** | Your confidence in your transcription/reading of the text |
| **P/A/O** | Your confidence in categorizing what's depicted (Person, Animal, or Object) |
| **G / G-OVR** | Your confidence in glyph identification and/or overlay placement |
| **R1** | Peer review 1 — verifies the evidence trail |
| **R2** | Peer review 2 — stress-tests for contradictions and gaps |
| **AI G/Y/R** | AI traffic light — Green (supported), Yellow (incomplete), Red (contradicted) |
| **Out of scope** | Damaged or unclear artifacts, or claims that can't be responsibly tested with available evidence |

## Submit your work

Interested in testing the workflow on a real case? I'm currently looking for:

- 2–3 serious testers willing to run the sheet on their own material,
- reviewer feedback on the workflow and field labels,
- and pilot collaborators who want to stress-test the method on real cases.

To submit a completed sheet to the community archive:

1. Read the [Zenodo record abstract](https://zenodo.org/records/18518231) — it explains how community submission works
2. Complete both peer reviews (reviewer 1 and reviewer 2)
3. Submit your finished sheet to the Zenodo community using the instructions in the abstract

To get in touch: [mlge9900@gmail.com](mailto:mlge9900@gmail.com)

## Repository structure

```
quickstart/       → One-page quick-start guide (PDF)
templates/        → Blank sheet + second-reviewer sheet (PDFs)
worked-examples/  → Ramesses II fully worked example (PDF)
```

## Roadmap

This project is currently a **prototype**. The Falsifiability Sheet is designed to be read by any multimodal AI (e.g., Claude, GPT-4) directly from a photo or scan — no software installation required.

**Current phase:** Paper/PDF-based workflow with AI integration via image recognition.

**Future phases:**
- Web-based form with structured data output (JSON)
- Validation tooling to auto-check field completeness and consistency
- Scalable deployment across institutions and research communities
- Additional worked examples across different script traditions

## Support the Open Lab

Echoes of the Script is supported through Fractured Atlas. Donations fund workflow updates, new worked examples, open research infrastructure, and future digitization of the sheet into a web-based tool.

[Support the lab via Fractured Atlas](https://fundraising.fracturedatlas.org/echoes-of-the-script-public-decoding-pop-ups)

## License

[Mozilla Public License 2.0](LICENSE)

Created by Michael Grasa. Falsifiability Sheet content is CC BY 4.0 (where applicable).
