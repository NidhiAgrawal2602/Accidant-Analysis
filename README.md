# Road Accident Analytics Dashboard
*  Created a Road Accident Analytics dashboard using Power BI
* In this, I used different Visualizations and power query formulas Like
1. Text Box - to write the Heading
2. Created 2 Slicer for Road surface and weather conditions
3. Created Another table and named as calender and the formulas that I had used are
   * Calender = CALENDAR(MIN(Data[Accident Date]), MAX(Data[Accident Date])) // to get the min to max date list from accident date column.
   * year = YEAR(Calender[Date]) // to get year
   * Month = FORMAT(Calender[Date],"MMM") // to get month name
   * Month Number = MONTH(Calender[Date]) // to get month Number
4. Now created the relation between both the tables
5. then created different cards for different types of accident.
6. Then created multi row card for accident happend with different vehicle and also added the images for different vehicles
   * Here also created a groups for different vehicle types (Right click on the column name for which you want to create group then create new groups and name them).
7. Now created the Area chart which will help me to check the trend in the Accident in both the years in every month.
8. Created the stacked bar chart based on road type
9. Created 2 donut chart based on Rural/ Urban area Accident happened and Day/Night
10. And at lasted created the Map view for the accidents

![image](https://github.com/NidhiAgrawal2602/Accidant-Analysis/assets/138298087/9e9ee232-9377-4453-9417-51c65bda0670)

