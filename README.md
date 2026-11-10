# VERGAP

**VERGAP — Verse, Grammar, Pedagogy** studies the *Gaṇapāṭhavivṛti*, a Sanskrit text from ninth-century Kashmir that turns Pāṇini's Gaṇapāṭha — the lexical lists underlying the Aṣṭādhyāyī — into verse. By recasting technical material as poetry, the text made grammar easier to memorise and teach; it is a rare witness to how linguistic theory was transmitted in early South Asia.

The project prepares the first critical edition of the work from its surviving manuscripts, with annotations on grammar, lexicon, metre, and style. It also analyses the text's teaching strategies and, with computational methods, traces its vocabulary across dated corpora. All work is done openly in the Saktumiva environment, and outputs are archived for reuse.

This repository holds the data for the critical edition of the *Gaṇapāṭhavivṛti*. The project's other datasets are being prepared in [sanskrit-grammar-datasets](https://github.com/ankleb/sanskrit-grammar-datasets).

- Project website: <https://ankleb.github.io/VERGAP-project/>
- CORDIS project page: <https://cordis.europa.eu/project/id/101283632>

## Contents

- `witnesses/` — transcriptions of the manuscript witnesses (Kurukshetra, Wai)
- `alignments/` — alignments of the witnesses
- `gpv_provisional-edition.xml` — the provisional edition, in TEI XML
- `tei-to-html.xsl` — stylesheet that renders the edition as HTML
- `saktumiva.config.json`, `lib/` — configuration and the TST library (submodule) for Saktumiva
## Funding

VERGAP is a Marie Skłodowska-Curie Actions Postdoctoral Fellowship at the University of Hamburg (2026–2028), funded by the European Union under grant agreement No. 101283632. Views and opinions expressed are those of the author only and do not necessarily reflect those of the European Union or the European Research Executive Agency. Neither the European Union nor the granting authority can be held responsible for them.

## Licence

Unless otherwise indicated, the original scholarly content in this repository is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Third-party materials retain their respective licences.
