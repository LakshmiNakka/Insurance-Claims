# Insurance-Claims
NC Workers Compensation Critical Claims – Prediction 
Report includes the key challenges faced by workers’ compensation claims management and how some of these challenges can be addressed with Big Data.

Key findings about the data about the claim process:
a)	Injury reporting process
b)	Plan to provide prompt medical attention to injured workers
c)   Claim reporting
d)  Accident Investigation
e)  Communication
f)  Early return to work

EDA:Tableau
Visualizations
1.Type of injuries, Count of records based on subcategory Gender, filter being the claim status.
Type of Injuries on X-axis 
Number of records on Y-axis
Visualization – Bar Chart
Columns – Gender, Injury Type, Count of records

2.Total cost incurred based on the body part, claim status filter being  Gender.
Body Part on X-axis
Total incurred Cost on Y-axis
Visualization – Bar Chart
Columns – gender,body part,total cost

3.Denied claims presented based on gender, body parts .
Attribute – IsDenied
Visualization – Bubble Chart

4.Fatality treemap calculated based upon the type body parts affected due to the  injuries.
Labels – Body part region and body parts.

5.Number of records of claims depending upon age.
Gender on the X-axis. Number of records – Y-axis
Represented as a bar chart


6.Injury Nature based on Claimant Age and Gender.
X-axis – Avg Claimant Age
Y-axis – Injury Nature
Represented as a histogram

7. Claims denied based on the claim type, claimant closed date
Columns – Claimant Type,Year,IsDenied Sum.
Visualization – Line Graph

8. Predicting body part injuries count , label being Avg payment Amount
Columns – Avg Payment Amount, Caim Id sum, Body Part Region, Body Part
Visualization – Highlight Tables

Key insights from visualizations:
1.The number of strain type of injuries are more in number than the other types.
2. The lower back area is the area in which injuries occur the most on which claims are raised.
3. The major amount of transactions are found around the year 2008.
4. When we check for the denied claims we come across of the fact the claims raised by women have a higher denial rate denial than men and indemnity type of claims were rejected the most.

Logistic regression to find critical claims-SAS 

SVM CLASSIFIER Python
