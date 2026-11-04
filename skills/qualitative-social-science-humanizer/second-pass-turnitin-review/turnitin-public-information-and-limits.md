# Turnitin Public Information and Limits

Read this module only when the user supplies Turnitin material or asks how that material should be interpreted. It supports responsible academic review and does not provide detector-evasion tactics.

Last source review: **27 August 2026**.

## Contextual processing

Turnitin's public materials describe a submitted paper as being processed in overlapping prose segments, with sentence-level values contributing to segment and document results. This supports reviewing a highlighted passage with its paragraph and section context rather than treating isolated words as the cause.

Sources: Turnitin's [technical whitepaper landing page](https://www.turnitin.com/whitepapers/turnitin-ai-writing-detection-model-architecture-and-testing-protocol) and [explanation of AI-checker processing](https://www.turnitin.com/blog/how-an-ai-checker-can-support-quality-original-writing).

## Qualifying long-form prose

Turnitin describes its AI-writing percentage as applying to qualifying prose in long-form writing, not necessarily every element of a submission. Its public release history records minimum qualifying-text requirements and notes that more text improves accuracy. The Skill does not attempt to reproduce this processing.

Sources: [Using the AI Writing Report](https://guides.turnitin.com/hc/en-us/articles/22774058814093-Using-the-AI-Writing-Report) and the [release-notes archive](https://guides.turnitin.com/hc/en-us/articles/33092161932045-Release-notes-archive).

## Advisory status

Turnitin states that its model may misidentify human-written, AI-generated, and altered text and should not be the sole basis for adverse action. Further scrutiny, human judgement, and institutional policy are required. Treat a score or highlight as external review information, not proof of authorship or misconduct.

Sources: [Using the AI Writing Report](https://guides.turnitin.com/hc/en-us/articles/22774058814093-Using-the-AI-Writing-Report), [reviewing the AI Writing Report](https://guides.turnitin.com/hc/en-us/articles/27139000787853-How-should-I-review-the-AI-Writing-report), and [responding to a high AI Writing score](https://guides.turnitin.com/hc/en-us/articles/27139113024269-What-should-I-do-if-the-AI-Writing-score-is-high).

## False positives and reporting rules

Turnitin acknowledges false positives. Its public guidance explains that some low-range results are displayed without a specific percentage or highlights because this range has a higher incidence of false positives. A display rule is not an integrity threshold and must not become a revision target.

Sources: [AI writing detection model release notes](https://guides.turnitin.com/hc/en-us/articles/28294949544717-AI-writing-detection-model) and [classic-report access guidance](https://guides.turnitin.com/hc/en-us/articles/28457596598925-AI-writing-detection-in-the-classic-report-view).

## Model changes

Turnitin's public release notes document continuing model and output changes. Reports created at different times may not be directly comparable, and a resubmission may produce a different result. The Skill must not infer stable hidden features from a single report.

Source: [AI writing detection model release notes](https://guides.turnitin.com/hc/en-us/articles/28294949544717-AI-writing-detection-model).

## What public sources do not establish

The cited public sources do not provide a reliable basis for:

- an individual-word trigger list;
- hidden feature weights or complete classifier inputs;
- a stable sentence-level threshold usable outside Turnitin;
- a guaranteed relationship between a particular edit and a final score;
- reverse-engineering or bypass tactics;
- a guarantee that human-authored or carefully edited prose will receive a particular classification.

Do not infer any of these claims.

## Safe editing implications

When Turnitin material is supplied:

1. record only what the supplied material actually shows;
2. apply the user's explanation of colours, or use blue as the default AI-written flag colour when the user gives no explanation;
3. map highlights to the exact first-pass manuscript;
4. inspect each mapped region in its paragraph and section context;
5. use the user's stored writing samples as the main author-voice reference;
6. revise only when an independent academic-quality problem exists;
7. keep academically justified or protected prose;
8. keep all non-flagged passages unchanged by default;
9. preserve drafts, notes, and revision history when authorship questions require process evidence;
10. state that no revision can guarantee a detector outcome.

## Maintenance

When updating this file, prefer current Turnitin documentation, record the review date, distinguish vendor claims from independent evidence, and remove or qualify information that current public documentation no longer supports.
