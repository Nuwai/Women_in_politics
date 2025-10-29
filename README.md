# Women's Involvement in Politics and Violence Against Women in Politics

## Project Overview
This project analyzes women's participation in politics and the prevalence of violence or attacks targeting women in political roles. By studying trends, patterns, and underlying factors, the project aims to:

- Provide insights into the challenges faced by women in politics
- Highlight areas requiring intervention
- Support data-driven advocacy for gender equity and the safety of women in politics
Note: This project is part of **ongoing research conducted by Myo Thida** on public violence targeting women in politics.

## Objective
- Assess the level of women's participation and representation in politics.
- Investigate trends and patterns of violence or attacks targeting women in political roles.
- Explore the underlying factors contributing to gender-based violence in politics.
- Provide actionable recommendations to support gender equity and the safety of women in politics.

### Data Points
Data will be collected through secondary sourcess:
- **Demographics**: Age, region, political affiliation, and roles held by women in politics.
- **Violence Reports**: Types, frequency, and severity of violence (physical, verbal, or cyber) targeting women in politics.

### Data Characteristics

- Multi-country coverage, including diverse political systems
- Includes both quantitative data (MP counts, violence counts) and qualitative insights (reports, case studies)
- Processed and analyzed for patterns across regions, roles, and political contexts
  
### Methodology
- **Parliamentary Data**: Public datasets on Members of Parliament (MPs) from different countries, including gender representation and political roles. (https://data.ipu.org/women-ranking/)
- **PVTW dataset**: Public datasets on violence against women in politics.(https://acleddata.com/political-violence-targeting-women/)
- **Descriptive Analysis**:  Use charts and graphs to identify trends, patterns, and differences across regions or demographics.
- **Data Collection & Preprocessing**
  - Collect parliamentary and PVTW datasets
  - Standardize formats and clean data for analysis
  - Merge datasets for cross-country comparison
- **Exploratory Data Analysis (EDA)**
  - Use charts, graphs, and descriptive statistics to identify trends
  - Compare women’s representation with frequency of PVTW incidents
- **Statistical Analysis**
  - Hypothesis testing and correlation analysis
  - Evaluate relationships between women’s political participation and PVTW
- **Reporting & Visualization**
  - Generate presentations, reports, and dashboards for policymakers, advocacy groups, and researchers

### Expected Outcomes
- **Insights into Women's Political Involvement**: A clear understanding of the current state of women's participation in politics.
- **Analysis of Violence Trends:**  Identification of the types and patterns of violence against women in politics.
- **Data-driven suggestions** for policymakers, advocacy groups, and international organizations to enhance gender equity and safeguard women in politics..

### Folder Structure
```
data analysis/
├── WIP_Data_Analysis_by_nuwai.ipynb
├── pvtw_event_analysis_by_nuwai.ipynb
├── pvtw_statistical_test_analysis_by_nuwai.ipynb

data collection and preprocessing/
├── WIP_data_collection.ipynb
├── WIP_data_preprocessing.ipynb
├── pvtw_data_preparaing_preprocessing.ipynb

reading/
├── EGM-report-Data-and-violence-against-women-in-politics-en.pdf

summary/
├── PVTW event and statistical analysis.pptx
├── Women in National Parliaments Comparison_v1.docx
├── Women in politics-data analysis.pptx
├── women in politics and PVTW-final revised.pptx
├── PVTW.pbix

README.md
```
### Results & Findings

## 1. Women's Representation in Parliament (2019–2024)

- Regional Variation: Women’s representation in parliaments differs significantly across regions. Some countries;such as Yemen, Oman, and Tuvalu—had no female representatives in their lower chambers.
- Impacting Factors:
  - Population size and total parliamentary seats affect representation levels.
  - Gender quotas and political system types (unicameral vs. bicameral) strongly influence women’s participation.
- Top Performers: The top 10 Asian countries in 2024 show that structured gender quotas and supportive political systems correlate with higher representation.
- Key Insight: While global representation is improving, regional and systemic inequalities persist—particularly in countries with unstable political systems or limited institutional support.

## 2. Political Violence Targeting Women (PVTW)

- Data Source: Analysis of ACLED PVTW data (2019–2024) shows political violence targeting women spans multiple forms—physical, verbal, and fatal attacks.
- Most Common Event Types:
  - Violence against civilians
  - Protests and demonstrations
  - Armed clashes
- Regional Trends: Southeast Asia exhibited notable fluctuations in fatalities and PVTW incidents.
  - Most frequent attacks were violence against civilians and political intimidation.
  - Some regions experienced spikes during transitional political periods like Myanmar.

## 3. Statistical Analysis

- Hypothesis Tested:
  - Is there a significant relationship between women’s representation in parliament and the level of political violence targeting women?
- Methodology:
  1. Spearman’s Rank Correlation
  2. Negative Binomial Generalized Linear Model (GLM)
  3. Mann-Whitney U Test (for skewed data distributions)
- Results:
  - A positive and statistically significant correlation was found between women’s representation and total fatalities during both transitional and non-transitional periods.
  - During transitional periods, the relationship was stronger (coef = 0.0543, p = 0.006) — political instability amplifies violence.
  - Even in non-transitional periods, the correlation remained significant (coef = 0.0582, p = 0.001), though with lower magnitude.
- Conclusion:
  - The **null hypothesis was rejected**, indicating that higher women’s representation is associated with increased political violence (PVTW events and fatalities). However, the severity and dynamics of violence depend on a country's transitional status and political stability.

### Key Insights
1. Representation ≠ Safety: Increasing women’s political participation does not automatically create safer environments.
2. Political Instability Matters: Transitional governments face higher fatality rates and more violence against women in politics.
3. Structural & Cultural Factors: Gender quotas, institutional frameworks, and societal attitudes shape both participation and vulnerability.
4. Policy Implication: Strengthening legal frameworks and protection mechanisms is essential to safeguard women in political spaces.

### Summary & Recommendations

- **Understanding Political Violence**: Future work should investigate how regional dynamics, ideology, and media portrayal influence political violence against women.
- **Focus on Stability**: Examine how governance and political transitions affect women’s safety in public roles.
- **Cultural & Institutional Support**: Promote gender equality programs, accountability mechanisms, and legal protection systems to reduce targeted violence.
- **Data-Driven Advocacy**: Encourage the use of datasets like IPU and ACLED to continuously monitor progress and risk factors.

### Key Deliverables

- Notebooks: EDA, PVTW event analysis, and statistical testing
- Reports & Presentations: PPTX and DOCX files summarizing findings and recommendations
- Dashboard: Power BI file (PVTW.pbix) for interactive visualization
- Research References: PDF reports for background and context
  
### Remark
- This project is a part of ongoing research led by Dr.Myo Thida, focusing on public violence targeting women in politics, and contributes to understanding and addressing this pressing issue.
- This project contributes to understanding gender-based political violence and supports data-driven advocacy for women's safety and participation in politics worldwide.
