# Math Proficiency of Primary Teachers: Insights from LSAY and PISA

Welcome to my project exploring mathematics proficiency in primary school teachers, utilising Longitudinal Surveys of Australian Youth (LSAY) and Programme For International Student Assessment (PISA) data! This repository will include content from the project used to create my report, however the repository with my analysis can be found [here](https://github.com/grattan/school-ed-2025-primary-maths/tree/lsay-analysis).

## Repository Structure

* **LSAY_EDA_files:** Contains all the visualisations creating within the LSAY_EDA quarto document. Not all were used, and some were starting points for visualisations used in the report.

* **R:** Folder containing set up R script with packages used in the LSAY_EDA quarto document. Included are R scripts that were utilised for other parts in the wider report, but not specific to my contribution to the project (01-dummy_charts.R and 03-lsay.R).

* **LSAY_EDA.qmd:** The Quarto document containing the analysis done on the LSAY/PISA data. This Quarto documents contains all the code used for my analysis with some description surrounding code for  readibility.

* **report.qmd:** Contains my report content based on the analysis and my contributions to the project.

Data files were omitted due to being private data.

## Project Overview

This project investigates the math proficiency of individuals who later became primary school teachers in Australia, contributing to a Grattan Institute's report on teacher proficiency and how this translates to being able to effectively teach mathematics. It examines teacher performance over time, comparing them to other professionals and the general population. It aims to provide a supplementary understanding on the the proficiency of mathematics teachers within this sample to as a wider goal, inform professional development initiatives and policy recommendations for improving math education outcomes.

### Methodology

The analysis draws from LSAY cohorts of 2003, 2006, 2009, and 2015, linked to PISA scores. Teachers were identified through ANZSCO occupational codes, with math proficiency assessed against national standards. Key variables were weighted to maintain representativeness.

The analysis aims to answer:

* How do teachers’ math skills evolve over time?

* How do teachers compare to other professionals?

* How do teachers perform relative to the general population?

Understanding these trends is crucial for targeting professional development and improving teacher effectiveness, which ultimately enhances student outcomes.


# Key Findings

* **Teachers vs. Non-Teachers:** Teachers consistently score higher than non-teachers, with over 80 percent meeting the national proficiency standard of 482 PISA points.

* **Comparison to Professionals:** Teachers perform lower than STEM professionals but better than the general population.

* **Score Consistency:** Teachers exhibit less variability in scores compared to non-teachers, though the small sample size of teachers limits statistical power.

# Reproducibility of Results

After cloning the repository, access to the LSAY data requires a formal request and registration process as managed by the Australian Data Archive (ADA). To see steps on how to acquire the data, view [here](https://www.lsay.edu.au/data/access).  This analysis utilised the available STATA versions of the data.

The data can be requested for from the [Dataverse website](https://dataverse.ada.edu.au/dataverse/lsay).

Please ensure to save this in a 'data' folder in the project. 

In order to recreate some of the visualisations included in the LSAY_EDA.qmd, please ensure all packages in R/00-setup.R are installed. In particular, the [grattantheme](https://github.com/grattan/grattantheme) and [ggdirectlabel](https://github.com/MattCowgill/ggdirectlabel).

After this, you will be able to knit the LSAY_EDA.qmd file utilised for findings discussed in the report.
