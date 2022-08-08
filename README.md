# Journ 124 Final Project: Data Analysis and Visualization of United States Gun Violence 
## By Timothy Henry
### Data Analysis Process
* Download the "Gun Violence" datasheet as a .cvs file, upload it to google drive, and open it with google sheets  

The following are five questions and step-by-step answers based on the data sets:


__Question 1: Which cities had the largest and least amount of murders since 2014?__

__Step-by-step answer:__

1. Insert a pivot table from the sheet with all the data so that we may compare all the cities report killings together from all years. 
2. When the Pivot Table is open, insert the category "City or County" into the rows column so that all the cities may be listed. 
3. Next put the category "N_killed" into the values section of your pivot table. (Be sure that the values for N_killed are summarized by the sum)
4. Referring back to the rows sections that contains the cities, change the sorting to "Sort by N_killed"
5. Put the order as Ascending so the data will reflect the cities with the least amount of murders to the cities with the most. 
![Screen Shot 2022-08-06 at 9 18 36 PM](https://user-images.githubusercontent.com/109619909/183275123-31ba80d6-c8d0-4502-aced-b0cfdec56c38.png)
* __Answer: As seen in the pivot table, there are several cities listied where no murders occured, however there were still reports of gun violence which is why they are listed on the data sheet. Cities such as Abbottstown,Abercrombie,Accident, and Achille had no murders from gun violence since 2014. These cities may have had people injured rather than killed.__
6. Next Change the order to descending to see which cities had the most amount of murders due to gun violence. 
![Screen Shot 2022-08-06 at 9 32 25 PM](https://user-images.githubusercontent.com/109619909/183275412-2b1b3adb-73c1-47e8-b39e-9a615db36b97.png)
* __Answer: The pivot table reflects that Chicago has the most murders by gun violence since 2014 with a staggering amount of 4,775. The city with the second most murders is Houston with 2,953 followed by Philadelphia with 2,691.__

__Question 2: Compare the amount of people injured in 2014 to the amount of people injured in 2021 in each state and analyze the states with the most injuries to see if there were any changes?__

__Step-by-step answer:__

1. Within the spreadsheet the data is seperated into different sheets by year. Click on the sheet labeled "2014" and create a pivot table. 
2. Once the pivot table is opened, bring the category "state" into the rows part of the pivot table. 
3. Next bring the category "N_injured" into the values part of the pivot tabe. (Be sure that the values for N_injured are summarized by the sum)
4. Referring back to the rows sections that contains the States, change the sorting to "Sort by N_injured".  
5. Change the order to descending so we may see the states with to most injuries listed at the top, and the states with least at the bottom. 
![Screen Shot 2022-08-07 at 1 25 08 PM](https://user-images.githubusercontent.com/109619909/183309786-c0a22819-ac68-420b-be19-86edbeedfc14.png)
6. Next click on the sheet labeled "2021" and create a pivot table. 
7. Once the pivot table is opened, bring the category "state" into the rows part of the pivot table. 
8. Next bring the category "N_injured" into the values part of the pivot tabe. (Be sure that the values for N_injured are summarized by the sum)
9. Referring back to the rows sections that contains the States, change the sorting to "Sort by N_injured".  
10. Change the order to descending so we may see the states with to most injuries listed at the top, and the states with least at the bottom. 
![Screen Shot 2022-08-07 at 1 31 02 PM](https://user-images.githubusercontent.com/109619909/183310051-a4e8e318-e265-42e0-add4-ff1f02a7b728.png)
* __Answer: There are several differences between the amount of people injured in 2014 compared to the amount of people injured in 2021. Although Illinois still is leading in the amount of injuries amongst the states, the amount of people injured doubled plus more. Many other states experiencd growth in the amount of injuries that occured as there are numerous states with values in the 2000's in 2021 whereas in 2014 Illinois was the only state to reach that amount of injuries.__

__Question 3: What year experienced the greatest and least amount of killings?__ 

__Step-by-step answer:__

1. There are sheets that correspond to each given year. Open a pivot table for 2014
2. Put number killed in the values part of the pivot table and the number will reflect the amount of killings for that given year.(Be sure that the values for N_killed are summarized by the sum)
3. Do this for each year, then analyze which year had the greatest amount and which year experienced the least. 
![Screen Shot 2022-08-07 at 11 57 28 PM](https://user-images.githubusercontent.com/109619909/183358198-fece1a38-7a27-4f50-ab2e-bf0d0dd37d82.png)
![Screen Shot 2022-08-07 at 11 54 32 PM](https://user-images.githubusercontent.com/109619909/183358217-61b6622f-5d0c-4889-9e42-b2aee82484b0.png)
* __Answer: 2014 experienced the least amount of murders with a value of 12,348, meanwhile 2021 experienced the most with 20,936 people dying due to hun violence__

__Question 4:Which states had the largest and least amount of murders since 2014?__

__Step-by-step answer:__

1. Insert a pivot table from the sheet with all the data so that we may compare all the states report killings together from all years. 
2. When the Pivot Table is open, insert the category "states" into the rows column so that all the states may be listed.
3. Next put the category "N_killed" into the values section of your pivot table. (Be sure that the values for N_killed are summarized by the sum)
4. Referring back to the rows sections that contains the states, change the sorting to "Sort by N_killed"
5. Put the order as Ascending so the data will reflect the states with the least amount of murders to the states with the most. 
6. Next Change the order to descending to see which states had the most amount of murders due to gun violence. 
![Screen Shot 2022-08-08 at 12 16 51 AM](https://user-images.githubusercontent.com/109619909/183361638-1fc7e1fe-0b4c-49d4-baa6-4874d214524f.png)
![Screen Shot 2022-08-08 at 12 16 34 AM](https://user-images.githubusercontent.com/109619909/183361689-567be72f-091f-4b69-b602-0bbe12df3e1c.png)
* __Answer: California has had the most amount of murder due to gun violence since 2014. They have experience 11,949 death. Vermont has has the least amount of murders, only experiencing 125 since 2014.__

__Question 5: Which day in 2022 expeienced the most amount of killings?__

__Step-by-step answer:__

1. Create a pivot table with the sheet containing the data for the year 2022. 
2. When the Pivot Table is open, insert the category "Incident dates" into the rows column so that all the dates may be listed.
3. Next put the category "N_killed" into the values section of your pivot table. (Be sure that the values for N_killed are summarized by the sum)
4. Referring back to the rows sections that contains the incident dates, change the sorting to "Sort by N_killed"
5. Next Change the order to descending to see which dates had the most amount of murders due to gun violence. 
![Screen Shot 2022-08-08 at 12 36 19 AM](https://user-images.githubusercontent.com/109619909/183364741-121d3283-5650-496e-b9f6-0ec09fbf4bcf.png)
* __Answer: January 1st had more killings than any other day in 2022, with an amount of 82.__


# Story Summary and Sourcing
Gun Violence has plagued the United States with staggering numbers in both killings and injuries. In 2014 there were a total of 12,348 homicides through the use of guns and by 2021 the new total had reached 20,936. There has been a steady increase each year which suggest gun violence is getting worse each year. California, Texas, and Florida are by far the state with highest homicide rates each producing more than 8,000 since the year 2014. California had the largest homicide rate with 11,949 people dying since 2014. The state with the fewest amount of deaths due to guns was Vermont. Vermont has had 125 deaths since 2014. Citizens are also getting injured through this violenceas as well. Illinois was the state that had the most injuries with a value of 2,230. By 2021 Illinois still saw the most amount of injuries and the number had grown to 4,578. In 2014 the states proceeding Illinois were Califonia (1,565) Florida (1,347) and Pennsylvania (1,236) In 2021 the states following Illinois in injuries were Texas (2,982) Pennsylvania (2,602) and California (2,297). Each state following Illinois was now in the 2,000s were as previosly in 2014 the following states hadnt reached more than 1,600. The trend is gun violence is worsening each year. 

To further this story, the PEW Research center has done addition reasearch on gun violence in America and presented it through the following article.  https://www.pewresearch.org/fact-tank/2022/02/03/what-the-data-says-about-gun-deaths-in-the-u-s/ They've done their own data analysis and their finding could be extremely useful with coming to new conclusions. Another beneficial source that could be used is the amnestry organization. They are an organation that presents key facts with hopes to gain gun reform. https://www.amnesty.org/en/what-we-do/arms-control/gun-violence/ A key person who would be good to interview for this topic is Carolyn Meadows, who is the president of the NRA. She has plenty of influence over reform and me be reached by contating the NRA headquartes phone number. Another great person to interview is gun violence activist Gabby Gaffords who had survived  a shooting. She preaches on gun reform and is very knowlegable regaurding the situation. 

# Data Visualization 

![NUjBK-homicide-by-gun-violence-for-each-state-from-2014-2022 (1)](https://user-images.githubusercontent.com/109619909/183401338-45116094-f16e-4140-91b6-c883806c2255.png)
https://datawrapper.dwcdn.net/NUjBK/2/
