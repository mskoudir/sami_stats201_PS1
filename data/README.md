# Data Description

## Overview
This dataset is sourced from publicly available hiring discrimination research and contains job application records used to study racial bias in hiring. The dataset helps analyze the impact of applicant names on callback rates and supports fairness-aware machine learning models.

## Data Source
- **Dataset Name:** State of Hiring Discrimination  
- **Source:** Scientific Data (Nature Research) / NeurIPS Datasets  
- **Format:** Excel Spreadsheet (`.xlsx`)  
- **Use Case:** Identifying patterns of racial bias in hiring decisions by analyzing callback rates across different demographic groups.  

## Data Dictionary
```
| Column Name         | Description |
|---------------------|-------------|
| `applicant_name`   | Name of the applicant (used for bias detection). |
| `race_ethnicity`   | Perceived race based on name. |
| `job_category`     | Industry or category of the job applied for. |
| `callback`         | 1 if the applicant received a callback, 0 otherwise. |
| `company_id`       | Unique identifier for the company. |
| `job_posting_id`   | Unique identifier for the job posting. |
| `education_level`  | Highest level of education attained by the applicant. |
| `experience_years` | Number of years of work experience. |
| `salary_expectation` | Expected salary range specified by the applicant. |
| `location`         | Geographical location of the job posting. |
```

## Complementary Datasets
If applicable, multiple datasets from different sources may be integrated to enhance research validity. Possible complementary datasets include:
- **Job Market Trends Data:** To analyze historical hiring trends.  
- **Employer Survey Data:** To compare employer attitudes with observed hiring behaviors.  

## Notes
This dataset is used for research and educational purposes only. Any personal data has been anonymized to maintain privacy compliance.

