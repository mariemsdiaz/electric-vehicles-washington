# **THE RISE OF ELECTRIC VEHICLES**

Electric vehicles have emerged as a pivotal solution in the quest for sustainable transportation alternatives. With advancements in technology, expanding infrastructure, and growing environmental awareness, EVs have gained traction as viable options for consumers and policymakers alike. Washington State, known for its progressive stance on environmental sustainability, has become a focal point in this global shift towards cleaner mobility solutions.


*Objectives of the Research and Analysis:*

Examine Growth Trends: Analyze the trajectory of EV adoption in Washington State across our data set, primarily with a focus over the last ten years. We primary focused on the vehicle registration growth, as a way to gage consumer interest in positive trends that could pretict future trends. 

Identify Contributing Factors: Explore the variables influencing the growth of EVs, including: legislative initiatives, consumer preferences, economic factors, and demographics. 


*Methodology:*
Our analysis leverages comprehensive data sources, including state vehicle registrations, electric and non-electric car data sources, gasoline price and housegold median income data. By applying data-driven insights and statistical analytical tools, we aim to provide a thorough understanding of the driving forces behind the surge in EV adoption across the state.

[Project Presentation in Slides HERE] (https://docs.google.com/presentation/d/1ZmoP9o2VKHLvygdWV3iQqxD_uJANb_G0lu4hFNyJKoI/edit?usp=sharing)

# *Tax Incentives and Diversity of Supply*

Starting this analysis, we wanted to get an overview of the data we had available to get a big picture of our story and find interesting aspects to further explore. We looked up total cars, unique cars, amount of cars per city, and what year had the largest amount of registrations. We didn't have the year the car was registered, bu we had the year of the car make so we were able to find a summary of the last ten years to visualize any trends. 

<img width="808" alt="Screenshot 2024-07-16 at 11 15 15 AM" src="https://github.com/user-attachments/assets/602742a0-9224-4ff7-b5de-ae38ef60f5cb">

![Fig2](https://github.com/user-attachments/assets/c9bb31f1-a3f4-42a9-a005-1042221b12cb)

From here, we also wanted to find a percentage growth by year and also an overall percentage growth from 2014 to 2024. This allowed us to see the steady growth of EV's, that had its peak in 2023, but continues steady in a positive direction. 

<img width="715" alt="Screenshot 2024-07-16 at 11 17 39 AM" src="https://github.com/user-attachments/assets/67283b9a-c052-47d8-9b0d-2a166518e95c">

<img width="566" alt="Screenshot 2024-07-16 at 11 17 57 AM" src="https://github.com/user-attachments/assets/3f2ebad4-866a-4af5-83c9-2e31e204dc2e">

*Relationship between Availability of Models and the Amount of Registered Cars*
Overview:
For this part of the collaborate effort to explore trends and relationships, We wanted to first focus on the relationship between the number of car models available and the total number of registered electric vehicles per year. Using a dataset of electric vehicles that we had for Washington State, We performed correlation and regression analyses to understand this relationship better.
<img width="622" alt="Screenshot 2024-07-16 at 11 24 24 AM" src="https://github.com/user-attachments/assets/87dfd370-55b2-4b0d-92ec-84a0b8cebb64">

[top_4_models.pdf](https://github.com/user-attachments/files/16242925/top_4_models.pdf)

*Statistical Interpretation:*
Slope: The slope of 457.10 indicates that for each additional car model introduced, there are on average 457.10 more registered vehicles.
Intercept: The intercept of -1714.18 is part of the regression equation.
R-squared: The R-squared value of 0.71 suggests that approximately 71% of the variability in the total number of vehicles can be explained by the number of car models available.
P-value: The p-value of 0.00 confirms that the regression model is statistically significant.

![Fig5](https://github.com/user-attachments/assets/e61745cc-8640-4006-9042-65b1e725ec33)

*Conclusion:*
This analysis reveals a strong positive relationship between the availability of car models and the total number of registered electric vehicles per year. Based on this we  can infer that the number of car models available could potentially drive higher vehicle registrations, highlighting the importance of diversity in model offerings to boost electric vehicle adoption. Our hypothesis was proven, as we believed that as demand for EV's increases, supply increases in variability giving the consumer more options. The statistical significance of these findings further further supports the strengtht of this relationship.

*Relationship between Eligibility that Meet Government’s Standards for Tax Credits and Registered Cars*

*Overview:*
The second relationship we wanted to explore, seems ovious and interesting at first. We wanted to see if Goverment programs created a strong enough incentive to increase demand in Electric Vehicles. We filtered the electric vehicle data to determine vehicles eligible for a potential tax credit under the "Clean Alternative Fuel Vehicle (CAFV) Eligibility" criterion. This analysis would help us understand the relationship between eligibility for tax credits and the total number of registered electric vehicles.
We wanted to start narrowing down our analysis by grouping my car data by eligible, and seeing if there is a correlation between this potential tax credit and purchase trends. 

<img width="880" alt="Screenshot 2024-07-16 at 11 25 43 AM" src="https://github.com/user-attachments/assets/b6e68213-a5f7-459a-b437-49434c0a0124">

![Fig1](https://github.com/user-attachments/assets/cd7ca6fa-e9b8-4b8c-9bd3-5df38e4f7e40)

*Statistical Interpretation:*
We ran a linear regression analysis including Pearson's R, to find the strenght of this relationship, and then we ploted my graph accodingly. 
The R-squared value of 0.17 indicates that approximately 17% of the variability in the total number of vehicles can be explained by the number of eligible vehicles. This suggests a weak but positive relationship. There might be other significant factors influencing the total number of vehicles that are not captured by this model.

<img width="997" alt="Screenshot 2024-07-16 at 11 24 52 AM" src="https://github.com/user-attachments/assets/f3a74e95-b820-4bf5-80f6-c48427d12e4e">

![Fig4](https://github.com/user-attachments/assets/738ccad1-b62c-4aa9-a215-bd949d7949c9)

This indicates that for each additional eligible vehicle, there is an estimated average increase of approximately 1.56 in the total number of vehicles. This suggests that vehicles eligible for government incentives or benefits are positively contributing to the total number of registered vehicles

*Conclusion:*
The analysis proves that their a weak positive relationship between the availability of government tax credits for clean alternative fuel vehicles and the total number of registered electric vehicles. Even thought there is an increase in eligible vehicles as the total number of registered vehicles grows, the effect is not very strong. This finding was surpising, as we expected that a potential tax incentive would intice a higher response in demand. This suggests that other factors, for example infrastructure, consumer education or gas price, could be playing a bigger role when it comes to determining electric vehicle growth in the State of Washington. 

 
# **Conclusion:** 
As we embark on this journey of exploration, it is clear that electric vehicles represent not just a mode of transport, but a paradigm shift towards a cleaner, more sustainable future. Through this research project, we succeded in illuminating the factors responsible for contributing to the growth of EVs in Washington State, paving the way for informed decisions and transformative policies and consumer decesions in the years to come.

**Trends**

The code creates a visually distinct bar chart where each bar represents the number of cars for a specific make, and each bar is a different color. This allows for easy differentiation between the various car makes in the dataset. The chart title provides context for the data being displayed, and the y-axis label is removed for a cleaner appearance.
  ![Screenshot 2024-07-13 at 9 48 47 PM](https://github.com/user-attachments/assets/70bb2393-11f0-445a-893f-23a07ab428fb)
![Screenshot 2024-07-13 at 11 14 10 PM](https://github.com/user-attachments/assets/bc3b8dba-779f-4c0a-b295-e55f821da8de)
Code sample:
# Count the number of cars for each make
make_counts = ev_data['Make'].value_counts()

# Generate a color map with a different color for each bar
colors = plt.cm.get_cmap('tab20', len(make_counts))

# Create a bar chart with each bar a different color
plt.figure(figsize=(15, 6))
make_counts.plot(kind='bar', color=[colors(i) for i in range(len(make_counts))])
plt.title('Number of Cars by Make')
plt.ylabel('')  # Remove the default 'Number of Cars' label
plt.show()

We looked at make and model year to see the trends year by year.
<img width="1245" alt="Screenshot 2024-07-17 at 3 38 48 AM" src="https://github.com/user-attachments/assets/ec43053e-ff09-485d-8ac4-9233be35c682">

Top 10 Makes Without Tesla:
The code groups the electric vehicle (EV) data by model year and make, excluding Tesla, to identify trends in EV sales over time.
By focusing on the top 10 makes, it highlights which manufacturers, aside from Tesla, have significant market presence in different years.
The stacked bar chart visually represents the number of EVs sold by make for each model year, allowing for an easy comparison of trends across different manufacturers over time.
Sorting the data within each year in descending order helps in quickly identifying the dominant makes in each year.


We looked at the correlation between Household Median Income and the number of EVs sold. According to this regression analysis, there is a correlation Income and EV purchases with R-squared of 0.55.
![Screenshot 2024-07-14 at 11 06 59 AM](https://github.com/user-attachments/assets/dc609002-c9a2-4a6d-ab78-4296fce137e4)


We looked at the correlation between gasoline prices and the number of EVs sold. According to this regression analysis, there is a modest correlation between gasoline prices and EV purchases.
![Screenshot 2024-07-14 at 11 06 42 AM](https://github.com/user-attachments/assets/aa6d94bc-3268-492f-b7e7-b7c066bfbbdd)



# Ruby_group_project_1
The mian goal of the analysis is to identify the trends and patternts of the electric vehicles in the Washington state.  This project analyzes the growth of electric vehicles (EVs) compared to non-electric vehicles over the years 2020 to 2024 using data from a CSV file named "Electric_Vehicle_Population_Size_History_By_County" from (https://catalog.data.gov/). In order to get the result the following tests were done.The data is visualized in a bar chart showing the annual counts of EVs and non-EVs

# Electric Vehicle Population Analysis
These data illustrating the growth of electric vehicles (EVs) versus non-electric vehicles from 2020 to 2024, The chart compares the total number of electric vehicles to non-electric vehicles over a five-year period (2020-2024). It also helps to understand the adoption rate of electric vehicles in comparison to traditional vehicles. 

# Plot the bar chart with numbers on the bars:

![Screenshot 2024-07-16 211731](https://github.com/user-attachments/assets/63b14646-1602-4c48-bf9f-4684b11da756)

![Graph_5](https://github.com/user-attachments/assets/cba63319-8cb7-4c35-8e26-b30bafbf0adf)

The proportion of electric vehicles over the specified years, highlighting trends and fluctuations in the adoption of electric vehicles.
This segment indicates that in 2017, EVs involved, on average, 6.0% of the total vehicle population. In 2018, EVs made up 6.8% of the total vehicle population.For 2019, the mean percentage of electric vehicles was 9.5%. The year 2020 saw an increase, with electric vehicles accounting for 11.1% of the total.There was a significant rise in 2021, where 17.3% of the vehicles were electric. 
In 2022, the percentage was slightly lower than 2021 at 16.8%. The year 2023 saw a further slight decline to 15.8%. In 2024, the percentage of electric vehicles increased again to 16.8%.

![Screenshot 2024-07-16 212023](https://github.com/user-attachments/assets/91ddf1bd-7a59-472a-8bf3-a6f2a43d7fbf)

![Percentage of Electric Vehicles by Year](https://github.com/user-attachments/assets/e4eb0295-1aa5-4cfc-a1a8-dffaca3313c7)

So, these data explore that there is a noticeable increasing trend in the percentage of electric vehicles from 2017 to 2021. However, after peaking in 2021, the percentage slightly fluctuated in the following years, with a slight decrease in 2022 and 2023, followed by an increase in 2024.

Rural VS Urban 
There has been a noticeable growth in the number of EVs in both urban and rural counties over the years. This growth is more pronounced in urban counties compared to rural counties. The number of non-EVs shows a relatively stable or declining trend, indicating a gradual shift towards electric vehicles. 

![Screenshot 2024-07-16 212318](https://github.com/user-attachments/assets/0cde2b29-b76f-436b-9956-55c620dbd288)
![Screenshot 2024-07-16 212240](https://github.com/user-attachments/assets/4a2b02a8-0062-4f32-ab46-8d7c1145e3e9)

![Screenshot 2024-07-15 225616](https://github.com/user-attachments/assets/03d6fc58-ce61-4f56-bed1-7e628db71ae4)

The bar chart effectively demonstrates the increasing trend of electric vehicle adoption from 2020 to 2024, against a backdrop of declining non-electric vehicle numbers. The analysis reveals a clear trend of increasing EV adoption in Washington State, with urban counties leading the way. While rural counties lag, they are gradually catching up as infrastructure and awareness improve. The insights from this analysis can inform policy decisions and strategic initiatives to promote EV adoption across the state, ensuring a more sustainable and environmentally friendly transportation future.

BEVs and PHEVs

This bar chart displays the number of January registrations for Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) in Washington State from 2017 to 2024. There is a clear increasing trend in the number of registrations for both BEVs and PHEVs from 2017 to 2024. BEV registrations consistently be more than PHEV registrations each year. The gap between the number of BEV and PHEV registrations widens over time, with BEV registrations increasing at a faster rate. Both BEV and PHEV registrations show significant growth, especially noticeable in the years 2023 and 2024.

![Screenshot 2024-07-16 212708](https://github.com/user-attachments/assets/d150da8f-063a-451f-8ec5-799cf290f947)
![Screenshot 2024-07-16 212728](https://github.com/user-attachments/assets/f2d087dd-d7f7-4995-9d98-56675b0eac1c)
![ZEVs Registered of BEV and PHEVs with Department of Licensing ](https://github.com/user-attachments/assets/a1e92fd6-03d7-4d7f-a964-0ebf6af15e77)

As per the data from the department of Licensing, the total number of EVs and plug-ins registered in Washington rose from 91247 in January 2023 to 134692 in January 2024.That is a surprising 43% increase in a single year. The output illustrates the growth and trends in BEV and PHEV registrations in Washington State, highlighting the increasing adoption of electric vehicles over the years.


# Conclusion
The data shows a positive trend in the adoption of electric vehicles in washington state over the years. Looking at data, it can be found that the increasing and steadily rise from 0.96% in 2020 to 2.97% in 2024. The percentage of electric vehicles increases steadily from 0.96% in 2020 to 2.97% in 2024. This indicates a positive trend in the adoption of electric vehicles in Washington State over the years. It can be also analysed that the data and visualization provide a clear picture of the growing adoption of electric vehicles from 2020 to 2024, with urban areas leading the way. To further accelerate EV adoption, especially in rural areas, targeted policies and infrastructure developments are essential. The overall growth in EV percentages is more pronounced in urban areas, which saw an increase from 1.26% in 2020 to 3.92% in 2024. In rural areas, although the growth is slower, there is still a noticeable upward trend, from 0.49% in 2020 to 1.48% in 2024.

Source: 1. https://catalog.data.gov/dataset/electric-vehicle-population-size-history-by-county
       2.  https://ecology.wa.gov/blog/april-2024/a-record-year-for-electric-vehicles-and-plug-in-hybrids-in-washington#:~:text=Digging%20into%20the%20data,up%20from%2013%25%20in%202022
        3. ChatGpt









