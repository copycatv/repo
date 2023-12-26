# Introduction

This is a readme file decribing the data cleaning process.

## 1. How to use the code (in data_cleaning.ipynb)?

In data_cleaning.ipynb, three datasets from hkgov 2000-2022/2023 are used.
They are labor_force.csv, age_structure.csv, gender_ratio.csv, which will be provided in the files.
First, you need to download the datasets and run all the code, and a files.zip zipfile will be generated, it includes five csv files (df_LF.csv,df_male_ratio.csv,df_female_ratio.csv,df_gender.csv,df_age_to_group.csv)

### 1.1 What does the output zipfile mean/do?

The df_Lf.csv file contain of the employment rate in HK from 2000-2022.
The df_male_ratio.csv contain of the male ratio in HK from 2000-2022.
The df_female_ratio.csv contains the female ratio in HK from 2000-2022.
The df_gender.csv contains the gender ratio from male to female in HK from 2000-2022(per 1000).
The df_age_to_group.csv contains the ratio of male and female in different age (0-85+), order by each year, range from 2000-2022.
Mentioned datasets will be used later on.
