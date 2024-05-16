# Project Overview:
This project explored the impact of Education on Earnings over a time span of 20 plus years with a focus on the Pay Gap between Genders through data visualization. 

**Team members:**

1. Elizabeth Arias 
2. Sebastian Fajardo 
3. Dawn Kim 
4. Chearine Pringle 
5. Zhongzhe Shen (Dennis) 
6. Vanessa Wright

**Usage and Installation Instructions**
This project utilizes two datasets from the US Bureau of Labor Statistics in CSV files named "earnings.csv" and "growth.csv".
1) The program requests an upload of "earnings.csv".
2) A data frame called "all_weekly_earnings" isolates only the necessary columns and drops the 'NaN' values.
3) A function is created to graph the median weekly earnings for both men and women and is called for four different education levels - "Less than a high school diploma", "High school graduates", "Bachelor's degree only", "Advanced degree".
4) A data frame and scatter plot is created showing the correlation value between men and women weekly earnings for each education level.
5) The program requests an upload of "growth.csv".
6) Two data frames are created, "yoy_men" and "yoy_women", which show the year over year growth of weekly earnings for men and women respectively.
7) A function is created to graph the year over year growth in % for both men and women for three different education levels- "Advanced degree", "High school graduates", "Bachelor's degree only".
8) Prophet models are created for men and women weekly earnings and two graphs are created showing the predicted values for the next 10 years.

![image](https://github.com/professav/project1.newrepo/assets/163077507/66dc96ff-56af-4281-b035-7895422c40f2)
![image](https://github.com/professav/project1.newrepo/assets/163077507/364a0e84-deb7-4f7e-b98a-47065ac60731)
![image](https://github.com/professav/project1.newrepo/assets/163077507/84b7b788-ebb5-45b7-ab43-3b2c7a3fb124)
![image](https://github.com/professav/project1.newrepo/assets/163077507/38712698-7ccd-4ac7-a761-72b38108576f)
![image](https://github.com/professav/project1.newrepo/assets/163077507/67b29a78-4480-417e-940b-d13b75cffd48)
![image](https://github.com/professav/project1.newrepo/assets/163077507/55ca024d-ea3a-4706-b150-849816263fc5)
![image](https://github.com/professav/project1.newrepo/assets/163077507/cc47a5db-9741-4a1f-8266-dd30728b0e62)
![image](https://github.com/professav/project1.newrepo/assets/163077507/359b29d6-7d43-4b9c-a5e7-d2f528ca185c)








**Dataset:**

US Bureau of Labor Statistics data set (https://www.bls.gov/data/#employment), spanning twenty years with salary, education, and gender as parameters.
Tools for Analysis:
Jupyter Notebook; Google Collab [https://colab.google/]

**Approach and Methodology:**

Started with project ideation, sourcing data & transforming it using excel and python to a usable dataframe and csv file. Then used Power BI to quickly gather insights on the downloaded  dataset and assess the feasibility of our hypothesis. Python was used for formatting and exploratory data analysis. The new layout was stored as a standard
CSV file that was read into our code as a dataframe. Github was used for code repository, presentation deck and README file. Finally built visualizations using Google Collab. Both top-down and bottom-up approachs were adopted to define the narrative, synthesizing of information/charts, and ensuring they answer the questions we set out to address.

bls.gov
Databases, Tables & Calculators by Subject (12 kB)
https://www.bls.gov/data/#employment

**The conclusions were:**

1) Both men & women earn more with increased education; While there is a noticeable gender gap in pay between men & women, pay across both genders are directionally aligned across all education levels.
2) Gender gap is fairly consistent ($0.70/$0.80 Female : $1 Male), with greater gender imparity the higher the education level i.e. Advanced Degree (compared to lower education levels).
3) Wage growth seems to be generally aligned across genders, showing almost perfectly positive correlation between genders.


**Articles:**
Gender pay gap in U.S. hasn’t changed much in two decades
https://www.pewresearch.org/short-reads/2023/03/01/gender-pay-gap-facts/

Gender wage gap widens even as low-wage workers see strong gains
https://www.epi.org/blog/gender-wage-gap-widens-even-as-low-wage-workers-see-strong-gains-women-are-paid-roughly-22-less-than-men-on-average/




