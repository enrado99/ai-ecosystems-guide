# AI Ecosystems Guide (v7, October 2026)

An interactive, Spanish-language guide to the generative AI landscape, written for people who are curious about AI but do not have a technical background. It compares the main labs and their models, explains how to read benchmarks and claims critically, and teaches practical prompt engineering.

**Live version:** https://enrado99.github.io/ai-ecosystems-guide/

> The guide itself is in **Spanish**.

## What makes it different

- **A confidence label on every claim:** independent (● measured or confirmed by a third party), reported by media (◐) or self-reported by the lab (○).
- **Third-party sources first:** Artificial Analysis, ARC Prize, METR and Epoch AI over lab announcements.
- **The same template for every lab,** including each one's limits and controversies.
- **Critical-thinking checklist, glossary and quiz** to practice reading AI news.

## Monthly releases

The guide is updated once a month. Each edition is a commit on `main` with a tag, so the history is kept and GitHub Pages always serves the latest one.

| Tag | Edition | Data verified |
| --- | --- | --- |
| `v7` | October 2026 | 11 Oct 2026 (covers up to 9 Oct) |
| `v6` | September 2026 | 20 Sep 2026 |

See [CHANGELOG.md](CHANGELOG.md) for what changed in each edition.

Checklist for each new edition:

1. Update `index.html`: edition badge, "what changed" table, timeline, lab pages, benchmarks, glossary and quiz.
2. Keep the guide's rules: same template for every lab, a confidence label on every figure, third-party measurements first, and a note on anything that could not be verified.
3. Update the verification date in this README and in the guide's "Fuentes y método" section.
4. Commit as `Add AI ecosystems guide vN (Month YYYY)` and tag it `vN`.

## Technical notes

- A **single self-contained HTML file** (`index.html`): no build step, no framework, no tracking. Fonts load from Google Fonts.
- Works offline apart from the fonts and the external source links.
- To run it locally, open `index.html` in any modern browser.

## About this project

Drafted with generative AI (Claude) under my direction and curated by me. It was first written for family and friends without a technical background.

## Keep in mind

The AI field changes every few weeks. Figures, model names and prices reflect the data verified on **11 October 2026**. Check the sources before relying on any number for a real decision.
