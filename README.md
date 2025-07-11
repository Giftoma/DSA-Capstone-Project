# DSA-Capstone-Project
This is where I start my analytical journey after going through classes and building my portfolio.  

 I have learnt a lot all through the process of my DSA Data Analytical journey, from Ms Excel, SQL, POWER BI and now to my Project work.

 ## Project Topic: Amazon Product Review Analysis(Excel) 

 ### Project Overview

 This data analysis project aims to generate insights that provides e-commerce analytics solution to sellers. By analysing the various parameters in the data, we seek to guide product improvement, marketing stretegies, and customer engagement by making reasonable decisions which enables us to gather enough insights grotten from the data and to also know the best products from our data. 

 ### Tool Used
 ---
- Ms Excel for Data Cleaning [Download Here](https://www.microsoft.com)
    - Data Collection
    - Data Cleaning
    - Creating a Pivot Table
    - Creating a Dashboard
 
### Data Cleaning and Preparation
---
 we performed the following actions at the initial stage of data cleaning and preparation
  1. Data loading and inspection
  2. Handling missing variables
  3. Data cleamimg and formatting

### Exploratory Data Analysis
---
 This involves the exploring of data to answer some questions such as:
   - What is the average discount percentage by product category?
   - How many products are listed under each category?
   - What is the total number of reviews per category?

### Data Analysis
---
 This is where we include some basic functons such as:
   - IF FUNCTION
   - COUNTIF FUNCTION

### Data Visualizsation

![Screenshot 2025-07-04 223418](https://github.com/user-attachments/assets/b168637e-84cc-445f-996e-6b743aed6c15)

![Screenshot 2025-07-04 231137](https://github.com/user-attachments/assets/5eeec51e-1f45-4a95-a5c4-98728fbb31cc)

      
![Screenshot 2025-07-05 060240](https://github.com/user-attachments/assets/0a4e285f-159e-415a-8201-fc640987a15e)
![Screenshot 2025-07-04 231431](https://github.com/user-attachments/assets/daf08b06-2337-436a-86af-1a98af8b372f)

![Sc![Screenshot 2025-07-05 060355](https://github.com/user-attachments/assets/47c78341-8db3-477a-bba6-106766a796bd)
reenshot 2025-07-05 060319](https://github.com/user-attachments/assets/94b54a38-7846-42ee-9fc5-e3ba3a607827)
![Screenshot 2025-07-05 060422](https://github.com/user-attachments/assets/b3c073e0-f241-4dbc-9d37-867e03014b11)
![Screenshot 2025-07-05 060448](https://github.com/user-attachments/assets/4a6e2b2e-f9b5-4de3-8e26-d57e27c02746)

![Screenshot 2025-07-05 060306](https://github.com/user-attachments/assets/09621ca2-4853-41f0-b5e6-a72d2f1801af)



![Screenshot 2025-07-05 061414](https://github.com/user-attachments/assets/a5ea6b9e-6600-43e0-9a56-fb111e22de4a)



### Data Cleaning and Preparation
---
In Data Cleaning and Preparations, we performed the following actions;
- Getting the Data, Loading the data and inspecting the data
- Handling undisclosed gender
- Data cleaning and formating

### Exploratory Data Analysis
---
EDA involves the exploring of Data to answer some questions about the data such as;
- What is the gender distribution in the organization?
- Rating insights based on gender
- Salary structure and gender pay gaps

**Key Insights**
---
- Total number of purchase: 1351 product were purchased. This suggest a good product market reliability,promoting customer's demand.
- Total potential Revenue is ₹113,643,74m. This indicates strong market demand.
- Total of Average actual price: ₹5,691.18
- Total of Average discouted price: ₹3,304.80
- Average rating count on product: 17644.5



## Project Topic: Palmoria Group HR Analysis

### Project Overview
---
 This Data Analysis project aims to address issues concerning gender inequality. By analysis the parameters of the data, we seek to analyse the company's HR data and come up with recommendations for management's attention. This will enable us to generate insights on Gender-Related issues.

### Tools used
---
- Power BI [Download] ([For Creating a Report](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
  - Data Collection
  - Data Cleaning
  - DAX Measures

 This is where some measures were used during analysis such as
 
 
  ```Power BI
  
  Gender Count = COUNT('Employee'[Gender])

Gender Percentage = DIVIDE(CALCULATE(COUNT('Employee'[Gender])),CALCULATE(COUNT('Employee'[Gender]),ALL('Employee'[Gender])))

Average Rating by Gender = AVERAGE('Employee'[Rating])

Rating Count by Gender = COUNT('Employee'[Rating])

Average Salary by Gender = AVERAGE('Employee'[Salary])

Salary Count by Department and Region = COUNT('Employee'[Salary])

Employees Below Minimum Salary = COUNTX(FILTER('Employee','Employee'[Salary]<90000),'Employee'[Salary])

```

  ### Data Visualization
  ---
  

![Screenshot 2025-07-05 001114](https://github.com/user-attachments/assets/349a9848-4316-4d80-8d98-81bf77dec3c8)
  




![Scr![Screenshot 2025-07-05 001259](https://github.com/user-attachments/assets/8e8a1450-b8cb-4c54-87b6-8fc12bc59a7c)

![Screenshot 2025-07-05 070156](https://github.com/user-attachments/assets/e4f95f9d-c4a1-4f9f-a55e-406213964165)




-![Screenshot 2025-07-05 070235](https://github.com/user-attachments/assets/028742ca-d82f-4375-9a7d-27a0c2186a74)

**Key Insights**
---
- In the gender distribution of the organization, there are more males than females in both region and department bringing about Gender Inequality
- The male has lower rating than the female ranging from Good to very poor. Only in Average do they have higher rating. This makes the male have the Total higher rating distribution by Gender
   - Male: 485
   - Female: 461
- 28 employees fall under the salary band of $20,000-$30,000
- 90 employees fall under the salary band of $90,000-$100,000
- 96 employees fall under the salary band of $50,000-$60,000
- 97 employees fall under the salary band of $110,000-$120,000
- 101 employees fall under the salary band of $30,000-$40,000
- 99 employees fall under the salary band of $60,000-$70,000
- 105 employees fall under the salary band of $40,000-$50,000
- 108 employees fall under the salary band of $80,000-$90,000
- 117 employees fall under the salary band of $70,000-$80,000
- Bonus Rate of employees is 29.75






