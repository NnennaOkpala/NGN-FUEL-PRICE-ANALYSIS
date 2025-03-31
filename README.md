# NGN-FUEL-PRICE-ANALYSIS(DEC 2023-DEC 2024)


## Introduction
The National Bureau of Statistics (NBS) is Nigeria’s primary source for reliable and comprehensive economic, social, and sectoral statistics. One of its key reporting areas includes fuel price monitoring, which provides critical insights into price fluctuations across different regions and states. This analysis focuses on the major fuel types—Premium Motor Spirit (PMS), Liquefied Petroleum Gas (LPG), Household Kerosene (NHK), and Automotive Gas Oil (AGO).

For this project, I conducted an in-depth analysis of PMS, LPG, NHK, and AGO prices across various states and regions in Nigeria. By examining trends, regional variations, and month-to-month changes, I aim to highlight key insights that can support decision-making for policymakers, businesses, and consumers.

---

## Problem Statement
Fuel price fluctuations significantly impact the Nigerian economy, influencing household expenses, business costs, and regional inequalities. Understanding the drivers behind these fluctuations is critical for informed policymaking and effective intervention strategies. This analysis focuses on the major fuel types—Premium Motor Spirit (PMS), Liquefied Petroleum Gas (LPG), Automotive Gas Oil (AGO), and Household Kerosene (NHK)—to uncover trends and disparities across states and regions.

Which regions and states consistently pay more for fuel, and why?

What trends emerge across fuel types, from PMS to LPG? Are there hidden relationships in pricing shifts?

How does urban demand compare to rural stability, and what role do supply chains play in shaping these disparities?

Where are the opportunities for improvement? What strategies can ensure fairness, efficiency, and stability in fuel distribution?

This study provides:

✔ A detailed breakdown of regional and state variations, highlighting areas with the highest and lowest fuel prices. ✔ An analysis of year-over-year and month-over-month trends, revealing the forces behind significant price changes. ✔ Insights into urban versus rural pricing patterns, shedding light on the demand-supply dynamics shaping fuel costs. ✔ Actionable recommendations for policymakers, distributors, and consumers to navigate fuel pricing complexities more effectively.

---

## Tools Used
To transform, analyze, and derive insights from the fuel price dataset, the following tools were utilized:
- **Microsoft Excel**: Data cleaning, preliminary analysis, and calculations.
- **Power Query**: Data transformation and integration.
- **Power BI**: Creating interactive visualizations and dashboards to present key insights.

---

## Skills Demonstrated
- **Data Manipulation**: Cleaning, transforming, and structuring fuel price data for analysis.
- **DAX Calculations**: Creating custom measures for percentage changes, comparisons, and rankings.
- **Power BI Quick Measures**: Leveraging built-in calculations for efficient analysis.
- **Filters & Slicers in Power BI**: Enhancing interactivity and usability of dashboards for dynamic reporting
- **Data Cleaning & Preprocessing**: Handling messy data, eliminating redundancies, and converting data types.

---

## Data Exploration & Cleaning
I explored the four fuel price datasets (PMS, LPG, AGO, and NHK) using Excel and Power Query, identifying data quality issues that required cleaning and transformation.

**Data Cleaning Steps**:
- Dropped irrelevant columns that were not necessary for the analysis.
- Converted data types (e.g., prices to decimal format, state names to text).
- Handled missing values by either removing null records or filling them appropriately.
- Standardized column names for uniformity across datasets.

For **LPG and NHK datasets**, I added:
- “Region” and “Price per kg” as separate columns to enhance regional comparisons.
### Uncleaned Dataset (Final View in Excel)
<img width="960" alt="uncleaned LPG dataset" src="https://github.com/user-attachments/assets/2a6996ee-4659-4feb-ac43-23a8328446a9" />                     
### Cleaned Dataset (Final View in Excel)
<img width="960" alt="lPG cleaned pictures " src="https://github.com/user-attachments/assets/4a60bd8d-3a4a-4f54-9450-f4b6d0b35b62" />#
  



For **AGO and PMS datasets**, I added:
- A “Region” column to enable better regional segmentation.
### Uncleaned Dataset (Final View in Excel)
<img width="960" alt="uncleaded dataset" src="https://github.com/user-attachments/assets/b9d07623-e7d6-4a8e-ab59-46c7f189cd56" />
### Cleaned Dataset (Final View in Excel)
![ago cleaned ](https://github.com/user-attachments/assets/7a693923-9db7-43f4-aa2f-5def4b2279a4)


After cleaning, mereging, and ranking the datasets were transformed and structured for further analysis in Power BI.

---

## Data Analysis
During this phase, I imported the cleaned datasets (PMS, LPG, AGO, and NHK) into Power BI for advanced analysis. Using DAX calculations, I answered key questions and provided insights into fuel price trends across different states and regions.

**Analysis Questions**:
1. Which region had the highest and lowest average PMS, LPG, AGO, and NHK prices in December 2024?
2. What was the average price per region for PMS, LPG, AGO, and NHK in December 2024?
3. What was the year-to-year percentage change in fuel prices for each category between December 2023 and December 2024?
4. Which states experienced the highest increase in average prices over the period analyzed?
5. Which states experienced the lowest increase in average fuel prices over the period analyzed?
6. What were the top 3 states with the highest PMS, LPG, AGO, and NHK prices?
7. What were the top 3 states with the lowest PMS, LPG, AGO, and NHK prices?
8. How did AGO and NHK prices fluctuate across different months?
9. Which states had the highest percentage increase in fuel prices between December 2023 and December 2024?
10. Was there any noticeable trend in fuel price increases in urban vs. rural regions?

---
## Data Visualization

 ## FUEL PRICE DASHBOARDS
 ![d1](https://github.com/user-attachments/assets/7e6a0c7b-fa7a-46a4-85cd-998825df291d)

![D2](https://github.com/user-attachments/assets/1d1eb6e8-2726-4c11-9663-6a19b04dddbd)



![D3](https://github.com/user-attachments/assets/580d71b9-3c63-43c6-8722-dca77b9171d4)



![D4](https://github.com/user-attachments/assets/879ac0f4-7747-4baf-b44f-f779a19e052f)






























# Insights Into Fuel Price Trends (2023-2024)

## Overview
Between December 2023 and December 2024, there were significant fluctuations in PMS, LPG, AGO, and NHK prices across various regions in Nigeria. This analysis aimed to uncover regional and state-level trends to identify patterns and underlying factors influencing fuel price changes.

---

## Regional Fuel Price Variations
1. The regions with the **highest average fuel prices** for LPG, NHK, AGO, and PMS in December 2024 were:
   - **LPG (12kg)**: South-South
   - **LPG (5kg)**: North East and North Central
   - **AGO (per liter)**: North Central
   - **AGO (per gallon)**: North West
   - **NHK**: North East
   - **PMS**: South East  
   
2. Northern regions generally experienced **higher fuel prices** compared to Southern regions due to logistical challenges and supply constraints.

---

## Year-to-Year Price Changes
3. Fuel prices saw **significant percentage increases** from December 2023 to December 2024:
   - **PMS**: +77%
   - **LPG**: +50% (5kg), +44% (12kg)
   - **AGO**: +28%
   - **NHK**: +54% (gallon), +50% (liter)  

4. These price changes reflect the impact of **supply chain disruptions, currency fluctuations, and increased transportation costs**.

5. **States with the Highest & Lowest Price Increases**:
   - States with **highest increases**: Lagos, Rivers, and Abuja, likely driven by higher demand and distribution costs.
   - States with **lowest increases**: Kano, Katsina, and Sokoto, reflecting relatively stable supply conditions.

---

## Top 3 States with Highest & Lowest Prices
6. **States with the highest fuel prices**:
   - **PMS**: Ogun, Abuja, Oyo
   - **LPG (5kg)**: Taraba, Lagos, Benue
   - **LPG (12kg)**: Taraba, Yobe, Rivers
   - **AGO**: Bauchi, Benue, Borno
   - **NHK (Gallon)**: Katsina, Jigawa, Kebbi
   - **NHK (Liter)**: Abuja, Akwa Ibom, Kaduna  

7. **States with the lowest fuel prices**:
   - **PMS**: Taraba, Adamawa, Delta
   - **LPG (5kg)**: Zamfara, Ondo, Delta
   - **LPG (12kg)**: Kwara, Nasarawa, Kebbi
   - **AGO**: Bauchi, Benue, Borno
   - **NHK (Gallon)**: Adamawa, Nasarawa, Niger
   - **NHK (Liter)**: Borno, Bayelsa, Adamawa  

Higher prices were observed in states with **high demand** and **limited supply**, while lower prices were recorded in states with **stable supply chains** and **lower consumption levels**.

---

## Fuel Price Fluctuations Over Time (NOV 2024 $ DEC 2024)
8. LPG (12kg)
North East: +6.01%—This sharp increase exceeds month-to-month changes observed for AGO (+0.46%) and PMS (declines across all regions), suggesting heightened regional demand or possible disruptions.

South West (+0.98%), South East (+0.8%), and North West (+0.61%) reflect moderate growth, aligning with month-to-month variations seen in AGO (+0.98% in North Central, +0.12% in South West).

NHK (Liter)
South South: +1.2%, a significant increase that mirrors AGO (+1.8%) trends and further demonstrates South South's regional demand surge.

South West (+0.9%), North Central (+0.7%), South East (+0.6%), North East (+0.5%), and North West (+0.1%) show consistent upward shifts, unlike LPG's contrasting trends, particularly in North Central.

AGO
Month-to-month increases for AGO were predominantly positive, with South East (+1.9%) leading, followed closely by South South (+1.8%) and North Central (+0.98%). This stability contrasts with the volatility seen in LPG prices.

PMS
Most regions saw declines, including South East (-0.24%), South West (-1.22%), North East (-1.46%), North West (-2.28%), and South South (-2.87%), with North Central (-3.66%) recording the sharpest decrease. This downward trend highlights a notable divergence from NHK's stability and LPG's mixed changes.

South East (-3.61%) and North Central (-4.91%) experienced notable decreases, contrasting with relatively stable NHK trends in these regions.
These figures underscore how **seasonal demand** and **supply chain disruptions** (Landing cost) impacted fuel prices differently across regions in 2024.


# Insights Into Fuel Price Dynamics

## Regional Trends
- **LPG** shows higher volatility, with steep increases in some regions (e.g., North East) and sharp decreases in others (e.g., North Central).
- **NHK** exhibits consistent, stable growth across regions, marking it as the most predictable fuel type in terms of month-to-month changes.

## Urban vs. Rural Dynamics
- **South South**: (+1.2% NHK, +1.8% AGO) reflects higher urban demand and logistical factors.
- **North Central**: LPG declines (-4.91%) align with rural stability trends observed in previous data.

## Fuel-Specific Variations
- **PMS** remains the most volatile, with declines across all regions due to reduction in landing cost which reflects the price of importing and distributing the product, indicates some relief in terms of global market fluctuations and supply chain factors in December 2024. This contrasts with NHK's uniform growth and LPG's mixed trends.


---

## Urban vs. Rural Price Trends
9. Urban centers consistently experienced **more pronounced fuel price fluctuations** compared to rural regions:
   - Urban hubs like **Lagos (South West)** and **Abuja (North Central)** recorded sharper changes—evidenced by the **PMS price decline of -1.22%** in South West and the **-3.66% decrease** in North Central.  
   - Regions with more rural characteristics, particularly in Northern states, displayed **stable pricing trends**, benefiting from **lower consumption levels** and **targeted government interventions**.

This pattern suggests that **higher demand**, **transportation challenges**, and **supply chain constraints** in densely populated urban areas led to **more volatile pricing**, whereas rural areas experienced greater stability.

---












# Recommendations

- **Increase investments in transportation and logistics systems**: Ensure efficient fuel distribution, especially in high-demand urban centers such as Lagos, Abuja, and Port Harcourt, where price fluctuations are more pronounced.

- **Upgrade storage and distribution facilities**: Focus on states with significant price increases, like Lagos, Rivers, and Taraba, to minimize disruptions and stabilize prices.

- **Provide targeted interventions in high-impact regions**: States such as Taraba, Adamawa, and North Central regions, where PMS prices are consistently higher, should receive better regulatory oversight and equitable distribution.

- **Reduce disparities in fuel availability and pricing**: Allocate more resources to high-impact regions to address existing inequalities in fuel distribution and pricing.

- **Integrate advanced monitoring systems**: Use real-time tracking tools to monitor fuel prices and distribution efficiency. This will help quickly identify problem areas and implement effective solutions.

- **Foster innovation through partnerships**: Promote collaboration between government agencies and private distributors to develop innovative strategies for addressing seasonal fluctuations and ensuring market efficiency.

- **Plan strategically for periods of higher demand**: Implement fuel distribution strategies to handle peak periods, such as festive seasons, to prevent shortages and price instability.

- **Allocate additional resources for volatile regions**: States like Lagos and Abuja, which experience significant price volatility, should receive extra resources during high-demand periods to maintain stability.

- **Enhance data transparency**: Share fuel price trends and insights with the public through regular education campaigns. This will help stakeholders understand the factors influencing pricing and encourage collaboration.

- **Conduct monitoring and evaluation**: Regions like North East and North West should have frequent monitoring exercises to prevent unnecessary price hikes and ensure fair practices.

- **Focus on states with significant price increases**: States such as Taraba, Adamawa, and Jigawa, which have recorded notable price increases, should be closely monitored for potential systemic inefficiencies.

- **Encourage stakeholder collaboration**: Work together to identify and mitigate factors driving significant fuel price changes across regions.

- **Leverage consistent data analysis**: Regularly compare fuel prices across states and regions to inform policy decisions and resource allocation strategies.

- **Use percentage change insights for stabilization policies**: Analyze price changes across regions to address discrepancies and create targeted policies for price stabilization.

---

## Author  
**Nnenna Okpala**  
This project transforms raw fuel price data into actionable insights, highlighting regional price variations, market trends, and key factors influencing fuel costs. Every chart, metric, and analysis is crafted to provide a clear, data-driven understanding of pricing dynamics—helping stakeholders navigate market shifts and make informed decisions.

---

## References
[National Bureau of Statistics](https://microdata.nigerianstat.gov.ng/index.php/home)

---

# DAX Measures Used

## Year-over-Year Percentage Change Across Different Fuels
```DAX
YoY Percentage Change (PMS) = 
VAR CurrentYearPrice = AVERAGE('Table 1 (Fuel December 2024)'[Average of Dec-24])
VAR PreviousYearPrice = AVERAGE('Table 1 (Fuel December 2024)'[Average of Dec-23])

RETURN 
IF(
    NOT(ISBLANK(CurrentYearPrice)) && NOT(ISBLANK(PreviousYearPrice)),
    DIVIDE(CurrentYearPrice - PreviousYearPrice, PreviousYearPrice, 0),
    BLANK()
)




--Month-over-Month Percentage Change in November 2024 & December 2024 for AGO & PMS

MoM Percentage Change (AGO) = 
VAR CurrentMONTHPrice = AVERAGE('Table 1 (DIESEL DECEMBER 2024)'[Average of Dec-24])
VAR PreviousMONTHPrice = AVERAGE('Table 1 (DIESEL DECEMBER 2024)'[Average of Nov-24])

RETURN 
IF(
    NOT(ISBLANK(CurrentMONTHPrice)) && NOT(ISBLANK(PreviousMONTHPrice)),
    DIVIDE(CurrentMONTHPrice - PreviousMONTHPrice, PreviousMONTHPrice, 0),
    BLANK()
)


---

