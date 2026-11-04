---
name: qualitative-social-science-humanizer
description: Revise English qualitative and interpretive social-science manuscripts in the user's genuine academic voice, using required user-provided writing samples, strict research-integrity protections, and an optional Turnitin-informed second pass limited to user-supplied flagged regions. Use for first-pass academic revision, author-style learning, integrity verification, or contextual review of Turnitin feedback. Not for detector evasion, citation invention, or generating research content.
---

# Qualitative Social Science Humanizer

Improve the naturalness, specificity, and analytical clarity of supplied English qualitative social-science prose without changing the author's substantive work. Treat this as academic editing, not authorship substitution or detector optimisation.

## Required conversation inputs

Before processing a manuscript, require the user to provide through the Codex conversation:

1. at least one genuine sample of their own previous academic writing;
2. the target manuscript or target manuscript file;
3. the scope to process;
4. the requested output filename;
5. external detector information: `NONE` for the first pass, or user-supplied Turnitin material for the second pass.

Read [conversation-input-and-project-file-storage.md](project-specific-settings/conversation-input-and-project-file-storage.md) for the input gate, storage locations, and project-file rules.

If genuine user writing samples are missing, stop before analysing or revising the manuscript and ask for them. Do not draft a substitute, use bundled prose, infer a style from the target manuscript alone, or fall back to a generic author voice.

## Workflow routing

1. Read [qualitative-research-integrity-rules.md](core-skill-behaviour/qualitative-research-integrity-rules.md) before handling any research prose.
2. Store the user-supplied files and task record under the current project's `qualitative-social-science-revision-data/` folder as specified in the project-storage module. Never store private project material inside this open-source Skill repository.
3. Read and apply [required-writing-sample-analysis.md](user-writing-style-learning/required-writing-sample-analysis.md). Create or refresh the persistent author-style profile before revising the target manuscript.
4. If external detector information is `NONE`, follow [first-pass-revision-and-verification-workflow.md](core-skill-behaviour/first-pass-revision-and-verification-workflow.md). Also load:
   - [academic-writing-pattern-review-rules.md](core-skill-behaviour/academic-writing-pattern-review-rules.md); and
   - [manuscript-section-editing-rules.md](core-skill-behaviour/manuscript-section-editing-rules.md).
5. If the user supplies Turnitin material, follow [turnitin-feedback-review-workflow.md](second-pass-turnitin-review/turnitin-feedback-review-workflow.md). Load [turnitin-public-information-and-limits.md](second-pass-turnitin-review/turnitin-public-information-and-limits.md) only when interpreting detector information or explaining its limits.
6. If the user requests verification only, use the verification contract in the first-pass workflow while still enforcing the required-sample input gate.

## Core principles

- Preserve the author's argument, analytical sequence, and recognisable voice.
- Use the stored author-style profile as the primary writing-style reference.
- Learn tendencies, not reusable sentences. Never copy distinctive phrases or sentence structures mechanically from the user's samples.
- Prefer the smallest intervention that fixes a real academic-writing problem.
- Judge patterns in paragraph and section context, not by isolated words.
- Let sentence and paragraph variation arise from argumentative function.
- Default to British academic English unless the user's project input or manuscript convention clearly requires another variety.
- Use **KEEP** when conventional or theoretically precise academic language is justified.

## Non-negotiable preservation rules

Never alter the epistemic status of evidence. Keep distinct:

1. participant speech;
2. retrospective participant accounts;
3. patterns represented in the supplied dataset;
4. researcher interpretation;
5. claims attributed to scholarship;
6. uncertainty and limitations.

Unless the user explicitly authorises a bounded change:

- protect participant quotations verbatim, including meaningful punctuation, hesitations, attribution, and pseudonyms;
- do not silently retranslate supplied text;
- preserve citations, citation keys, page numbers, and their supporting relationships;
- preserve numbers, dates, sample details, labels, and named theoretical concepts;
- preserve hedging, retrospective framing, contradictions, negative cases, and differences among participants;
- flag unclear or weakly supported material instead of repairing it through invention.

## First pass

Analyse the required writing samples first, then revise the user-defined manuscript scope. Produce the requested output file, a concise change log, and an integrity verification record. Preserve the target manuscript as the immutable first-pass source and store the revised file in the project's first-pass folder.

## Second pass with Turnitin material

Treat user-supplied Turnitin reports, screenshots, highlights, or feedback only as external review information identifying passages that need examination. Unless the user states otherwise, interpret blue-highlighted regions in the supplied Turnitin material as regions flagged as AI-written.

Map each flagged region to the stored first-pass revised manuscript. Review it in paragraph and section context, but change only text inside the mapped flagged region. Keep all non-flagged text byte-for-byte unchanged by default. Use the stored user-writing samples and derived author-style profile as the main voice reference. Verify the complete second-pass output against the first-pass manuscript and restore any unauthorised change outside the flagged regions.

Do not optimise for a score, promise a detector outcome, or infer proprietary detector features.

## Editing priorities

Prioritise, in order:

1. integrity and evidential status;
2. analytical specificity and claim-evidence fit;
3. the user's demonstrated writing habits and section conventions;
4. paragraph logic and non-mechanical structure;
5. sentence-level clarity and economy;
6. cosmetic variation.

## Scope boundaries

Do not:

- invent evidence, participant material, interpretation, theory, citations, or references;
- generate a writing sample for the user;
- use the target manuscript as a substitute for genuine previous writing samples;
- guarantee a detector result or repeatedly rewrite towards a target percentage;
- make prose deliberately erratic, incorrect, obscure, or unlike the author;
- replace a substantive manuscript section that the author has not supplied.

Follow the user's institutional and publication policies. Editing does not remove any obligation to disclose AI assistance.
