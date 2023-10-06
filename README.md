# Midterm Project

## Authors:  

- **Nico San Pedro**
- **Paul Abah**
- **Leo Fonseca (me)**

## Dataset file: [MMDA_TrafficIncidents_Tab.xlsx](https://github.com/leoaugusto1976/Midterm_Project/blob/main/data/MMDA_TrafficIncidents_Tab.xlsx)

# Traffic Incidents Analysis in the Philippines

Welcome to the Traffic Incidents Analysis project, where we explore and analyze traffic incident data from various cities in the Philippines. This dataset provides valuable insights into traffic-related incidents, their locations, and various factors contributing to these incidents.

## Dataset Overview

- **Date**: The date when the incident occurred.
- **Time**: The time of day when the incident took place.
- **City**: The city in the Philippines where the incident occurred.
- **Location**: Specific location or area within the city where the incident was reported.
- **Latitude** and **Longitude**: Geographical coordinates of the incident location.
- **High_Accuracy**: Indicates whether the incident location was recorded with high accuracy.
- **Direction**: Directional information related to the incident.
- **Type**: The type or nature of the traffic incident.
- **Lanes_Blocked**: Information about the number of lanes blocked as a result of the incident.
- **Involved**: Details about the vehicles or parties involved in the incident.
- **Tweet**: Any relevant tweets or social media updates related to the incident.
- **Source**: The source or channel through which the incident information was reported.
- **Incident Type**: The specific category or classification of the traffic incident.
- **WeekDay**: The day of the week when the incident occurred.
- **WeekDayIndex**: An index representing the day of the week.
- **RoundedTime**: Time of day rounded to a specific interval.
- **Hour_of_the_day**: The hour of the day when the incident took place.

## Project Goals

In this project, we aim to leverage this rich dataset to gain insights into traffic patterns, incident frequencies, and factors influencing traffic incidents in the Philippines. By exploring and visualizing this data, we seek to identify trends, hotspots, and potential areas for traffic management improvements. Our analysis may contribute to a better understanding of traffic-related challenges in the region and inform strategies for safer and more efficient transportation systems.

On this data-driven journey as we delve into the world of traffic incidents in the Philippines and uncover valuable insights that can help improve road safety and traffic management.

## Process

1. We conducted a thorough analysis of the dataset to pinpoint key insights, facilitating the development of an interactive dashboard aimed at enhancing user understanding and decision-making.  
As part of our data preparation, we meticulously addressed missing values. Additionally, we introduced a new data column named 'Hour_of_the_day.' This classification categorizes incidents into 'Morning,' 'Afternoon,' 'Evening,' and 'Night,' providing a clearer representation of when these incidents typically occur throughout the day.

2. To create the dashboards, we develops these graphs:

- Traffic Incidents  
Type: Line graph  
This graph provides a monthly overview of traffic incidents, with the X-axis representing each month and the Y-axis indicating the number of reported accidents. By visualizing incident trends over time, we can identify monthly variations and patterns in accident frequency, contributing to a better understanding of road safety dynamics. 
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet1)

- Number of Accidents Reported by Weekday  
Type: Treemap  
This graph presents the distribution of reported accidents based on the day of the week. It helps us understand which weekdays experience higher or lower accident rates, shedding light on potential patterns in road safety. By analyzing accident data in this way, we can identify weekdays with increased accident incidents and explore factors contributing to these fluctuations.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet2)

- Number of Accidents Reported by Month  
Type: Treemap  
This graph provides an overview of accident reporting throughout the year, showcasing the total number of accidents reported each month. It allows us to identify any monthly patterns or trends in accident occurrences, helping us better understand the seasonal variations in road safety incidents. Analyzing accident data by month can aid in the development of targeted safety measures and resources during specific times of the year.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet3)

- Number of Accidents Reported by Time of Day  
Type: Pie chart  
This graph visually represents the frequency of reported accidents categorized by different times of the day, namely 'Morning,' 'Afternoon,' 'Evening,' and 'Night.' It offers insights into the distribution of accidents across these time periods, helping us understand when road incidents are most prevalent. Analyzing accidents by time of day can assist in optimizing safety measures and resource allocation during specific hours.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet4)

- Traffic Incidents by City  
Type: Bar chart
This graph provides an overview of traffic incidents reported in various cities. It visualizes the distribution of incidents across different urban areas, helping us identify cities with higher or lower incident rates. This information can be valuable for city officials and planners to prioritize safety measures and traffic management strategies in specific locations.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet5)

- Number of Accidents by City  
Type: Heatmap  
This heatmap visualization depicts the density of traffic accidents across different cities. The intensity of color signifies the number of incidents, with darker shades indicating higher accident frequencies. It offers a quick and visually intuitive way to identify cities with elevated accident rates, allowing for focused attention and targeted safety interventions in areas with greater traffic incident activity.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet6)

- Number of Accidents Reported by Direction  
Type: Bar chart  
This graph illustrates the distribution of reported accidents categorized by different directions, including 'Eastbound' (EB), 'Northbound' (NB), 'Southbound' (SB), 'Westbound' (WB), and other directions. It provides insights into the prevalence of accidents in each direction, helping us understand traffic incident patterns and potential areas for improved safety measures.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet7)
    - **Direction options**:  
        - **CLOSED**: Typically, this indicates that a road or lane is closed to traffic, often due to construction, accidents, or other temporary obstructions. It signifies that vehicles cannot pass through the specified direction.
        - **EB**: This stands for "Eastbound," indicating that the traffic or route is oriented in the direction of the east.
        - **NB**: "NB" represents "Northbound," signifying that the traffic or route is oriented in the direction of the north.
        - **SB**: This stands for "Southbound," indicating that the traffic or route is oriented in the direction of the south.
        - **WB**: "WB" represents "Westbound," signifying that the traffic or route is oriented in the direction of the west.
        - **CLARA**, **DAR**, **PAX**: These abbreviations appear to represent specific location, route, or road designations. However, without additional context or a defined reference, it's challenging to ascertain their precise meanings. In our analysis, we were unable to find a specific definition or reference for these abbreviations, which limits our ability to provide a concrete interpretation.

- Number of Accidents Reported by Incident Type  
Type: Pie chart  
This graph displays the count of reported accidents grouped by various incident types. It offers an overview of the most common types of traffic incidents, helping to identify the nature of accidents frequently reported. By analyzing accident data by incident type, we can focus on addressing specific safety concerns and implementing targeted prevention measures.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet8)

- Incidents Heat Map  
Type: heatmap  
This heat map visually represents the distribution of traffic incidents over the course of a month, with columns representing individual days and rows representing days of the week. The intensity of color indicates incident frequency, with darker shades highlighting days and times when accidents are more prevalent. This visualization helps us identify any recurring patterns or hotspots in traffic incidents, facilitating better insights into when and where accidents tend to occur.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet9)

- Top Incidents 
Type: Table  
This graph provides a detailed breakdown of traffic incidents by type, displaying the number of incidents for each specific incident category. The last row represents the total count of all incidents. This breakdown allows for a clear understanding of the composition of reported incidents, highlighting the most prevalent incident types and their contribution to the overall incident count.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet10)

- Incidents Trend  
Type: Area chart  
This area chart visually depicts the trend in traffic incidents over time, organized by quarters of the year. It provides a dynamic view of how incident frequencies have changed throughout the year, highlighting any seasonal patterns or trends. Analyzing incidents by quarter allows us to identify periods of increased or decreased incident activity, offering insights into the dynamics of road safety over time.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet11)

- Vehicle Involvement Breakdown  
Type: Bar chart  
This bar chart provides a clear breakdown of traffic incidents based on the types of vehicles involved. Each bar represents a specific vehicle category, and the height of each bar corresponds to the number of incidents in which that type of vehicle was involved. This visualization helps us understand the relative contribution of different vehicle types to overall traffic incidents, providing insights into the dynamics of road safety.  
[Click here to see the Graph on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Sheet13)

In our comprehensive analysis of traffic incident data from various cities in the Philippines, we've uncovered valuable insights into the dynamics of road safety. By exploring the data through a series of visualizations, we've gained a deeper understanding of the factors contributing to traffic incidents, their distribution across time, locations, and incident types.

Key findings from our analysis include:

**Incident Trends**: We've identified patterns and trends in incident reporting, including seasonal variations and peak incident times.

**Directional Insights**: The distribution of incidents by direction provides valuable information for traffic management and safety measures.

**Incident Types**: Understanding the breakdown of incident types allows for targeted preventive actions and safety campaigns.

**City-Specific Analysis**: By examining incidents across different cities, we can prioritize safety efforts in areas with higher incident rates.

**Time-of-Day Analysis**: Categorizing incidents by the time of day offers insights into when accidents are most likely to occur.

Now, armed with these insights, we move forward to the Dashboard phase of our project. The dashboard will offer an interactive and user-friendly platform for stakeholders and decision-makers to explore this data further, enabling data-driven decisions to enhance road safety in the Philippines.

# Overall

In our comprehensive analysis of traffic incident data from various cities in the Philippines, we've uncovered valuable insights into the dynamics of road safety. By exploring the data through a series of visualizations, we've gained a deeper understanding of the factors contributing to traffic incidents, their distribution across time, locations, and incident types.

**Key findings from our analysis include**:

- **Incident Trends**: We've identified patterns and trends in incident reporting, including seasonal variations and peak incident times.

- **Directional Insights**: The distribution of incidents by direction provides valuable information for traffic management and safety measures.

- **Incident Types**: Understanding the breakdown of incident types allows for targeted preventive actions and safety campaigns.

- **City-Specific Analysis**: By examining incidents across different cities, we can prioritize safety efforts in areas with higher incident rates.

- **Time-of-Day Analysis**: Categorizing incidents by the time of day offers insights into when accidents are most likely to occur.

Now, armed with these insights, we move forward to the Dashboard phase of our project. The dashboard will offer an interactive and user-friendly platform for stakeholders and decision-makers to explore this data further, enabling data-driven decisions to enhance road safety in the Philippines.

In the next phase as we transform these findings into actionable insights through our interactive dashboard.

# Dashboards

## Traffic Incidents Dashboard

Welcome to the Traffic Incidents Dashboard, your comprehensive tool for exploring and analyzing traffic incident data from various cities in the Philippines. This interactive dashboard brings together a wealth of insights to help you understand the dynamics of road safety.

### Explore Traffic Incident Trends

- **Temporal Insights**: Gain insights into how traffic incidents have evolved over the years, including quarterly, monthly, and daily patterns.

- **Geographical Distribution**: Explore incident data across different cities and regions to identify areas with higher incident rates.

- **Time-of-Day Analysis**: Understand when accidents are most likely to occur throughout the day, enabling targeted safety measures.

### Customized Data Views

This dashboard provides flexibility with interactive filters:

- **City Filter**: Focus on incidents within a specific city to assess localized road safety trends.

- **Weekday Filter**: Examine incident data for specific days of the week to uncover weekly patterns.

- **Time-of-Day Filter**: Tailor your analysis to particular times of the day for precise insights.

[Click here to see the Traffic Incidents Dashboard on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Dashboard1)

## Comprehensive Traffic Analysis Dashboard

Welcome to the Comprehensive Traffic Analysis Dashboard, your one-stop platform for in-depth exploration and analysis of traffic incident data across various cities in the Philippines. This interactive dashboard is designed to offer a holistic view of road safety and traffic dynamics.

### Uncover Insights with Ease

- **City-Wide Overview**: Explore the distribution of traffic incidents by city to identify areas of concern and prioritize safety measures.

- **Incident Types**: Dive into the breakdown of incident types to understand the nature of traffic-related issues and plan targeted interventions.

- **Temporal Patterns**: Analyze incidents over time, identifying trends, seasonal variations, and hotspots on an interactive heat map.

- **Vehicle Involvement**: Gain insights into the types of vehicles most frequently involved in incidents and tailor safety measures accordingly.

### Flexible Filters for Precise Analysis

Customize your analysis with interactive filters:

- **Quarter Filter**: Focus on specific quarters to assess seasonal variations and year-round trends.

- **Incident Type Filter**: Isolate specific incident types for specialized investigations and prevention strategies.

- **City Selection**: Drill down into data for a particular city, enabling tailored approaches to road safety.


[Click here to see the Comprehensive Traffic Analysis Dashboard on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Dashboard2)  

## Presentation Dashboard

Welcome to the Comprehensive Traffic Analysis Dashboard, your central hub for exploring and dissecting traffic incident data from various cities in the Philippines. This dynamic dashboard encompasses a wide range of visualizations and insights to facilitate a deeper understanding of road safety.

### Key Insights and Visualizations

- **Incident Number**: Get an overall count of traffic incidents, providing a snapshot of the total incidents recorded.

- **Incidents by Month**: Explore the distribution of incidents over months, identifying monthly trends and variations.

- **Incidents by Year**: Delve into incident data over the years to detect long-term patterns and changes.

- **Heatmaps**: Visualize incident hotspots with interactive heatmaps:
  - **Heatmap**: Gain a spatial perspective of incidents across different regions and cities.
  - **City Heatmap**: Zoom in on individual cities to pinpoint areas with higher incident rates.
  - **Weekday Heatmap**: Examine incidents by the day of the week, uncovering weekly patterns.

### Data-Driven Decision Making

This dashboard equips you with the tools needed to make informed decisions, implement targeted safety measures, and enhance road safety across the Philippines. Whether you're a city planner, safety advocate, or decision-maker, these visualizations empower you to prioritize actions where they matter most.  

[Click here to see the Presentation Dashboard on the Tableau Public website](https://public.tableau.com/app/profile/leo.fonseca/viz/TrafficAccidentsMidtermProject/Dashboard3) 

# Project Conclusion

In our journey through the world of traffic incident data analysis across the cities of the Philippines, we've uncovered valuable insights, patterns, and trends that shed light on road safety dynamics. From the inception of data exploration to the creation of interactive dashboards, our project has been a comprehensive effort to enhance road safety and inform data-driven decisions.

## Key Accomplishments

- **Data Exploration**: We embarked on a meticulous journey through the dataset, unearthing critical insights into traffic incidents, their types, locations, and temporal patterns.

- **Visualization Excellence**: We leveraged the power of data visualization to translate complex data into clear, actionable insights. Through various graphs and heatmaps, we provided a dynamic representation of traffic incident data.

- **Interactive Dashboards**: We developed two interactive dashboards, each tailored to address different aspects of road safety. These dashboards enable stakeholders to explore data, identify trends, and make informed decisions.

- **Filtering Capabilities**: The inclusion of interactive filters in our dashboards allows for precise data exploration, enabling users to focus on specific cities, incident types, and time frames.

## Empowering Road Safety

Our project goes beyond data analysis; it empowers decision-makers, city planners, and safety advocates to take proactive measures to enhance road safety. By understanding the dynamics of traffic incidents, we pave the way for:

- **Targeted Interventions**: Identifying areas with higher incident rates allows for the prioritization of safety measures where they are needed most.

- **Preventive Strategies**: Analyzing incident types and temporal patterns aids in the development of targeted prevention campaigns and safety strategies.

- **Informed Decision-Making**: Our interactive dashboards equip stakeholders with the tools they need to make data-driven decisions and allocate resources effectively.

## A Data-Driven Future

As we conclude this project, we look ahead to a future where data-driven insights continue to shape road safety efforts. We believe that our work will contribute to safer roads, fewer incidents, and improved transportation systems for communities across the Philippines.

Thank you for joining us on this data-driven journey, and we encourage you to use the insights gained here to create a safer and more efficient road network for all.