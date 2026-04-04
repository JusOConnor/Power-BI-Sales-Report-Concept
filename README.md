## Sales Dashboard - Power BI | In Development
This is currently a work in progress "Sales Report" concept. The data was created using Claude 
and modified to fit in a hybrid Star/Snowflake schema to balance query performance with flexibility. The prompt called for a small- to 
medium-sized business with naming conventions inspired by Microsoft Dynamics.
___
*This dashboard would be updated every morning to ensure the previous day is captured in full.*

**Executive Summary:** </br>
The slicers at the top allow the user to filter on the Item Group, Sales Type, Customer Group, 
and the Sales Rep.</br>
The light blue section shows the previous date's data. The Cases, Revenue, Gross Margin, and 
Gross Margin percentage are shown. </br>

The dark blue section shows the month to date Cases, Revenue, and Gross Margin. I also include 
the Run Rate calculations for each based on a Monday through Friday work week. </br>

The next blue section shows the previous month's metrics. </br>

The gauge currently shows the year to date revenue vs plan. The plan is based on an assumed 15% 
growth over the previous year overall. Since revenue is currently below plan, the gauge color is 
automatically set to red. </br>

The two purple cards below the gauge show the current annual run rate for the revenue and the 
actual plan. </br>

The lower half of the page is driven off the slicer on the left. This is utilizing the Parameter 
function allowing users to adjust the metrics for both the matrix and chart by selecting the 
measure from the slicer. </br>



![Executive_Summary](Screenshots/Executive%20Overview.png)\
