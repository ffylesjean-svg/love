# First-Pass Revision and Verification Workflow

Use this workflow when `EXTERNAL DETECTOR INFORMATION` is `NONE`. The normal first-pass outcome is a revised manuscript file based on the user's target manuscript and required genuine writing samples.

## Preflight gate

Before reading the target manuscript for revision, confirm that the Skill has:

- the five required user-defined input fields;
- at least one genuine user writing sample stored in the current project;
- a completed, current author-style analysis;
- an exact stored copy of the target manuscript;
- a clear scope and output filename.

If the writing sample or style analysis is missing, stop. Do not use generic prose, the target manuscript alone, or generated text as a substitute.

## First-pass method

1. Read the stored author-style profile and consult the eligible user writing samples.
2. Identify manuscript sections and apply the built-in section-intensity rules.
3. Lock participant quotations, citations, citation keys, pseudonyms, numbers, dates, sample information, protected theory, and epistemic markers.
4. Review the requested scope in paragraph and section context for genuine academic-writing problems.
5. Revise HIGH-priority problems by default and MEDIUM-priority problems only when the improvement is clear. Preserve LOW and KEEP material by default.
6. Work at the smallest useful level. Use paragraph-level repair only for paragraph-level problems; do not rely on mechanical synonym substitution.
7. Preserve argument order, evidence order, and emphasis unless the user has explicitly authorised restructuring.
8. Use the user's demonstrated writing habits as the author-voice reference without copying distinctive phrases or sentence structures.
9. Compare the complete revision with the stored target manuscript and run the integrity checks below.
10. Save the revised manuscript in `qualitative-social-science-revision-data/first-pass-revisions/` using the user's requested output filename.
11. Save the verification record in `qualitative-social-science-revision-data/verification-records/` without overwriting earlier records.

## Integrity verification

Check:

- participant quotations unchanged unless specifically authorised;
- citations, citation keys, and page numbers preserved;
- pseudonyms and participant labels preserved;
- numbers, dates, and sample information preserved;
- participant attribution preserved;
- named theoretical terminology preserved;
- no stronger causal, factual, or general claim introduced;
- no loss of hedging or uncertainty;
- no retrospective account converted into objective fact;
- no disagreement, contradiction, or negative case removed;
- no evidence, quotation, interpretation, or citation invented;
- argument and evidence order preserved unless authorised;
- the requested scope respected;
- output filename and storage location correct.

Any unexplained mismatch in a protected element is a failed check and must be repaired before delivery.

## First-pass output

Return:

1. a link or exact path to the revised manuscript file;
2. a concise change log limited to changes actually made;
3. an integrity result: `PASS`, `PASS WITH AUTHOR QUESTIONS`, or `FAIL`;
4. any question that requires the author's substantive judgement;
5. a note that the first-pass file is the required baseline for any later Turnitin-informed second pass.

Do not claim that the revision changes an AI probability or guarantees a detector result.

## User-requested audit

If the user explicitly requests an audit without revision, apply the same input gate and contextual review. Do not rewrite. For each material issue, report the passage location, pattern, contextual reason, priority, and revision direction. Use `HIGH`, `MEDIUM`, `LOW`, or `KEEP` and identify protected elements.

An audit does not authorise revision.

## User-requested verification only

If the user asks only to compare supplied versions, do not silently edit either version. Return a concise check record for protected elements, scope, evidential status, and unauthorised additions. Use `PASS`, `PASS WITH FLAGS`, or `FAIL`, and identify exact differences requiring repair or author decision.
