# TMEM175, SCARB2 and CTSB associations with Parkinson's disease risk across populations

# Summary

This is the online repository for the manuscript titled "TMEM175, SCARB2 and CTSB associations with Parkinson's disease risk across populations". This study focuses on exploring the role of lysosomal related genes(TMEM175, SCARB2, CTSB and GBA1) in existing PD/control datasets from the AMP-PD and GP2 Neurobooster genotyping array.

# Data statement
All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson’s disease, and are available via application on the website (https://amp-pd.org/register-for-amp-pd). For up-to-date information on GP2 data acquisition, access, and policies, visit https://gp2.org/. 
All data was using GP2 release 8(https://zenodo.org/records/13755496) and AMP-PD release 4. Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub.

## Helpful Links

- [GP2 Website](https://gp2.org/)
  - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
  - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

# Repository Orientation
- The analyses/ directory includes all analyses discussed in the manuscript
 -  GP2/ includes 3 notebooks on processing and analyzing GP2 Neuobooster array data from release 8
 -  AMP-PD/ includes 1 notebook on processing and analyzing whole genome sequencing data from release 4

THIS_REPO/
├── README.md
└── analyses/
    ├── AMP-PD/
    │   └── 00_GBA1_AMPPD.ipynb
    └── GP2/
        ├── 00_TMEM175_ALL_GLM.ipynb
        ├── 01_SCARB2_ALL_GLM.ipynb
        └── 02_CTSB_ALL_GLM.ipynb

# Analysis Notebooks
## Languages: Python, bash, and R
| Notebooks   | Description | 
|----------------|--------|
| TMEM175_ALL_GLM         | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of TMEM175 with GP2 Neurobooster array|
| SCARB2_ALL_GLM         | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of SCARB2 with GP2 Neurobooster array|
| CTSB_ALL_GLM         | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of CTSB with GP2 Neurobooster array|
| GBA1_AMPPD         | single variant based and gene based analysis of GBA1 with AMPPD|



# Software
| Software   | Version(s) | Resource URL |
|----------------|--------|------------------|
| ANNOVAR         | 2020-06-08 | http://www.openbioinformatics.org/annovar/ |
| PLINK  | 1.9 and 2.0    | http://www.nitrc.org/projects/plink             |
| GCTA | 1.94.1  | https://yanglab.westlake.edu.cn/software/gcta/#Overview         |
| RVTests | 2019-02-05  | http://zhanxw.github.io/rvtests/         |
| LDpair | /  | https://ldlink.nih.gov/?tab=ldpair         |
| Python Programming Language | 3.10.15  | http://www.python.org/         |
| R Project for Statistical Computing | 4.3.3  | http://www.r-project.org/        |


