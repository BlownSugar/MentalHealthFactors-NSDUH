
# Understanding the Factors Influencing Mental Healthcare Utilization among Adults with Mental Health Problems

## Overview
This project investigates the various factors that influence mental healthcare utilization among adults. Utilizing the National Survey of Drug Use and Health (NSDUH) dataset, we shed light on the determinants that lead adults with mental health issues to seek healthcare services.

## Dataset
The primary dataset employed in this analysis is the `NSDUH_2019_Tab.txt` file, which provides an exhaustive overview of tobacco, alcohol, and drug use; substance use disorders; mental health conditions; and the utilization of related services in the U.S. For this research, our focus is predominantly on adults who have self-reported diagnoses or symptoms related to mental health problems.

## Methodology
The crux of our analytical approach is logistic regression. This method offers insights into the relationship between the utilization of mental healthcare services (a binary dependent variable) and various independent variables encompassing demographic, socioeconomic, and health-related factors.

## Features Analyzed:
- **Demographic:** Attributes like age, gender, ethnicity, marital status, and job status, among others.
- **Insurance:** Aspects related to health insurance.
- **Income:** Elements tied to income and work status.
- **Health:** Varied facets concerning physical health.
- **Social Environment:** Diverse elements of the surrounding social environment.
- **Mental Health:** Various dimensions of mental health.
- **Mental Service Utilization:** Multiple aspects related to the utilization of mental health services.

## Analysis Steps:
1. Data Loading & Pre-processing: The `NSDUH_2019_Tab.txt` dataset is loaded and pre-processed to filter relevant columns and handle missing values.
2. Feature Engineering: Relevant features are grouped under categories like demographic, health, and mental health.
3. Logistic Regression: This statistical method is applied to understand how different factors influence the utilization of mental healthcare services.
4. Results Interpretation: Coefficients and significance levels of the independent variables are analyzed to derive insights.

## Conclusion
The analysis provides a comprehensive understanding of the myriad factors that play a pivotal role in determining whether adults with mental health problems seek healthcare services. These insights can be instrumental for healthcare providers, policymakers, and researchers in enhancing the accessibility and utilization of mental health services.

**Note:** To reproduce the analysis, ensure that the `NSDUH_2019_Tab.txt` file is present in the same directory as the Jupyter notebook.

