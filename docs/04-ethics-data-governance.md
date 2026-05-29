# Ethics and Data Governance

## Status

This document is an operational draft. It is not an ethics approval, legal assessment, or institutional authorization.

Before recruitment or data collection, verify the current KTH and Swedish requirements with the relevant KTH support channels.

Official KTH sources checked on 2026-05-29:

- KTH, Ethics review for research on humans: https://intra.kth.se/en/forskning/overgripande-stod/etik-och-god-forskni/ethicsreview/ethics-review-for-research-on-humans-1.1146316
- KTH, Application for ethics review: https://intra.kth.se/en/forskning/overgripande-stod/etik-och-god-forskni/ethicsreview/application-for-ethics-review-1.1146329
- KTH, Ethical and legal aspects of research data management: https://www.kth.se/en/biblioteket/publicera-analysera/hantera-forskningsdata/planera-och-dokument/etiska-och-juridiska-aspekter-kring-hantering-av-forskningsdata-1.861140

## Practical implication

The KTH pages state that ethics review may be required for research on human participants, especially where sensitive personal data or other legally relevant categories are processed. They also point to the Swedish Ethical Review Authority and KTH research support processes.

For this study, do not start interviews until the required route is clarified.

## Data classification

Expected data:

- consent records;
- audio recordings, if consented;
- verbatim transcripts;
- field notes;
- de-identified corpus records;
- coded segments and analytic memos.

High-risk data:

- audio recordings;
- exact role and department combinations;
- names of colleagues, supervisors, courses, labs, or projects;
- unpublished research details;
- personal opinions tied to identifiable institutional situations.

## Repository rule

This git repository must not contain identifiable data.

Allowed:

- protocols;
- blank templates;
- de-identified excerpts;
- generalized participant metadata;
- analytic memos without identifying details.

Not allowed:

- raw audio;
- raw transcripts;
- signed consent forms;
- names, emails, or exact personal identifiers;
- identifiable combinations of role, department, course, nationality, supervisor, or project.

## Participant IDs

Use IDs such as:

- `KTH-FAC-001`
- `KTH-PHD-001`
- `KTH-STU-001`

Keep the ID key outside git in a secure location approved for the project.

## De-identification

Before any transcript enters `corpus/`, remove or generalize:

- person names;
- exact department or division where unnecessary;
- course codes and small program names;
- supervisors or lab names;
- exact nationality if not analytically necessary;
- rare biographical combinations;
- unpublished research details.

Use bracketed replacements:

- `[department generalized]`
- `[course omitted]`
- `[supervisor omitted]`
- `[research topic generalized]`

## AI tool use on interview data

Do not upload identifiable audio, transcripts, or field notes to third-party AI tools unless this is explicitly approved by the data governance route and covered by participant information and consent.

Local or institutionally approved tools may still require documentation.

## Traceability

Maintain the evidence chain without exposing identity:

`participant_id -> transcript segment id -> de-identified excerpt -> PRAXIS code -> memo -> report section`

Use `analysis/traceability-table.md` for publication-facing evidence tracking.

