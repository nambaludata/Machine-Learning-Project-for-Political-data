# Political Data Analysis: Voting Behaviour in Kenya

## Project Overview

This project explores voting behaviour and political participation in Kenya using survey data. It covers the research data workflow, from data collection and preparation to exploratory data analysis (EDA), statistical analysis, and reporting.

The project aims to examine patterns in voter participation and investigate how demographic, socioeconomic, and geographic characteristics relate to previous voting behaviour and future voting intentions.

Rather than focusing solely on predictive modelling, the project documents the analytical process used to transform raw survey data into a structured dataset and meaningful research insights.

## Project Objectives

- Collect and organise survey data relating to political participation and voting behaviour.
- Clean and prepare the collected data for reliable analysis.
- Explore demographic and socioeconomic characteristics of respondents.
- Investigate patterns in previous voting behaviour and future voting intentions.
- Examine associations between selected categorical variables.
- Communicate findings through visualisations, statistical analysis, and a research report.

## Project Workflow

### 1. Data Collection

Survey data was collected to explore political participation, voting behaviour, and factors associated with voting decisions.

The dataset includes information on respondent demographics, socioeconomic characteristics, political interest, previous voting, future voting intentions, sources of political information, local issues, and geographic location.

### 2. Data Cleaning and Preparation

The collected data underwent extensive cleaning and preparation before analysis. This stage involved inspecting the dataset, reviewing variable structures, identifying data-quality issues, and preparing the data for exploratory analysis.

The cleaning workflow is documented in the `PoliticalDatasetCleaning-230608-191614.ipynb` notebook.

### 3. Exploratory Data Analysis (EDA)

Exploratory data analysis was conducted using Python to understand the characteristics of the dataset and identify patterns in the responses.

The analysis included:
- Examining demographic and socioeconomic distributions.
- Exploring previous voting behaviour and future voting intentions.
- Comparing voting responses across selected demographic and geographic groups.
- Creating visualisations to communicate distributions and differences between groups.
- Using cross-tabulations and Cramér's V to explore associations between categorical variables.

The EDA workflow is documented in `PoliticalDatasetEDA-230706-175420.ipynb`.

### 4. Statistical Analysis and Interpretation

Categorical association analysis was used to explore relationships between selected characteristics and voting responses.

Cramér's V was used as a measure of association strength. These results provide an exploratory view of relationships in the dataset; they do not establish causation.

### 5. Research Reporting

The findings were consolidated into a research report covering the analytical process, observed patterns, interpretation of results, and considerations for further investigation.

The report is available in the repository as `Political Voting Behaviour Research Report.doc`.

## Tools and Technologies

- **Python** — data analysis and processing
- **Pandas** — data manipulation and preparation
- **NumPy** — numerical operations
- **Matplotlib and Seaborn** — data visualisation
- **Jupyter Notebook** — documenting and executing the analytical workflow
- **Statistical methods** — descriptive analysis, cross-tabulation, and categorical association analysis

## Repository Structure

```text
Machine-Learning-Project-for-Political-data/
│
├── PoliticalDatasetCleaning-230608-191614.ipynb
├── PoliticalDatasetEDA-230706-175420.ipynb
├── Political Voting Behaviour Research Report.doc
└── README.md
```

## Key Learning Outcomes

This project demonstrates practical experience in:

- Survey data handling and research-oriented data analysis.
- Data cleaning, validation, and preparation.
- Exploratory data analysis and visual storytelling.
- Statistical interpretation of categorical variables.
- Investigating patterns in political participation.
- Translating analytical results into a structured research report.

## Limitations and Further Work

The results should be interpreted in the context of the survey's sampling method, geographic coverage, and data quality. Observed associations do not establish causal relationships, and the findings should not be assumed to represent all Kenyan voters without evidence that supports such generalisation.

Further work could include additional statistical testing, deeper investigation of factors associated with voting intentions, and the development and evaluation of predictive models where appropriate.

## Conclusion

This project demonstrates an end-to-end approach to survey data analysis, connecting data collection and preparation with exploratory analysis, statistical interpretation, and research reporting. It illustrates how structured analytical workflows can support a better understanding of voting behaviour and political participation in Kenya.
