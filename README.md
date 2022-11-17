# Bike-Sales-Dashboard-excel
Performing data analysis on bike sales data to uncover Trends and created simple Dashboard (source: Alex the analyst) 

Data source : https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx
## Dashboard Preview
![bike sales dashboard](https://user-images.githubusercontent.com/103429014/202375323-6b6d12b6-c7dc-43e0-b106-cc4b75d35c70.png)
## Data Cleaning
Deduping the Data

Deduped the data based on ID
- Manually checked the duplicates using conditional formatting to verify no other field is needed
- Deduped on ID Column
- 26 duplicates were removed; 1,000 unique values remain

## Applied user friendly names:

- Married...M -> Married | S -> Single
- Gender... M -> Male | F -> Female

## Added Age Bracket to group the ages for better visualization

- =IF([@Age]>54,"Old",IF([@Age]>=31,"Middle Age", IF([@Age]<31,"Adolescent","Invalid")))


# Pivot Table Creation
## Created multiple pivot tables:

- Average Income per purchase 
- % of bikes purchased by Age Bracket
- % of bikes purchased by Commute Distance
# Dashboard Creation
By using the pivot tables, I created dynamic graphs that will change based on the filters provided.

## Slicer/Filter Creation:

I created slicers that connected to all the pivot tables/charts
- One based on Region
- One based on Marital Status
- One based on Education
