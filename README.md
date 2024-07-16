Analysis of Project 1 Findings

Starting this analysis, I wanted to get an overview of the data we had available to get a big picture of our story and find interesting aspects to further explore. I looked up total cars, unique cars, amount of cars per city, and what year had the largest amount of registrations. We didn't have the year the car was registered, bu we had the year of the car make so i was able to find a summary of the last ten years to visualize any trends. 
![Fig2](https://github.com/user-attachments/assets/c9bb31f1-a3f4-42a9-a005-1042221b12cb)

From here, I also wanted to find a percentage growth by year and also an overall percentage growth from 2014 to 2024. This allowed me to see the steady growth of EV's, that had its peak in 2023, but continues steady in a positive direction. 


Relationship between Availability of Models and the Amount of Registered Cars
Overview:
For my part of this collaborate effort to explore trends and relationships, I wanted to first focus on the relationship between the number of car models available and the total number of registered electric vehicles per year. Using a dataset of electric vehicles that we had for Washington State, I performed correlation and regression analyses to understand this relationship better.
[top_4_models.pdf](https://github.com/user-attachments/files/16242925/top_4_models.pdf)

Statistical Interpretation:
Slope: The slope of 457.10 indicates that for each additional car model introduced, there are on average 457.10 more registered vehicles.
Intercept: The intercept of -1714.18 is part of the regression equation.
R-squared: The R-squared value of 0.71 suggests that approximately 71% of the variability in the total number of vehicles can be explained by the number of car models available.
P-value: The p-value of 0.00 confirms that the regression model is statistically significant.
![Fig5](https://github.com/user-attachments/assets/e61745cc-8640-4006-9042-65b1e725ec33)

Conclusion:
This analysis reveals a strong positive relationship between the availability of car models and the total number of registered electric vehicles per year. Based on this I can infer that the number of car models available could potentially drive higher vehicle registrations, highlighting the importance of diversity in model offerings to boost electric vehicle adoption. My hypothesis was proven, as I believed that as demand for EV's increases, supply increases in variability giving the consumer more options. The statistical significance of these findings further further supports the strengtht of this relationship.

Relationship between Eligibility that Meet Government’s Standards for Tax Credits and Registered Cars

Overview:
The second relationship I wanted to explore, seems ovious and interesting at first. I wanted to see if Goverment programs created a strong enough incentive to increase demand in Electric Vehicles. I filtered the electric vehicle data to determine vehicles eligible for a potential tax credit under the "Clean Alternative Fuel Vehicle (CAFV) Eligibility" criterion. This analysis would help me understand the relationship between eligibility for tax credits and the total number of registered electric vehicles.
I wanted to start narrowing down my analysis by grouping my car data by eligible, and seeing if there is a correlation between this potential tax credit and purchase trends. 
![Fig1](https://github.com/user-attachments/assets/cd7ca6fa-e9b8-4b8c-9bd3-5df38e4f7e40)

Statistical Interpretation:
I ran a linear regression analysis including Pearson's R, to find the strenght of this relationship, and then I ploted my graph accodingly. 
The R-squared value of 0.17 indicates that approximately 17% of the variability in the total number of vehicles can be explained by the number of eligible vehicles. This suggests a weak but positive relationship. There might be other significant factors influencing the total number of vehicles that are not captured by this model.
![Fig4](https://github.com/user-attachments/assets/738ccad1-b62c-4aa9-a215-bd949d7949c9)

This indicates that for each additional eligible vehicle, there is an estimated average increase of approximately 1.56 in the total number of vehicles. This suggests that vehicles eligible for government incentives or benefits are positively contributing to the total number of registered vehicles

Conclusion:
The analysis proves that their a weak positive relationship between the availability of government tax credits for clean alternative fuel vehicles and the total number of registered electric vehicles. Even thought there is an increase in eligible vehicles as the total number of registered vehicles grows, the effect is not very strong. This finding was surpising, as I expected that a potential tax incentive would intice a higher response in demand. This suggests that other factors, for example infrastructure, consumer education or gas price, could be playing a bigger role when it comes to determining electric vehicle growth in the State of Washington. 



The statistical analysis, visualization, and overall code production for this project was self generated with the help of fellow group contributors, class activites, ChatGpt, and Xper Learning Assistant. 



