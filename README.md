# grp6_nhanesanalysis
Title: Investigating the Impact of Thyroid Hormones on Sleep Duration: An NHANES-Based Analysis 

Research Question: To what extent are variations in thyroid hormone levels (TSH, Free T4, Total T3) associated with differences in sleep duration among U.S. adults from the years 2007 to 2012, and do similar associations extend to other health outcomes such as BMI and depression? 

Brief Background: Thyroid hormones are critical in regulating metabolism, mood, and circadian function. While past studies have suggested links between sleep duration and thyroid dysfunction, few have investigated how thyroid hormone levels themselves may influence not only sleep but also mood and weight-related outcomes. This study builds on existing literature by incorporating a broader set of thyroid markers and evaluating their relationships with multiple health indicators.

NHANES Dataset Cycles Used:
- 2007–2008
- 2009–2010
- 2011–2012
Data Sources & Variable Overview

| Category               | NHANES Variable | Description                                      |
|------------------------|------------------|--------------------------------------------------|
| Thyroid Function       | `LBXTSH`         | Thyroid Stimulating Hormone (TSH)               |
|                        | `LBXTT3`         | Total Triiodothyronine (Total T3)               |
|                        | `LBXT4F`         | Free Thyroxine (Free T4)                        |
| Demographics           | `RIDAGEYR`       | Age                                              |
|                        | `RIAGENDR`       | Gender                                           |
| Sleep                  | `SLD010H`        | Average hours of sleep on weekdays              |
| Depression             | `DPQ010–DPQ090`  | PHQ-9 Depression Scores                          |
| BMI                    | `BMXBMI`         | Body Mass Index (BMI)                           |
| Smoking                | `SMQ020`         | Ever smoked 100+ cigarettes                     |
| Physical Activity      | `PAD615`         | Minutes of moderate/vigorous physical activity  |
** For a detailed breakdown of all variables, including codes, units, sources, and clinical significance, see the variable table in the Colab notebook in this repo.

Objectives (summarised):
- To evaluate the association between thyroid hormones (TSH, Free T4, Total T3) and key health outcomes: sleep duration, BMI, and depression scores among US adults.
- To examine how demographic and lifestyle factors (e.g., age, gender, physical activity, smoking) influence or modify the relationship between thyroid biomarkers and health outcomes.
- To describe the distribution and trends of thyroid hormones and relevant health outcomes (mainly sleep duration) across NHANES cycles (2007–2012).

Methodology Overview
- Data merged across three NHANES cycles (2007–2012).
- Outcome variables: Sleep duration, BMI, PHQ-9 depression score.
- Independent variables: TSH, Free T4, Total T3, age, gender, smoking status, physical activity.
- Statistical analyses: Descriptive statistics, data visualisation

Key Tools
- Google Colab
- NHANES datasets
- ChatGPT (for code, documentation, interpretation assistance)

Authors
- Liew Cheng Kai
- Isabella Noens
- S. Shiva Sayshathri
