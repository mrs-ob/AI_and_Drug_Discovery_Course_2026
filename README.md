# AI_and_Drug_Discovery_Course_2026

**Selected target name:** Prostate-specific antigen (KLK3)

**Number of bioactivity records:** 7

**Short description of data curation workflow:** Bioactivity data for the KLK3 target protein were retrieved from the ChEMBL database by identifying the most relevant target entry and extracting associated bioactivity records using its ChEMBL ID. Only IC₅₀ measurements reported in nanomolar (nM) units were retained and exported as a CSV file. The dataset was subsequently cleaned by removing missing or invalid bioactivity values and compounds lacking valid SMILES representations. Bioactivity values were classified into active, intermediate, or inactive categories based on predefined IC₅₀ thresholds. Relevant fields were extracted to generate a finalized, preprocessed bioactivity dataset for downstream analysis.
