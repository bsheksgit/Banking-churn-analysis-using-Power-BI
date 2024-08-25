This is a PowerBI project for churn analysis of a bank. (People's Finance Bank)

CSV file was imported and transformed using power query editor.
First all the null values were removed, then the coloumns for customer ID and serial number were removed since they wouldn't be useful in the analysis.
The names of coloumns were changed to meaningful names since they would make the charts more self explanatory and future edits more simpler to process.
New columns are created to add the values into bins of various interval. These cloumns are of text type. After binning, the numerical base columns were removed.

A new data model was created by isolating some of the key columns and creating new reference tables. In this way, a star schema was created by linking the coloumns in the main data table with the new reference tables.
This data is now loaded for analysis.

The dashboard consists of churn analysis based on Gender, Activity status, Credit card status, Country and Products using doughnut charts. Customer churn is further analysed using line and coloumn charts against age groups, credit scores and account balance.

To give more control to the viewer, a slicer is added at the top so that the user can view the charts based on the churn status as well.







