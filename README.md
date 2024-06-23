# Online-Job-Posting-Mining-Using-SPSS

AIM:
To identify relationships between the following:
a)
Examine the relationship between categorical.
b)
Examine the relationship between a categorical and continuous field.

PROCEDURE TO IMPLEMENTATION:
a)
Examine the Relationship between Categorical fields
STEP1: Import the file telco x data.txt. From the Output palette, add a Matrix node downstream from the Type node.
STEP 2: Edit the Matrix node.
➢
In the Rows box, select HANDSET.
➢
In the Columns box, select CHURN.
➢
Click the Include missing values check box to disable it.
STEP 3: In the Appearance tab. Click the Percentage of row check box to enable it. And also Click the Include row and column totals check box to enable it. Click Run.
The churn rate for customers with handset ASAD170 is 4.627%, whereas it is 94.856% for those with handset ASAD90.
Close the Matrix output window.
STEP 4: From the Graphs palette, add a Distribution node downstream from the Type node.
STEP 5: Edit the Distribution node.
EXP :4
DATE:
IDENTIFY RELATIONSHIPS IN THE
TELECOMMUNICATIONS DATA
In the Field box, select HANDSET. In the Color box, select CHURN. Click the Normalize by color check box to enable it. Click Run.
b) Examine the Relationship between Categorical and Continuous field
STEP 1: From the Output palette, add a Means node downstream from the Type node.
STEP 2: Edit the Means node. In the Grouping field box, select CHURN. Similarly In the Test field(s) box, select DROPPED_CALLS. Click Run.
Close the Means output window.
STEP 4: From the Graphs palette, add a Histogram node downstream from the Type node
STEP 5: Edit the Histogram node. In the Field box, select DROPPED_CALLS. In the Color box, select CHURN. Click Run.
