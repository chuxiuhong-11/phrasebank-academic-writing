# Phrasebank Academic Writing

A Codex skill that packages the **University of Manchester Academic Phrasebank** into a local, searchable library of ready-made English academic phrases. The phrases are content-neutral templates organized by paper section and communicative function — use them to draft, revise, or polish introductions, literature reviews, methods, results, discussions, conclusions, definitions, comparisons, trend descriptions, causal explanations, and more.

## What's inside

**20 files, ~1,600 phrase templates in total.**

| Path | What it is |
|---|---|
| `SKILL.md` | Skill instructions: reference map, 5-step workflow, usage rules, common mistakes |
| `agents/openai.yaml` | UI metadata (display name, default prompt) |
| `references/` | 18 phrase collections — one per Phrasebank page, each organized by rhetorical function (e.g. *Identifying a knowledge gap*, *Hedging*), with phrases as ready-to-adapt templates (`X`/`Y` + `…` placeholders) |

### Reference files

| File | Covers | Phrases* |
|---|---|---|
| `introducing-work.md` | Essay/paper/thesis introductions: importance, literature review, gaps, aims, structure | 276 |
| `referring-to-sources.md` | Citing, summarizing, and commenting on sources | 183 |
| `describing-methods.md` | Research design, participants, materials, procedures, statistics | 203 |
| `reporting-results.md` | Reporting findings, statistical results, table/figure references | 148 |
| `discussing-findings.md` | Interpreting results, comparing with literature, implications | 138 |
| `writing-conclusions.md` | Summarizing, concluding, limitations, future work | 129 |
| `being-critical.md` | Evaluating and criticizing previous work, highlighting weaknesses | 88 |
| `writing-definitions.md` | Defining terms and concepts | 75 |
| `using-cautious-language.md` | Hedging, uncertainty, cautious claims | 63 |
| `signalling-transition.md` | Transitioning between sections and ideas | 62 |
| `explaining-cause-and-effect.md` | Expressing causes, effects, and mechanisms | 47 |
| `classifying-and-listing.md` | Classifying items and listing types/categories | 42 |
| `describing-quantities.md` | Describing amounts, sizes, and proportions | 38 |
| `giving-examples.md` | Introducing examples and illustrations | 37 |
| `compare-and-contrast.md` | Comparing, contrasting, similarities/differences | 36 |
| `writing-about-the-past.md` | Past events, literature history, study background | 26 |
| `describing-trends.md` | Upward, downward, and stable trends | 9 |
| `about.md` | Background on the original Phrasebank resource | 19 |

*\*Approximate count of phrase bullets and combination tables per file.*

Each reference file follows the same pattern: a short guidance paragraph, then the phrases grouped under `#####` subheadings that name the rhetorical move (e.g. *Establishing the importance of the topic*, *Identifying the paucity of previous research*), so you can jump straight to the function you need.

## Install

For Codex (or other agent runtimes that read `~/.codex/skills`):

```bash
# copy the whole folder into your skills directory
cp -r phrasebank-academic-writing ~/.codex/skills/
```

On Windows, copy the `phrasebank-academic-writing` folder to `C:\Users\<you>\.codex\skills\`. Then trigger it in plain language, e.g.:

> 用 phrasebank-academic-writing 帮我写一段论文引言（英文）
> Use the phrasebank-academic-writing skill to draft a cautious discussion of my results.

## Usage notes

- Phrases are generic templates: replace `X`/`Y` and the trailing ellipsis (`…`) with your own content.
- Match tense to the section (methods/results/past events → simple past; definitions and established facts → present).
- Keep hedging strength proportional to the evidence.
- See `SKILL.md` for the full workflow and common pitfalls.

## Attribution

Content is derived from the **Academic Phrasebank** by John Morley, University of Manchester (© 2023), <https://www.phrasebank.manchester.ac.uk/>. The original resource states that the phrases are generic and that using them does not constitute plagiarism. This repository is a personal convenience copy of the phrase templates; please respect the original resource and its usage terms.
