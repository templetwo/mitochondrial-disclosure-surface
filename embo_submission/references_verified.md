# Reference verification record

All 17 references in `exploratory_report.md` were verified against the **CrossRef REST API**
(canonical publisher metadata) on 2026-05-26. Author lists, journal, volume, pages/article
number, year, and DOI were taken directly from the CrossRef record for each DOI below.
Resolve any entry at `https://doi.org/<DOI>`.

| # | First author / year | DOI | Type | Notes |
|---|---------------------|-----|------|-------|
| 1 | Bayrhuber 2008 | 10.1073/pnas.0808115105 | Journal (PNAS) | hVDAC1 NMR structure |
| 2 | Chu 2013 | 10.1038/ncb2837 | Journal (Nat Cell Biol) | 26 authors; list truncated with "et al" after 20 |
| 3 | Daniilidis 2025 | 10.1038/s41467-025-65363-1 | Journal (Nat Commun) | **Keystone** VDAC1-N/Bcl-xL; peer-reviewed (not preprint) |
| 4 | Ham 2020 | 10.1073/pnas.1909814117 | Journal (PNAS) | Parkin/VDAC1; reports K274 mono-ub, **not K53** — residue claim removed from text |
| 5 | Huang 2015 | 10.1074/jbc.M115.648774 | Journal (J Biol Chem) | Cyathin-R |
| 6 | Jahn 2023 | 10.1038/s41467-023-43570-y | Journal (Nat Commun) | VDAC dimer scramblase |
| 7 | Kagan 2005 | 10.1038/nchembio727 | Journal (Nat Chem Biol) | Cardiolipin peroxidase |
| 8 | Keinan 2010 | 10.1128/mcb.00165-10 | Journal (Mol Cell Biol) | First CrossRef title-query returned a wrong record; corrected via direct DOI |
| 9 | Lafargue 2025 | 10.1038/s42003-025-08311-5 | Journal (Commun Biol) | VDAC1 honeycomb / lipid organization |
| 10 | McArthur 2018 | 10.1126/science.aao6047 | Journal (Science) | 25 authors; list truncated with "et al" after 20 |
| 11 | Puighermanal 2024 | 10.1038/s41467-024-51884-8 | Journal (Nat Commun) | CBD/PPARγ; 23 authors, truncated after 20 |
| 12 | Ravishankar 2025 | 10.1101/2025.06.30.661942 | **Preprint (bioRxiv)** | VBIT-4 audit — flagged `[preprint]` in text and refs |
| 13 | Riley 2018 | 10.15252/embj.201899238 | Journal (EMBO J) | eLocator e99238 |
| 14 | Rostovtseva 2008 | 10.1073/pnas.0806303105 | Journal (PNAS) | Tubulin–VDAC gating |
| 15 | Szabadkai 2006 | 10.1083/jcb.200608073 | Journal (J Cell Biol) | IP3R–GRP75–VDAC1 |
| 16 | Ujwal 2008 | 10.1073/pnas.0809634105 | Journal (PNAS) | mVDAC1 crystal structure |
| 17 | West 2015 | 10.1038/nature14156 | Journal (Nature) | mtDNA → cGAS–STING |

## Items requiring author judgment before submission

- **Author-list length.** EMBO Reports' EndNote style may require *all* authors spelled out.
  Entries 2, 10, and 11 (26/25/23 authors) are truncated with "et al" after the 20th name —
  expand if the journal requires the full list.
- **Ravishankar 2025 is a preprint.** Re-check before submission in case the peer-reviewed
  version has appeared; update the citation if so.
- **Lys53 claim.** The residue-specific statement (Parkin ubiquitinates VDAC1 at Lys53) was
  **removed**: Ham et al (2020) reports K274 mono-ubiquitination, and the "Lys53" assignment
  originates from a separate liver-fibrosis study (Exp Mol Med 2023, doi:10.1038/s12276-022-00923-9).
  The text now cites Ham 2020 only for the functional mitophagy-vs-apoptosis claim it supports.
  If the residue-specific point is wanted, add the Exp Mol Med paper and attribute K53 to it.
