# Youth Fellowship Needs Assessment Analysis (2024)

A data analysis project examining survey results from a 652-respondent needs assessment conducted for the Youth Fellowship of Cherubim and Seraphim Movement Church, Surulere Headquarters (Lagos, Nigeria) \u2014 a congregation of approximately 3,500 members.

## Project Overview

In 2024, the fellowship's leadership commissioned a structured assessment to understand how impactful its programs (Sunday services, bands/units, etc.) have been to members, and where members feel the church should provide more support (academics, career, relationships, health, spiritual guidance). The original analysis was conducted in SPSS and delivered to the executive committee as a presentation.

This repository reconstructs that analysis in Python, demonstrating an end-to-end data analysis workflow: survey methodology, descriptive statistics, data visualization, and translating findings into concrete recommendations for decision-makers.

## Methodology

- **Sample size:** 652 respondents (634 in-person, 18 online) from a base congregation of ~3,500 members
- **Instrument:** Structured questionnaire combining categorical demographic questions and 5-point Likert-scale impact ratings
- **Likert scale:** Strongly Agree = 5, Agree = 4, Undecided = 3, Disagree = 2, Strongly Disagree = 1
- **Decision rule:** A program's mean score above the benchmark (3.0) supports the hypothesis that the program is impactful

## Key Findings

- All 8 surveyed Sunday service components scored above the 3.0 benchmark, with **Thanksgiving (Joyful Noise)** rated highest (mean 4.66) and **Male & Female Forum** rated lowest, though still positive (mean 3.81)
- **Spiritual guidance** (55.5%) and **professional training/networking** (51.8%) are the two most-requested areas for church intervention \u2014 ahead of academics and health
- Female respondents made up 62.4% of the sample, versus 34.5% male
- A year-over-year comparison shows the Thanksgiving service's impact held steady and slightly improved between 2022 and 2024 (70.0% \u2192 72.4% strongly affirming impact)

## Repository Structure

```
yfc-needs-assessment/
\u251c\u2500\u2500 README.md
\u251c\u2500\u2500 YFC_Needs_Assessment_Analysis.ipynb   # Full analysis notebook
\u2514\u2500\u2500 outputs/                               # Generated chart images
    \u251c\u2500\u2500 gender_distribution.png
    \u251c\u2500\u2500 employment_status.png
    \u251c\u2500\u2500 service_impact.png
    \u251c\u2500\u2500 intervention_needs.png
    \u251c\u2500\u2500 band_participation.png
    \u2514\u2500\u2500 year_over_year.png
```

## Tech Stack

- **Python** (pandas, matplotlib, seaborn)
- **Jupyter Notebook**
- Original raw analysis conducted in **SPSS**; this repository reconstructs and visualizes the aggregate findings in Python

## Recommendations Delivered to Leadership

1. Invest further in career-focused programming (professional training, entrepreneurship)
2. Strengthen the Male & Female Forum format, given its comparatively lower impact score
3. Expand access to spiritual guidance through small-group structures
4. Use band-level participation data to target outreach to under-engaged bands
5. Maintain the Thanksgiving service format, given its consistently strong and improving impact

## Note on Data

This project reconstructs the analysis from the original 2024 report's aggregate frequency tables and summary statistics (the raw individual-response dataset was analyzed in SPSS and is not available for this reconstruction). All summary figures shown match the original report.

## Author

Abidemi Adeyeye \u2014 M.S. Applied Mathematics, Georgia Southern University
[LinkedIn] \u00b7 [GitHub]
