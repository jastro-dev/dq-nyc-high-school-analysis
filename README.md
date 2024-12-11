# New York City Schools Data Analysis

## Overview
This project analyzes various aspects of New York City schools, including SAT scores, demographics, AP test results, and survey data to uncover meaningful correlations and insights about educational performance.

## Key Features
- Data integration from multiple NYC school datasets
- Statistical analysis of correlations between various factors
- Visualization of key relationships
- Investigation of safety scores, racial demographics, gender distribution, and AP test performance

## Key Findings
1. **Safety and Academic Performance**
   - Positive correlation between school safety and SAT scores
   - Manhattan schools show highest safety scores (6.83)
   - Brooklyn schools show lowest safety scores (6.37)

2. **Demographic Insights**
   - Strong correlations between racial demographics and SAT performance
   - Geographic variations in school performance across boroughs
   - Gender distribution analysis shows slight variations in academic outcomes

3. **Survey Analysis**
   - Strong correlations between survey responses and academic performance
   - Safety perception scores show meaningful relationship with SAT scores

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Sources
- SAT Results
- AP Test Scores
- Demographics
- School Surveys
- Class Size Data
- School Directory
- Graduation Rates

## Visualizations
The project includes several visualizations:
- SAT score correlations
- Safety scores vs academic performance
- Demographic distribution analysis
- Gender impact analysis
- AP test taking patterns

## Project Structure
```
nyc-schools-analysis/
├── schools/                     # Raw data files
│   ├── ap_2010.csv              # Advanced Placement test results
│   ├── class_size.csv           # School class size data
│   ├── demographics.csv         # Student demographic information
│   ├── graduation.csv           # Graduation rate statistics
│   ├── hs_directory.csv         # High school directory information
│   ├── sat_results.csv          # SAT score results
│   ├── survey_all.txt           # General school survey responses
│   └── survey_d75.txt           # District 75 school survey responses
├── visualizations/              # Generated charts and plots
│   ├── ap_vs_sat.png            # AP test takers vs SAT scores
│   ├── female_vs_sat.png        # Female percentage vs SAT scores
│   ├── gender_vs_sat.png        # Gender correlation with SAT scores
│   ├── hispanic_vs_sat.png      # Hispanic percentage vs SAT scores
│   ├── race_vs_sat.png          # Race correlation with SAT scores
│   ├── safety_vs_sat.png        # Safety scores vs SAT scores
│   └── sat_corr.png             # SAT score correlations
└── main_notebook.ipynb          # Main analysis notebook with data processing and visualizations
```