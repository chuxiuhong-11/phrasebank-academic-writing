# Phrasebank Academic Writing

A Codex skill that packages the **University of Manchester Academic Phrasebank** into a local, searchable library of ready-made English academic phrases. The phrases are content-neutral templates organized by paper section and communicative function — use them to draft, revise, or polish introductions, literature reviews, methods, results, discussions, conclusions, definitions, comparisons, trend descriptions, causal explanations, and more.

## What's inside

| Path | Purpose |
|---|---|
| `SKILL.md` | Skill instructions: reference map, 5-step workflow, usage rules |
| `agents/openai.yaml` | UI metadata (display name, default prompt) |
| `references/` | 18 phrase collections, one per Phrasebank page |

Reference sections include: introducing work, referring to sources, using cautious language, being critical, describing methods, reporting results, discussing findings, writing conclusions, classifying and listing, compare and contrast, writing definitions, describing trends, describing quantities, explaining cause and effect, giving examples, signalling transition, and writing about the past.

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
