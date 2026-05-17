# Nigeria Kidnapping Analysis  
## Introduction
#### 
This project was completed during the She Code Africa Data Analytics Mentorship Program as part of a collaborative mentorship project. The dataset were provided by our mentor to help mentees practice real-world data analysis and visualization skills.For this project, I created an interactive dashboard using Microsoft Excel and Power BI to analyze the dataset, uncover insights, and present findings through visual storytelling. The project strengthened my skills in data cleaning, dashboard design, and data visualization.

### 1. Understanding the Data
The first step involved reviewing the Nigerian kidnapping dataset carefully. This included understanding each column, its meaning, and the overall structure of the data. Key issues such as missing values, inconsistent formatting, and incorrect data types were identified before analysis.

---

### 2. Data Cleaning & Preparation
The dataset was cleaned and prepared to ensure accuracy and consistency. Key steps included:

- Handling missing values appropriately  
- Standardizing text entries 
- Converting columns to correct data types (dates and numeric fields)  
- Creating new derived columns such as:
  - Year  
  - Month  
  - Ransom gap  
  - Survival flag  

This step ensured the dataset was ready for meaningful analysis and visualization.

---

### 3. Data Analysis & Exploration
After cleaning, exploratory data analysis was conducted to identify patterns and trends in the dataset. Key questions explored included:

- Which states or regions have the highest incidents?
 
![Pivot table - state incidents](https://github.com/Khaye45/NIGERIA-KIDNAPPING-/blob/main/Stateswithhighestnumberofincidets.png)

- What patterns exist in ransom demands and payments?

 ![chart - ransoms](https://github.com/Khaye45/NIGERIA-KIDNAPPING-/blob/main/ransomdemandedvspaidxl.png) 
 
- Does response time affect outcomes?
 
![chart responsetime](https://github.com/Khaye45/NIGERIA-KIDNAPPING-/blob/main/otcomesvsresponcexl.png)
 
- Are incidents more common in urban or rural areas?

 ![chart - urbanvsrural](https://github.com/Khaye45/NIGERIA-KIDNAPPING-/blob/main/ruralvsurbanxl.png)
 
- How do incidents change over time?
 
![linechart incidentsovertime](https://github.com/Khaye45/NIGERIA-KIDNAPPING-/blob/main/trendsovertimeexcel.png)


---
### 4. Data Modeling & Visualization
The cleaned dataset was imported into **Power BI** for modeling and visualization.

An interactive dashboard was created to:
- Display regional distribution of cases by use of a map chart    
- Show trends over time  using a line chart
- Compare outcomes across categories using a clustered bar chart 
- Highlight key performance indicators (KPIs) using cards 
- Present insights using charts, maps, and interactive visuals  

---

## 🔍 Key Insights

### 1. Geographic Concentration and Spread
Kidnapping incidents are not evenly distributed; certain regions experience significantly higher rates.

Northern states (e.g., Northwest and Northcentral), as well as the Southwest, showed higher frequency, likely due to insurgency and banditry.

Southern regions, particularly the South-South, have also historically recorded kidnappings linked to militancy and oil-related conflicts.


### 2. Target Profiles
Victims come from various locations such as markets, waterways, and villages.

There is an increase in mass abductions (e.g., markets and schools), indicating a shift toward high-impact operations.

People living in residential areas are particularly vulnerable due to weak neighborhood security systems.


### 3. Time Trends
Certain periods (e.g., festive seasons) show spikes in kidnapping activity.

This suggests that incidents may be influenced by seasonal or socioeconomic factors.


### 4. Ransom Gap
There is often a wide gap between ransom demanded and ransom paid, and in some cases a negative gap.

Negotiation plays a key role, with families or communities frequently paying reduced amounts, though in some cases higher amounts are paid.

Reduced payment does not necessarily determine the outcome of victims; outcomes may include release, prolonged captivity, or death.


### 5. Security Response and Outcomes
Areas with faster and more coordinated security responses tend to have higher rescue rates.

However, inconsistent response times and limited resources hinder effectiveness in many regions.  


### 6. Tools Used
- Microsoft Excel (data exploration & structuring)  
- Power BI (data modeling & dashboard creation)

---

### 📁 Dataset Source
This project uses the [Nigerian Kidnapping Dataset](https://github.com/Khaye45/NIGERIA-KIDNAPPING-/blob/main/nigeria_kidnapping_dirtydataset.xlsx), provided during the She Code Africa Data Analytics Mentorship Program. The dataset was cleaned and transformed before analysis.

