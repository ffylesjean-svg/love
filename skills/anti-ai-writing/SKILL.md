---
name: anti-ai-writing
description: "Detect and remove AI prose and slop in academic science writing. Covers citation integrity, epistemic precision, quantification, US English and em-dash rules, and the surface-prose patterns (throat-clearing, binary contrasts, rhetorical adverbs, metronomic rhythm) that mark LLM-generated text. For journal articles, theses, grant proposals, and technical reports."
---

# Academic Science Writing: Detecting and Removing AI Prose

*For journal articles, theses, grant proposals, and technical reports.*

---

## 0. How to use this skill: fix substance before style

AI-generated science writing fails on three dimensions, in this order of severity:

1. **Citation integrity.** Fake, unverified, or mismatched references.
2. **Epistemic accuracy.** Conclusion strength that exceeds what the design allows.
3. **Specificity.** Scope and quantitative claims left vague or unmeasured.

Surface vocabulary and rhythm signals are real but secondary. Work the list top-down: a perfectly de-slopped sentence built on a fabricated citation is still worthless. Fix the substance first (Sections 5 to 8), then the style (Sections 1 to 4).

---

## 1. Core language rules

These apply to every sentence without exception.

**US English.** American spelling throughout: "analyze" not "analyse," "color" not "colour," "sulfur" not "sulphur" (the IUPAC standard, relevant to soil chemistry), "center" not "centre," "catalog" not "catalogue," "defense" not "defence," "recognize" not "recognise," "modeling" not "modelling." If the target journal requires British spelling, override this to match the journal style guide, but be consistent within the manuscript.

**No em dashes.** Em dashes (--) are a frequent marker of LLM-generated prose and should not appear anywhere. Do not use them for parenthetical clauses, appositives, or sentence breaks. Restructure, or use commas, parentheses, or a colon.

- Wrong: "The model -- which was calibrated on 30 years of data -- performed well."
- Right: "The model, calibrated on 30 years of data, performed well."
- Right: "The model performed well (calibrated on 30 years of data)."

**Hyphens and en dashes.** Hyphens are for compound adjectives only: "field-measured data," "long-term experiment," "well-drained soil." En dashes are for numeric ranges (2020-2024, 10-20 mg kg^-1) and for compound modifiers with a multi-word element ("oil palm-derived compost"). En dashes are not sentence punctuation.

---

## 2. The main signal is clustering, not isolated words

Single flagged words are not proof of AI use. This matters most in science writing, where many "slop" words are legitimate technical vocabulary. The test is whether a word does technical work or rhetorical work (Section 4).

The strongest AI signals in academic science:

- Epistemic verbs stronger than the design allows ("demonstrate" when data only "suggest").
- Scope claims without quantification ("a comprehensive analysis" with no n, spatial range, or time period).
- Vague authority ("the literature suggests" with no citation).
- Generic abstractions that add no information ("this study enhances our understanding of soil health").
- Conclusions that restate the introduction without adding what was found.
- Balanced three-part lists where the three items do not differ functionally.

A caution: surface-style detection is not proof of authorship. Do not accuse a colleague of AI use on vocabulary clustering alone. Use this skill to improve writing, not to adjudicate authorship.

---

## 3. Surface prose patterns

Secondary to Sections 5 to 8, but worth a dedicated pass.

**Throat-clearing openers.** Cut phrases that announce a point instead of making it.

| Remove | Do instead |
|---|---|
| "It is important to note that..." | State the point. |
| "It is worth mentioning that..." | State it or delete it. |
| "Here's what we found:" / "What's more," / "Which is why" | Delete the opener; lead with the content. |
| "It turns out that..." / "The real reason is..." | State the finding; the framing adds nothing. |
| "Interestingly," / "Notably," / "Remarkably," | State the finding; let the reader judge interest. |
| "In today's world," / "In the current landscape," | State the actual condition with a date or source. |

**Binary contrasts.** The "not X, it's Y" cadence is a strong LLM tell when used for rhetorical effect: "This is not just a correlation, it's a causal mechanism." State Y directly. Two related variants: the additive hedge "not just X but also Y," which usually collapses to "both X and Y" or to the part that carries information; and negative listing ("Not a soil-structure effect. Not a moisture effect. A temperature effect."), a rhetorical runway the reader does not need. State the conclusion. The legitimate exception is genuine contrastive findings ("The effect was driven by temperature, not by water stress"), which are normal scientific content. The tell is the empty rhetorical version, not the substantive one.

**Rhetorical adverbs.** Remove adverbs doing rhetorical work: clearly, notably, interestingly, remarkably, importantly, crucially, fundamentally, inherently, inevitably, undoubtedly. Keep adverbs doing technical work: statistically, approximately, respectively, significantly (in the formal sense), spatially, temporally. The question is always whether the adverb carries information or just emphasis.

**Metronomic rhythm.** Three or more consecutive sentences of near-identical length read as machine-generated. Vary length. This is a minor signal in science and never overrides clarity, so do not contort a methods sentence for rhythm.

**False agency vs. scientific metonymy.** Two things are easy to confuse:

- *Acceptable scientific metonymy* (keep): "Figure 2 shows," "the model predicts," "the data suggest," "results indicate." These are established conventions and readers parse them correctly.
- *Genuine anthropomorphization* (remove): data that "believe," a study that "aims to prove," findings that "want to tell us." Data and models have no intentions. Rewrite with an explicit agent: "We aimed to test whether..." not "The study aims to prove..."

**Meta-commentary.** Performative asides ("Plot twist:", "As we'll see," "Let me walk you through") are slop. Structural signposting is different and is acceptable, even expected, in long documents: "Section 3 describes the model; Section 4 reports the calibration results" is standard thesis and report practice. Keep functional signposting; cut the performative version.

**Grant-proposal jargon.** Papers rarely carry corporate jargon, but proposals and reports sometimes do. Watch for "the research landscape," "navigate the challenges," "deep dive," "game-changer," "lean into." Replace with plain equivalents: "the field," "address," "detailed analysis," "important," "adopt."

**Vague declaratives.** "The reasons are structural." "The implications are significant." Name the specific reason or implication, or cut the sentence.

**Lazy extremes.** "Every," "always," "never," "all" doing vague universal work are usually overstatement. In science they are also falsifiability traps (Section 8 on dated scope claims).

**What to cut and what to keep.** Cutting dead words is always safe because it removes no information: do it in any sentence regardless of where it sits. Cutting content is never done: numbers, units, parameters, procedural steps, and citations stay, even when the sentence ends up dense. The next entries target dead words only. Do not compress a sentence by dropping a measured value, a sample size, or a method detail for the sake of brevity.

**Nominalizations (hidden verbs).** Science writing buries verbs inside nouns, which adds words and drains energy, and LLMs overproduce the pattern. Recover the verb when the noun form adds words without adding precision.

| Wordy (nominalized) | Concise |
|---|---|
| "performed a measurement of" | "measured" |
| "conducted an analysis of" | "analyzed" |
| "carried out an investigation of" | "investigated" |
| "made a comparison between" | "compared" |
| "gave a description of" | "described" |
| "showed a reduction in" | "reduced" or "decreased" |
| "is in agreement with" | "agrees with" |

Caveat: some nominalizations are the correct technical term ("the calibration was poor," "soil respiration"). Recover the verb only when doing so loses nothing.

**Wordy connectives and redundant phrases.** Replace multi-word connectives with one word, and cut redundant pairs.

| Wordy | Concise |
|---|---|
| "due to the fact that" | "because" |
| "in order to" | "to" |
| "in the event that" | "if" |
| "for the purpose of" | "to" or "for" |
| "with regard to" / "in terms of" | "for," "about," or delete |
| "a number of" | "several," "many," or a count |
| "the majority of" | "most" |
| "at this point in time" | "now" or "currently" |
| "in close proximity to" | "near" |
| "a total of 47 samples" | "47 samples" |

Redundant pairs and pleonasm: "end result" to "result," "absolutely essential" to "essential," "completely eliminated" to "eliminated," "past history" to "history," "red in color" to "red," "large in size" to "large."

**Expletive constructions.** "There is/are X that..." and "It is X that..." bury the subject and add words. "There are three factors that affect yield" becomes "Three factors affect yield." "It is temperature that drives the effect" becomes "Temperature drives the effect." Cut these when they hide a real subject. Leave the standard reporting form "It was found that..." alone; it is conventional passive, not padding.

**Hedge stacking.** One hedge is calibration; three is mush. "may possibly suggest that it could potentially..." becomes "may suggest." Keep the single hedge that names the actual source of uncertainty (Section 5.3).

---

## 4. Technical vs. rhetorical word use

Many flagged words are legitimate technical terms in soil, crop, and agronomic science. The test is technical work vs. rhetorical work.

| Term | Technical use (valid) | Rhetorical use (slop) |
|---|---|---|
| robust | "A robust estimator is resistant to outlier influence" | "Our approach is robust and effective" |
| optimize | "We optimized soil water parameters using PEST-HP" | "We optimized our approach for best results" |
| facilitate | "Mycorrhizae facilitate P uptake by extending the root absorption zone" | "This framework facilitates knowledge transfer" |
| enhance | "Biochar application enhanced water retention by 18% (p < 0.01)" | "This study enhances our collective understanding" |
| dynamic | "Soil carbon dynamics under no-till management" | "A dynamic and holistic approach to the challenge" |
| comprehensive | "A comprehensive survey of 47 soil series across Peninsular Malaysia, 2018-2024" | "A comprehensive review of the literature" (no scope) |
| framework | "The FAO World Reference Base (WRB) soil classification framework" | "A conceptual framework for enhanced outcomes" |
| significant | "Significantly higher bulk density (p < 0.001, F = 18.4, df = 3, n = 45)" | "This is a significant finding for the discipline" |
| impact | "The impact of waterlogging on root aerobic respiration" | "The impact of this study on advancing knowledge" |
| model | "A crop growth model calibrated with field lysimeter data" | "A model for collaborative success" |

**Terms almost never technical in science writing:** "delve," "underscore" (as a verb), "pivotal," "crucial," "transformative," "groundbreaking," "seamless," "holistic," "actionable," "cutting-edge." Replace with specific, data-supported claims.

---

## 5. Epistemic precision

### 5.1 Epistemic verb strength

Match the verb to the design. Misuse is one of the most consistent AI-writing failures.

| Verb | When valid | What it implies |
|---|---|---|
| prove | Almost never in empirical science | Logical or mathematical certainty |
| demonstrate | Only when the design eliminates plausible alternatives | Strong causal or mechanistic evidence |
| show | Results consistent with the claim, alternatives unlikely given the design | Standard for well-controlled experiments |
| indicate | Results point toward the claim but confounders are present or unmeasured | Observational or semi-controlled studies |
| suggest | Results consistent with the claim but evidence is incomplete or preliminary | Exploratory results, small samples |
| imply | Follows logically from other results but not directly tested | Inference only, not measurement |

AI writing defaults to "demonstrate" or "show" regardless of design. Match the verb to the actual design.

### 5.2 "Significant" vs. "substantial"

"Significant" means statistically significant: a formal test rejected the null at a stated alpha. It does not mean important, large, or meaningful. Use "substantial," "marked," "large," "meaningful," or report the effect size directly when you mean practical importance.

Example: "The difference was statistically significant (p = 0.003) but the effect size was small (Cohen's d = 0.18), suggesting limited practical relevance at field scale."

Do not write "highly significant" without the exact p-value. Report the p-value; let the reader weigh it.

### 5.3 Calibrated hedging vs. AI-style vague hedging

Appropriate hedging names the specific source of uncertainty: "This estimate may be biased by the absence of dry-season measurements." AI-style hedging is non-specific: "More research is needed to fully understand this complex and dynamic issue." If you cannot name the specific gap, question, or design requirement, the hedge probably does not belong. "More research is needed" is not a conclusion.

### 5.4 Correlation and causation

Do not use causal language for observational or correlational data. "X was associated with Y" is not "X caused Y." AI writing slips into causal framing without a design that permits causal inference. If the design is observational, use "associated with," "was related to," or "predicted."

---

## 6. Statistical and quantitative reporting

- Report n, the test statistic, degrees of freedom, and exact p-value where available. "p < 0.05" alone is insufficient when the exact value is obtainable.
- Report effect sizes alongside p-values. AI-generated statistics sections frequently omit them, making results impossible to interpret practically.
- Use consistent units. State units at first mention in every table and figure. Do not mix SI and non-SI units without justification.
- Distinguish within-group descriptive statistics (mean, SD, SE) from between-group test results. Report both where relevant.
- Do not interpret non-significant results as proof of no effect. State the confidence interval or achieved power: "The difference was not significant (p = 0.12); the 95% CI ranged from -2.3 to 18.6 g kg^-1, which does not exclude agronomically meaningful effects."
- "Data" is plural in formal scientific writing: "the data show," "the data were collected." Standard in most natural science journals, though not universally enforced.
- Report uncertainty around model outputs, not just point estimates. A single value without confidence bounds or sensitivity analysis presents false precision.

---

## 7. Specificity in science writing

**Conclusion inflation.** "Our results demonstrate that..." is frequently wrong when "our results suggest that..." is the defensible claim. See Section 5.1.

**Missing quantification.** "Soil pH is crucial for nutrient availability" is rhetorical. "Soil pH between 6.0 and 7.0 maximizes P availability in Ultisols under humid tropical conditions (Jones, 2020)" is scientific. Replace rhetorical adjectives with measurable properties.

**Fake scope claims.** "A comprehensive analysis of soil carbon dynamics" means nothing without stating how many sites, what range, what period, what methods. Always specify actual scope.

**Vague quantifiers.** "Many studies have found..." and "several authors have argued..." are unacceptable. Cite the specific studies, or give a number: "Twelve field trials across Southeast Asia have reported..."

**Novelty overstatement.** "This is the first study to..." is a strong falsifiability claim. Use "To our knowledge, this is the first study in [specific domain, region, or crop system] to..." and only after searching the relevant databases.

**Tense.** Judge per sentence by what the sentence does, not by which section it sits in. An action you performed takes past tense ("we measured," "samples were collected"). An established fact or a figure or table description takes present tense ("clay content increases water retention," "Figure 2 shows..."). Stated objectives can take future tense, used sparingly. Flag only internal inconsistency or a clear function mismatch (a reported result written in present tense, an established fact written in past). AI writing frequently mixes these.

---

## 8. Citation integrity

- Check every citation manually against the stated claim. AI prose includes DOIs that resolve to real papers that do not support the cited point.
- Do not cite review articles for claims that originate in primary studies. Trace the claim to the primary source.
- "The literature suggests..." with no citation is not acceptable. Name the study or remove the sentence.
- Cite the paper that described a method, not the paper that used it. If Smith (2020) applied van Genuchten (1980) without deriving it, cite van Genuchten (1980) for the method.
- Do not stack citations: five papers for a basic fact suggests the author read none of them. Two well-chosen primary sources beat five undifferentiated ones.
- Date your scope claims. "No study has examined..." becomes wrong the moment one appears. Use "As of [year], no published study has examined..." and specify the search scope.
- Label preprints explicitly and note that peer review has not occurred. arXiv and bioRxiv carry different epistemic weight than peer-reviewed articles.

---

## 9. Voice

Passive voice is not AI-prose in science, so do not rewrite it on sight. "Samples were collected to 1 m" and "the model was calibrated against lysimeter data" are standard and correct. Converting every passive to active is a common over-correction; leave passive alone when it reports a procedure or a measurement.

The one voice pattern worth flagging is an interpretive claim that hides its agent. A sentence that argues a conclusion is stronger when it names who is arguing: "We interpret the yield decline as water stress" is more accountable than "The yield decline may be interpreted as water stress." This is detectable in the sentence itself: the sentence is drawing an inference rather than reporting a procedure. Offer the active rewrite as a suggestion, not an automatic change, since some authors and journals require the impersonal form.

This rule reads each sentence on its own and needs no knowledge of which section it came from.

---

## 10. Editing checklist

### Language and format
- US English throughout? Check sulfur/sulphur, analyze/analyse, color/colour, modeling/modelling, center/centre.
- Any em dashes? Remove all. Restructure or use commas, parentheses, colons.
- Any vague quantifiers (many, several, various, numerous, often, some)? Replace with numbers or citations.
- Tense matches each sentence's function? Past for actions performed; present for established facts and figure descriptions. Flag inconsistency, not section.

### Surface prose
- Any throat-clearing openers ("It is important to note," "Interestingly," "What's more")? Cut to the content.
- Any empty "not X, it's Y" or "not just X but also Y" contrasts? State the point directly. (Keep genuine contrastive findings.)
- Any rhetorical adverbs (clearly, notably, importantly, fundamentally)? Remove. (Keep statistically, approximately, respectively.)
- Any genuine anthropomorphization (data "believe," study "aims to prove")? Rewrite with an explicit agent. (Keep "Figure shows," "model predicts.")
- Any performative meta-commentary ("As we'll see," "Plot twist")? Cut. (Keep functional signposting in theses and reports.)
- Any nominalization hiding a verb ("conducted an analysis of" for "analyzed"), wordy connective ("due to the fact that" for "because"), or expletive ("there are X that") padding a sentence? Recover the verb, shorten, or cut. Cut dead words only; never drop a number, unit, or method detail.
- Any interpretive claim that hides its agent ("may be interpreted as")? Suggest the active form. Leave procedural passive ("samples were collected") alone.
- Three or more consecutive sentences of identical length? Break one, without sacrificing clarity.

### Epistemic accuracy
- Does verb strength match the design? "Demonstrate" requires alternatives excluded; "suggest" fits observational or preliminary data.
- Does "significant" mean statistically tested with reported alpha, statistic, and p-value? If not, replace.
- Are causal claims supported by a design that permits causal inference? If observational, use associative language.
- Are scope claims specific (n, range, period, method)?

### Specificity
- Does every rhetorical adjective (crucial, robust, comprehensive) have a measurable or scoped replacement?
- Does every "the literature suggests" have a specific citation?
- Does every quantitative result include units, an uncertainty estimate, and the test statistic?
- Does every "first study to" include a search scope and date?

### Citations
- Has every citation been checked manually against the specific claim?
- Any citation that looks plausible but cannot be found in the named journal or database?
- Are methods cited to the describing paper, not the using paper?
- Are preprints labeled as such?

### AI-style phrases to remove or rewrite

| Remove | Rewrite as |
|---|---|
| "It is important to note that..." | State the point. |
| "This study aims to..." | State the objective, or use past tense for what you did. |
| "The results underscore the importance of..." | State the specific implication. |
| "This enhances our understanding of..." | State what is now known that was not before. |
| "More research is needed" | Specify the exact question, design, and scope. |
| "A growing body of literature suggests..." | Cite the key papers specifically. |
| "The findings have important implications for..." | State the specific implication. |

---

## 11. Scoring

Rate the draft 1 to 10 on each dimension. The first three are weighted heaviest because they track the severity hierarchy in Section 0.

| Dimension | Question | Weight |
|---|---|---|
| Citation integrity | Does every claim trace to a verified, correctly matched source? | High |
| Epistemic accuracy | Does every verb match what the design supports? | High |
| Specificity | Are scope, quantities, and units stated, not gestured at? | High |
| Directness | Statements, or announcements and throat-clearing? | Medium |
| Density | Anything cuttable without losing information? | Medium |

Below 35/50 overall, or any of the first three scoring below 6, means revise before submission.

---

## 12. What this skill does not replace

Style and AI-prose patterns only. It does not cover:

- Research design validity or internal/external validity assessment.
- Statistical method selection for specific designs.
- Journal-specific style guides (APA, CSE, ACS, Vancouver): always defer to the target journal's author guidelines.
- AI use disclosure: most journals now require explicit disclosure if AI tools generated or substantially revised manuscript text. This is an ethical authorship requirement, not a style question. Check the specific journal policy before submission.

---

## 13. Source notes

[Juzek and Ward, 2024/2025](https://arxiv.org/abs/2412.11385): Identifies 21 words overrepresented in LLM-associated scientific writing, including "delve," "intricate," and "underscore." The most directly applicable empirical source. Published at COLING.

[El Attar et al., 2026](https://arxiv.org/abs/2606.04177): Large-scale study across 27 LLMs and 10 text domains. Key finding: many proposed AI-writing indicators are context-dependent; lexical richness is more robust. Not peer-reviewed as of this date; treat as provisional.

[Kousha and Thelwall, 2025](https://arxiv.org/abs/2509.09596): Corpus-level tracking of LLM-associated terms across scholarly databases.

[Jakesch, Hancock, and Naaman, 2022](https://arxiv.org/abs/2206.07271): Human heuristics for detecting AI writing are unreliable. Do not accuse a colleague of AI use on vocabulary clustering alone.

[Georgiou, 2024](https://arxiv.org/abs/2407.03646): Linguistic feature comparison between human and ChatGPT essays. Domain- and prompt-specific.

[Shaib et al., 2025](https://arxiv.org/abs/2509.19163): Taxonomy of AI slop. Binary quality judgments are subjective but correlate with coherence and relevance dimensions.

---

## 14. Conclusion

AI-generated science writing fails on three dimensions, in order of severity: citation integrity, epistemic accuracy, and specificity. Vocabulary and rhythm signals are real but secondary. Fix the substance first, then the style. The safest test is accountability: does every claim have a specific source, a measurable scope, and an appropriately hedged epistemic verb? If not, the sentence needs rewriting regardless of whether AI was involved.
