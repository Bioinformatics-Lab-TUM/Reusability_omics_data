# A Thorough Investigation into the Reuse of Public Omics Data Across 5 Million Research Publications

This repository contains the analysis and tools developed for a comprehensive study into the reuse of public omics datasets across over 5 million research publications. Publicly accessible omics data play a pivotal role in driving reproducibility, enabling re-analysis, and facilitating meta-analyses that lead to new discoveries. This study focuses on understanding the patterns and extent of secondary data reuse from 2001 to 2024.

## Key Features:
- **Data Reuse Patterns**: Analysis of over 5 million open-access publications, identifying 400,000 papers related to omics data, with 58% of them reusing publicly available datasets.
- **Normalized Reusability Index (NRI)**: A novel metric developed to quantify dataset reuse, revealing that 16% of omics datasets are reused at least ten times annually.
- **Trend Analysis**: From 2016 to 2024, a 30% increase in publications reusing gene expression data was observed, surpassing studies using newly generated data.
- **Interactive Web Tool**: Provides ongoing updates on omics data reuse trends, facilitating further exploration by the scientific community.
- **Data Collection**: Publications were sourced from PubMed Central (PMC) and included omics datasets from repositories such as the Sequence Read Archive (SRA) and Gene Expression Omnibus (GEO). A total of 276,642 publications mentioning omics datasets were identified using text mining techniques.

## Methodology:
1. **Text Mining and Classification**: We applied regular expressions to classify publications as either primary or secondary analyses based on the dataset release date.
2. **Validation**: Achieved high classification accuracy, with 97.6% for primary analyses and 97.4% for secondary analyses. Misclassifications were primarily due to incomplete texts or pre-print journals.
3. **Comprehensive Dataset**: The dataset spans 5,547,235 open-access publications, offering valuable insights into trends in omics data reuse.

## Impact:
The study highlights the growing importance of reusing public omics data in scientific research, reducing the need for costly and resource-intensive data generation. By encouraging secondary analysis, researchers can accelerate discoveries and enhance the reproducibility of scientific results. The findings underscore the need for improved metadata and open science practices to overcome barriers to data reuse.

## Performance Metrics:
- **Dataset Reuse**: 56% of omics datasets were reused at least once, and 16% were reused ten or more times annually.
- **Validation Accuracy**: 97.6% for primary analyses, 97.4% for secondary analyses.

## References:
1. Rajesh, A. et al. (2021). "Improving the completeness of public metadata accompanying omics studies." *Genome Biology*, 22, 106.
2. "The Replication Crisis: How Can Open Science Improve the Scale of Reproducibility?" Bio-IT World (2024). [https://www.bio-itworld.com/news/2024/05/10/the-replication-crisis-how-can-open-science-improve-the-scale-of-reproducibility](https://www.bio-itworld.com/news/2024/05/10/the-replication-crisis-how-can-open-science-improve-the-scale-of-reproducibility).
3. Oza, V. H. et al. (2023). "Ten simple rules for using public biological data for your research." *PLOS Computational Biology*, 19, e1010749.

## Authors:
- **Viorel Munteanu**, **Nicolae Drabcinski**, **Dumitru Ciorba**  
  Technical University of Moldova
- **Serghei Mangul**  
  University of Southern California
