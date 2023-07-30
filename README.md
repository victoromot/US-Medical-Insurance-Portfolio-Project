# US Medical Insurance Project
## Description
This project involves a comprehensive analysis of health insurance costs using Python and data manipulation techniques, specifically employing dictionaries, lists, functions, and loops. The dataset contains valuable information on individuals' age, sex, region, BMI, and smoking status, enabling a detailed investigation.

## Description of Columns

1. The *age* column indicate the age of the individual . This coulumn contains numerical datatype that are discrete. 
2. The *sex* column indicates if the individual is male or female. This variable is categorical
3. The *bmi* indicates the Body Mass Index of the individual. BMI is generally used to measure body weight based on weight and height. The entries in this column are continuous numerical variables. According to the WHO, the normal BMI is between 18.5 & 24.9.
4. The *children* column contains discrete numerical variables that show the number of children by the indvidual.
5. The *smoker* column specifies if the individual is a smoker or not. It is a categorical variable with only two possible values, yes or no.
6. The *region* column indicates what region(location) in the US the individual is based and it is a categorical data.
7. The *charges* coulumns indicate the cost of medical insurance for the individual. This is a continuous numerical variable.

Findings:
1. **Average Age and Age Group Distribution:**
   - The dataset's average age of observations is 39 years.
   - Age group distribution is relatively even, with the most entries for individuals aged 45 to 54 and the least entries for individuals aged 55 to 64.

2. **Region and Sex Distribution:**
   - The dataset shows an even distribution of individuals across regions and sex, indicating no skewness in this regard.

3. **Smokers vs. Non-Smokers:**
   - The ratio of smokers to non-smokers in the dataset is approximately 1:4.
   - The average insurance cost for smokers is significantly higher at about 32,000 dollars, approximately three times the cost for non-smokers (8,400 dollars).
   - The dataset has a smaller sample size of smokers compared to non-smokers.

4. **Regional Differences in Insurance Costs:**
   - The southeast region has the highest average insurance cost of 14,735.44 dollars, while the southwest region has the lowest average charge, which is approximately 2,500 dollars less.
   - The southeast region also exhibits the highest average BMI of 33.36 and the lowest average age among the four regions.

5. **Impact of Age and Gender on Insurance Costs:**
   - The average insurance cost increases with age.
   - On average, men pay around 1,000 dollars more than women for insurance.

## Insights
The analysis showcases the capabilities of Python programming, utilizing dictionaries, lists, functions, and loops to extract valuable insights from complex datasets. These findings can be instrumental in supporting decision-making processes within the insurance industry.

## Recommendations
Based on these findings, insurance companies may consider adjusting premiums based on age, smoking status, and regional factors to better align insurance costs with individual risk profiles.

