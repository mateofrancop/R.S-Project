# R.S Project

### Issue / General Question:

- What is the company's behavior?

### Data Sources

- The data provided by the company can be found at [R.S_Data](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/datos-RS.xlsx).

### Data Cleaning

- The Python code used for data cleaning (using Pandas) is available in the file [Cleaning.ipynb](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/cleaning.ipynb).

### Data Analysis

- The Python code used for data analysis (utilizing Pandas, Matplotlib, and Seaborn) is located in the file [analysis.ipynb](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/analysis.ipynb).

### Dashboard

- You can download the dashboard [here](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/Analisis_RS.pbix) (Power BI).

## Analysis

### Introduction

##### The company has experienced a decrease in sales, so it's important to understand what's happening.

The business is a coffee shop located in downtown, offering a variety of goods and products with over 7 years of market presence. The company has provided data on its inputs and outputs from April 2022 to June 2023. However, the data was messy, so data cleaning was necessary.

### Results

- ##### There is a downward trend in sales.

In the Power BI dashboard, you can observe a downward trend in sales on the line graph. Additionally, upon analyzing the data, it was discovered that there is a dependence on a nearby university. During months like November-December and June-July, when students are on holiday, sales decrease. Furthermore, the transition to virtual appointments during the morning hours also contributed to the decline in sales.

- ##### Key Findings.

1. From April 2022 to June 2023, the total input was $151.4 million, which is a positive indicator considering the country's economic context.

2. The best sales month is August, when there are more students than during the rest of the year, attracting more customers.

3. The weakest sales day of the week is Friday, as there are fewer students and less foot traffic.

![Sales Trend](https://i.imgur.com/rfkY4gd.png)
> You can access the complete dashboard [here](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/Analisis_RS.pbix) (Power BI).

- ##### Input Features

As seen in the histogram, most of the input data falls between $400,000 and $500,000. This suggests that there are more days with sales in this range, which raises some concerns as the company needs to improve its sales.

![Input Data](https://i.imgur.com/5vGOSvZ.png)
> You can review the complete analysis [here](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/analysis.ipynb) (Python).

Moreover, in the daily inputs and outputs behavior graph, there are days where outputs exceed inputs. This is due to expenses like rent or payroll, which increase on certain days.

![Daily Inputs and Outputs](https://i.imgur.com/OacGNGL.png)
> You can review the complete analysis [here](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/analysis.ipynb) (Python).

- ##### Output Features

1. From April 2022 to June 2023, the total output was $130.7 million, with an increase compared to the previous year due to the economic and political environment.

2. The three main expenses are supplies, payroll, and rent, which is typical in this industry.

3. Additionally, there are three other expenses that may be related to supplies: beverage cost, disposable expenses, and market expenses, with beverage cost being the highest.

4. Finally, there's a scatter plot showing the relationship between inputs and outputs. As you can see, the graph is diagonal, indicating a direct proportional relationship. In other words, investing more money results in higher sales.

![Output Data](https://i.imgur.com/WB6gcqY.png)
> You can download the complete dashboard [here](https://github.com/mateofrancop/Personal_projects-Data-Analyst-/blob/main/Rinconcito_del_sabor/Analisis_RS.pbix) (Power BI).

## Recommendations

1. #### Diversify your customer base beyond university students. Consider implementing digital sales as many people are currently working from home, which may be contributing to the decrease in sales. Don't rely solely on the university, as unforeseen events could impact this customer base.

2. #### Introduce special discounts, perhaps on Fridays, when sales are typically lower. The goal is to increase sales and attract more customers, even if it means temporarily sacrificing profits.

3. #### Plan for months with negative profits by saving during profitable months.

4. #### Explore multiple suppliers for the three main supplies and negotiate special loyalty contracts to reduce costs.

5. #### Lastly, remember that investing more in your company can lead to growth and better outcomes.
 
