---
name: descriptive-statistics-human-voice
description: Audit and edit natural Chinese or English academic prose reporting descriptive survey statistics, frequencies, percentages, cross-tabs, Likert responses, and small-sample findings. Preserve every number and inference boundary. Use for "my descriptive statistics sound AI-written", "rewrite Results prose", quantitative narrative review, or percentage-heavy academic paragraphs.
---

# Descriptive Statistics & Human Voice / 描述性统计与自然学术表达

This skill is an original, focused companion to:
- [Anti-AI Writing](../anti-ai-writing/SKILL.md) — editorial style, evidence discipline and quantitative reporting;
- [Academic Research & Human Voice](../academic-research-human-voice/SKILL.md) — concept protection, voice matching, argument continuity;
- [Prose Quality Review](../prose-quality-review/SKILL.md) — focused diagnosis before editing.

**Objective:** Turn accurate descriptive results into concise, discipline-appropriate, readable prose **without changing data, hiding sampling limitations, inflating claims, or manufacturing analytical findings**. This is not a detector-evasion tool and cannot establish whether a text was AI-authored.

## Select the task mode

1. **Audit only:** User asks if a statistics paragraph is valid, repetitive, or natural. Check and report; do not rewrite without authorization.
2. **Naturalise prose:** User supplies a passage, table or data and requests editing. Verify numbers as possible; rewrite only prose and correct demonstrable arithmetic errors with an explicit note.
3. **Write descriptive Results:** Given verified tabulations, produce an appropriately restrained Results section; do not invent values or tests.
4. **Compute + report:** When raw data and execution capability are provided, compute with a real statistical tool first, record grouping, missing values, denominator, weighting and code/version where relevant; then write. Never calculate silently from incomplete inputs.

## Gate 1 — numerical integrity before language

Check the following before a single sentence is polished:

- **Population / sample:** state what group was sampled, when necessary, and whether figures are from respondents, responses, cases, or items. Convenience / volunteer / snowball samples do not represent the wider population without additional justification.
- **Denominator:** for each numerator and percentage, specify the eligible n: overall n, subgroup n, item-specific valid n, or number of responses. Different items can have different bases because of skipped questions or exclusions.
- **Question type:** distinguish mutually exclusive single choice, multiple response, ordinal / Likert, continuous measures, and open text coded into categories. For multi-response, totals may exceed 100%; do not force them to sum to 100%.
- **Calculation:** if source counts are given, verify percentage = count / correct denominator × 100. Check rounding precision, missingness, whether figures are weighted, and exact wording of row / column percentages. If data or denominator is unavailable, mark 'unverified' rather than inventing.
- **Comparisons:** distinguish absolute count differences, **percentage-point** differences, and relative percent changes. A difference of 60% vs 45% is **15 percentage points**, not '15% more'. Do not infer meaningful patterns from tiny cells without context.
- **Summary measures:** mean and standard deviation require a quantitative scale and appropriate rationale. For ordered response categories, consider counts / distribution / median as relevant; do not treat a Likert item as inherently interval-scale without justification. Do not interchange SD, SE or CI.
- **Analysis type:** descriptive comparisons are **not** evidence of statistical significance. Do not invent p values, CIs, effect sizes, regressions, reliability, significance labels or causal mechanisms.
- **Question scope:** do not silently merge, recode, dichotomise or reorder response categories. Explicitly explain any necessary aggregation, threshold, exclusion or category coding.
- **Source retention:** preserve all units, sample sizes, question wording, question IDs, captions, numbers, source references and meaningful qualifiers.

If the original table and prose disagree, present the exact conflict and ask for the correct source or identify an arithmetic correction explicitly. Never conceal a conflict under a smooth narrative.

## Gate 2 — evidence-proportionate interpretation

Write what is visible from a table, not what sounds publishable.

Permitted:
- "In this sample, X of Y respondents (Z%) selected ..."
- "Within group A, the most frequently selected option was ..."
- "The observed proportion was higher in group A than group B; this is a descriptive difference."
- "These responses suggest a possible concern among the participants; the instrument does not establish its cause."

Not permitted without additional evidence:
- "X proves that [country/group] is more ..."
- "These results demonstrate a significant difference" when no inferential test was run.
- "Participants increasingly ..." from one cross-sectional measurement.
- "This shows the mechanism of ..." without supporting qualitative data, analytical steps or theory warrant.
- "Most respondents" when numerator does not exceed half of the relevant denominator.
- "No difference" or "no effect" merely because two observed percentages are close or a test was non-significant.

For small samples, name the observed pattern but resist country-level generalisation. If items do not directly measure a complex construct like 'intercultural dialogue', do not silently equate a single response with the entire construct.

When qualitative open responses are analysed via thematic analysis, retain the analytic distinction between thematic interpretation and numeric questionnaire frequencies. Counts of coded comments do not by themselves establish theme salience, statistical prevalence, or representativeness.

## Gate 3 — make quantitative prose less formulaic

**Edit for genuine information density, not for an AI detector.**

- Open a paragraph with the most relevant observable pattern. Do not start every sentence "Table X shows / The results indicate / It is worth noting that".
- Do not narrate every table cell. Report only the contrasts, distributions and exceptions that advance the research question; leave routine cells in the table. Do not cherry-pick contradictory or inconvenient results away.
- Combine repeated statistics under one clear subject. Avoid mechanical 'firstly, secondly, finally' and ceremonial closing sentences ("this provides valuable insights").
- Show the denominator at first mention or when it changes; do not repeat it in every clause if context remains clear.
- Name categories precisely; do not replace variable labels or construct names with evocative synonyms that shift their meaning.
- Preserve necessary hedging. 'May suggest' is warranted when the evidence is weak; don't replace it with 'proves' to sound confident.
- A smooth paragraph should keep a natural flow: observation → limited comparison → necessary qualification; interpretation only where justified by design and surrounding evidence.
- Use the author's genuine writing samples to calibrate tone. Never manufacture an anecdote, a quote, or a research motive to make the passage sound "human".

### Chinese writing defaults

Prefer concise, coherent paragraphs rather than repeated numbered bullet points or exaggerated rhetorical contrasts. Only use "数据表明", "值得注意的是", "这充分证明", "更为重要的是" if these words do specific argumentative work (in most descriptive passages they do not).

**Illustration only; invented numbers are NOT study findings.**

Before:
> 数据结果充分表明，在40名受访者中，有23名受访者（57.5%）选择了选项A，而17名受访者（42.5%）选择了选项B。这一结果深刻揭示了受访者对于A的显著偏好，并为理解该现象提供了重要启示。

After:
> 在40名受访者中，23人（57.5%）选择A，17人（42.5%）选择B。A在这组样本中更常见，但这只是描述性差异，不能据此推断更广泛群体的偏好。

This example does **not** imply that adding a boilerplate caveat to every paragraph is necessary. State each caveat once where it matters.

### English academic writing defaults

Use British English unless the target venue instructs otherwise. Prefer direct, data-anchored sentences. Keep terms required by the specific discipline, and established statistical notation.

Before (illustrative, not actual results):
> The survey findings clearly demonstrate a significant and compelling preference for option A, which was chosen by a remarkable 57.5% of respondents.

After:
> Of the 40 respondents, 23 (57.5%) chose option A, compared with 17 (42.5%) who chose B.

Do not introduce a significance test or claim this difference characterises any wider population.

## Output contract

For **audit**, report a small number of located issues, each labelled Numerical / Denominator / Inferential overreach / Ambiguity / Prose. Do not invent a quantitative "AI score".

For **rewrite**, provide:
1. The edited passage, retaining numbers and defined concepts;
2. A short change note identifying substantive edits, if any;
3. Any numerical conflicts or evidence gaps that remain unresolved.

If no numeric source was provided, explicitly say "figures retained as supplied; underlying data not independently verified" instead of implying an audit was run.

Never change data to lower an AI detection score. Academic transparency and research-integrity obligations always apply.
