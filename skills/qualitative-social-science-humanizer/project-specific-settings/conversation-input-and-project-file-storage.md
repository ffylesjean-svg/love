# Conversation Input and Project File Storage

This module controls the information the user defines and where conversation-supplied materials are retained for the current project. It does not replace the built-in research-integrity, writing-style, section, or review rules.

## Required user-defined input

Before processing a manuscript, read these five completed fields from the Codex conversation:

```text
INPUT FILE:
[User provides the target manuscript]

SCOPE:
[User defines the part of the manuscript to process]

OUTPUT FILE:
[User defines the output file name]

USER WRITING SAMPLES:
[User provides their own previous academic writing examples]

EXTERNAL DETECTOR INFORMATION:
[NONE for the first pass, or Turnitin material for the second pass]
```

These are the only required user-defined settings. Do not ask the user to restate rules that are already built into the Skill.

The user may upload the materials in one message or in consecutive messages in the same Codex task. Treat conversation attachments and pasted text as supplied input. Resolve each uploaded file by its actual attachment path when available.

## Input gate

At least one genuine previous academic writing sample from the user is mandatory before any manuscript analysis, revision, or verification begins.

If the field is missing, empty, points only to the target manuscript, or contains Codex-generated prose:

1. do not process the manuscript;
2. explain that genuine previous academic writing is required;
3. ask the user to upload or paste at least one sample;
4. do not create a substitute sample or generic author-style profile.

Accept only material the user identifies as their own previous academic writing. If authorship or provenance is unclear, ask for clarification before using it for style learning.

## Project data location

Create the following private working structure in the user's current research-project root only after the user supplies project material:

```text
qualitative-social-science-revision-data/
├── project-specific-settings/
│   └── current-user-input.md
├── user-provided-writing-samples/
├── learned-user-writing-style/
│   └── author-writing-style-profile.md
├── target-manuscripts/
├── first-pass-revisions/
├── turnitin-feedback/
├── second-pass-revisions/
└── verification-records/
```

Do not place personal writing, manuscripts, reports, or derived author profiles inside the installed Skill repository. The project data folder is deliberately separate so one project's material cannot influence another project.

## Storage rules

- Copy conversation-supplied writing samples into `user-provided-writing-samples/` without modifying their contents.
- Copy the target manuscript into `target-manuscripts/` without overwriting the user's original attachment or source file.
- Record the five user-defined fields and the resolved stored filenames in `project-specific-settings/current-user-input.md`.
- Store the derived style profile in `learned-user-writing-style/author-writing-style-profile.md`.
- Store the first-pass result in `first-pass-revisions/` using the user-defined output filename.
- Store uploaded Turnitin files in `turnitin-feedback/` when a local copy is available.
- Store second-pass results in `second-pass-revisions/` and comparison reports in `verification-records/`.
- Preserve prior files when the user returns for later work. Use unambiguous names or dated subfolders rather than overwriting a prior revision.
- Treat all stored material as private research data. Warn the user before any action that would publish or commit it.

If no writable project root is available, ask the user to choose one. Do not silently store private writing inside the Skill installation.

## Pass selection

- `EXTERNAL DETECTOR INFORMATION: NONE` selects the first-pass revision workflow.
- Supplied Turnitin material selects the second-pass review workflow.
- If detector material is supplied but the exact checked first-pass manuscript is unavailable, require that manuscript before proceeding.

Do not require a separate mode field. Infer the pass from the external-detector field while following any explicit scope instruction from the user.

## Built-in settings that users do not need to enter

The Skill already controls:

- research-integrity and evidence-preservation rules;
- mandatory author-style learning from genuine user samples;
- section-sensitive editing intensity;
- first-pass revision and verification;
- default interpretation of blue Turnitin highlights;
- second-pass flagged-region mapping and non-flagged text locking;
- British academic English as the fallback convention;
- prohibitions on invented content, detector optimisation, and mechanical phrase copying.
