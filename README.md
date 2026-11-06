# Jean-Pierre Serre, *Faisceaux algébriques cohérents* (FAC, 1955)

[Français](README.fr.md)

Serre's "FAC", *Annals of Mathematics* (2) 61 (1955), pp. 197–278: coherent sheaves on algebraic varieties and their
cohomology. This edition gives the paper in LaTeX, in French and in an English translation.

| | |
|---|---|
| [French as printed (PDF, 63 pages)][dip] | including the printing's misprints |
| [French, corrected (PDF, 63 pages)][cor] | evident misprints corrected |
| [English translation (PDF, 78 pages)][en] | |
| [LaTeX sources (ZIP)][zip] | also browsable in this repository |

Build each with pdfLaTeX: `fac.tex` in `french-diplomatic/` or `french-corrected/`, and
`english/Serre_FAC_English_complete_reference_v2.tex`, as many passes as the references need (three is enough).

## How it was made

AI-transcribed and AI-translated, July–August 2026, from the scan of the *Annals* article
([10.2307/1969915](https://doi.org/10.2307/1969915)). A first-pass French transcription (Claude Opus 5, according to
the project records) was checked against the scan and corrected by OpenAI Codex (GPT-5.6, Ultra effort), which also
made the English translation.

An English translation by Piotr Achinger and Łukasz Krupa already existed (2010,
[achinger.impan.pl/fac](https://achinger.impan.pl/fac/fac.pdf)). Numbers 1–79 of this English were translated before
it was known; numbers 80–81 were completed with it at hand for comparison, and were still translated from Serre's
French.

## Quality

This release has not yet been spot-checked against the scan by a second model. More checking is planned; until then,
cite the printed paper.

## Rights

The rights in the original work belong to its author or the author's representatives or heirs. Where we hold rights,
in the AI-produced transcription, translation, corrections and typesetting, they are dedicated to the public domain
under CC0 1.0. This edition is published for educational, non-profit purposes, and we claim no rights we do not hold.
If you hold rights in this work and object to its publication here, please open a GitHub issue and we will take it
down.

[dip]: https://github.com/KokunoYumeto/serre-fac/releases/download/edition-2026-11-06/fac-fr-diplomatic.pdf
[cor]: https://github.com/KokunoYumeto/serre-fac/releases/download/edition-2026-11-06/fac-fr-corrected.pdf
[en]: https://github.com/KokunoYumeto/serre-fac/releases/download/edition-2026-11-06/fac-en.pdf
[zip]: https://github.com/KokunoYumeto/serre-fac/releases/download/edition-2026-11-06/fac-sources.zip
