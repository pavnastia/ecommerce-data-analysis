# E-commerce Data Analysis

### 📊 Interactive Tableau Dashboard

**[View Sales Performance Dashboard on Tableau Public](https://public.tableau.com/app/profile/anastasiia.pavlenko/viz/SalesPerformanceOverview_17914707526710/Dashboard1#1)**

## Project Overview

This project focuses on analyzing e-commerce sales performance, user behavior, traffic sources, and purchasing patterns using Python and statistical methods.

The analysis explores the relationships between website traffic, sales revenue, device types, geographic regions, and customer characteristics to identify key business insights.

The project also includes an interactive Tableau dashboard for visualizing sales performance.

## Tools & Technologies

- **Python** — data analysis and statistical testing
- **Pandas** — data cleaning, manipulation, and aggregation
- **NumPy** — numerical calculations
- **Matplotlib & Seaborn** — data visualization
- **SciPy & Statsmodels** — statistical hypothesis testing
- **Google Colab** — analysis environment
- **Tableau** — interactive dashboard

## Dataset

The dataset contains **349,545 user sessions** recorded between **November 1, 2020, and January 31, 2021**.

It includes information about:

- User sessions and geographic locations
- Devices, browsers, and operating systems
- Traffic sources and acquisition channels
- User registration and email verification status
- Product categories, names, and prices
- Purchasing activity

## Analysis Workflow

### 1. Data Cleaning & Preparation

- Checked data structure, missing values, and duplicate records.
- Converted date columns to the appropriate format.
- Examined missing values and their business meaning.
- Validated product prices.
- Prepared the dataset for exploratory and statistical analysis.

### 2. Exploratory Data Analysis (EDA)

Analyzed sales performance across several dimensions:

- **Geography:** sales and purchases by continent and country.
- **Product categories:** top-performing product categories.
- **Devices:** sales distribution and conversion rates across desktop, mobile, and tablet.
- **Traffic channels:** traffic volume, revenue contribution, and average purchase value.
- **User characteristics:** differences between registered and unregistered users.
- **Sales dynamics:** daily sales trends, peak dates, and weekly patterns.

### 3. Pivot Tables

Created pivot tables to compare:

- Session counts by traffic channel and device type.
- Sales by country and product category.
- Sales revenue by traffic channel and device type.

### 4. Correlation Analysis

Used Pearson correlation analysis to examine relationships between:

- Daily sessions and total sales.
- Daily sales across continents.
- Daily sales across traffic channels.
- Daily sales across product categories.
- Daily sales across device types.

### 5. Statistical Hypothesis Testing

Applied statistical tests to investigate differences between groups:

- **Wilcoxon signed-rank test** — daily sales of registered vs unregistered users.
- **Friedman test** — daily session counts across traffic channels.
- **Two-proportion z-test** — Organic Search share in Europe vs Americas.
- **Mann–Whitney U test** — sales per subscribed vs unsubscribed user.
- **Chi-square test of independence** — purchase rates by email verification status.

## Key Findings

### Sales Performance

- **Americas** is the largest market, generating approximately **\$17.67M** in sales.
- The **United States** is the leading country, contributing approximately **\$13.94M** in sales.
- **Sofas & armchairs** is the highest-performing product category, generating **\$8.39M**.

### Traffic & Devices

- **Organic Search** generates the largest share of sales (**35.76%**).
- **Desktop** accounts for **59.0%** of sales, while mobile contributes **38.7%**.
- Conversion rates are similar across device types, ranging from approximately **9.2% to 9.6%**.

### User Behavior

- Unregistered users generate significantly higher total sales than registered users, largely due to their greater representation in the dataset.
- No statistically significant differences in purchase rates were found between users with verified and unverified email addresses.
- Email subscription status was not associated with statistically significant differences in sales per user.

### Statistical Insights

- A **strong positive correlation** was found between daily sessions and total sales (**r = 0.791**, p < 0.05).
- Sales across regions, traffic channels, and device types often follow similar patterns.
- Daily session counts differ significantly across traffic channels according to the Friedman test.
- No statistically significant difference was found in the share of Organic Search sessions between Europe and Americas.

## Business Recommendations

Based on the analysis:

1. **Prioritize Organic Search** as a key source of traffic and sales revenue.
2. **Maintain a strong presence in the United States**, the company's largest market.
3. **Focus on leading product categories**, particularly Sofas & armchairs, Chairs, and Beds.
4. **Optimize the mobile experience**, as mobile generates a substantial share of revenue with conversion rates similar to desktop.
5. **Increase high-quality website traffic**, given its strong positive relationship with sales.
6. **Explore growth opportunities in other regions** to reduce dependence on the United States market.
7. **Investigate differences between traffic channels** to identify opportunities for improving acquisition performance.
8. **Validate incomplete sales records**, particularly at the end of the analyzed period.

## Conclusion

This project demonstrates how exploratory data analysis, statistical testing, and data visualization can be combined to better understand e-commerce performance.

The findings highlight the importance of traffic acquisition, geographic market concentration, product category performance, and cross-device user behavior.

The analysis provides data-driven insights that can support business decision-making and identify opportunities for further investigation.
