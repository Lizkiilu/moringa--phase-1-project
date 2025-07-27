# AFRICAN AVIATION CO. AVIATION VENTURE

## INTRODUCTION
African Airways Co. wants to venture into the airplanes business within its region.The vision is to purchase and operate airplanes for commercial and private clients.The company has taken a data driven apporach to make critical decisions for the set-up and onward operation of this new venture, based on assessment of risk factors associated with operating equipment (airplane) and selection of the most risk-averse and profitable model of airplane to launch this business.
This analysis aims at bringing out assessed data that has been modelled to: 

1. Analyse data on various aircraft safety records.
2. Highlight the risks associated with selected airplanes that can be deployed. 
3. Actionable insights to help make decisions for the new business on low risks aircrafts to venture into.

## 1. ACCESSING AND ASSESSING DATA

The data used for the analysis of this project can be found here : https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

The data is from National Transportation Safety Board and includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
The following libraries were imported to facilitate access, view and analysis of data : Pandas, numpy and matplotlib.
The original data set had 31 columns and 90,348 entries. After assessing the data,removal of nulls and columns that did not serve our objectives was done. 

## 2. EXPLORING DATA ANALYSIS

The remaining data set was scanned  and data cleaning done. columns wer filled by either a numeric '0' or 'unknown' depending in information required. Other columns were added through combination of columns, to help bring clarity and proper integration during data analysis

## 3. CONDUCTING DATA ANALYSIS

Analysis of data was done in three steps. Data was analysed for aircrafts types associated with high risk factors (carastrophic), medium risks associated with minor incidences and low risk where aircrafts were associated in incidences but with minimal to nill casualties.

## 4. ASSESSMENTS

Aircrafts incidence data was used to determine the safety factors in operating them. Assessment of safety factor was first done to aircrafts with the largest value_counts. It was assumed these airceafts were popular and most preferred. 
A comparison assessment of safety factor was done to aircrafts percieved to have a low risk profile.
It was found that low risk profile aircraft had a higher safety factor compared to popular aircrafts analysed.

A visualization showing safety records for both popular and low risk aircraft was done and displayed.

## 5. SUMMARY

If African Airways Co. would like to consider the most common aircraft operated as their choice of flight based on information assessed:
a)Most common aircraft selected have lower numbers of passangers, maybe due to the flights being smaller
b)further analysis should be done to know why they are common. It could be that they are cheaper to acquire
c) The safety percentage for these aircraft is however low at 42%

African Airways Co.rather consider the low risk aircraft operated as their choice of flight based on information assessed:
a) They appear to move large volumes of passangers
b)The safety record is quite impressive at95.27%