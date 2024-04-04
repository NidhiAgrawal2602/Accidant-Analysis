# Road Accident Analytics Dashboard
*  Created a Road Accident Analytics dashboard using Power BI
* In this, I used different Visualizations and power query formulas Like
1. Text Box - to write the Heading
2. Created 2 Slicer for Road surface and weather conditions
3. Created Another table and named as calender and the formulas that I had used are
   * a. Calender = CALENDAR(MIN(Data[Accident Date]), MAX(Data[Accident Date])) // to get the min to max date list from accident date column.
   * b. year = YEAR(Calender[Date]) // to get year
   * c. Month = FORMAT(Calender[Date],"MMM") // to get month name
   * d. Month Number = MONTH(Calender[Date]) // to get month Number
