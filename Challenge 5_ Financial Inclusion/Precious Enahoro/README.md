# Precious Enahoro - Beyond Farming - Financial Inclusion and Livelihood Analysis

## Overview
This project explores how smallholder farmers discuss financial topics such as market prices, credit access, savings, and other non-farming livelihood concerns, to better understand their economic realities, challenges and opportunities for inclusion through financial tools, information to manage risk and investments in productivity. This analysis would inform Producer Direct's support for farmer entrepreneurship, market access, and rural financial systems.

## Research Questions
- Question 1: What specific question are you trying to answer?
- Question 2: What patterns are you looking for?
- Question 3: What insights do you hope to provide?

## Key Findings

### Finding 1: [Title]
Description of the finding, supported by data and visualizations.

**Implications for Producers Direct:**
- How this finding can be used
- What actions it suggests

### Finding 2: [Title]
Description of the finding, supported by data and visualizations.

**Implications for Producers Direct:**
- How this finding can be used
- What actions it suggests

### Finding 3: [Title]
Description of the finding, supported by data and visualizations.

**Implications for Producers Direct:**
- How this finding can be used
- What actions it suggests

## Visualizations

### [Visualization 1 Title]
![Visualization 1](visualizations/viz1.png)

**Interpretation**: What this visualization shows and why it matters.

### [Visualization 2 Title]
![Visualization 2](visualizations/viz2.png)

**Interpretation**: What this visualization shows and why it matters.

## Limitations and Challenges

### Data Limitations
- Missing data issues
- Data quality concerns
- Sample size or coverage limitations

### Methodological Limitations
- Assumptions made
- Simplifications required
- Alternative approaches not explored

### Technical Challenges
- Computational constraints
- Translation accuracy issues
- Other technical hurdles

## Next Steps and Recommendations

### For Further Analysis
1. **Recommendation 1**: What could be explored next
2. **Recommendation 2**: How to deepen this analysis
3. **Recommendation 3**: Related questions to investigate

### For Producers Direct
1. **Action 1**: Specific recommendation for the organization
2. **Action 2**: How to use these insights
3. **Action 3**: What additional data or resources would help

## Methodology
### Data Source
- Producers Direct English Dataset

### Approach
1. **Step 1**: Data loading and initial exploration
2. **Step 2**: Data cleaning and preprocessing
   Data was deduplicated to remove multiple responses to a particular question, since the analysis focused only on questions. This reduced the final dataset to ~3M rows.
4. **Step 3**: Analysis techniques applied
5. **Step 4**: Visualization and interpretation
Exploratory analysis and visualizations were obtained from Tableau [Tableau Packaged Workbook Uploaded]

### Tools and Technologies
- **Programming Language**: SQL
- **GenAI Tools Used**: ChatGPT
- **Other Tools**: Tableau, Excel.

## Use of Generative AI
### AI-Assisted vs. Human-Created
- **AI-Assisted**:
    - Generating SQL CASE WHEN blocks and regex patterns.
    - Debugging SQL/regex errors and restructuring complex logic.
    - Creating aggregation query templates and cleaning functions.
    - Providing statistical test outputs and helping phrase insight summaries.
    - Exploratory thought partner on financial taxonomy and figuring out edge cases.

- **Human-Created**
    - Designed the financial taxonomy and defined all category logic.
    - Cleaned, prepared, and deduplicated the raw farmer-question dataset.
    - Built and validated the final classification rules.
    - Created aggregated tables, trends, and chi-square analyses.
    - Interpreted patterns (seasonality, country differences, product-level insights).
    - Designed Tableau visuals and wrote the final analytical narrative.
    * All AI-generated SQL code and initial insight summaries were reviewed and tested for accuracy.*

## Files in This Contribution

```
your_name_analysis/
├── README.md (this file)
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_analysis.ipynb
├── scripts/
│   ├── data_loader.py
│   ├── preprocessing.py
│   └── visualization.py
├── visualizations/
│   ├── viz1.png
│   ├── viz2.png
│   └── viz3.png
├── results/
│   ├── summary_statistics.csv
│   └── findings.md
└── data/ (if applicable - only small derived datasets)
    └── processed_sample.csv
```

## Dependencies

SQL code ran using DuckDB driver in DBeaver.
```

### Cleaning the Data and Running the Analysis --to be updated
# Open and run scripts in order:
# 1. 01_data_exploration.ipynb
# 2. 02_data_cleaning.ipynb
# 3. 03_analysis.ipynb
```

## References and Resources

### Academic Papers
- Author, A. (Year). Title. Journal.

### Datasets
- Dataset Name. Source. URL.

### Tools and Libraries
- Library Name. Version. URL.

## Contact and Collaboration

**Author**: [Your Name]
**GitHub**: @hwilner
**Slack**: @[your_slack_handle]

**Collaboration Welcome**: 
- Open to feedback and suggestions
- Happy to collaborate on related analyses
- Available to answer questions about this approach

## Acknowledgments

- Thanks to [other contributors] for [specific help]
- Built upon work by [other contributors] in [other challenges]
- Inspired by [specific approach or paper]

---

**Last Updated**: 11/26/2025
**Status**: In Progress

