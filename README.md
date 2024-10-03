# Electric Vehicle Charging Patterns Analysis

This project focuses on analyzing and modeling electric vehicle (EV) charging patterns using a dataset that provides detailed insights into EV user behavior, energy consumption, and charging station utilization. The dataset contains 1,320 samples of charging session data, which have been explored, transformed, and modeled to uncover trends and predictive insights.

## About the Dataset

This dataset provides a comprehensive analysis of electric vehicle charging behavior and patterns, including important metrics related to charging sessions, vehicle specifications, and user habits. The dataset allows for the investigation of key features that impact charging durations, energy usage, and user cost.

### Key Features:

1. **User ID**: Unique identifier for each user.
2. **Vehicle Model**: The model of the electric vehicle being charged (e.g., Tesla Model 3, Nissan Leaf).
3. **Battery Capacity (kWh)**: Total battery capacity of the vehicle in kilowatt-hours.
4. **Charging Station ID**: Unique identifier for the charging station used.
5. **Charging Station Location**: Geographic location of the charging station (e.g., New York, Los Angeles).
6. **Charging Start Time**: Timestamp indicating when the charging session began.
7. **Charging End Time**: Timestamp indicating when the charging session ended.
8. **Energy Consumed (kWh)**: Total energy consumed during the charging session, measured in kilowatt-hours.
9. **Charging Duration (hours)**: Total time taken to charge the vehicle, measured in hours.
10. **Charging Rate (kW)**: Average power delivery rate during the charging session, measured in kilowatts.
11. **Charging Cost (USD)**: Total cost incurred for the charging session, measured in US dollars.
12. **Time of Day**: Time segment when the charging occurred (e.g., Morning, Afternoon).
13. **Day of Week**: Day of the week when the charging occurred (e.g., Monday, Tuesday).
14. **State of Charge (Start %)**: Battery charge percentage at the start of the charging session.
15. **State of Charge (End %)**: Battery charge percentage at the end of the charging session.
16. **Distance Driven (since last charge) (km)**: Distance traveled since the last charging session, measured in kilometers.
17. **Temperature (°C)**: Ambient temperature during the charging session, measured in degrees Celsius.
18. **Vehicle Age (years)**: Age of the electric vehicle, measured in years.
19. **Charger Type**: Type of charger used (e.g., Level 1, Level 2, DC Fast Charger).
20. **User Type**: Classification of user based on driving habits (e.g., Commuter, Long-Distance Traveler).

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Conducted initial data exploration to understand the distribution of key features.
- Visualized charging patterns, vehicle usage, and cost trends across different geographic locations and vehicle models.
- Identified key factors influencing charging duration, energy consumption, and overall charging cost.

### 2. Feature Engineering and Transformation
- Performed feature transformations, including one-hot encoding for categorical features such as vehicle model, charging station location, and charger type.
- Engineered new features, such as calculating the efficiency of energy consumed per kilometer traveled and creating time-based categories for charging sessions.
- Applied scaling to numerical features like energy consumption, charging cost, and temperature for modeling purposes.

### 3. Unsupervised Learning Techniques
- Applied clustering techniques to identify patterns in user behavior and vehicle usage.
- Grouped users based on their charging habits (e.g., time of day, day of week, charging duration) and charging efficiency.
- Used Principal Component Analysis (PCA) to reduce dimensionality and better visualize patterns within the dataset.

## Results and Insights
- **Vehicle Model Trends**: Tesla Model 3 and Nissan Leaf showed distinct charging patterns, with the former having a higher average charging cost due to its larger battery capacity.
- **Location-Based Patterns**: Urban charging stations (e.g., in Los Angeles and New York) had significantly higher charging durations compared to suburban areas.
- **User Behavior**: Long-distance travelers tended to use fast chargers more frequently, while commuters showed preference for slower, more cost-efficient chargers.
- **Seasonal Effects**: Charging patterns varied with temperature, as colder temperatures correlated with increased charging times and lower charging efficiency.

## Tools and Libraries Used
- **Python**: For data manipulation and analysis.
- **Pandas**: For data wrangling and feature engineering.
- **Seaborn & Matplotlib**: For data visualization.
- **Scikit-learn**: For applying unsupervised learning techniques and feature transformation pipelines.

## Conclusion
This project provides valuable insights into the patterns of electric vehicle charging behavior and the factors influencing energy consumption, cost, and charging efficiency. The analysis reveals opportunities for optimizing charging infrastructure and improving user experience by identifying location-specific and vehicle-specific trends.

---

This README file outlines the key aspects of your Electric Vehicle Charging Patterns project.