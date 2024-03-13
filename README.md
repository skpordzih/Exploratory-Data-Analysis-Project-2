# Exploratory Data Analysis of World Roller Coaster 

### Project Overview

In this project, I delve into a dataset containing information about roller coasters from various locations around the world. Through exploratory data analysis (EDA) techniques using Python and Pandas, I aim to uncover patterns, trends, and relationships within the data to gain a deeper understanding of the world roller coaster population.
Understanding the characteristics and distribution of roller coasters can provide insights into amusement park trends, engineering advancements, and geographical preferences. 

![coaster_speed_histogram](https://github.com/skpordzih/Exploratory-Data-Analysis-Project-2/assets/163223093/d6de9532-2762-4a44-b6fb-07d3edc52404)



### Data Sources

Rollercoaster Data: The primary dataset used for this analysis is the 'rollercoaster.csv' file.The dataset used in this project contains information about over a thousand roller coasters, including their names, locations, manufacturers, introduction years, speeds, heights, and other relevant attributes. It encompasses a wide range of roller coaster types, statuses, and features.

### Tools

Jupyter Notebook

- Python

  
### Data Preprocessing:

The initial step involved loading the dataset into a Pandas DataFrame, checking for missing values, and cleaning the data to ensure consistency and accuracy.

### Exploratory Data Analysis:

Conducted descriptive statistics, visualizations, and correlation analysis to understand the dataset's characteristics and relationships between variables.

EDA involved exploring the data to answer questions such as:

- What are the locations with the fastest roller coasters?
- Is there any relationship between the year a coaster was introduced and its speed or height?
- Are there any geographical patterns in coaster distribution, such as clustering of coasters in certain regions?

### Data Analysis

```python

manufacturer_counts = df['Manufacturer'].value_counts()
top_manufacturers = manufacturer_counts.head(10)  # Assuming you want the top 10 manufacturers
print("Top Coaster Manufacturers by Number of Coasters Produced:")
top_manufacturers

```

### Findings

The analysis results are summarized as follows:
- The top locations with the fastest roller coasters include Six Flags Magic Mountain, Cedar Point, and Busch Gardens Williamsburg.
- Vekoma, Bolliger & Mabillard, and Intamin are among the top coaster manufacturers by the number of coasters produced.
- Steel coasters generally have higher average speeds compared to wooden coasters.
- Speed and height have a relatively strong positive correlation, while speed and g-force also show a moderately positive correlation. However, the relationship between speed and inversions is very weak.

### Recommendations
Based on the analysis, I recommed the following actions:
- Theme parks in locations such as Cedar Point and Busch Gardens Williamsburg could leverage their fast coasters as major attractions to draw in more visitors.
- Manufacturers like Vekoma and Bolliger & Mabillard could continue to capitalize on their market dominance by focusing on innovation and quality in coaster design.
- Theme parks in regions with sparse coaster presence might consider investing in new coaster installations to attract visitors and enhance their offerings.
- Future coaster designs could prioritize aspects such as speed, height, and g-force to deliver thrilling experiences while considering safety and comfort for riders.
- Further research could explore additional factors influencing coaster design and popularity, such as theme integration, ride duration, and special features like VR elements.

🎢
🎆
