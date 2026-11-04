# Turnitin Feedback Second-Pass Review Workflow

Use this module only after a first-pass revised manuscript exists and the user supplies Turnitin material through the Codex conversation. The Turnitin material is external review information that identifies passages for further examination. It is not proof of AI authorship, misconduct, or a hidden writing defect.

## Required second-pass inputs

Confirm all of the following before editing:

- the stored user writing samples;
- the stored author-style profile;
- the exact first-pass revised manuscript that the user checked;
- the user-defined second-pass scope;
- the requested second-pass output filename;
- the supplied Turnitin report, screenshots, highlighted document, or written feedback.

If the first-pass manuscript cannot be identified unambiguously, stop and ask the user to identify or upload the exact checked version. Do not compare the report with the original pre-revision manuscript or with a later unverified copy.

## Interpret the supplied feedback

1. Follow any explicit legend or explanation supplied by the user.
2. Otherwise, treat blue-highlighted regions as the passages Turnitin flagged as AI-written.
3. Do not infer that other colours have the same meaning.
4. Read screenshots and reports carefully enough to capture the full highlighted span. If a boundary or word is unreadable, ask for a clearer image or the corresponding text rather than guessing.
5. Record report metadata that the user supplied, but do not infer missing dates, versions, percentages, or categories.

## Map flags to the first-pass manuscript

Create an internal flagged-region ledger before revising. For each flag, record:

- a stable region identifier;
- the exact highlighted text as visible in the supplied material;
- the matching location in the first-pass manuscript;
- enough unflagged text before and after the region to verify the match;
- match status: `EXACT`, `UNIQUE CONTEXT MATCH`, `AMBIGUOUS`, or `NOT FOUND`;
- any protected element inside the region.

Revise only regions with an exact or unique contextual match. If the same wording appears more than once, the report boundary is unclear, or the text cannot be found, stop on that region and ask the user to resolve it. Never choose a location by guesswork.

## Contextual review

For every mapped region:

1. read the whole paragraph and the relevant section context;
2. identify whether the flagged span has an independent academic-writing problem under the core rules;
3. compare it with the user's stored writing samples and author-style profile;
4. choose `KEEP` when the wording is academically justified or protected;
5. choose `REVISE FOR ACADEMIC QUALITY` only when a real issue exists independently of the Turnitin flag.

The surrounding paragraph is context for judgement, not permission to edit outside the mapped region.

## Editing boundary

- Changes may occur only inside a mapped flagged span.
- All non-flagged passages are locked and must remain byte-for-byte unchanged by default.
- If a safe revision would require changing unflagged text, do not make that change. Explain the dependency and request explicit authorisation.
- Preserve quotations, citations, evidence, theoretical terminology, qualitative hedging, retrospective attribution, participant differences, uncertainty, and analytical meaning inside flagged regions.
- Do not add new claims, evidence, sources, interpretations, or participant material.
- Do not copy distinctive phrases or sentence structures from the writing samples. Apply only the user's broader demonstrated habits.
- Do not revise sound prose merely because it was highlighted.

## Verification against the first-pass manuscript

After producing the second-pass manuscript:

1. compare the complete second-pass file with the exact first-pass manuscript;
2. confirm every changed character falls inside an authorised mapped flagged region;
3. confirm every non-flagged passage is unchanged;
4. recheck quotations, citations, pseudonyms, numbers, dates, sample information, theory, hedging, causality, retrospective status, disagreement, and negative cases;
5. restore any change outside the permitted regions;
6. store the second-pass file and verification record in the project data folder.

Treat any unexplained non-flagged difference as a failed verification.

## Second-pass output

Return:

1. the second-pass manuscript at the requested output path;
2. a flagged-region decision log with the region identifier, location, decision, academic reason, and whether text changed;
3. an integrity statement confirming preservation of protected elements;
4. a scope-lock statement confirming that non-flagged text was compared with the first-pass manuscript and remained unchanged;
5. unresolved mapping questions, if any.

Do not report a claimed reduction in AI probability or promise how Turnitin will classify the revision.
