# Conference Update Schedule

This document tracks when to search for newly accepted fashion-related papers for this repository.
Months are approximate and should be checked against each conference's official dates page every year.

## Fashion Keywords

Use these keywords when searching GitHub, arXiv, OpenReview, official programs, and project pages:

```text
garment, dress, cloth, fashion, sewing, textile, apparel, outfit, style, try-on, clothing
```

Also search common variants:

```text
virtual try-on, VTON, try on, re-texturing, sewing pattern, cloth simulation, garment fitting
```

## Monthly Watch Schedule

| Month | Conferences to Watch | What to Do |
| --- | --- | --- |
| January | ICLR | Check OpenReview decisions and accepted/spotlight/oral tabs. Search GitHub and arXiv for ICLR + fashion keywords. |
| February | ICLR, CVPR | Do an ICLR follow-up sweep. After CVPR decisions, run the first CVPR GitHub/arXiv sweep. |
| March | CVPR, SIGGRAPH | Do a CVPR second sweep. After SIGGRAPH Technical Papers decisions, run the first SIGGRAPH sweep. |
| April | SIGGRAPH, ICML | Do a SIGGRAPH follow-up sweep. After ICML decisions, run the first ICML sweep. |
| May | CVPR, SIGGRAPH, ICML | Calibrate CVPR against virtual/proceedings pages when available. Do ICML follow-up. Check SIGGRAPH final/publication updates. |
| June | CVPR, ICCV/ECCV | Final CVPR cleanup. After ICCV or ECCV decisions, run the first ICCV/ECCV sweep. |
| July | ICCV/ECCV, SIGGRAPH, SIGGRAPH Asia | Do ICCV/ECCV follow-up. Calibrate SIGGRAPH against program/proceedings. After SIGGRAPH Asia decisions, run the first SIGGRAPH Asia sweep. |
| August | ICCV/ECCV, SIGGRAPH Asia | Do ICCV/ECCV program pre-checks. Do SIGGRAPH Asia follow-up. |
| September | ICCV/ECCV, NeurIPS | Final ICCV/ECCV cleanup when program/proceedings are available. After NeurIPS decisions, run the first NeurIPS sweep. |
| October | NeurIPS, ICCV/ECCV | Do NeurIPS follow-up. Finish ICCV/ECCV program/proceedings checks. |
| November | NeurIPS, SIGGRAPH Asia | Calibrate SIGGRAPH Asia against final program/publication. Do NeurIPS program pre-checks. |
| December | NeurIPS | Calibrate NeurIPS against final program/proceedings. Do annual dedupe, broken-link checks, and label cleanup. |

## Decision vs. Public List Timing

| Conference | Decision Month | More Complete Public List Usually Appears |
| --- | --- | --- |
| ICLR | January | Late January to February on OpenReview; program details around March-April. |
| CVPR | February | March for early public traces; May-June for virtual site/proceedings. |
| SIGGRAPH | March | May-July after conditional acceptance, revisions, and final publication updates. |
| ICML | April | Late April-May for accepted papers; June-July for program/proceedings. |
| ICCV | June | July for early public traces; September-October for program/proceedings. |
| ECCV | June | Late June-July for early public traces; August-September for program/proceedings. |
| SIGGRAPH Asia | July | August for early public traces; September-November for final program/publication. |
| NeurIPS | September | Late September-October for accepted papers; November-December for program/proceedings. |

Notes:

- ICCV and ECCV alternate years: ICCV is usually odd years; ECCV is usually even years.
- SIGGRAPH and SIGGRAPH Asia often have conditional acceptance and final revision stages, so final public lists can lag decisions by months.
- NeurIPS is the current conference name; older materials may still use NIPS.

## Search Workflow

For each active conference/month:

1. Check official source first:
   - CVPR/ICCV: conference dates, virtual site, accepted papers, openaccess pages.
   - ECCV: ECVA conference pages and official accepted/program pages.
   - SIGGRAPH/SIGGRAPH Asia: Technical Papers pages and conference schedule pages.
   - ICLR: OpenReview accepted/oral/spotlight tabs.
   - ICML/NeurIPS: official dates, accepted papers, program, proceedings pages.
2. Search GitHub:
   - `"CVPR 2026" garment`
   - `CVPR2026 garment`
   - `"ECCV 2026" "virtual try-on"`
   - `ECCV2026 fashion`
   - Repeat with every fashion keyword and common variant.
3. Search arXiv and project pages with the same conference + keyword combinations.
4. Compare against `README.md` to avoid duplicates.
5. List candidates for manual review before editing the repo.
6. After approval, update `README.md`, run `git diff --check`, commit, and push.

## Candidate Review Template

Before updating the repo, list proposed additions in this format:

| Conference | Title | Authors | Links | Keywords | Notes |
| --- | --- | --- | --- | --- | --- |
| ECCV 2026 | Example Paper Title | Author A, Author B | GitHub / arXiv / official page | garment, virtual try-on | Evidence that it is accepted and fashion-related. |

Only add papers after the candidate list has been checked.

## Known Candidates for Next Update

| Conference | Title | Authors | Links | Keywords | Notes |
| --- | --- | --- | --- | --- | --- |
| ECCV 2026 | DiffGI: Differentiable Geometry Images for High-Fidelity Thin-Shell 3D Generation | Eungjune Shim, Hansol Lee, Eunjung Ju | [project](https://ejshim.github.io/diffgi/) | garment, thin-shell 3D generation, geometry images | User requested adding this in the next ECCV 2026 update; project page states ECCV 2026 and highlights thin-shell objects such as garments. |

## README Update Rules

- Put new entries under `Latest Fashion-Related Papers`.
- Use one section per conference, for example `ECCV 2026-Fashion-Related-Papers`.
- In the `Title` column, make the paper title directly clickable with `<a href="...">Title</a>`.
- Prefer official conference page links when available; otherwise use GitHub/project page, then arXiv.
- Add labels only when confirmed by official sources:
  - `🏅best`
  - `🏆oral`
  - `🌟highlight`
- Keep unconfirmed edge cases out of the README. If a paper only mentions fashion as an example application, list it as a candidate but do not add it unless manually approved.

## Suggested Automation Policy

A weekly automation is easier to maintain than many separate monthly jobs:

- Run once per week.
- Detect the current month.
- Use the monthly schedule above to choose which conferences to scan.
- Produce a candidate list only.
- Do not edit files automatically unless explicitly instructed in that run.

During active decision windows, add follow-up sweeps:

- Decision week: first scan.
- Four weeks later: second scan.
- Two to four weeks before the conference: final program/proceedings calibration.
