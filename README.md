# Reporting on Women's Progress

## Project Overview

This data analytics project uses data from **The Social Institutions and Gender Index (SIGI)**, a comprehensive measure tracking the impact of discriminatory laws and social norms on females worldwide. SIGI provides valuable insights that can inform policy and highlight areas needing attention regarding gender equality.

The project focuses on visualizing and analyzing the progress of women in 12 countries with the world's highest GDP, emphasizing crucial metrics such as unpaid domestic work, household roles, managerial gender gaps, and legal discrimination in reproductive autonomy.

## Project Goals

- Identify key areas where gender equality requires increased attention.
- Highlight significant disparities and discriminatory practices affecting women in high-GDP countries.
- Provide clear, actionable insights for policymakers and researchers to drive meaningful change.

## Data Sources

- **SIGI Framework Data:** Original data sets documenting women's rights, domestic responsibilities, economic opportunities, and reproductive autonomy.
- Raw and cleaned data are available in the repository, ensuring transparency and reproducibility of the analysis.

## Methodology

- Data was cleaned, organized, and analyzed using Python libraries, primarily **Pandas**.
- Key metrics evaluated include:
  - **Time spent on unpaid care and domestic work**
  - **Perceptions of household gender roles**
  - **Gender gaps in managerial positions**
  - **Legal discrimination in reproductive autonomy**

## Key Findings

- **Gender Inequality in Reproductive Autonomy:** Highest discrimination levels were observed in Brazil, Japan, and the USA.
- **Household Gender Roles:** Higher acceptance of traditional gender roles compared to acceptance of female managerial roles.
- **Burden of Unpaid Domestic Work:** Persistent inequalities, particularly in Mexico and India.

## Repository Structure

```
reporting_on_womens_progress
├── Data
│   ├── Old: the raw data obtained from OECD Data Explorer: https://data-explorer.oecd.org/
│   └── Loose Files: cleaned data used for analysis
├── ipynb
│   └── Analysis_Notebook.ipynb
├── Part_II_explanatory_LW_Portfolio.pdf
├── .gitignore
└── LICENSE
```

- **Data Folder:** Contains both raw and cleaned datasets used for analysis.
- **ipynb Folder:** Contains the Jupyter notebook with Python code used for data cleaning and analysis.
- **PDF Report:** Comprehensive summary and insights from the analysis.

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/lawwrites/reporting_on_womens_progress.git
   ```

2. Navigate to the analysis notebook:

   ```
   cd ipynb
   jupyter notebook Analysis_Notebook.ipynb
   ```

## Libraries Used

- **Pandas**: Data manipulation and analysis

## License

This project is licensed under the CC0-1.0 license, allowing open use and distribution.
