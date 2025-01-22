# # Project 3: Analyzing Air Traffic Patterns in Florida

## Introduction
Analyzing air traffic data is crucial for understanding congestion, delays, and optimal routing. This project aims to identify patterns and trends in the flow of air traffic in Florida, evaluate the performance of air traffic operations, and analyze the impact of weather conditions and climate change on flight operations.

## Objectives
- **Identify Traffic Patterns**: Analyze air traffic data to identify patterns and trends in the flow of air traffic.
- **Assess Performance**: Evaluate the performance of air traffic operations, including congestion and delays.
- **Mitigate Congestion**: Identify busy regions and times to mitigate congestion based on data insights.
- **Climate Impact**: Analyze the impact of weather conditions on fuel consumption and climate change.

# How to Interact with Air Traffic Analysis
- create an API key on stack aviation. For the free version you will receive only 100% of usuage each month. Therefore, please pull your data accordingly.
- Once you sign up and create an API key from stack aviation. Enter your API key in the "API_KEY_HERE" code on the first tab.
- Once you perform an API call, you can run your data accordingly. 
- Air traffic data is real time, so the data might change from day-to-day usuage.


## Data Sources
- FlightAware (flight tracking data for Major Airports)
- Flightradar24
- Aviation Stack (flight tracking data for Major Airports)

## Methodology
### Data Collection
- Collect real-time and historical data from listed sources.
- Use APIs to gather data on flights, city data, and arrival and departure times.

### Data Cleaning
- Handle missing values, outliers, and ensure data consistency.
- Replace 'Unknown' values with appropriate placeholders or `NaN`.

### Data Analysis
- Perform descriptive analysis to summarize the data and identify initial insights.
- Conduct trend analysis to analyze the flow, congestion, and delays.
- Build predictive models to forecast delays.

### Data Storage
- Use SQL and PostgreSQL for data storage and querying.

### Programming Languages and Libraries
- **Python**: Data analysis and modeling.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib** and **Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning for predictive modeling.
- **Folium**: Data visualizations

## Advanced Analysis
### Real-time Data Processing
- Set up real-time data processing using foilum and SQL.

### Predictive Modeling
- Build machine learning models to predict delays based on various factors such as weather, time, and air traffic.

### Visualization Enhancements
- Create interactive visualizations using `folium` and `plotly` to represent air traffic congestion and routing optimizations.

# What is Folium?
- Follium is used in our code to create interactive visualization for airtraffic.Folium makes it easy to visualize data that’s been manipulated in Python on an interactive leaflet map.

# What is Seaborn?
- Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

## Repository Link
[Project 3 Repository](https://github.com/ElizabethA28/Project-3)

## Documentation
Ensure thorough documentation of the entire process, from data collection to advanced analysis, to maintain transparency and reproducibility. Maintain version control using GitHub and include comprehensive explanations of all analyses and findings.

# Ethical Considerations
In this project we considered ethical consideration in data collection primarily focusing on data privacy interms of keeping any API keys private. As well as not sharing API keys on online platforms and taking measures to prevent unauthorized access to these api keys. We also focused on ensuring transparency about the data that was collected by only using real-time data and not creating data that was not permisssible. Lastly, we have been transparent throughout the project that this is real-time data and all data collected came from reputable sources such as stackaviation.

## Conclusion
This project will provide valuable insights into air traffic patterns in Florida, helping to optimize routing, mitigate congestion, and understand the impact of weather conditions on flight operations. By leveraging advanced data analysis and machine learning techniques, we can improve the effi
