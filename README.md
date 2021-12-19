# Data Scientist Roles in Malaysia

This project focuses on **data collection** retrieved from Indeed[^1] job site using **webscraping**.
The **exploratory data analysis** involved study on the posts' companies, job titles, date, salaries, ratings, number of reposts, and role summaries.
The process involved in this project includes: 

1. Data collection with **Python**, **beautifulsoup** on [this Jupyter notebook.](https://github.com/FatehaRozy/data-scientist-jobs-malaysia/blob/main/data-collection/indeed_scraper.ipynb)
2. Data cleaning with **Pandas** on [this Jupyter notebook.](https://github.com/FatehaRozy/data-scientist-jobs-malaysia/blob/main/data-cleaning/data_cleaning.ipynb)
3. Data analysis and visualization using **Seaborn** and **Matplotlib** on [this Jupyter notebook.](https://github.com/FatehaRozy/data-scientist-jobs-malaysia/blob/main/exploratory-data-analysis/ds_jobs_eda.ipynb)

---

## Exploratory Data Analysis findings:

![](/exploratory-data-analysis/images/avg_salary_freq.jpg)
> - Most postings for data scientist roles in Malaysia prefer **not** to disclose its salary to public.
<br />

![](/exploratory-data-analysis/images/correlations.jpg)
> - The most noticable correlation is between Length of Job Title and the Average Salary.
<br />

![](/exploratory-data-analysis/images/title_len_freq.jpg)
> - Most roles offered have short titles (less than 20 characters).
<br />

![](/exploratory-data-analysis/images/title_sal_pivot.png)
> - Interestingly, job title with the most character offers the highest average salary.
<br />

![](/exploratory-data-analysis/images/rating_freq.jpg)
> - Most companies that post data scientist roles have not yet received any ratings on Indeed.
<br />

![](/exploratory-data-analysis/images/rating_sal_pivot.png)
> - However, none of the companies with ratings (positive numbers) disclose offered salaries in their postings.
<br />

![](/exploratory-data-analysis/images/sal_vs_repost.jpg)
> - Even with disclosed salaries, the same job offers were reposted multiple times.
<br />

![](/exploratory-data-analysis/images/recent_post_pivot.png)
> - Some companies are still recently reposting the same exact offer despite already reposting it more than 20 times.
<br />

![](/exploratory-data-analysis/images/wordcloud.jpg)
> - Overall, these are the keywords that appear the most in the job summaries.[^2]
<br />


📌 Note from Author: As of early December 2021, data scientist opportunities in Malaysia are still considerably limited. Should there be an increase in demand in the future, more data can be collected, and prediction is recommended to be done using Machine Learning. 

[^1]: Indeed URL: https://malaysia.indeed.com/jobs?q=data+scientist&l=Malaysia&start=0
[^2]: Wordcloud EDA reference: https://github.com/PlayingNumbers/ds_salary_proj/blob/master/data_eda.ipynb

