# group_14_project

## Project Contributors
Julie Bruun Brockhoff (JulieBrockhoff), s204519 \
Amalie Drud Nielsen (amaliedn), s204560 \
Cecilie Kejlberg Leth (CecilieLeth), s204564 \
Chrysillis Polhaus (ChrysillisPolhaus), cjmp/s153664 \
Lise Lotte Eriksen (Zyanis), 154123

## Data Retrieval
The project is based on data from the Human Tumor Atlas Network (HTAN) and describes clinicopathological features of breast cancer metastases. \
The data can be retrieved from the HTAN website: https://humantumoratlas.org/publications/hta1_2024_pdf_johanna-klughammer?tab=overview. \
The original publication on the dataset can be found via this DOI: https://doi.org/10.1038/s41591-024-03215-z \
Download tsv from HTAN website and name the file: "raw_data.tsv"

## Overview 
Load:
Done

Clean data:
  Include: HTAN Participant ID, Age at Diagnosis (years), Primary Diagnosis, 	Site of Resection or Biopsy OR Tissue or Organ of Origin, Tumor grade, Last Known Disease Status, Days to Last Known Disease Status, Race, Caurse of death, Year of Death
  Maybe include: Morphology, Progression or Recurrence

Make model:
Comparing by p-val which parameters are signifigant

Plots:
