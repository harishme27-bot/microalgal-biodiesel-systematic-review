# Microalgal biodiesel systematic review — supplementary data

Supplementary data for the manuscript:

> Harish H, Kondragunta Rama Krishnaiah, Younus Pasha, Arun Kumar G L, Allacheruvu Brahmaiah.
> **Linking Catalysis, Fuel Quality and Process Energy in Microalgal Biodiesel Production: A Systematic Review.**
> *Thermal Science and Applications* (under review, revision R1, 2026).

The review follows PRISMA 2020. Scopus was searched on 20 October 2026 (1907 records; 1905 screened). After two protocol amendments and strict full-text assessment, 64 reports were assessed and **29 studies were included** (28 full text, 1 abstract only).

## Contents

| Path | Description |
|---|---|
| `data/Supplementary_Data_S1.xlsx` | Main supplementary workbook (Supplementary Data S1). Sheets: Protocol (search string, criteria, amendments, operational definitions); PRISMA (live counts); Records (screening and amendment decisions for all 1907 records); Full-text list; Extraction (eligibility decision and reason for all 64 assessed reports, and extracted data for included studies); Extraction_v1_original (original submission, superseded); Values_status_source; Appraisal; Selection_bias; Second_screening; Kappa. |
| `data/included_studies_extraction.csv` | One row per included study: feedstock, route, catalyst, conditions, yield and yield type (C1–C4, NS), focus dimensions, reuse, kinetics, energy class and boundary, by-products, measured and calculated fuel properties, appraisal items and rating. |
| `data/extracted_values_status_source.csv` | Every numerical value used in the synthesis with its unit, status (measured, calculated, reported or fitted), basis, ester type (FAME/FAEE) and the page of the source article. |
| `data/excluded_reports_with_reasons.csv` | Reports excluded at eligibility assessment, with reasons and stage. |
| `screening/Second_screening_decisions_and_kappa.xlsx` | Original and second-reviewer decisions for the screening sample (n = 469), amendment sample (n = 162) and full-text assessment (n = 62), with Cohen's kappa formulas. |
| `screening/second_screening_reconciliation.csv` | Every disagreement between reviewers and how it was resolved. |
| `figures/` | Figures 1–6 (PNG and 600 dpi TIFF) and the graphical abstract. |

## Key definitions

- **Focus dimensions** (a study needed a measured ester yield and at least two):
  **P** — at least one fuel property of the ester measured and reported numerically (calculated values do not count);
  **R** — reuse of the conversion catalyst, enzyme or IL/DES over ≥ 3 cycles with quantified yield or activity;
  **T** — kinetic parameters of the conversion, quantified process energy, or TGA/DSC of the ester product;
  **B** — quantified valorisation of residue, glycerol or a co-product.
- **Yield types** (never pooled): C1 conversion or yield by GC or NMR (GC ester mass per lipid in g/g is expressed as %); C2 isolated (gravimetric) ester mass on oil or lipid; C3 ester content of the product; C4 ester mass on dry biomass; NS method not stated.
- **Energy evidence classes**: measured electricity; calculated thermal; nominal power × time; modelled (life cycle or techno-economic).

## Screening reliability

A second reviewer independently screened a random sample. Cohen's kappa before reconciliation: title–abstract screening 0.28, amendment decisions 0.44, full-text eligibility 0.71. All disagreements were reconciled against the source documents (see `screening/`).

## Notes

- Full texts and abstracts of the included articles are not redistributed here because of publisher copyright; each study is identified by its record ID, and bibliographic details are in the Records sheet.
- AI assistance (Claude, Anthropic) was used for screening proposals, data extraction and figure preparation; all decisions and values were checked against the source documents (see the manuscript, Section 2.8).

## Licence

Data and figures are released under the Creative Commons Attribution 4.0 International licence (CC BY 4.0).

## Contact

Dr. Harish H, RK College of Engineering, Vijayawada, India — harish.me27@gmail.com

## Revision history

- R1 (Nov 2026): strict eligibility, 29 included studies, second screening.
- R2 (Nov 2026): GC-quantified g/g yields reclassified to C1; density compared with EN 14214 only at 15 °C; Full-text list sheet marked as superseded.
