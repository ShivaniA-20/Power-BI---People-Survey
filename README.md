# Power-BI-People-Survey

## Project Overview  
This project involved cleaning and analyzing a raw dataset from a people survey to uncover insights about roles, salaries, programming preferences, and work-life balance within the data industry. The analysis was visualized using Power BI, leveraging its advanced visualization tools to present key metrics and trends effectively.  

## Dataset Description  
The raw dataset included the columns like:  

* Unique ID  
* Email  
* Q1 - Which Title Best Fits your Current Role?  
* Q2 - Did you switch careers into Data?  
* Q3 - Current Yearly Salary (in USD)  
* Q4 - What Industry do you work in?  
* Q5 - Favorite Programming Language

## Data Cleaning and Transformation  
### 1. Column Cleanup  
 * Q1 - Current Role:
   * Simplified multiple values in the "Other" category by merging them into a single category labeled Other.
     
![image](https://github.com/user-attachments/assets/ee264501-8ade-4e64-abc2-1d27b8eff343)



 * Q3 - Current Yearly Salary:  
   * Split the column using the "Split Column by Delimiter" option to extract numeric values.  
   * Created a __Custom Column__ to calculate the __Average Salary__ for each range.
     
![image](https://github.com/user-attachments/assets/ef4ba0be-0d25-420c-942c-77f796b24bf1)  ![image](https://github.com/user-attachments/assets/8f0ec76f-1948-4f9d-920f-0eced3c1b694)  

__Result:__  

![image](https://github.com/user-attachments/assets/8139b990-3b3e-42f0-80d7-dfe4255bf323)

  

### 2. Transformation Approach
 * Used Power BI's data transformation tools to standardize data for consistent analysis.  
 * Ensured clean and structured data by handling duplicates, splitting columns, and creating calculated columns. 

## 

## Visualizations  
### 1. Card Visual
* Displayed key metrics such as:
  * __Total Survey Takers__ (Unique ID count).
  * __Average Age of Participants__: 30 years.
 
    ![image](https://github.com/user-attachments/assets/2f8e5b2f-f65f-481d-a068-c066f2594683)

 
### 2. Stacked Bar Chart
* __Objective:__ Compare average salaries across job titles.  
* __Insights:__  
    * Data Scientists have the highest average salary of __$95k.__
    * Data Engineers earn __$65k__, and Data Architects earn __$63k__.

![image](https://github.com/user-attachments/assets/c5b658ff-a364-422a-b7f0-756a205813c8)


### 3. Stacked Column Chart
* __Objective:__ Identify the most used programming languages and categorize usage by job role.
* __Insights:__
    * Python is the most popular programming language, primarily used by Data Analysts.
    * Least usage of Python was observed among Data Architects and Database Developers.
 
  ![image](https://github.com/user-attachments/assets/32036511-e738-4662-acd1-efc6cb41d5c6)



### 4. Treemap
* __Objective:__ Compare average salaries across countries and job titles.
* __Insights:__
     * In the __United States__, Data Scientists earn an average of __$140k__, while in __Canada__, the same role earns __$95.5k__.
     * Each country dynamically updates metrics across other visualizations when selected.
       

![image](https://github.com/user-attachments/assets/e97b9fa6-81ae-499f-bc50-17bdbf0e58d6)


![image](https://github.com/user-attachments/assets/7aae8ca9-a190-4ae3-b4be-70ff63735578)



### 5. Gauge Visual
* __Objective:__ Display key performance indicators (KPIs).
* __Insights:__
    * __5.74%__ of survey participants are satisfied with their work-life balance.
    * __4.27%__ of participants are satisfied with their salary.

![image](https://github.com/user-attachments/assets/eb1e3a5e-bc66-4dbc-b1ad-eadeaa72d404)



### 6. Donut Chart
* __Objective:__ Visualize survey responses on challenges in the data field.
* __Insights:__
    * __42%__ of respondents found breaking into data neither easy nor difficult.
    * Only __4%__ of respondents found it easy to understand data concepts.
 
  ![image](https://github.com/user-attachments/assets/85799e1f-1b92-4eee-97e5-15b9782fc29e)


  ## Outcomes  
* Provided actionable insights into salary trends, programming language preferences, and work-life satisfaction across the data industry.
* Highlighted the disparities in average salaries across countries and roles.
* Enabled dynamic interaction through visuals like Treemap, showing country-specific metrics in real-time.

## Key Features of Power BI Used
* __Data Cleaning Tools:__ Split Column by Delimiter, Calculated Columns.
* __Visualizations:__ Card, Stacked Bar Chart, Stacked Column Chart, Treemap, Gauge, and Donut Chart.
* __Interactivity:__ Cross-filtering and real-time updates across visualizations.
