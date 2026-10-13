# SWYNEX – Biological Dataset Selection

## Project overview
This project documents a publicly available biological dataset from the NCBI Gene Expression Omnibus (GEO). The selected study investigates gene-expression patterns associated with cigarette smoking and lung adenocarcinoma.

## Dataset selected
- **Title:** Gene expression signature of cigarette smoking and its role in lung adenocarcinoma development and survival
- **GEO Series accession:** GSE10072
- **Curated GEO DataSet:** GDS3257
- **Organism:** *Homo sapiens* (human)
- **Experiment type:** Expression profiling by microarray
- **Platform:** Affymetrix Human Genome U133A Array (GPL96)
- **Final processed dataset:** 107 expression profiles — 58 lung tumour samples and 49 non-tumour lung tissue samples
- **Raw-data archive:** The GEO record lists a GSE10072_RAW.tar archive of approximately 375.3 MB.
- **Public source:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE10072
- **Curated dataset page:** https://www.ncbi.nlm.nih.gov/gds/3257

## Research question
**How do gene-expression patterns differ between lung adenocarcinoma tissue and non-tumour lung tissue, and how might smoking status relate to these patterns?**

This is a proposed question for exploring the dataset, not a claim that this repository performed a new statistical analysis.

## Why this dataset?
1. It comes from a recognised public repository maintained by NCBI.
2. The GEO record explains the study design, organism, platform, sample count and available downloads.
3. It connects molecular biology with a relevant biomedical research topic.
4. It can support future exploratory work, such as comparing expression profiles between tumour and non-tumour groups, while accounting for smoking status and other confounding variables.

## What the dataset contains
The study used microarray technology to measure the expression of many genes in human lung tissue. The final reported expression set contains 107 values/profiles: 58 tumour and 49 non-tumour tissue samples. Smoking information was recorded for participants. The GEO page also lists the raw CEL-file archive separately.

**Important size clarification:** “107 samples” refers to the final processed expression profiles described on the GEO record. The separate raw archive is approximately 375.3 MB. These are two different measures of dataset size.

## Proposed next steps (not performed in this task)
- Read the sample annotations and confirm the group labels.
- Review the platform annotation and expression-value format.
- Explore data quality and missing values.
- Compare tumour and non-tumour groups using an appropriate statistical workflow.
- Consider smoking status and other possible confounders before drawing conclusions.
- Report limitations and avoid treating association as proof of causation.

## Limitations and responsible use
- This is a microarray study, not a whole-genome sequencing dataset.
- Sample counts are not perfectly balanced between the two tissue groups.
- Clinical and lifestyle variables may confound observed differences.
- Findings from this dataset alone cannot establish that smoking caused a particular expression change.
- No laboratory work or new data analysis was performed for this dataset-selection task.

## Sources
1. NCBI GEO Series GSE10072: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE10072
2. NCBI GEO DataSet GDS3257: https://www.ncbi.nlm.nih.gov/gds/3257
3. NCBI GEO DataSet documentation: https://www.ncbi.nlm.nih.gov/geo/info/datasets.html
4. NCBI GEO download documentation: https://www.ncbi.nlm.nih.gov/geo/info/download.html

## Task summary
This repository records the dataset choice, its source, scale, biological context, proposed research question and limitations. It is a dataset-selection and documentation project; it does not claim original experimental or computational results.
