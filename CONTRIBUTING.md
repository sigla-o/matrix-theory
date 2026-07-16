# Contributing to Matrix Theory (MT)

Thank you for your interest in contributing to the Matrix Theory project! This document provides guidelines for contributions — whether you're reporting issues, suggesting improvements, or submitting content.

---

## Repository Structure

Before contributing, please familiarize yourself with the current structure:

<pre>
mt-theory/
├── README.md
├── LICENSE
├── .gitignore
├── CONTRIBUTING.md
│
├── docs/
│   ├── foundation/
│   │   ├── FOUNDATION_lv.md
│   │   └── FOUNDATION_en.md
│   │
│   ├── roadmap/
│   │   ├── MT_ROADMAP_lv.md
│   │   └── MT_ROADMAP_en.md
│   │
│   ├── physics/
│   │   ├── MT_QED_lv.md
│   │   ├── MT_QED_en.md
│   │   ├── GRAVITY_lv.md
│   │   ├── GRAVITY_en.md
│   │   ├── COSMOLOGY_lv.md
│   │   └── COSMOLOGY_en.md
│   │
│   ├── life/
│   │   ├── LIFE_lv.md
│   │   └── LIFE_en.md
│   │
│   ├── mathematics/
│   │   ├── MATHEMATICS_lv.md
│   │   ├── MATHEMATICS_en.md
│   │   ├── ID_GRADIENT_lv.md
│   │   └── ID_GRADIENT_en.md
│   │
│   ├── technology/
│   │   ├── TECHNOLOGY_lv.md
│   │   └── TECHNOLOGY_en.md
│   │
│   ├── ethics/
│   │   ├── ETHICS_lv.md
│   │   └── ETHICS_en.md
│   │
│   └── comparison/
│       ├── QM_COMPARISON_lv.md
│       └── QM_COMPARISON_en.md
│
├── supplementary/
│   ├── FAQ_lv.md
│   ├── FAQ_en.md
│   ├── SUMMARY_lv.md
│   ├── SUMMARY_en.md
│   ├── MATH_TASKS_lv.md
│   ├── MATH_TASKS_en.md
│   ├── ai_evaluations_lv.md
│   ├── ai_evaluations_en.md
│   ├── critical_questions_lv.md
│   └── critical_questions_en.md
│
└── archive/
    ├── KARTE_lv.md
    ├── KARTE_en.md
    ├── ARCHITECTURE/
    └── APPENDIX/
</pre>

---

## Language Policy

All documents are maintained in two languages:

- **Latvian** (`_lv.md`) — primary language of the theory author.
- **English** (`_en.md`) — for international accessibility.

When contributing:

- If you add or modify a document, please provide both language versions.
- If you only have capacity for one, indicate this clearly in your pull request.
- Translations should be faithful to the original meaning and terminology.

---

## Content Guidelines

### Core Documents (docs/)

These are the main theory documents. They should be:

1.  **Structured** — use clear headings, numbered sections, and tables where appropriate.
2.  **Quantitative** — include mathematical formalism and testable predictions where possible.
3.  **Connected** — reference other MT documents and the MATHEMATICS formalism.
4.  **Consistent** — use the established MT terminology (TE, VEU, Qn, FV, TZ, ID system, ROADMAP).

### Supplementary Materials (supplementary/)

These include FAQs, summaries, task lists, evaluations, and critical questions. They should be:

1.  **Useful** — provide additional context or clarify aspects of the core theory.
2.  **Referenced** — link to relevant core documents where appropriate.
3.  **Clear** — written in accessible language without oversimplifying.

### Archive (archive/)

This folder contains outdated files that are kept for historical reference. Do not edit files in this folder unless you are moving them out of archive.

---

## ID System and ROADMAP Compliance

All contributions must be aligned with:

- **ID system** (ID_GRADIENT_lv.md) — use the correct ID notation (e.g., ID1.0, ID2.5/8/1, ID0.n). Format: ID{modulation}.{size_category}/{parameters}.
- **ROADMAP** (MT_ROADMAP_lv.md) — clearly separate H0 path (gravity, dynamics) and L1 path (redshift, CMB). Do not mix operators from different paths.

Checklist:

- All objects are assigned an ID.
- ID notation follows the correct format.
- H0 path operators (∇δ, G(ρᵥ)) are not mixed with L1 path operators (√ρᵥ, z).
- L1 dual nature (focusing/dispersion) is respected where applicable.

---

## Writing Style

- Be precise — use clear, unambiguous language.
- Use formulas — mathematical expressions should use LaTeX-style notation: \( E = mc^2 \).
- Use tables — for comparisons, data, and summaries.
- Avoid jargon — define all terms on first use.

---

## Scientific Rigor

MT is a quantitative, testable theory. Contributions should:

1.  Be falsifiable — propose testable predictions.
2.  Reference data — compare with existing experimental or observational data where possible.
3.  Show derivations — mathematical results should be derived from established MT operators (from MATHEMATICS_lv.md).
4.  Acknowledge limitations — clearly mark preliminary or speculative content.
5.  Include ID correspondence — every table and formula should include ID correspondence where applicable.

---

## Testability and Predictions

New contributions should, where possible, include:

- A clear statement of what the contribution predicts.
- A quantitative relationship between the prediction and the MT formalism.
- A suggested method for testing the prediction.
- A comparison with existing experimental data (if available).

Example from COSMOLOGY_lv.md:

| Prediction | Equation | Value | Test method | ID correspondence |
| :--- | :--- | :--- | :--- | :--- |
| 6th CMB peak | \( \ell_6 = 35.325 \times 47 \) | \( \ell_6 \approx 1660 \) | CMB-S4, Simons Observatory | ID0.47 |

---

## How to Contribute

### 1. Reporting Issues

If you find an error, inconsistency, or ambiguity:

- Open an Issue on GitHub.
- Describe the problem clearly.
- Suggest a correction or improvement.
- Reference the specific document and section.

### 2. Suggesting Improvements

For broader suggestions (new sections, new documents, structural changes):

- Open an Issue with the label "suggestion".
- Explain the proposed change and why it would improve the theory or documentation.

### 3. Submitting Content

For direct contributions (new documents, translations, corrections):

1.  Fork the repository.
2.  Clone your fork locally.
3.  Create a new branch for your changes.
4.  Make your changes following the guidelines above.
5.  Commit with a clear message.
6.  Push to your fork.
7.  Open a Pull Request (PR) to the main repository.

---

## Pull Request Checklist

Before submitting a PR, please ensure:

- Documents are in both Latvian (`_lv.md`) and English (`_en.md`) (or reason given).
- Mathematical formulas use LaTeX notation.
- Terminology is consistent with existing MT documents (ID system, ROADMAP).
- Links to other documents are correct.
- Tables and formatting are clean.
- ID correspondence is included where applicable.
- A clear PR description explains the changes.

---

## Contact

For questions or discussions, please open an Issue or contact the repository maintainer.

---

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

---

Last updated: July 2026
