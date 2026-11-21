# Academic Research & Human Voice Skill Library

A curated collection of attributed third-party skills and user-specific bilingual editing workflows, saved on the branch `skills-academic-voice-20261104`.

## One phrase to remember · 只记一句话

**「用我的 GitHub 学术润色。」**

If this conversation has not loaded the repository before, attach the **direct entry link** below to that instruction:

https://github.com/ffylesjean-svg/love/blob/skills-academic-voice-20261104/skills/academic-research-human-voice/SKILL.md

Then provide your text. The router chooses the appropriate focused skill: English academic writing defaults to **自然、准确、不过度母语化**; Chinese essays use Chinese natural voice, descriptive statistics use the quantitative audit, and `grill me` starts a critical research interview only on explicit request.

A vague phrase alone does **not** always reliably locate a GitHub file in a new chat. To avoid repeating the link, save it in ChatGPT's custom instructions or paste it once in each new context.


## Start here
**[Integrated Academic Research & Human Voice workflow](academic-research-human-voice/SKILL.md)**

The integrated skill selects among research, argument review, academic writing, English humanizing, and Chinese language editing. It prioritizes evidence integrity, established scholarly terminology, and the author's distinctive voice over AI-pattern checklists.

## Contents
| Folder | Purpose | Attribution |
| --- | --- | --- |
| `deep-research/` | Literature discovery and evidence synthesis | [kinqsradio](https://github.com/kinqsradio/academic-research-skills) |
| `academic-paper/` | Academic manuscript preparation | [kinqsradio](https://github.com/kinqsradio/academic-research-skills) |
| `academic-paper-reviewer/` | Argument, method, evidence and citations audit | [kinqsradio](https://github.com/kinqsradio/academic-research-skills) |
| `prose-quality-review/` | Identify unclear and formulaic writing | [kinqsradio](https://github.com/kinqsradio/academic-research-skills) |
| `academic-writing/` | Academic editing and reviewer responses | [David Saeteros](https://github.com/David-Saeteros/claude-skills) |
| `humanizer-en/` | Academic English prose editing | [ashgreat](https://github.com/ashgreat/humanizer) |
| `humanizer-zh/` | Natural Chinese writing and voice matching | [nothing0here](https://github.com/nothing0here/humanizer-zh) |
| `anti-ai-writing/` | Quantitative reporting integrity and academic prose editing | [cbsteh](https://github.com/cbsteh/anti-ai-writing) |
| `anti-defensive-writing/` | General English/Chinese prose: remove redundant caveats, defensive framing and over-explanation | [Kiterlin](https://github.com/Kiterlin/anti-defensive-writing) (MIT) |
| `anti-defensive-writing-zh/` | Chinese prose: direct claims, natural structure, accurate scope; includes genre references and optional audit scripts | [Devilyuu](https://github.com/Devilyuu/anti-defensive-writing-zh) (MIT) |
| `anti-defensive-academic-press-release/` | Academic contribution framing and manuscript structure; Chinese core with English reference version | [Adkid-Zephyr](https://github.com/Adkid-Zephyr/anti-defensive-writing-Skill) (MIT) |
| `descriptive-statistics-human-voice/` | Natural Chinese/English reporting of descriptive survey statistics, with numerical integrity checks | Original adapted companion |
| `grill-me/` | Critical questions for research ideas, decisions and philosophical arguments, with accompanying references | [hiDaDeng](https://github.com/hiDaDeng/grill-me) |
| `qualitative-social-science-humanizer/` | Genuine author-voice preservation for interpretive social science | [XuyueyangHe](https://github.com/XuyueyangHe/Qualitative-social-science-humanizer) |
| `natural-non-native-academic-english/` | Correct, restrained English editing without unnecessary native-speaker polishing | Locally authored mode |
| `academic-research-human-voice/` | Default entry point and mode router | Derived workflow |

## Anti-defensive writing · 默认反防御规则
The integrated workflow now includes three anti-defensive writing modules. When this repository is actually read for a prose or academic editing task, use `anti-defensive-writing/` as the general style pass and `anti-defensive-writing-zh/` for Chinese; use `anti-defensive-academic-press-release/` selectively for academic abstracts, introductions, contribution statements, conclusions, and responses to reviewers. For English manuscript guidance in the third module, see its `references/english-version.md`.

Apply the edits only when they improve clarity. Preserve genuine uncertainty, qualifying evidence, negative findings, required disclosures, authorial voice and theoretical distinctions. The third upstream module's advice to foreground strengths does not justify hiding contradictory findings or changing evaluation criteria after observing results. Avoid formulaic paragraph openings, unnecessary 'not X but Y' pivots and repetitive concluding caveats, but retain them when they perform a real argumentative function.

This GitHub library stores copies of instructions; it does **not** guarantee that a new ChatGPT conversation automatically fetches or executes them. Custom instructions can express a standing stylistic preference, while full Skill execution requires actual access to the files.

## How to use
In a new conversation, provide the URL of `skills/academic-research-human-voice/SKILL.md` from this branch and ask the assistant to read and follow it, specifying the task. A repository copy **does not automatically install a Skill in ChatGPT** or guarantee cross-conversation triggering.

## Scope and reuse
- Most upstream `SKILL.md` instructions are copied verbatim; the Adkid-Zephyr Chinese skill frontmatter `name` is changed to `anti-defensive-academic-press-release` to avoid a collision with Kiterlin's skill. This is **not a full clone** of every original repository. Some references, scripts, or project workflows used by these upstream files may not be present.
- Upstream skill instructions are treated as guidance, not automatic authorization to run code or send private manuscript data elsewhere.
- No external scripts have been executed. No user documents, unpublished research, credentials, or personal records have been added here.
- This is a **public repository**. Keep confidential materials out.
- The `grill-me` copy includes its original reference-route files and templates. Its upstream `SKILL.md` frontmatter says MIT, but the repository root `LICENSE` is Apache-2.0; this library preserves the root Apache-2.0 licence and flags the inconsistency rather than claiming a resolved licence.
- The `anti-ai-writing` and `grill-me` copies are third-party source material; `descriptive-statistics-human-voice` is newly authored and explicitly prohibits alteration or fabrication of numbers.
- The original `qualitative-social-science-humanizer` directory includes its required reference modules; its voice-learning workflow strictly requires at least one genuine user-authored prior academic writing sample. The separate `natural-non-native-academic-english` mode supports restrained proofreading even if no verified prior sample has been supplied; it must not misrepresent that limited task as full author-profile matching.
- The XuyueyangHe repository is MIT licensed; its licence is copied to `licenses/qualitative-social-science-humanizer-MIT.txt`.
- Original projects retain their authorship and copyright. MIT license copies for kinqsradio, ashgreat, and nothing0here, and CC BY 4.0 attribution terms for David Saeteros are in [licenses](licenses). Additional upstream licence copies for cbsteh (MIT) and hiDaDeng (Apache-2.0) are also included. This integrated work makes no claim of third-party endorsement.
- Copied and expanded on 2026-11-04; anti-defensive writing modules added 2026-11-22. Their full MIT licence notices are in `licenses/anti-defensive-writing-Kiterlin-MIT.txt`, `licenses/anti-defensive-writing-zh-Devilyuu-MIT.txt`, and `licenses/anti-defensive-academic-Adkid-Zephyr-MIT.txt`. Check upstream for updates.
