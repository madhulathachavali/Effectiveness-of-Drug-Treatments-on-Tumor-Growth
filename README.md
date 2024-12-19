# Dataset Overview
This dataset includes 249 mice diagnosed with squamous cell carcinoma (SCC) tumors. Mice were treated with various drug regimens:

Drugs: Ramicane, Capomulin, Infubinol, Placebo, Ceftamin, Stelasyn, Zoniferol, Ketapril, Propriva, Naftisol
Age Groups: Mice aged between 1 to 24 months
Gender: Both male and female mice
Timepoints: Tumor development was measured over a 45-day period

# Objective
The goal of this study is to compare the effect of a single drug regimen versus placebo on tumor growth in mice across age groups and timepoints.

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

### Metastasis Sites 

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





