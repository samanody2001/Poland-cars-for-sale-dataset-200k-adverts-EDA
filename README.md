# Data_engin_project
Team memberes:
Youssef amr rlsamanoudi 2000986
karim emad 2000859
Abderlrahman mamdouh 2005529
In this project,we tried to gain hidden aqnd useful insights from the data by asking research questions that we want answers for them or to validate them
In this milestone,we first explored data with diffirent techniques including (.unqiue,.info,.null,.value_counts,and more) to explore unique values,data types,null values,percentage of null values,also we used multiple graphs types as pie chart,barplot chart,bubble chart,histogram distribution,boxplot,We droped the columns that their values are 30% or more and saved to another dataframe so we dont lose the original dataframes and these columns,then
we start to impute null values based on every coloumn type,for example doors number we used mode operation,however with displacement and power_hp null values
we used the mean of each them based on the vehicle brand,before we impute any coloumn null values,we first removed outliers using Z-score and IQR techniques,also we used heatmap to discover correlations between variables and each other
#Our Research quesitions are:
# Reasearch question1:Is nowadays cars companies are shifting toward automatic transimission than manual transimission?
Yes,each year car companies shift toward manfuctring automatic cars than manual cars
# Research question2:Are brands that have high price points overall has higher Power_HP than brands with lower price points
Using bubble plot.Yes,car brands that have high price point as mercedes and BMW have bigger power_hp than other cars brands,as power_hp represent by size of the bubble
# Research question 3:Are newer cars are more expensive than older cars?
You could think that this is a trivial question,however it not always the case that the newer the car,the more expensive it is ,before 2000 there are cars
that are much expensive than new cars,because these cars considred to be very valuable beacuse they are rare and have limited quantities
# Research question4: Are colours affects the car price in each brand?
Yes,in each brand,their are colours that are more expensive than other colours,sometimes beacuse these colours are rare
# Research_question5:How diffirent fuel type affect the Co2_emisssion?
Diffirent fuel type leads to diffirent C02_emission,the graph shows how each fuel type in each brand affects the co2_emmisions
# Research_question6:Is there relation between mileage_km and transmission type for each brand?
In each brand manual cars have higher mean mileage_km than automtic car,main reason because most old cars are manual ,and offcourse the older the car ,the more mileage_km consumed
# Research question7: How diffirent car types affects car prices?
There are specific car types that are much expensive than other car types
# Arrangement from highest to lowest in price
# 1. Coupe
# 2. SUV
# 3. Convertible
# 4. Sedan
# 5. station wagon
# 6. minivian
# 7. compact
# 8. city cars
# 9. small cars
