# AGENTS.md - PRAXIS KTH Interviews

## Startup sequence

1. Read this `AGENTS.md`.
2. Read `docs/04-ethics-data-governance.md`.
3. Read `docs/01-methodology.md`.
4. Apply the requested task without violating the rules below.

## Project scope

This repository is a separate qualitative follow-up of PRAXIS at KTH Royal Institute of Technology.

The study keeps the original PRAXIS framework and codebook logic, but changes the instrument:

- from online questionnaire to face-to-face semi-structured interviews;
- from Italian school/university samples to KTH teachers/faculty, doctoral students, and students;
- from primarily survey-style answers to interview transcripts and field notes.

## Canonical structure

```
docs/                  project design, methodology, protocol, governance
templates/             reusable consent, transcript, and record templates
codebook/              KTH-adapted PRAXIS codebook material
data/raw-audio/        local raw audio only, never committed
data/raw-transcripts/  local verbatim transcripts only, never committed
data/processed/        local de-identified intermediate files, normally not committed
corpus/                de-identified corpus records only, committed case by case
analysis/              analytic memos, coding summaries, traceability tables
logs/                  fieldwork and decision logs
```

## Non-negotiable rules

1. Do not commit identifiable audio, transcripts, names, email addresses, or direct role combinations that can identify a participant.
2. Do not use KTH affiliation details as identifiers unless they have been generalized.
3. Keep empirical interview evidence separate from bibliographic references.
4. Do not invent evidence. If an interview does not support a claim, state that the evidence is missing.
5. Preserve the PRAXIS dimensions unless a documented KTH-specific extension is needed.
6. Record codebook changes in `logs/codebook-decision-log.md`.
7. Record recruitment and fieldwork progress in `logs/fieldwork-log.md`.
8. Treat this as qualitative research. Do not add inferential statistical claims unless explicitly requested and methodologically justified.

## PRAXIS framework

- `P`: Practice patterns
- `R`: Readiness beliefs
- `A`: Adequacy of support
- `X`: eXpectations
- `I`: Interpersonal & Institutional trust
- `S`: Skepticisms

