# project1.newrepo
Project Overview:
This project explored the impact of Education on Earnings along the Time with a focus on the Gap between Genders through data visualization. 

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

**Team members:**
Elizabeth Arias, Sebastian Fajardo, Dawn Kim, Chearine P, Zhongzhe Shen (Dennis), Vanessa

**Dataset:**
US Bureau of Labor Statistics data set (https://www.bls.gov/data/#employment), spanning twenty years with salary, education, and gender as parameters.
Tools for Analysis:
Jupyter Notebook; Google Collab [https://colab.google/]

**Approach and Methodology:**
Started with project ideation, sourcing data & transforming it manually to the usable CSV file.  Then used Power BI to quickly assess the feasibility of the downloaded
downloaded dataset into an excel tab separated values. Further took Python to explore, clean and analyze the data. The new layout was stored as a standard
CSV file and Github for code repository. Finally built visualizations with Jupyter Notebook and Google Collab. Both top-down and bottom-up approachs were
adopted to come up with a narrative, synthesizing information/charts, and ensuring they answer the questions we set out to address.
bls.govbls.gov
Databases, Tables & Calculators by Subject (12 kB)
https://www.bls.gov/data/#employment

**The conclusions were: **
1) Both Earnings and Education level increase continuously along the Time;
2) There is a consistent gap between Women's and men's earnings;
3) Education level does not narrow down or widen up this gap;
4) Effort is needed to bring awareness to the gender pay gap.

