# Echoes of the Script — OpenLab

**A repeatable claim-record verification workflow for AI-assisted humanities and heritage interpretation.**

Claims about ancient scripts spread fast — especially when AI is involved. This toolkit slows that down. Every claim is logged, bounded to one artifact, tied to evidence, and checked by two independent human reviewers before it is trusted.

> **Start here:** Open the [completed Ramesses II example](worked-examples/Falsifiability_Sheet_v5vai2_RamessesII_WorkedExample.pdf) — it shows exactly what a finished, reviewed claim record looks like.

| | |
|---|---|
| **Status** | Prototype — actively maintained |
| **Repo version** | v1.0-alpha |
| **Sheet version** | Falsifiability Sheet v5 |
| **License** | [MPL-2.0](LICENSE) (code) · CC BY 4.0 (sheet content) |
| **Zenodo** | [zenodo.org/records/18518231](https://zenodo.org/records/18518231) |
| **Cite this** | See [CITATION.cff](CITATION.cff) |

---

## Start here in 3 minutes

1. **Open the finished worked example** — [Ramesses II Falsifiability Sheet (PDF)](worked-examples/Falsifiability_Sheet_v5vai2_RamessesII_WorkedExample.pdf)
   One claim. One artifact. Evidence logged. Both peer reviews recorded. Outcome: Confirmed.

2. **See why it counts** — the sheet below it passed the full trust chain (see [Proof strip](#how-the-trust-chain-works)). That is what makes it a verified claim record, not just a filled-in form.

3. **See the second-reviewer template** — [Second Reviewer Blank Template (PDF)](templates/Second_Reviewer_Blank_Template.pdf)
   This is the blank form the independent second reviewer uses to stress-test the claim.

4. **Ready to try it yourself?** Jump to [Quick start](#quick-start) or grab a [blank template](templates/Falsifiability_Sheet_v5vai2_Blank.pdf).

---

## How the trust chain works

A completed sheet carries weight because it passed every stage of this chain:

```
Claim recorded          →  One testable statement about one artifact
Evidence bounded        →  Sources checked and unchecked are both logged
AI logged (if used)     →  Prompt, output, and rating recorded — not hidden
Reviewer 1 checked      →  Verified the evidence trail (not just the conclusion)
Reviewer 2 checked      →  Independent stress-test for contradictions and gaps
Outcome recorded        →  Confirmed · Revise · Defer · Unproven
```

No stage can be skipped. If both reviewers are not recorded, the sheet is provisional, not verified. The worked example shows every stage completed.

---

## The problem

Claims about ancient scripts are hard to check. A reader often cannot tell:

- what evidence was used,
- what was inferred versus directly observed,
- whether AI was treated as evidence instead of logged input,
- or whether anyone else reviewed the claim independently.

This is worse when AI is involved, because AI outputs can sound authoritative while being wrong. This project exists to make claims inspectable and reviewable.

---

## What this is

A **repeatable verification workflow** for evaluating claims about ancient writing and heritage material.

It includes:

- a structured one-page review sheet (the **Falsifiability Sheet**),
- a worked example showing a completed, reviewed sheet,
- a two-reviewer workflow with defined roles,
- field labels and a glossary,
- and a method for recording AI involvement without letting AI act as authority.

This is **not** a tool that asks people to trust AI.
It is a workflow that asks people to **document claims clearly, review them carefully, and separate evidence from interpretation**.

---

## Example output

A completed Falsifiability Sheet for a Ramesses II cartouche (British Museum EA1006). One claim, one artifact, both peer reviews recorded, outcome: Confirmed.

![Completed Falsifiability Sheet — Ramesses II cartouche, British Museum EA1006](assets/ramesses-ii-example.png)

[Download the full worked-example PDF](worked-examples/Falsifiability_Sheet_v5vai2_RamessesII_WorkedExample.pdf)

---

## How ChatGPT / AI fits into this workflow

AI tools (ChatGPT, Claude, Gemini, or others) can be used inside this workflow. Their role is strictly limited: **AI is logged input, not authority.**

**AI can:**
- suggest interpretations or possible readings,
- summarize visible patterns,
- help generate comparison ideas,
- support structured note-taking.

**AI cannot:**
- act as final authority on any claim,
- replace reviewer judgment,
- raise confidence on its own,
- count as evidence.

### What gets logged

When AI is used, the sheet records:

| Field | Example |
|---|---|
| **Prompt used** | "Identify the cartouche glyphs in this image of EA1006" |
| **Output used** | "The cartouche reads Wsr-Mꜣꜥt-Rꜥ Stp-n-Rꜥ (Ramesses II throne name)" |
| **Accepted or rejected** | Accepted — consistent with published BM catalog reading |
| **Sources checked against** | Kitchen, *Ramesside Inscriptions* vol. II; BM online catalog |
| **Model / version / date** | ChatGPT-4o, 2025-01-15 |

Both peer reviewers see this log and rate the AI output using a traffic light:

- **Green:** AI output is supported by the physical evidence and published sources.
- **Yellow:** AI output is plausible but incomplete — evidence doesn't fully confirm or deny it.
- **Red:** AI output is contradicted by the evidence, or makes unsupported leaps.

The real question is never "Did you use AI?" The real question is: **"Does the evidence support what the AI suggested?"**

---

## Quick start

1. **See what a finished sheet looks like** — open the [Ramesses II worked example (PDF)](worked-examples/Falsifiability_Sheet_v5vai2_RamessesII_WorkedExample.pdf) for a completed sheet with both peer reviews and a final outcome.
2. **Read the one-page guide** — open [`quickstart/`](quickstart/) for every step and field label on one page, with a glossary on the right.
3. **Download a template:**
   - [**Blank Sheet**](templates/Falsifiability_Sheet_v5vai2_Blank.pdf) — start from scratch with your own artifact and claim
   - [**Second Reviewer Blank Template**](templates/Second_Reviewer_Blank_Template.pdf) — blank form for the independent second reviewer
4. **Compare** the claim, evidence, reviewer notes, and outcome across the example and the blank.
5. **Try the workflow on one small case** — start with well-understood material (e.g., Egyptian hieroglyphs) to learn the form before tackling contested or undeciphered scripts.

> **Three documents, three purposes:**
> The *worked example* shows what a finished, reviewed sheet looks like. The *blank sheet* is where the original author records their claim and evidence. The *second reviewer blank template* is a separate form for the independent second reviewer — it is not a copy of the blank sheet.

---

## Who this is for

- Humanities researchers working with ancient texts and inscriptions
- Epigraphers and paleographers
- Historians evaluating contested or AI-generated readings
- Digital humanities scholars incorporating AI into artifact analysis
- Grant reviewers looking for structured verification methods
- Public-interest AI researchers studying how AI claims are audited
- Pilot partners interested in stress-testing the method on real material

---

## How it works (the full 12 steps)

The workflow is simple at a high level:

**claim → fill sheet → reviewer 1 → reviewer 2 → outcome**

In practice:

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
| 9 | **Reviewer 1**: a reviewer verifies your evidence trail (not just your conclusion) |
| 10 | **Reviewer 2**: a second reviewer stress-tests for contradictions, alternatives, or gaps |
| 11 | Log **outcome**: Confirmed / Revise / Defer / Unproven — if reviewers disagree, log both |
| 12 | **Publish** the completed sheet (PDF) with back-links to source records |

**Lean option:** A LIGHT pass logs traceability and provisional confidence (good for early-stage work). A FULL pass adds both peer reviews (required for anything public-facing).

---

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
| **R1** | Reviewer 1 — verifies the evidence trail |
| **R2** | Reviewer 2 — stress-tests for contradictions and gaps |
| **AI G/Y/R** | AI traffic light — Green (supported), Yellow (incomplete), Red (contradicted) |
| **Out of scope** | Damaged or unclear artifacts, or claims that can't be responsibly tested with available evidence |

---

## Versioning

This project has three version numbers. They are independent:

| What | Current | Meaning |
|---|---|---|
| **Repository** | v1.0-alpha | The GitHub repo structure, docs, and templates |
| **Falsifiability Sheet** | v5 | The one-page review form (field layout, labels, sections) |
| **Workflow maturity** | Prototype | The overall readiness level for public use |

The sheet version (v5) is higher than the repo version (v1.0-alpha) because the sheet went through several iterations before this repository was created. This is normal — the method predates the repo.

---

## What works now vs. what comes next

### Usable now

- Full paper/PDF-based workflow — no software installation required
- Blank template and second-reviewer template (downloadable PDFs)
- One completed worked example with both peer reviews
- Quick-start guide with field glossary
- Zenodo integration for archival and community submission
- The Falsifiability Sheet is designed to be readable by any multimodal AI (e.g., Claude, GPT-4) directly from a photo or scan

### Coming next

- Additional worked examples across different script traditions
- Web-based form with structured data output (JSON)
- Validation tooling to auto-check field completeness and consistency
- Scalable deployment across institutions and research communities

---

## Submit your work

Interested in testing the workflow on a real case? I'm currently looking for:

- 2–3 serious testers willing to run the sheet on their own material,
- reviewer feedback on the workflow and field labels,
- and pilot collaborators who want to stress-test the method on real cases.

To submit a completed sheet to the community archive:

1. Read the [Zenodo record abstract](https://zenodo.org/records/18518231) — it explains how community submission works
2. Complete both peer reviews (Reviewer 1 and Reviewer 2)
3. Submit your finished sheet to the Zenodo community using the instructions in the abstract

To get in touch: [mlge9900@gmail.com](mailto:mlge9900@gmail.com)

---

## Repository structure

```
quickstart/       → One-page quick-start guide (PDF)
templates/        → Blank sheet + second-reviewer sheet (PDFs)
worked-examples/  → Ramesses II fully worked example (PDF)
assets/           → Images used in this README
```

---

## Support the Open Lab

Echoes of the Script is a fiscally sponsored project of [Fractured Atlas](https://fundraising.fracturedatlas.org/echoes-of-the-script-public-decoding-pop-ups), a non-profit arts service organization. Donations fund workflow updates, new worked examples, open research infrastructure, and future digitization of the sheet into a web-based tool.

[Support the lab via Fractured Atlas](https://fundraising.fracturedatlas.org/echoes-of-the-script-public-decoding-pop-ups)

---

## License

[Mozilla Public License 2.0](LICENSE)

Created by Michael Grasa. Falsifiability Sheet content is CC BY 4.0 (where applicable).
