# group_14_project

## Project Contributors
Julie Bruun Brockhoff (JulieBrockhoff), s204519 \
Amalie Drud Nielsen (amaliedn), s204560 \
Cecilie Kejlberg Leth (CecilieLeth), s204564 \
Chrysillis Polhaus (ChrysillisPolhaus), cjmp/s153664 \
Lise Lotte Eriksen (Zyanis), s154123

## Data Retrieval
The project is based on data from Next-generation mRNA sequencing of ovarian cancer cell lines SKOV3 and OVCAR3 with knock out of HERV-K env. \
The data can be retrieved from NCBI Gene Expression Omnibus (GEO) website using the accession GSE269969: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE269969 \
\
Guide to data retrieval:
- Go to the NCBI-link above
- Under 'Download', press "http"
- Unzip .zip-folder and make sure the four files are .txt
- Save the four .txt-files in a folder called "data/_raw/"

The data was published in the study: \
Ko EJ et. Al, "Transcriptome analysis of the effect of HERV-K env gene knockout in ovarian cancer cell lines", Genes Genomics, 2024 Sep 13, doi: 10.1007/s13258-024-01544-4 \

## Link to Presentation
To access our project presentation, use the following link:\
https://raw.githack.com/rforbiodatascience24/group_14_project/main/doc/presentation.html

## Analysis not Included in the Project
Two analysis in the R folder: 101_ and 102_, are possible analysis that did not yield useful results:
- 101_analysis_t_test.qmd
- 102_analysis_pca.qmd

## Software and Packages
**Software used:**
- R version 4.3.1, Wickham H, Averick M, Bryan J, Chang W, McGowan LD, François R, Grolemund G, Hayes A, Henry L, Hester J, Kuhn M, Pedersen TL, Miller E, Bache SM, Müller K, Ooms J, Robinson D, Seidel DP, Spinu V, Takahashi K, Vaughan D, Wilke C, Woo K, Yutani H (2019). “Welcome to the tidyverse.” Journal of Open Source Software, 4(43), 1686. doi:10.21105/joss.01686.

  
**Packages used:**
- **tidyverse, version 2.0.0**, Wickham H, Averick M, Bryan J, Chang W, McGowan LD, François R, Grolemund G, Hayes A, Henry L, Hester J, Kuhn M, Pedersen TL, Miller E, Bache SM, Müller K, Ooms J, Robinson D, Seidel DP, Spinu V, Takahashi K, Vaughan D, Wilke C, Woo K, Yutani H (2019). “Welcome to the tidyverse.” Journal of Open Source Software, 4(43), 1686. doi:10.21105/joss.01686.
- **here, version 1.0.1**, Müller K (2020). _here: A Simpler Way to Find Your Files_. R package version 1.0.1, <https://CRAN.R-project.org/package=here>.
- **readr, version 2.1.4**, Wickham H, Hester J, Bryan J (2023). _readr: Read Rectangular Text Data_. R package version 2.1.4, <https://CRAN.R-project.org/package=readr>.
- **broom, version 1.0.5**, Robinson D, Hayes A, Couch S (2023). _broom: Convert Statistical Objects into Tidy Tibbles_. R package version 1.0.5, <https://CRAN.R-project.org/package=broom>.
- **scales, version 1.3.0**, Wickham H, Pedersen T, Seidel D (2023). _scales: Scale Functions for Visualization_. R package version 1.3.0, <https://CRAN.R-project.org/package=scales>.
- **clusterProfiler, version 4.10.1**, T Wu, E Hu, S Xu, M Chen, P Guo, Z Dai, T Feng, L Zhou, W Tang, L Zhan, X Fu, S Liu, X Bo, and G Yu. clusterProfiler 4.0: A universal enrichment tool for interpreting omics data. The Innovation. 2021, 2(3):100141
- **biomaRt, version 2.58.2**, Mapping identifiers for the integration of genomic datasets with the R/Bioconductor package biomaRt. Steffen Durinck, Paul T. Spellman, Ewan Birney and Wolfgang Huber, Nature Protocols 4, 1184-1191 (2009)
- **enrichplot, version 1.22.0**, Yu G (2023). _enrichplot: Visualization of Functional Enrichment Result_. doi:10.18129/B9.bioc.enrichplot <https://doi.org/10.18129/B9.bioc.enrichplot>, R package version 1.22.0 <https://bioconductor.org/packages/enrichplot>.
