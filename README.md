## Data Science Job Salaries Dataset


This dataset, available at [Kaggle](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries), contains information about salaries from years 2020 to 2022 for jobs realted to Data Science. Information about company location, experience level, remote ratio and employment type are also included. 

I analysed the dataset using MySQL.

## Process
- First I checked the dataset if it doesn't contain any null or missing values. The dataset is cleaned alerady.
- Next I wanted to see how many countries are there in the dataset and with how many entries. Based on the results I decided to split the dataset in two bigger groups (US based companies and nonUS based comapnies).
- Following step is to compare a


## Questions

  Before I started analyzing the dataset I wrote down questions I am interested in finding answers for:
  - How many countries are in the dataset and how many entries are there for each country?
    (Note: After reviewing the results I decided to split the dataset it two main groups US based companies and nonUS based companies)
  - What is the average salary for each group? 
    (Note: Seeing the amount of entries for each group I wanted to see what is the median of salaries for each group instead)
  - What is the lowest and highest salary?
  - Is the average salary rising with different year?
  - Is the number of senior/executive position rising?
  - What is the percentage for remote:hybrid:in office positions? 
  - Does remote work affect the salary?
  - 

## Datasets limitations, issues and interesting insight: 
1. Some of the salaries are per month and others per year. It is not possible to tell which ones are which as countries salaries and employment type varies.
2. There are 50 countries feature in the dataset. Based on the amount of entries from US which is over 50% I decided to split it in two groups US and nonUS countries. Entries for US 355, for nonUS 252. 
3. Salaries from US companies are twice as high as salaries from non US companies. 
  	I will split the dataset into two for non US companies and US companies.
4. Median salary in USD for US companies is 135000 USD, for nonUS companies 62689 USD.
5. The salary is comparable in US companies for all 3 years. For nonUS companies a jump in average salary is recorded in 2022.
6. The dataset is too small to make conclusions (accoarding to the available sources there are almost 80k data analyst related posistion only in US)

