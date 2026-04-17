# Contributing to Awesome Reward Hacking

Thanks for taking the time to contribute! This reading list is a **living companion** to our survey — the reward-hacking literature moves fast, and community contributions are what keep the list useful.

## What we welcome

- 📌 **New papers** (reward hacking, specification gaming, reward overoptimization, alignment faking, evaluator manipulation, agentic exploitation, sycophancy, length bias, fabricated reasoning, etc.).
- 🔧 **Corrections** — typos, wrong venue/year, broken links.
- 🗂️ **Better classification** — if a paper sits in the wrong section under our taxonomy.
- 🧠 **Suggestions** for new subsections or better section descriptions.
- 🌐 **Translations** of the README.

## How to contribute

### Option A — Pull request (preferred)

1. Fork this repo and create a branch: `git checkout -b add-paper-xyz`.
2. Add your paper under the most appropriate section in [`README.md`](./README.md), following the entry format below.
3. (Optional) Add the BibTeX entry to [`references.bib`](./references.bib).
4. Open a pull request. Please briefly state **which taxonomy level/section** the paper belongs to and **one-line justification**.

### Option B — Open an issue

If you are not comfortable with a PR, open an [issue](https://github.com/xhwang22/Awesome-Reward-Hacking/issues/new) with:

- Paper title
- Authors
- Venue + year
- Link (arXiv / DOI / project page)
- Proposed section (e.g., `3.2 Sycophancy`)
- 1–2 sentences on why it belongs there

## Entry format

We use two rendering styles in the README, depending on section size:

### Bullet style (for smaller sections)

```markdown
- [**Paper Title**](https://arxiv.org/abs/XXXX.XXXXX)
  Author1 et al. · *Venue Year*
```

### Table style (for sections with 25+ papers)

```markdown
| Title | Authors | Venue | Year | Link |
|---|---|---|---|---|
| Paper Title | Author1 et al. | NeurIPS | 2024 | [link](https://arxiv.org/abs/XXXX.XXXXX) |
```

### Formatting rules

- **Prefer arXiv links** when available (stable + open-access). Otherwise use the publisher DOI or official project page.
- **Authors:** `LastName et al.` (3+ authors) · `A & B` (two) · `A` (one).
- **Venue:** use the short form — `NeurIPS`, `ICML`, `ICLR`, `ACL`, `EMNLP`, `CVPR`, `arXiv`, `TMLR`, etc.
- **Ordering within a section:** newest first, ties broken alphabetically by title.

## Taxonomy — where should my paper go?

Please place papers according to the survey's taxonomy:

| # | Section | When to use |
|---|---|---|
| 1.1–1.4 | **Foundations / PCH** | Theoretical framing, Goodhart, specification gaming, taxonomy contributions. |
| 2.1 | **Verbosity / stylistic** | Length bias, markdown bias, stylistic shortcuts. |
| 2.2 | **Sycophancy** | Agreement optimization, evaluator-pleasing. |
| 2.3 | **Fabricated reasoning** | Unfaithful CoT, hallucinated justification. |
| 2.4 | **Overoptimization** | Proxy–gold divergence, scaling laws for reward hacking. |
| 3.x | **Emergent misalignment** | Generalization, alignment faking, evaluator modelling, co-adaptation. |
| 4.x | **Detection / diagnosis** | Monitors, interpretability, auditing. |
| 5.x | **Mitigation** | Objective decompression (rubrics, multi-criteria), regularization, co-evolution. |
| 6.x | **Multimodal / generative / agentic** | MLLMs, T2I/T2V, tool-use / agentic exploitation. |
| 7 | **Open challenges** | Surveys, position papers, forward-looking work. |

If you're unsure, pick your best guess and we'll help adjust during review.

## Code of conduct

Be kind, be specific, and assume good faith. We follow the [Contributor Covenant v2.1](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](./LICENSE) of this repository.
