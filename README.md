# Echoes of the Script — OpenLab for Ancient Scripts

**A one-page peer-review form that makes ancient script claims testable, traceable, and auditable — including claims made with AI.**

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

Someone studies an ancient inscription and says: *"This symbol means X."* But where's the evidence? Which sources did they check? Did anyone else verify it? And if they used ChatGPT or Claude to help — did they log what the AI said, and did it actually hold up?

Right now, there's no standard way to answer those questions. Claims about ancient scripts get shared, cited, and built on — without a traceable evidence trail or independent review.

## What this is

This toolkit gives you a **Falsifiability Sheet** — a one-page structured form you fill out for a single claim about a single artifact. It forces you to:

1. **State one testable claim** (not a theory — one specific, falsifiable sentence)
2. **Record where the artifact comes from** (museum, collection, catalog ID, stable URL)
3. **Log which evidence you actually checked** (sign lists, object descriptions, provenance records)
4. **Rate your own confidence** for each part of your analysis, separately
5. **Log any AI output** and rate whether it was supported, incomplete, or contradicted by the evidence
6. **Get two independent peer reviews** — one verifies your evidence trail, the other stress-tests for gaps
7. **Record a final outcome**: Confirmed, Revise, Defer, or Unproven

The result is a single auditable page. Anyone can pick it up, see what you claimed, what you checked, what the AI said, what the reviewers found, and whether the claim held.

## How it works

```
You claim          →  You fill the sheet  →  Reviewer 1         →  Reviewer 2         →  Outcome
"This cartouche       (artifact, source,     checks your           stress-tests for      Confirmed /
reads Ramesses II"    evidence, confidence,  evidence trail        contradictions        Revise /
                      AI output if used)                           and gaps              Defer /
                                                                                         Unproven
```

That's it. One artifact, one claim, one sheet. No claim gets published without a traceable trail and two independent checks.

**Lean option:** A LIGHT pass logs traceability and provisional confidence (good for early-stage work). A FULL pass adds both peer reviews (required for anything public-facing).

## How ChatGPT fits into this workflow

AI (ChatGPT, Claude, Gemini, etc.) is treated as **logged input, not authority.**

Here's what that means in practice:

- **You can use AI** — to read glyphs, suggest interpretations, identify parallels, check sign lists, or anything else. There is no penalty for using it.
- **You must log what it said** — paste the AI's output into the "AI comments" section of the sheet.
- **You must rate it honestly** using a traffic light:
  - **Green:** AI output is supported by the physical evidence and published sources
  - **Yellow:** AI output is plausible but incomplete — evidence doesn't fully confirm or deny it
  - **Red:** AI output is contradicted by the evidence, or makes unsupported leaps
- **Reviewers see the AI output** — both peer reviewers can check whether you rated the AI fairly and whether it influenced your conclusion without justification.

The Falsifiability Sheet does not ban AI. It audits AI. The question is never "did you use AI?" — it's "does the evidence support what the AI said?"

## Quick start

### 1. See what a finished sheet looks like

Check [`worked-examples/`](worked-examples/) — a fully completed sheet using a Ramesses II cartouche from the British Museum (EA1006). This shows every field filled in, both peer reviews recorded, and a final outcome of "Confirmed."

### 2. Read the one-page guide

Open [`quickstart/`](quickstart/) — a one-page PDF that lists every step and every field label, with a glossary on the right side.

### 3. Download a template and try it

Go to [`templates/`](templates/) and grab:

- **Blank Sheet** — start from scratch with your own artifact and claim
- **Second-reviewer Sheet** — pre-formatted for someone doing the second peer review

**Tip:** Start with well-understood material (e.g., Egyptian hieroglyphs) to learn the form before tackling contested or undeciphered scripts.

## The 12-step workflow

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

## Field labels (glossary)

The sheet uses short labels to fit on one page. Here's what they mean:

| On the sheet | What it means |
|------|---------|
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

## Who is this for?

- Researchers and academics working with ancient texts and inscriptions
- Students learning epigraphic or paleographic methods
- Digital humanities scholars incorporating AI into artifact analysis
- Anyone who wants a structured, falsifiable approach to interpreting ancient writing

## Submit your work

1. Read the [Zenodo record abstract](https://zenodo.org/records/18518231) — it explains how community submission works
2. Complete both peer reviews (reviewer 1 and reviewer 2)
3. Submit your finished sheet to the Zenodo community using the instructions in the abstract

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

## Support the Open Lab

Echoes of the Script is supported through Fractured Atlas. Donations fund workflow updates, new worked examples, open research infrastructure, and future digitization of the sheet into a web-based tool.

[Support the lab via Fractured Atlas](https://fundraising.fracturedatlas.org/echoes-of-the-script-public-decoding-pop-ups)

## License

[Mozilla Public License 2.0](LICENSE)

Created by Michael Grasa. Falsifiability Sheet content is CC BY 4.0 (where applicable).
