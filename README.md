# Data Science in Business - Replication Study

## Overview
This repository contains materials related to the replication study **"What Can Historically Black Colleges and Universities Teach about Improving Higher Education Outcomes for Black Students?"**. The study aims to replicate the findings of Price & Viceisza (2023) using R and publicly available datasets.

## Contents
- **Data_science_in_business_Manvanth_sundareshan.pdf**: The main report detailing the replication process, methodology, and findings.
- **Data_science_in_business_Manvanth_sundareshan.Rmd**: The R Markdown file containing code and analysis for the replication.
- **Supporting datasets and scripts**: Necessary files to perform data processing, statistical analysis, and table replication.

## Objectives
- Validate the findings of Price & Viceisza (2023) regarding the impact of Historically Black Colleges and Universities (HBCUs) on student success.
- Reproduce three key tables comparing outcomes between HBCUs and non-HBCUs using R.
- Ensure transparency and reproducibility in empirical research.

## Methodology
1. **Data Collection**
   - Utilized publicly available datasets from **NCES**, **Gallup**, and **MSI Data Project**.
   - Downloaded replication package and verified data sources.

2. **Data Processing**
   - Used R packages: `tidyverse`, `dplyr`, `haven`, `readxl`, `kableExtra`.
   - Applied data cleaning, transformation, and filtering techniques.

3. **Statistical Analysis & Table Replication**
   - Calculated summary statistics and generated comparison tables.
   - Used `kable()` for table formatting and Markdown for documentation.

4. **Validation**
   - Compared replicated results with original findings to ensure consistency.
   - Identified challenges and discrepancies in data interpretation.

## Replicated Tables
The study replicates the following tables from Price & Viceisza (2023):

1. **Table 1** - Characteristics of Selected HBCUs.
2. **Table 2** - Educational and Labor Market Outcomes.
3. **Table 3** - Student Support and Experiential Learning Opportunities.

## Challenges Encountered
- **Column name mismatches**: Adjusted data selection based on dataset structure.
- **Missing instructions**: Some filtering details were not explicitly mentioned in the original paper.
- **Data formatting issues**: Addressed character-to-numeric conversions for proper analysis.
- **Table layout constraints**: Adjusted formatting to fit Markdown and PDF outputs.

## How to Run the Replication
### Prerequisites
Ensure you have **R** installed along with the necessary packages:
```r
install.packages(c("tidyverse", "haven", "dplyr", "readxl", "kableExtra"))
```

### Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/data_science_replication.git
   cd data_science_replication
   ```
2. Open `Data_science_in_business_Manvanth_sundareshan.Rmd` in RStudio.
3. Run all code chunks sequentially to reproduce the results.
4. Check the generated tables and compare them with the original study.

## Future Scope
- Extend analysis by incorporating additional datasets.
- Apply machine learning techniques to assess predictive features of graduation rates and economic mobility.
- Expand replication efforts to international contexts.

## License
This project is licensed under the MIT License.

## Author
Developed by **Manvanth Sundareshan**. For inquiries, contact **sudareshan.manvanth@stud.hs-fresenius.de**.

## References
Price, G. N., & Viceisza, A. C. G. (2023). What can historically black colleges and universities teach about improving higher education outcomes for black students? *Journal of Economic Perspectives, 37(3), 213–232.* [DOI](https://doi.org/10.1257/jep.37.3.213)
