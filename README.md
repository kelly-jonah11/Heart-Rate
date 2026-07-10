# Heart-Rate
This analysis is intended to provide an overview of the risk of heart attack of various age groups.

Objective of the Analysis
This analysis is intended to provide an overview of the risk of heart attack of various age groups as well as cholesterol and liproprotein levels. The study also provides a predictive model for determining the likelihood of heart attacks.

This dataset was examined to provide an overview of the risk of heart attack, cholesterol, and liproprotein level of various age groups and to provide predicive model for decision making. The dataset was obtained from a CSV file comprises of 10 fields and 1,000 observations. The data types are in whole numbers and decimal numbers. Hence the dataset was subjected to cleaning before analyzing.

Data cleaning:- The Query Editor was use to clean and transform the data. The change type command was use to change data type such as  wholenumbers to text, and decimalnumbers to wholenumbers, the replaced value command was use on the sex field to replaced "1" as "male" and "0" as "female", for smoking, diabetes and heart attack field replaced "0" with "No" "1" with "Yes". After cleaning the data, the new cleaned data was loaded to a new worksheet. Pivot table was used to organized, summarized, and analyzed the dataset without changing the original dataset.

Questions
1. What is the average distribution for total cholesterol, heart heart and diabetes levels across various age grades?

from the analysis that was carrieed out, the various age grades were categorised into four categorie; Young Aduit, Aduit, Older Aduit, and Elderly.  the average distribution for total cholesterol, heart attack, and diabetes levels across these categories were; 

The Elderly had the highest average cholesterol, third highest on average diabetes and highest on average heart attack.

The Older Aduit had the second highest on average cholesterol, lowest on average diabetes and second highest on heart attack.

The Aduit had the third highest on average cholestrol, second highest on average diabetes, and third highest on average heart attack.

The Young Aduit had the lowest of average cholesterol, highest on average diabetes, and lowest on average heart attack.
<img width="460" height="268" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/18c32337-7248-44d9-9ed6-94a6d5daae9b" />
<img width="464" height="283" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/8b4e95be-aa08-4a8e-8fda-fd0e5533a250" />
<img width="471" height="285" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/05549d6e-6ef8-425e-8f33-81099b6cd694" />
2. Determines if high cholesterol levels increase heart attack risk?

From the analysis that was examined, showed 818 people living without high cholesterol and 182 people living with high cholesterol level. It was observed that high cholesterol level cannot necessary increase the risk of heart attack.

3. What is the relationship between Total Cholesterol and Heart Attack?

The relationship between total cholesterol and heart attack is relatively low.

4. How does LDL and HDL infleunce Total cholesterol levels?
<img width="572" height="390" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/b78c0370-8a42-4946-8bc4-821b70fa77b4" />
<img width="586" height="384" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/cd5090c7-768e-45aa-b561-ea5fac52967e" />
from the partten shown ,as the ldl level  is increases, the cholestorl level decreases.
as hdl increases cholesterol level decreases

5. Generate the predictive model to determine likelihood of developing a heart attack?
