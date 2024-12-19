
# Placebo vs Capomulin: Effect on Tumor Volume, Weight, and Metastasis

# Dataset Overview

This dataset includes 249 mice diagnosed with squamous cell carcinoma (SCC) tumors. Mice were treated with various drug regimens:

Drugs: Ramicane, Capomulin, Infubinol, Placebo, Ceftamin, Stelasyn, Zoniferol, Ketapril, Propriva, Naftisol

Age Groups: Mice aged between 1 to 24 months

Gender: Both male and female mice

Timepoints: Tumor development was measured over a 45-day period

Data Source: https://github.com/ShipraGupta16/Pymaceuticals

# Objective
The goal of this study is to compare the effect of a single drug Capomulin versus placebo on tumor growth in mice across age groups and timepoints.

# Summary Statistics 

## Summary Statistics for Age

| Drug Regimen | Age_mean | Age_median | Age_std | Age_min | Age_max |
|--------------|----------|------------|---------|---------|---------|
| Placebo      | 10.73    | 10.0       | 6.35    | 1       | 21      |
| Capomulin    | 13.46    | 16.5       | 7.72    | 1       | 24      |
| Ceftamin     | 13.25    | 12.0       | 8.07    | 2       | 24      |
| Infubinol    | 16.23    | 20.0       | 7.51    | 1       | 24      |
| Ketapril     | 15.66    | 18.0       | 6.02    | 1       | 24      |
| Naftisol     | 12.00    | 9.0        | 6.72    | 2       | 23      |
| Propriva     | 10.57    | 8.0        | 7.19    | 1       | 24      |
| Ramicane     | 10.68    | 9.0        | 5.95    | 1       | 23      |
| Stelasyn     | 12.78    | 14.0       | 7.94    | 1       | 23      |
| Zoniferol    | 12.60    | 12.5       | 5.79    | 2       | 24      |

---

## Summary Statistics for Weight

| Drug Regimen | Weight_mean | Weight_median | Weight_std | Weight_min | Weight_max |
|--------------|-------------|---------------|------------|------------|------------|
| Placebo      | 27.93       | 28.0          | 1.84       | 25         | 30         |
| Capomulin    | 19.97       | 20.5          | 2.73       | 15         | 25         |
| Ceftamin     | 27.40       | 28.0          | 1.58       | 25         | 30         |
| Infubinol    | 27.20       | 27.0          | 2.18       | 23         | 30         |
| Ketapril     | 27.86       | 28.0          | 1.84       | 25         | 30         |
| Naftisol     | 27.17       | 27.0          | 1.50       | 25         | 30         |
| Propriva     | 27.08       | 26.0          | 1.69       | 25         | 30         |
| Ramicane     | 19.68       | 19.0          | 3.24       | 16         | 25         |
| Stelasyn     | 27.86       | 28.0          | 1.64       | 25         | 30         |
| Zoniferol    | 27.69       | 28.0          | 1.42       | 25         | 30         |

---

## Summary Statistics for Tumor Volume

| Drug Regimen | Tumor_Volume_mean | Tumor_Volume_median | Tumor_Volume_std | Tumor_Volume_min | Tumor_Volume_max |
|--------------|-------------------|---------------------|------------------|------------------|------------------|
| Placebo      | 54.03             | 52.29               | 7.82             | 45.00            | 73.21            |
| Capomulin    | 40.68             | 41.56               | 4.99             | 23.34            | 48.16            |
| Ceftamin     | 52.59             | 51.78               | 6.27             | 45.00            | 68.92            |
| Infubinol    | 52.88             | 51.82               | 6.57             | 36.32            | 72.23            |
| Ketapril     | 55.24             | 53.70               | 8.28             | 45.00            | 78.57            |
| Naftisol     | 54.33             | 52.51               | 8.13             | 45.00            | 76.67            |
| Propriva     | 52.39             | 50.91               | 6.57             | 45.00            | 72.46            |
| Ramicane     | 40.22             | 40.67               | 4.85             | 22.05            | 47.62            |
| Stelasyn     | 54.23             | 52.43               | 7.71             | 45.00            | 75.12            |
| Zoniferol    | 53.24             | 51.82               | 6.97             | 45.00            | 73.32            |

---

## Summary Statistics for Metastatic Sites

| Drug Regimen | Metastatic_Sites_mean | Metastatic_Sites_median | Metastatic_Sites_std | Metastatic_Sites_min | Metastatic_Sites_max |
|--------------|-----------------------|-------------------------|----------------------|----------------------|----------------------|
| Placebo      | 1.44                  | 1.0                     | 1.34                 | 0                    | 4                    |
| Capomulin    | 0.71                  | 0.0                     | 0.85                 | 0                    | 3                    |
| Ceftamin     | 1.18                  | 1.0                     | 1.18                 | 0                    | 4                    |
| Infubinol    | 0.96                  | 1.0                     | 1.03                 | 0                    | 4                    |
| Ketapril     | 1.30                  | 1.0                     | 1.39                 | 0                    | 4                    |
| Naftisol     | 1.18                  | 1.0                     | 1.22                 | 0                    | 4                    |
| Propriva     | 1.00                  | 1.0                     | 1.09                 | 0                    | 4                    |
| Ramicane     | 0.55                  | 0.0                     | 0.69                 | 0                    | 3                    |
| Stelasyn     | 0.87                  | 1.0                     | 0.97                 | 0                    | 4                    |
| Zoniferol    | 1.23                  | 1.0                     | 1.25                 | 0                    | 4                    |


## Placebo vs Capomulin  

### Treatment Effects on Tumor Growth, Weight, and Metastasis Across Age Groups

Each age group is evaluated at 9 timepoints, ranging from 0 to 45 days, with 5-day intervals. As the study progresses, the number of observations decreases; for example, at 5 months, Capomulin starts with 12 mice at timepoint 0 and only 2 at timepoint 45. Visualizations are provided only for age groups with data for both placebo and drug treatments at a given timepoint.

Fig 1a: Tumor Size Distribution for Placebo vs Capomulin by Age (1 to 24 months) and Sex 

<img width="803" alt="image" src="https://github.com/user-attachments/assets/a681392c-0951-40ac-b9d3-6e1d2069d263" />

Fig 1b: Tumor Size Distribution for Placebo vs Capomulin for Selected Age Groups [1, 3, 7, 9, 12, 16, 17, 18, 20, 21]

<img width="803" alt="image" src="https://github.com/user-attachments/assets/0a66f4b7-2d47-4e76-8ed1-7fa944bfb3e7" />

Fig 1c: Weight (g) Distribution for Placebo vs Capomulin for Selected Age Groups [1, 3, 7, 9, 12, 16, 17, 18, 20, 21]

<img width="803" alt="image" src="https://github.com/user-attachments/assets/5a289ca5-1bcc-417c-a14b-c5b323e74d2f" />

Fig 1d: Metastasis Sites Counts for Placebo vs Capomulin for Selected Age Groups [1, 3, 7, 9, 12, 16, 17, 18, 20, 21]

<img width="803" alt="image" src="https://github.com/user-attachments/assets/d651363e-8f74-4ec5-8391-64f87b7e60fa" />

## Summary 

### Placebo vs Capomulin: Tumor Volume (mm³) Across Age Groups

Fig 2a: ANOVA Results for Placebo vs Capomulin on tumor volume (mm³)

| Age (Months) | F-statistic | p-value         | Interpretation                                      |
|--------------|-------------|-----------------|-----------------------------------------------------|
| 1            | 45.04       | 2.76e-07        | Statistically significant (p < 0.05)                |
| 3            | 51.55       | 9.19e-09        | Statistically significant (p < 0.05)                |
| 7            | 38.49       | 1.06e-06        | Statistically significant (p < 0.05)                |
| 9            | 26.52       | 6.72e-05        | Statistically significant (p < 0.05)                |
| 12           | 19.23       | 3.57e-04        | Statistically significant (p < 0.05)                |
| 16           | 42.84       | 7.42e-07        | Statistically significant (p < 0.05)                |
| 17           | 62.78       | 2.88e-10        | Statistically significant (p < 0.05)                |
| 18           | 12.04       | 3.76e-03        | Statistically significant (p < 0.05)                |
| 20           | 32.74       | 2.00e-05        | Statistically significant (p < 0.05)                |
| 21           | 16.09       | 1.01e-03        | Statistically significant (p < 0.05)                |

Fig 2b: Placebo vs Capomulin: Mean Tumor Volume (mm³) Across Age Groups

<img width="666" alt="image" src="https://github.com/user-attachments/assets/4b14dabb-0e08-4dd0-a0e4-d7e3aab39f78" />


#### Insights:

All age groups show a statistically significant difference in tumor volume between Placebo and Capomulin (p-values < 0.05).

The F-statistic values are high, indicating a strong difference in means relative to variances between the two drug groups.

The ANOVA results suggest that Capomulin is more effective than Placebo in inhibiting tumor growth across all selected age groups.

### Placebo vs Capomulin: Weight(g) Across Age Groups

Fig 2c: ANOVA Results for Placebo vs Capomulin on Weight(g)

| **Age Group (Months)** | **F-statistic** | **p-value**          | **Interpretation**                                                         |
|------------------------|-----------------|----------------------|-----------------------------------------------------------------------------|
| 1                      | 1577.33         | 3.63e-26             | **Significant**: p-value < 0.05 indicates a significant difference between Placebo and Capomulin. |
| 3                      | 269.60          | 1.24e-19             | **Significant**: p-value < 0.05 indicates a significant difference.          |
| 7                      | 336.00          | 3.94e-17             | **Significant**: p-value < 0.05 indicates a significant difference.          |
| 9                      | ∞               | 0.00e+00             | **Significant**: Infinity indicates perfect separation between groups, with no variation in one or both groups. |
| 12                     | ∞               | 0.00e+00             | **Significant**: Same as age group 9, indicating perfect separation.         |
| 16                     | 1088.89         | 3.91e-22             | **Significant**: p-value < 0.05 indicates a significant difference.         |
| 17                     | 466.56          | 2.26e-26             | **Significant**: p-value < 0.05 indicates a significant difference.         |
| 18                     | ∞               | 0.00e+00             | **Significant**: Same as age group 9, indicating perfect separation.         |
| 20                     | ∞               | 0.00e+00             | **Significant**: Same as age group 9, indicating perfect separation.         |
| 21                     | ∞               | 0.00e+00             | **Significant**: Same as age group 9, indicating perfect separation.         |

Fig 2d: Placebo vs Capomulin: Mean Weight(g) Across Age Groups

<img width="676" alt="image" src="https://github.com/user-attachments/assets/b1241ec5-a519-4e4f-a4ec-061dba618a1b" />


#### Insights:

Groups 1, 3, 7, 16, and 17 show statistically significant differences between the Placebo and Capomulin groups, indicating that the drug has an effect on tumor weight in these age groups.

### Placebo vs Capomulin: Metastasis Sites Across Age Groups

Age 1 Month: Capomulin shows fewer metastatic sites (12 with 0), while Placebo has more spread (3 with 3 sites).

Age 3 Months: Capomulin has 21 with 1 site, while Placebo has 9 with 1 site.

Age 7 Months: Capomulin has most mice with 0 sites (14), while Placebo has more spread (4 with 3 sites).

Age 9 Months: Capomulin is concentrated around 0 and 1 sites (5 and 3), while Placebo is spread across 1 and 2 sites.

Age 12 Months: Capomulin shows more 0 sites (4), while Placebo has more 0 and 1 sites.

Age 16 Months: Capomulin has 15 with 0 sites, showing strong treatment effect. Placebo is more spread.

Age 17 Months: Capomulin has mixed counts, 11 with 1 site and 11 with 2 sites. Placebo is more even.

Age 18 Months: Capomulin has 7 with 2 sites, while Placebo has more 1 site (4).

Age 20 Months: Capomulin has 10 with 0 sites, while Placebo shows more variation, including 5 with 4 sites.

Age 21 Months: Capomulin shows 6 with 0 sites, while Placebo has more spread with 3 having 4 sites.

#### Insights:

Capomulin generally shows more mice with 0 metastatic sites, especially in younger age groups.

Placebo shows more variability with higher metastatic counts, especially in older groups.


## Conclusion: Placebo vs Capomulin

#### Tumor Volume: Capomulin significantly reduces tumor volume compared to Placebo across all age groups, with p-values < 0.05 indicating strong evidence of a difference in efficacy.

#### Tumor Weight: Capomulin shows a significant effect on tumor weight in age groups 1, 3, 7, 16, and 17, where the differences between Placebo and Capomulin are statistically significant, indicating the drug's efficacy.

#### Metastasis Sites: Capomulin results in more mice with 0 metastatic sites, especially in younger age groups, suggesting better control of metastasis compared to Placebo, which exhibits higher variability and more metastatic sites, particularly in older age groups.

#### Capomulin is effective in inhibiting tumor growth and metastasis, especially in age groups 1, 3, 7, 16, and 17.






