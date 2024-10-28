# Math Proficiency of Primary Teachers: Insights from LSAY and PISA

Welcome to my project exploring mathematics proficiency in primary school teachers, utilising Longitudinal Surveys of Australian Youth (LSAY) and Programme For International Student Assessment (PISA) data! This repository will include content from the project used to create my report, however the repository with my analysis can be found [here](https://github.com/grattan/school-ed-2025-primary-maths/tree/lsay-analysis).

## Repository Structure

* **LSAY_EDA_files:** Contains all the visualisations creating within the LSAY_EDA quarto document. Not all were used, and some were starting points for visualisations used in the report.

* **R:** Folder containing set up R script with packages used in the LSAY_EDA quarto document. In the source repository linked up, included are R scripts that were utilised for other parts in the wider report, but not specific to my contribution to the project (01-dummy_charts.R and 03-lsay.R).

* **LSAY_EDA.qmd:** The Quarto document containing the LSAY/PISA data analysis. This Quarto document contains all the code used for my analysis with some description surrounding the code for readability.

* **report.qmd:** Contains my report content based on the analysis and my contributions to the project.

* **presentation.pdf:** The presentation version of this project.

Data files were omitted due to being private data.

## Project Overview

This project investigates the math proficiency of individuals who later became primary school teachers in Australia, contributing to Grattan Institute's report on teacher proficiency and how this translates to being able to effectively teach mathematics. It examines teacher performance over time, comparing them to other professionals and the general population. It aims to provide a supplementary understanding of teachers proficiency in mathematics within this sample to, as a wider goal, inform professional development initiatives and policy recommendations for improving math education outcomes.

### Methodology

The analysis draws from LSAY cohorts of 2003, 2006, 2009, and 2015, linked to PISA scores. Teachers were identified through ANZSCO occupational codes, with math proficiency assessed against national standards. Key variables were weighted to maintain representativeness.

The analysis aims to answer:

* How do teachers’ perform on average across the years compared to non-teachers?

* How do teachers compare to other professionals?

* How do teachers perform relative to the general population each year?

Understanding these trends is crucial for targeting professional development and improving teacher effectiveness, which ultimately enhances student outcomes.


# Key Findings

* **Teachers vs. Non-Teachers:** Teachers consistently score higher than non-teachers, with over 80 percent meeting the national proficiency standard of 482 PISA points.

* **Comparison to Professionals:** Teachers perform lower than STEM professionals but better than the general population.

* **Teachers performed better each year:** Teachers exhibit less variability in scores compared to non-teachers, and performed better than non-teachers in each year analysed.

# Reproducibility of Results

After cloning the repository, access to the LSAY data requires a formal request and registration process as managed by the Australian Data Archive (ADA). To see steps on how to acquire the data, view [here](https://www.lsay.edu.au/data/access).  This analysis utilised the available STATA versions of the data.

The data can be requested for from the [Dataverse website](https://dataverse.ada.edu.au/dataverse/lsay).

Please ensure to save this in a 'data' folder in the project. 

## Packages and Software 

R and RStudio both are required (latest versions preferable).
Please ensure all packages in R/00-setup.R are installed.

The [grattantheme](https://github.com/grattan/grattantheme) and [ggdirectlabel](https://github.com/MattCowgill/ggdirectlabel) packages will also be necessary to recreate some visualisations.

