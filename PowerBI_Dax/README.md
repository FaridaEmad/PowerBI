# PowerBI_Dax
In this repository I shows most of the things I can do with DAX in PowerBi

***All the Dax measures, tables, parameters I made for them a simple visualization, You can see it from the screenshots or open the project.***

# Date Caculated Table
I used three ways to create this table.
![Data_dim using Calender](/PowerBI_Dax/Date_dimCreationWithCalender.png)
I used the calender function to create this table with start date and end date.
![Data_dim using Calender Auto](/PowerBI_Dax/Date_dimCreationWithCalenderAuto.png)
CALENDERAUTO function get all the dates that exist in my dataset.
![Data_dim using Calender Auto + Columns](/PowerBI_Dax/Date_dimCreationWithCalenderAutoAndAddingColumns.png)
I used ADDCOlUMNS function to add all the columns and used inside it another functions like CALENDERAUTO, FORMATE and some other functions.
***And I didn't forget to link the date_dim with the fact table through date model.***
![Job Title Dimension Creation](/PowerBI_Dax/Job_title_dimCreation.png)
I created this table using DISTINCT function to get distinct or unique values from job_title_short column exist in job_posting_fact table.
# Calculated Coloumns
![Salary Hour Adjusted](/PowerBI_Dax/salary_hour_adjCreation.png)
![Salary Year and Hour](/PowerBI_Dax/salary_year_and_hourCreation.png)
# Calculated Measures
![Job Count](/PowerBI_Dax/JobCount.png)
![Median Yearly Salary](/PowerBI_Dax/MedianYearlySalary.png)
![Median Yearly Salary For United States](/PowerBI_Dax/MedianYearlySalary(US).png)
![Skill Count](/PowerBI_Dax/SkillCount.png)
![Job Per Job](/PowerBI_Dax/SkillPerJob.png)
![Grand Total Skill Count](/PowerBI_Dax/GrandTotalSkillCount.png)
# Parameters
![Select Category Parameter](/PowerBI_Dax/SelectCategoryParameter.png)
![Measures Parameters](/PowerBI_Dax/MeasuresParameters.png)
![Select Deduction Rate Parameter](/PowerBI_Dax/SelectDeductionRate.png)
And I used this parameter in this measure.
![Median Yearly Salary Take Home Pay](/PowerBI_Dax/MedianYearlySalaryTakeHomePay.png)