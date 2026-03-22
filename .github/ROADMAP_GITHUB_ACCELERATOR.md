# Roadmap: GitHub Accelerator Application

**Goal:** Apply to the GitHub Accelerator ($20K sponsorship, 10-week program)
**Project:** Echoes of the Script — OpenLab
**Maintainer:** Michael Grasa
**Current status:** ~50% ready
**Target:** Next open cohort (monitor https://accelerator.github.com)

---

## What the Accelerator Looks For

1. An open source project with a clear purpose and active maintenance
2. A **software component** (code people can use, install, or run)
3. Community traction (stars, forks, contributors, users)
4. A maintainer with a GitHub Sponsors profile (required to receive the $20K)
5. A credible plan for sustainability and growth

---

## What You Already Have (Completed)

- [x] Public GitHub repository with clean structure
- [x] Open source license (MPL-2.0 + CC BY 4.0)
- [x] CITATION.cff for academic citation
- [x] CONTRIBUTING.md with clear contribution paths
- [x] SECURITY.md with reporting policy
- [x] Zenodo integration (https://zenodo.org/records/18518231)
- [x] Well-documented 12-step methodology
- [x] Templates (Blank Sheet + R2-ready Sheet)
- [x] One fully worked example (Ramesses II)
- [x] Quick-start guide

---

## Phase 1: Foundation (Week 1)

**Priority: HIGH — Do these first**

### 1.1 Enable GitHub Sponsors

- Go to https://github.com/sponsors and set up your profile
- This is **required** to receive the $20K sponsorship
- You need a Stripe account or fiscal host (Open Collective works too)
- Estimated time: 1-2 hours (approval may take a few days)

### 1.2 Add a DOI Badge to README

- Your Zenodo record should provide a DOI
- Add the DOI badge to the top of your README for academic credibility
- Example: `[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)`

### 1.3 Add a CHANGELOG

- Create a `CHANGELOG.md` tracking your version history
- Start with v1.0-alpha and list what's included
- This shows active, organized development

---

## Phase 2: Build a Software Component (Weeks 1-3)

**Priority: CRITICAL — This is the single biggest gap**

The Accelerator funds **software projects**. Right now you have PDFs and documentation, but no code. You need at least one of the following:

### Option A: Web-Based Sheet Generator (Recommended)

Build a simple web form where users:
1. Fill in their artifact claim, provenance, evidence, and confidence ratings
2. Get a completed Falsifiability Sheet as a downloadable PDF
3. Optionally validate that all required fields are filled

**Tech stack suggestion:** HTML/CSS/JavaScript (static site, host on GitHub Pages)

**Why this is the best option:**
- Lowest barrier to entry for new users
- Deployable for free on GitHub Pages
- Visible, demonstrable product for the application
- Can grow into a full platform over time

### Option B: Python CLI Validator

Build a command-line tool that:
1. Reads a filled-in sheet (JSON or YAML format)
2. Validates completeness (all 12 steps covered)
3. Flags missing fields, unsupported confidence ratings, or missing AI disclosures
4. Outputs a pass/fail report

**Tech stack:** Python, installable via `pip install falsifiability-sheet`

**Why this works:**
- Fits the open source software model perfectly
- Scriptable, testable, CI-friendly
- Could integrate into academic workflows

### Option C: Structured Data Schema

Create a machine-readable schema for the Falsifiability Sheet:
1. JSON Schema defining all fields, types, and validation rules
2. Example JSON files for each worked example
3. A small validation script

**Why this works:**
- Lightweight to build
- Makes the project interoperable with other tools
- Opens the door to API integrations

**Recommendation:** Start with **Option A** (web form) for maximum visibility, then add **Option C** (schema) for technical credibility.

---

## Phase 3: Expand Worked Examples (Week 2-3)

**Priority: MEDIUM**

One example (Ramesses II) is not enough. Add 2-3 more to show the methodology works across different contexts:

### Suggested Examples

| Example | Script System | Why It's Useful |
|---------|--------------|-----------------|
| Rosetta Stone excerpt | Egyptian + Greek | Well-known, demonstrates bilingual analysis |
| Indus Valley seal | Undeciphered | Shows how the sheet handles "Defer" or "Unproven" outcomes |
| Cuneiform tablet | Mesopotamian | Demonstrates a different script family entirely |
| Linear B tablet | Mycenaean Greek | Demonstrates a deciphered-but-complex system |

Pick at least **two** that you can complete with real sources.

---

## Phase 4: Build Community Traction (Weeks 2-6)

**Priority: HIGH — Start early, takes time to grow**

### 4.1 Share in Academic Communities

Post about the project in:
- Digital Humanities forums and mailing lists
- Epigraphy/paleography academic groups
- Reddit: r/AncientLanguages, r/Archaeology, r/DigitalHumanities
- Twitter/X: tag relevant academics and DH practitioners
- Mastodon: scholar.social and similar instances

### 4.2 Reach Out to Potential Contributors

- Contact 3-5 colleagues or students who work with ancient scripts
- Ask them to try filling in a sheet and give feedback
- Invite them to submit their completed sheets to Zenodo
- Even 1-2 external contributors strengthens the application significantly

### 4.3 Gather GitHub Stars and Engagement

- Add "Star this repo" call-to-action in your README
- Share the repo link when discussing the methodology
- Respond promptly to any issues or discussions
- Target: **20+ stars** before applying

### 4.4 Open GitHub Discussions

- Enable the Discussions tab on your repo
- Create a welcome thread explaining the project
- Post questions to engage potential users (e.g., "What scripts would you like to see examples for?")

---

## Phase 5: Polish the Application (Week 5-6)

**Priority: HIGH — Do this before applying**

### 5.1 Write a Project Narrative

Draft a 2-paragraph summary that answers:
- **What problem does this solve?** (Unverified claims in ancient script research undermine academic integrity)
- **Why does it matter?** (AI tools are making it easier to generate plausible-but-wrong interpretations; this toolkit provides a structured verification layer)
- **Who uses it?** (Researchers, students, heritage professionals)
- **What's your growth plan?** (Expand to more script systems, build community of peer reviewers, integrate with academic publishing workflows)

### 5.2 Record a 2-Minute Demo

- Screen-record yourself filling in a sheet (or using the web tool from Phase 2)
- Upload to YouTube (unlisted is fine)
- Link it in your application — this makes your project tangible to reviewers

### 5.3 Update README with Software Section

Once you've built the software component, update the README to:
- Link to the live tool (GitHub Pages) or installation instructions
- Add usage examples
- Include a "Contributing code" section in CONTRIBUTING.md

---

## Phase 6: Apply (When Cohort Opens)

### Application Checklist

Before submitting, confirm you have:

- [ ] GitHub Sponsors profile active and receiving-ready
- [ ] At least one working software component (web form, CLI, or schema)
- [ ] 3+ worked examples across different script systems
- [ ] 20+ GitHub stars
- [ ] At least 2 external contributors or users
- [ ] Updated README reflecting the software component
- [ ] Project narrative written (2 paragraphs)
- [ ] Demo video recorded
- [ ] Zenodo community with at least 1 external submission
- [ ] CHANGELOG.md with version history

### Where to Apply

- **URL:** https://accelerator.github.com
- **Watch for announcements:** Follow @github on Twitter/X and check the GitHub Blog
- Applications typically open once per year (historically Q1)

---

## Stretch Goals (After Application)

These are not required for the application but would strengthen a future reapplication or help you grow post-acceptance:

- [ ] Publish an academic paper describing the methodology
- [ ] Build a review-matching system (connect R1/R2 reviewers with submissions)
- [ ] Create a GitHub Action that validates sheets in CI pipelines
- [ ] Integrate with ORCID for reviewer identity verification
- [ ] Build an API that other academic tools can call

---

## Timeline Summary

| Week | Focus | Key Deliverable |
|------|-------|-----------------|
| 1 | Foundation | GitHub Sponsors active, DOI badge, CHANGELOG |
| 1-3 | Software | Web form or CLI tool live and usable |
| 2-3 | Examples | 2-3 new worked examples added |
| 2-6 | Community | Share widely, gather stars, recruit contributors |
| 5-6 | Application prep | Narrative, demo video, README update |
| TBD | Apply | Submit when next cohort opens |

---

## Resources

- GitHub Accelerator: https://accelerator.github.com
- GitHub Sponsors setup: https://github.com/sponsors
- GitHub Pages (for hosting web tool): https://pages.github.com
- Zenodo community: https://zenodo.org/records/18518231

---

*This roadmap was created to track progress toward a GitHub Accelerator application for Echoes of the Script — OpenLab.*
