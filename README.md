# CollegeAdmissions-
This project analyzes the relationship between university admission rates and SAT/ACT submissions and financial aid percentages using the College Admissions dataset from Kaggle. The analysis reveals that financial aid has a stronger impact on admissions, emphasizing accessibility in higher education. 
Here's a detailed README for your project:

---

# AnalysisReport1_Pranga_Marcus

## Overview
This project explores the correlation between university admission rates and three key factors: the percentage of freshmen submitting SAT scores, the percentage of freshmen submitting ACT scores, and the percentage of freshmen receiving financial aid. The dataset used for this analysis is the **College Admissions dataset** from Kaggle, containing information from 1,517 colleges in the United States. The analysis aims to determine which factor has the most significant impact on admission rates.

## Dataset
The dataset used in this analysis is publicly available on Kaggle: [College Admissions Dataset](https://www.kaggle.com/datasets/samsonqian/college-admissions). Key variables include:
- Total number of applicants, admissions, and enrolled students for each institution
- SAT/ACT scores submitted
- Financial aid statistics
- Other relevant metrics such as tuition, demographic information, and student retention rates

## Research Question
The primary research question is:
> "Which variable among the percentage of freshmen submitting SAT scores, the percentage of freshmen submitting ACT scores, and the percentage of freshmen receiving financial aid has the highest correlation with a university's admission rate?"

## Analysis Steps
1. **Data Wrangling**:
   - Selected relevant columns for analysis.
   - Checked and removed missing data.
   - Renamed columns for clarity and transformed variables for better interpretation.
2. **Correlation Analysis**:
   - Conducted Pearson correlation analysis to explore the relationships between the variables.
   - Standardized variables for consistent comparison.
3. **Visualizations**:
   - Created scatter plots and a heatmap to visualize the relationships between the variables and admission rates.

## Findings
- The analysis shows that **financial aid** has a stronger positive correlation with admission rates compared to SAT or ACT submissions.
- Scatter plots and the correlation heatmap indicate that universities offering more financial aid tend to have higher admission rates, suggesting a shift towards prioritizing accessibility in higher education.

## Requirements
The following libraries are required to run the analysis:
- `tidyverse`
- `readr`
- `ggplot2`
- `reshape2`

To install these packages, you can run:
```R
install.packages(c("tidyverse", "readr", "ggplot2", "reshape2"))
```

## Usage
To reproduce the analysis:
1. Download the dataset from Kaggle and save it to your working directory.
2. Load the dataset using the path in the R script.
3. Run the script to see the data wrangling steps, correlation analysis, and visualizations.

## Conclusion
This project demonstrates that financial aid has a more substantial influence on university admission rates compared to standardized test submissions. This finding aligns with the trend of universities focusing on accessibility and affordability. Future analyses could include additional variables like institutional reputation and geographical location for a more comprehensive understanding of admission dynamics.
