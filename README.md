## The Impact of Covid-19 on World Development Indicators

### Datasets

Utilized two datasets for our analysis:
* World Development Indicators Dataset
   - Features annual changes in 5 world development indicators across six countries (USA, India, China, Singapore, South Africa, Kenya) from 2020 to 2022.

* Covid-19 Dataset
   - Details daily Covid-19 changes from 2020 to 2023 for the same six nations.

### Data Preprocessing

In the data preprocessing phase,performed the following steps:

1. Identified and addressed duplicates and incomplete values in both datasets.
2. Imputed mean values for null entries in the World Development Indicators dataset for data completeness.
3. Reorganized the World Development Indicators dataset, grouping columns by 'indicators' and calculating annual averages.
4. Selected key features from the Covid-19 dataset: 'country,' 'date,' and 'new_cases.'
5. Filtered dates from 2020 to 2022 and converted 'date' to 'year.' Summed up 'new_cases' to align with the other dataset.
6. Standardized 'new_cases' and 'greenhouse gas emissions' from 0 to 1 for better comparison.
7. Merged World Development Indicators and Covid-19 data using the 'year' column.

* Merged dataset columns

### Exploratory Data Analysis

### Indicators Analysis
