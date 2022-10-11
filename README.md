## 📚 Data Science Job Salaries Dataset
This dataset, available at [Kaggle](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries), contains information about salaries from the years 2020 to 2022 for jobs related to Data Science. Information about company location, experience level, remote ratio, and employment type is also included. 

Dataset was analyzed using MySQL, the code used for analysis can be found in this [repository](https://github.com/pavkovatereza/SQL-project-Data-Science-salaries/blob/main/Data_Science_salaries.sql).

Visualization was created using Tableau Public and is available [here](https://public.tableau.com/app/profile/tereza.pavkova/viz/DataScienceSalaries_16647362211800/DataScienceSalaries).

## ❓ Questions

  Before I started analyzing the dataset I wrote down questions I am interested in finding answers for:
  - How many countries are in the dataset and how many entries are there for each country?
    (Note: After reviewing the results I decided to split the dataset it two main groups, US-based companies, and nonUS-based companies, and compare them)
  - What is the average salary? 
    (Note: Seeing the amount of entries for each group I wanted to see what is the median of salaries for each group instead)
  - What is the lowest and highest salary?
  - Is the average salary changing with different years?
  - Is the number of senior/executive positions rising?
  - What is the percentage for remote:hybrid:in-office positions? 
  - Does remote work affect the salary?
  - Where is the highest percentage of remote positions?
  - How many entry-level positions are working remotely?
  - What is the percentage of different experience levels working in different remote conditions? 
  - What is the most common employment type? What is the average salary for each employment type?
  - What is the most common job title?
  - How does the size of a company affect salary?
  - Do large companies have more data-related positions?

## 🚩 Datasets limitations and issues
1. Some of the salaries appear very low, probably as per month and others per year. It is not possible to tell which ones are which as salaries per country and employment type vary.
2. There are only 607 entries in the dataset(according to the available sources there are almost 80k active data science-related positions only in the US by 2022). This dataset is for practice purposes only. To provide more valuable and valid insight, a larger dataset with correct information is needed.
3. There are 50 countries featured in the dataset. Based on the number of entries from the US which is over 50% I decided to split it into two groups: the US and non-US countries. Entries for US 355, for nonUS 252. 

## 💭 Interesting insight
1. **Salary from the US companies is twice as high as salaries from the nonUS companies.**
2. Median salary in USD for US companies is 135,000 USD and for nonUS companies 62,689 USD.
3. The salary is comparable in US companies for all 3 years. For nonUS companies, a jump in average salary is recorded in 2022.
4. **75% of positions in US companies are remote** and only 46% of positions in nonUS companies are remote.
5. Average salary for remote position is slightly higher in US companies, for nonUS companies the average salary is not affected by remote work conditions.
7. **In the US 94% of executive level positions are working remotely, for nonUS only 30% ofexecutive level positions are working remotely.**
8. Large nonUS companies are more likely to offer a hybrid position. Small and medium non US and all sizes of US companies are prone to offer a remote position.
9. Full-time contract is the most common type of employment for both groups.
10. The most common job titles are data scientist, data engineer, and data analyst.
11. Vast majority of employees are residents of the same country as the company location.

## 🎯 Conclusion
Even though the dataset contains only a limited amount of data, it still offers an interesting insight into data science employment conditions. I Analyze thoroughly the data using MySQL. The most interesting outcome is the huge difference between the salary that is offered by companies in the US and outside the US. In average it is 144,000 USD for US companies compared to 67,500 USD for companies located outside the US. 

A big difference can be also seen in the approach to remote work. In the US 75% of positions are remote. Companies outside the US slowly follow with the trend with only 46% remote positions and 31% hybrid positions. Those numbers clearly show that data science and analysis can be done remotely and that the idea of shorter/less frequent commute is getting more and more popular. In fact, remote positions are often better paid (applies to US-based companies).

In general, large companies are more likely to offer higher salaries compare to medium and small-size companies. A full-time contract is the most common type of employment.

The numbers also show that the majority of employees (91,6%) reside in the same country as the company headquarters. I would be very interested to see whether this is caused by company policies and contract conditions, as many job ads are published as remote within a specific country/state, or by employees decisions.
