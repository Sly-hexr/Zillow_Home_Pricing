# Zillow Home Analysis
## Purpose
### The purpose of this repository to perform an analysis on the most expensive zip codes among several states and narrow down the data to answer stakeholder questions.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#    Our first Goal will be to find out our largest Features
![image](https://github.com/Sly-hexr/Zillow_Home_Pricing/assets/133910731/7ff6dd63-9035-4b27-b84a-79312d6f3078)
##    Having Central A/C, a Hillside construction, and the overall condition are our 3 most positively impactful features towards the sale price of the home.

##    Having a Home banked however seems to give the most significant decrease to the sale price of a home.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Our second Goal will be to lock down our most important features to our target
![image](https://github.com/Sly-hexr/Zillow_Home_Pricing/assets/133910731/02e69010-ffff-4bc5-be6f-8bd5ad26e157)
## Our 6 most important features are in order:

### 1. Gr Liv Area

### 2. Total Bsmt SF

### 3. Lot Area

### 4. Lot Frontage

### 5. TotRms AbvGrd

### 6. Overall Cond

## Overall Cond, TotRms AbvGrd, & Lot Frontage also make a return from our largest and smallest coefficients
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#    They would also like us to interpret the top 6 most important features. According to shap, what effect does each feature have on the model’s prediction?
![image](https://github.com/Sly-hexr/Zillow_Home_Pricing/assets/133910731/cb229368-bf16-458b-9b4a-3487f860512d)

###    1. Gr Liv Area- The more living area (SQft)above grade a home has(red), the more likely it will positively impact the prediction value.

###    2. Total Bsmt SF - the larger a basement in a home(Red), the more likely it will positively impact the prediction value.

###    3. Overall Cond- the lower the rating of the condition of the home(blue), the more likely it will negativly impact the prediction value. While a higher rating does positivly impact the model, the negative impact of a lower rating outvalues having a higher rating.

###    4. Lot Area- a central cluster of mixed values would indicate a less than average impact in either direction on the predicted value.

###    5. Lot Frontage- The more linear feet of street connected to the property(Red) the more likely it is to positively impact the model.

###    6. Central Air Y- if the home DOES have central air, it is likely to positively impact the model.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#    Additionally they would like for us to figure out the 5 most expensive states by home prices from 2010-2020
![image](https://github.com/Sly-hexr/Zillow_Home_Pricing/assets/133910731/7fb18115-7f03-4610-b77d-1cbad992a7c6)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Tableau Workbook

https://public.tableau.com/views/Zillow_RealEstate_Story/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

