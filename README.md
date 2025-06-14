# !!!! WORK IN PROGRESS !!!!

# Master Thesis

This repository contains the code and documentation for my Master Thesis on the analysis of the drivers of firms' participation in the EDIH initiative, a digitalization and innovation program put in place by the European Commission.

## Structure of the Repository

- **`code/`**: Contains R and RMarkdown scripts for data analysis and visualization.
- **`Data/`**: Raw and processed datasets used in the analysis. It should include confidential data, which is cut from the public repo
- **`latex/`**: LaTeX files for writing the thesis document.
- **`Output/`**: Outputs of the analysis, such as plots, tables, and processed datasets.
- **`README.md`**: Overview of the repository.

## How to replicate the results

The files **`Analysis.rmd`** and **`cut-and-merge.rmd`** include most of the analysis done on the DMA dataset and the results from the probit regression. The script in **`untreated_sample_creation.rmd`** picks the random bvd_ids to then be downloaded from WRDS. The file **`matching_loop.rmd`** is the one doing the matching between DMA data and ORBIS observations, matching country by country the firms. The **`services-reporting-data-analysis.rmd`** and **`RIS-Analysis.rmd`** files are concerned with EDIH-based analysis of services reported and correlation of average DMA scores with regional innovation indicators respectively (this part is cut from the thesis).



