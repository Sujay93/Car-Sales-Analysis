# Car-Sales-Analysis

## Page 1
![Page 1](https://github.com/user-attachments/assets/c0314fac-24c2-4e3d-aa87-f0205747a90f)

## Page 2
![Page 2](https://github.com/user-attachments/assets/c6c62cbb-9ab2-48eb-980b-e9f850512ba0)

## Business Problem
A leading car dealership is facing challenges in balancing inventory distribution and optimizing pricing strategies across new, used, and certified pre-owned cars. With fluctuating price trends and disproportionate inventory composition, the dealership seeks insights to improve inventory planning, price positioning, and ultimately boost profitability.

## Scope of Analysis

### 1. Inventory Challenges

A large portion of the inventory is skewed toward **new cars (nearly 59%)**, while **used** and **certified** cars account for a much smaller share. This could lead to **overstocking of new cars** while **under-serving budget-conscious customers** looking for used or certified vehicles.

**Key Business Questions:**
- Are we maintaining the right inventory mix?
- Which car categories or brands are over- or under-represented?

### 2. Price Optimization

Price trends indicate **drastic fluctuations in the value of new cars in recent years**. This raises questions about pricing strategy:
- **Overpricing** may lead to slower sales and inventory pile-up.
- **Underpricing** can impact overall profit margins.

**Key Business Questions:**
- How have prices evolved over time by status (New, Used, Certified)?
- Are Certified or Used cars priced competitively?
- Is there a correlation between pricing and inventory turnover?

---

## Insights & Recommendations
1. **Total Cars by Status**
  * Used cars dominate the inventory, indicating strong resale market activity.
  * New cars follow next, while Certified cars make up the smallest portion.
    
2. **Average Price by Status**
  * New cars have the highest average price, as expected.
  * Certified cars are priced higher than used cars, reflecting added quality assurance and warranty.
  * Used cars are the most affordable, catering to budget-conscious buyers.
    
3. **Top Brands by Total Sales Price**
  * Brands like Toyota, Ford, and Chevrolet lead in total sales value.
  * These brands likely balance volume with value, showing a wide consumer base.
    
4. **Yearly Price Trend by Car Status**
  * A dramatic spike in new car prices (~1.9B) occurred around early 2020s, possibly due to supply chain issues or pandemic-related           shortages.
  * Used car prices steadily increased, reaching around 0.20B, highlighting strong demand in the second-hand market.
  * Certified car prices remained consistently low, peaking only at 0.05B, suggesting limited market penetration.

5. Increase focus on used car inventory, as it holds the majority market share and steady price growth.
   
6. Promote certified cars more aggressively—they offer better margins than used cars and attract trust-focused buyers.

7. Buyers seeking reliability and warranties at a lower price than new cars should consider certified pre-owned vehicles.

---

## Dataset
[https://github.com/Sujay93/Car-Sales-Analysis/blob/main/Cleaned%20Cars%20data.csv]

## Data cleaning
* Imported the dataset using Python libraries to prepare for analysis.
* Identified and removed duplicates to maintain data accuracy.
* Handled missing values through appropriate replacement strategies to ensure completeness.
* Eliminated irrelevant columns not aligned with the analysis objectives.
* Validated and corrected data types for consistency and analytical accuracy.
* Standardized formatting to enhance data usability for analysis
* Exported the cleaned data set to PowerBI for data visualization and analysis.

## Data Visualization and Analysis
1. **Total cars by status**
   ![Total cars by status](https://github.com/user-attachments/assets/4963a5f9-6ea0-4ec8-b690-6cb1ccc9b7bd)

* This donut chart gives a clear summary of total cars by status
* This donut chart visualizes the distribution of total vehicles across three categories: New (58.9%), Used (35.5%), and Certified         (5.6%).
* The analysis highlights that new cars dominate the inventory with 80,000 units, followed by 48,000 used cars and 8,000 certified ones,   helping dealerships prioritize stocking and marketing strategies accordingly.
* **Breakdown of Inventory**  
  - **New:** 80K vehicles, 58.89% of total inventory
  - **Used:** 48K vehicles, 35.52%
  - **Certified:** 8K vehicles , 5.59%

2. **Total cars by Brand**
![Total cars by brand](https://github.com/user-attachments/assets/abb8088f-5314-4d3f-b591-982bb4d22575)

* The bar chart gives a clear summary of total cars by brand
* **Insights:**
  - The inventory is heavily concentrated among three major brands: Ford (16.5K), Chevrolet (13.9K), and Toyota (13.7K).
  - These top 3 brands alone account for nearly 50%+ of the total stock.
  - Other brands like RAM, Lexus, and Honda are underrepresented.
* **Business Implication:**
  - The brand skew could indicate market preference, dealership partnerships, or demand assumptions.
  - However, over-dependence on certain brands may lead to risks if market trends shift.
 
3. **Dealer wise Inventory Breakdown**
![Dealer wise inventory breakdown](https://github.com/user-attachments/assets/122f5cc1-3745-4406-9dc1-c7f7deebe4d0)

* This stacked bar chart displays the total inventory value of each dealer.
* The "Not Available" category leads with $21M, mostly in used cars. 
* Knauz Auto Park and Auto Hub follow closely with significant shares across all categories. 
* **Key Insights**
  - **Highest Total Inventory:** Not Available tops the list with $21M in inventory & Knauz Auto Park has $12M, with a balanced split                                     across all categories.
  - **High Inventory Dealers:** Auto Hub, Pat Lobb Toyota of McKinney, Koons Tysons Toyota, and Ourisman Lexus all have ~$9M in                                          inventory.
  - **Lower Inventory Dealers:** Dealerships like Elite Motors, Fair Oaks Ford, and Castle Chrysler Dodge show around $7M                                                 inventory,still substantial but below the top performers.
 
4. **Top 10 Brands by Revenue**
![Top 10 brands by total revenue](https://github.com/user-attachments/assets/81036474-b0a1-4553-bfe5-17ebfc54fb45)

* This visualization ranks the top car brands based on total sales revenue.
* Ford leads the market with 0.87 billion, followed by Chevrolet (0.72bn) and Toyota (0.57bn). Premium and luxury brands like BMW,         Mercedes, and Audi also appear in the top 10, highlighting their strong market presence despite premium pricing.
* **Key Insights**
  - Ford dominates with a total revenue of 0.87 billion, significantly higher than all other brands.
  - **Strong performers:** Chevrolet: 0.72bn , Toyota: 0.57bn
  - **Mid-range brands:** BMW (0.47bn), GMC (0.46bn), Mercedes (0.43bn), and Jeep (0.42bn) are close competitors in the mid-range category.
  - **Lower tier:** RAM (0.31bn), Audi (0.28bn), and Lexus (0.25bn) generate comparatively lower revenue but still rank among the top 10
 
5. **Average Price by Year**
![Avg price by year](https://github.com/user-attachments/assets/4621d033-9ac5-4e39-bc91-ffde409a8a3c)

* This visualization highlights average car prices by year from 1960 to 2023. 
* The chart reveals significant pricing spikes in the 1960s and 70s, likely due to data outliers or rare luxury vehicles. 
* More consistent trends emerge post-1980, with a notable surge in prices after 2015. The recent increase reflects market inflation and    growing demand for high-end or electric vehicles.
* **Key Insights**
     - **Extreme Peaks in Early Decades**
     - 1960: Sharp spike to 145K, followed by a dramatic drop to 13K.
     - 1970: Another major jump to 128K, again followed by a steep fall.
     - These anomalies may be due to data outliers, limited entries, or luxury vehicles in those early years.
- Stabilization After 1980
- From 1980 onward, prices became more consistent, with values mostly ranging between 15K and 48K.	
- Minor peaks seen in 1983, 1987, 1995, and 1999
- Since 2015, there's a steady upward trend in average car prices.
- From a low of 19K, prices rose sharply to 63K in 2022, indicating increased demand, inflation, and possibly EV or luxury model influence.

6. **Average Price by Brand and status**
![Avg price by brand   status](https://github.com/user-attachments/assets/7e02958b-c32c-49dd-967b-c2c096e5f247)

* The analysis reveals premium pricing trends for brands like Mercedes and BMW, while also highlighting significant depreciation patterns from new to used vehicles. 
* This helps understand brand value perception and pricing strategy across the market segments.
* **Key Insights**
     - **Premium Brands** Lead in Average Price 
     - Mercedes has the highest average prices across all statuses: Certified: 72K, New: 97K, Used: 50K
     - BMW and Lexus follow closely, especially in Certified and New categories.
     - Price Drop from New to Used 
     - All brands show a clear price reduction trend from New to Used, which is expected.
     - **Lower Average Price Brands:** Honda, Toyota, and Jeep represent more budget-friendly brands, with average prices below 50K in         all categories.
     - Certified Cars Generally Priced Between New and Used 
     - Certified prices often sit between New and Used, aligning with standard dealership pricing strategies.

---
## Conclusion

* This project provided an end-to-end analysis of car inventory and pricing trends using Python for data cleaning and Power BI for         interactive visualizations. 
* Key insights highlighted an imbalance in the inventory mix, with a heavy tilt toward new cars, and identified significant                fluctuations in pricing over time. These patterns suggest a need for better inventory management and pricing optimization strategies.
* By identifying over- or under-represented car categories and analyzing price evolution across different statuses (New, Used,             Certified), this analysis empowers dealerships to make data-driven decisions that can improve sales efficiency, customer targeting,      and profitability.



















