# PRAXIS KTH Interviews

Studio qualitativo separato per replicare il metodo PRAXIS al KTH, usando lo stesso framework e lo stesso impianto di codebook, ma con interviste semi-strutturate faccia a faccia invece di domande online.

## Repository di riferimento

Questo repository e' il riferimento operativo principale per lo studio PRAXIS KTH Interviews. Tutte le decisioni metodologiche, i protocolli, gli adattamenti del codebook, i template e i log di lavoro relativi alla replica KTH devono essere mantenuti qui, senza mescolare questo studio con il repository PRAXIS originale o con il repository della survey online.

## Obiettivo

Capire come docenti/faculty, dottorandi e studenti del KTH usano, interpretano e regolano la GenAI nei contesti di insegnamento, apprendimento, ricerca e supervisione.

## Disegno

- Metodo: interviste qualitative semi-strutturate in presenza.
- Partecipanti: KTH teachers/faculty, doctoral students, students.
- Framework: PRAXIS.
- Analisi: codifica tematica qualitativa, con codebook PRAXIS adattato al contesto KTH.
- Comparabilita': mantenere i codici PRAXIS originali dove possibile; introdurre domande e sottocodici KTH solo con decisione documentata.

## Struttura

```
docs/
  00-project-brief.md
  01-methodology.md
  02-interview-protocol.md
  03-codebook-adaptation.md
  04-ethics-data-governance.md
  05-analysis-plan.md
templates/
  participant-information-sheet.md
  consent-form.md
  interview-record-template.md
  transcript-template.md
codebook/
  praxis-kth-codebook.yaml
data/
  raw-audio/          # non versionare
  raw-transcripts/    # non versionare
  processed/          # non versionare salvo decisione esplicita
corpus/               # solo record de-identificati
analysis/
logs/
```

## Stato

Baseline repository creata il 2026-05-29.

Prima della raccolta dati bisogna verificare le procedure KTH su etica, consenso, GDPR e gestione dei dati. Il repository include bozze operative, non approvazioni istituzionali.
