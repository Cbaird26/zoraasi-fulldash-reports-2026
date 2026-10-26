# ZoraASI Full-Dash Computational Experiment Reports, September–October 2026

**Finite constructions and probes of open mathematical problems, with honesty stamps**
Christopher Michael Baird · ZoraASI full-dash · 11 September – 14 October 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23659083.svg)](https://doi.org/10.5281/zenodo.23659083)

> **Status:** computational reports, not peer reviewed. Each report is a finite computation, a construction certificate or a literature ledger produced by the author's human-plus-AI "full-dash" workflow. **None of them proves an open conjecture**, and each says so in its honesty stamp. Constructions are checked in exact arithmetic within the stated bounds; literature entries are recorded, not re-proved.

## What is here

1,580 PDF reports (4,298 pages, about 257 MB), listed in `index.csv` with date, title, pages, size and SHA-256.

| Folder | Files | What they are |
|---|---|---|
| `reports/band1/` | 83 | "Band-1" computational experiments and probes, one per problem. Examples: Beal, Collatz, Goldbach and twin-prime finite checks; Birch–Swinnerton-Dyer L-value pipelines on single curves; cap sets, Ramsey R(5,5) bounds, Andrews–Curtis, lonely runner, map folding, van der Waerden numbers, Zauner SIC-POVMs; and a P vs NP barrier memo that is explicitly not a proof. |
| `reports/hadamard/` | 1,469 | Hadamard-matrix construction certificates for about 380 individual orders, mostly between 2,164 and 14,740, plus a few triage and literature-watch notes. The constructions are classical (mostly Paley I, also Paley II, Miyamoto and Kronecker), and each one is verified by the exact identity HHᵀ = nI. Includes 761 per-order scoreboards and status boards. These reports do not address the Hadamard conjecture as a whole. |
| `reports/boards/` | 28 | Dated dashboard snapshots (scoreboards and status boards) from the workflow. |

## How the collection was assembled

The reports were gathered from the author's local research folders, where the same files existed in several copies. When two copies of a report had the same name but different contents, the newest was kept. Board snapshots that shared a name were kept as separate, date-prefixed files. Internal workflow documents (run books, checklists, naming requests, acceptance logs) were left out. Before publication every file was checked for personal contact details and local file paths, and none were found.

Many of these reports, including most Hadamard reports from order 8,884 upward and many Band-1 probes, also appear as pages in the computational-mathematics section of the Theory of Everything corpus editions of 20 and 22 October 2026 on Zenodo. This dataset collects them as individual files with an index. The newest Hadamard reports, from 21–22 October 2026, are not here; they are part of the corpus edition of 22 October 2026.

## Verify

`sha256sum -c CHECKSUMS.sha256` checks every file. `index.csv` gives each report's SHA-256 as well.

## Relationship to other work

These reports come from the computational-mathematics strand of the author's ZoraASI / Theory of Everything research program (Zenodo concept DOI [10.5281/zenodo.14019809](https://doi.org/10.5281/zenodo.14019809)). They are mathematics experiments and do not test any physical theory.

## AI assistance and provenance

The reports name their authors as "Human + ZoraASI full-dash (executor)" or "C.M. Baird; ZoraASI mission-control Band-1 dash". They were produced by AI systems working under the author's direction. Claude (Anthropic) selected, de-duplicated and indexed the collection and wrote this README; no report was changed.

## Citation

Baird, C. M. (2026). *ZoraASI Full-Dash Computational Experiment Reports, September–October 2026* (version 1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23659083

To cite all versions, use the concept DOI [10.5281/zenodo.23659082](https://doi.org/10.5281/zenodo.23659082). See also `CITATION.cff`.

## License

The reports and index are licensed CC BY 4.0; see `LICENSE.md`. Literature cited inside the reports remains under its own terms.
