---
name: academic-research-human-voice
description: Bilingual humanities and social-science research, evidence audit, argument review, and voice-preserving academic editing.
---
# Academic Research & Human Voice Workflow (v1.0)

This is a user-specific integrated workflow adapted from the attributed Skills in ../. It is **not** an AI-detector evasion tool. Do not claim it is automatically installed in ChatGPT.

## Modes
- **research**: Consult `../deep-research/SKILL.md`. Search only authorized sources; document queries, dates, and reading scope. Verify titles/authors and exact claim locations; distinguish source findings from interpretations.
- **argument-review**: Consult `../academic-paper-reviewer/SKILL.md`. Audit research question, method, case selection, evidence, warrant, limitation, and conclusion before stylistic editing.
- **structure**: Consult `../academic-paper/SKILL.md` and `../academic-writing/SKILL.md`. Assess paragraph function, logical progression, and reviewer comments; propose the smallest effective revision.
- **english-voice**: By default for humanities/social science and multilingual authors, consult `../natural-non-native-academic-english/SKILL.md`; it routes to `../qualitative-social-science-humanizer/SKILL.md` for strict author-voice matching when genuine original writing samples are available. Otherwise use a minimal-edit mode without inventing a non-native style. Consult `../prose-quality-review/SKILL.md` and `../humanizer-en/SKILL.md` only as supplementary editorial guidance, not vocabulary bans.
- **chinese-voice**: Consult `../prose-quality-review/SKILL.md` and `../humanizer-zh/SKILL.md`. Edit Chinese literary/theoretical prose without flattening its individual voice.
- **quantitative-prose**: Consult `../descriptive-statistics-human-voice/SKILL.md`, with `../anti-ai-writing/SKILL.md` as a secondary editorial reference. Audit raw counts, denominators, percentages, question types and representativeness before changing prose; never alter numbers to seem less AI-written.
- **grill-me**: On explicit request to be challenged or "grilled", consult `../grill-me/SKILL.md` and its `references/academic.md` (research) or `references/thinking.md` (conceptual argument); challenge assumptions and ask only questions whose answers change the thesis or decision.
- **full**: Apply relevant research, evidence, argument and language stages in order, ending with a meaning-preservation audit. For quantitative manuscripts include `quantitative-prose`. Do not activate `grill-me` by default.
- **quick invocation / 简称「我的GitHub学术润色」**: If a user has explicitly provided this repository and asks for `我的 GitHub 学术润色`, select the relevant mode automatically. English defaults to **natural, accurate, not over-nativised**, Chinese to voice-preserving editing, tables/percentages to quantitative-prose. Preserve content by default and ask for genuine author samples only when detailed voice matching is requested.

## Non-negotiable editorial rules
1. **Meaning and evidence first**. Never introduce unsupported specifics, invented quotes, unverifiable citations, imaginary findings, false causal claims, or fabricated first-person experience.
2. **Protect established terms**. Do not mechanically simplify terms such as *affect*, *jouissance*, *interpellation*, *mediation*, *animatic configuration*, or established Chinese theoretical translations. Explain them when needed rather than replace them.
3. **Preserve qualifications**. Keep negation, quantifiers, modal verbs, distinctions between possible and proven claims, methodological scope, citations, precise dates, page numbers, and source attribution.
4. **Minimal intervention**. Prefer a local correction to a paragraph rewrite, and a paragraph rewrite to restructuring a section. Flag substantive changes in theoretical interpretation or research direction for author choice.
5. **Author samples take precedence**. Use only the author's own approved original writing as voice calibration; never assume a model-polished draft represents their native voice.
6. **Academic conventions override generic humanizer heuristics**. Passive voice, abstractions, long sentences, parenthetical qualifiers, and contrast structures are legitimate when performing real work.
7. **No detector promises**. Do not claim that wording can reliably defeat AI detectors; disclose AI use as required by applicable academic and publishing rules.

## English: Academic Human Voice
Use British English by default, subject to journal style. Identify inflated framing, meta-signposting without argumentative value, padding, unsupported booster adjectives, nominalization obscuring actors, and repeated transitions. Avoid forcing first-person "we", short sentences, active voice, or simple synonyms if the discipline calls for conceptual exactness. Preserve rhetorical differences between a film close reading, conceptual essay, empirical paper, and journal response.

## 中文：理论写作与自然表达
保留作者本人用词、理论密度、长短句节奏、批判立场与经过选择的文学修辞。不机械删去“不是……而是……”“然而”“值得注意的是”等表达；只修改无实际推进作用的重复与套话。反对在不充分阅读原文时将作者观点过度总结为常识，或为“人味”虚构感受。书评、随笔与正式学术论文使用不同的风格边界。

## Review output
For a full review, deliver: (1) concrete issues with exact locations; (2) why they impair reasoning or clarity; (3) smallest revisions proposed; (4) complete revised text when requested; (5) a short audit of preserved terminology, quotes, evidence, stance and voice. For a simple polish request, give the finished text and a concise note; do not over-report. Do not rewrite when the user requested diagnosis only.

## Scope/compatibility
These are copied Markdown instructions, not automatically installed tools, external scholarly database access, or CLI dependencies. Some upstream relative links may depend on files outside this curated library. Follow only those portions supported by the current environment, with limitations made explicit.

## Original projects
- https://github.com/kinqsradio/academic-research-skills (MIT; Deep Research, Academic Paper, Reviewer, Prose Quality)
- https://github.com/David-Saeteros/claude-skills (CC BY 4.0; Academic Writing)
- https://github.com/ashgreat/humanizer (MIT; English Humanizer)
- https://github.com/nothing0here/humanizer-zh (MIT; 中文 Humanizer)
- https://github.com/cbsteh/anti-ai-writing (MIT; quantitative evidence and style discipline)
- https://github.com/hiDaDeng/grill-me (repository LICENSE Apache-2.0; note SKILL frontmatter inconsistent, claiming MIT)
- https://github.com/XuyueyangHe/Qualitative-social-science-humanizer (MIT; preserve a genuine author's interpretive social-science voice)
- `../natural-non-native-academic-english/SKILL.md` (locally authored editing mode)
- `../descriptive-statistics-human-voice/SKILL.md` (local authored survey-results prose workflow)
Read `../README.md` for credit and license links.
