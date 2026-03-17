# US-Cars-Sales-2020-2024


# Table of contents
- [Objective](#Objective)
- [Data Source](#Data-Source)
- [Design](#Design)
  - [Dashboard components required](#Dashboard-components-required)
  - [Tools](#Tools)
- [Development](#Development)
  - [Methodology](#Methodology)
  - [Data Exploration](#Data-Exploration)
  - [Data Cleaning](#Data-Cleaning)
- [Visualization](#Visualization)
  - [Dashboard](#Dashboard)
- [Analysis](#Analysis)
- [Conclusion](#Conclusion)


# Objective

The objective of this project is to develop an interactive MS Excel dashboard presenting sales data for new and used vehicles in the United States market. The analysis covers the critical pandemic and post-pandemic periods (2020–2024).
The dashboard will help identify key market shifts within the US automotive sector. 
Through interactive visualizations, this tool wil allow for a rapid assessment of the competitive positioning of leading brands.

# Data Source

What do we need to create this dashboard?

- Vehicle Sales Volume
- Status (new or used)
- Price

Data source: [kaggle.com]([https://docs.fastf1.dev/](https://www.kaggle.com/datasets/juanmerinobermejo/us-sales-cars-dataset?resource=download)).

# Design

## Dashboard components required

What are the questions we want the dashboard to answer:
- How has the total sales volume fluctuated from the peak of COVID (2020) to the post-pandemic era (2024)?
- At what point did prices stabilize or begin to drop after the post-pandemic surge?
- Which segment (New or Used) showed more resilience during the pandemic supply chain shortages?
- Which brands dominate the sales volume in the US market, and has their market share changed since 2020?
- What is the current average market price, and how does it compare to the 5-year historical average?

This may change as we proceed with the analysis.

## Tools

| Tool               | Purpose                               |
|-------------------|---------------------------------------|
| MS Excel+Power Query   | Data evaluation, data cleaning and dashboard creation    |
| GitHub              | Host project documentation        |


# Development

## Methodology

1. Get the data
2. Explore the data
3. Evaluate the data
4. Clean the data
5. Build template for the dashboard
6. Create pivot tables
7. Visualize the data in MS Excel
8. Write documentation

## Data Exploration

What have we learned?
- Data covers the period from 1959 to 2024.
- Some price values are missing.
- We have all the information we need for the dashboard.
- The data is clean and consistent.


## Data Cleaning

What have we done?
- Removed rows with missing price values.
- Filtered the data to include only the years 2020–2024.
  

# Visualization

## Dashboard

### Qualifying Tab

![quali](assets/images/quali_dash.gif)

### Race Tab

![race](assets/images/race_dash.gif)

### Python Tab

![python](assets/images/python_dash.gif)



# Analysis

### 1. What were the qualifying and race results?

Qualifying was won by Lando Norris. Second place was claimed by his teammate Piastri, and third place went to Russell.

The race was won by Leclerc, with McLaren driver Piastri finishing in second place and Norris taking third.


### 2. What was the margin in qualifying?

The first five places remained within 0.186 seconds. After that, the gap to P1 began to grow more quickly, with the biggest gap reaching 2.118 seconds.

### 3. What was the performance of each driver in each sector?

The winner of the qualifying, Norris, had a poor sector 1 time, losing 0.269 seconds to Sainz. However, in the 2nd and 3rd sectors, Norris was the fastest driver and made up for the lost time.

We can also see that McLaren wasn't the best car in sector 1 because Norris's teammate Piastri also had quite a margin to Sainz. Sector 1 in Monza mostly consists of straights, which suggests that McLaren didn't have a fast car on the straights compared to rivals.

### 4. What were the top speeds in qualifying and the race?

The best top speed in qualifying was 353 km/h, achieved by Racing Bulls driver Daniel Ricciardo. In the race, the fastest top speed was 357 km/h, set by Haas F1 Team driver Kevin Magnussen.

It's worth to mention that slower teams had higher top speeds in both qualifying and the race. This could indicate that the top teams can afford to have slower cars on the straights because they can make up time in the corners.

Additionally, the higher top speed values in the race are largely due to slipstreaming and DRS.


### 5. What compounds did the drivers use in the race?
The most common compound was the hard tire, with drivers spending most of their time on it. Softs were almost not used at all; only Stroll drove 2 laps on this tire during the race. Probably to try and achieve the fastest lap of the race.


### 6. How many pit stops did each driver make?
|Driver|No. of pitstops|
|-----|----------------|
|LEC|1|
|PIA|2|
|NOR|2|
|SAI|1|
|HAM|2|
|VER|2|
|RUS|2|
|PER|2|
|MAG|1|
|ALB|1|

As we can see, the most common strategy among the top 10 was a two-stopper. However, the driver who won the race used a one-stop strategy, raising the question of whether the two-stop strategy was the best approach.


### 7. How did tire life affect pace?
For most drivers, lap times on medium tires started to drop after around 10 laps. On the other hand, the hard tires were able to maintain pace for over 30 laps.


### 8. What was the overall race pace for drivers and teams?
"It seems that McLaren had the fastest car, followed by Ferrari. Mercedes and Red Bull had very similar median lap times, and their lap times were more spread out. In the midfield, there were four teams, while Alpine and Kick Sauber had the slowest cars.


# Conclusion

The power of data in motorsport is invaluable. Teams can gather and analyze data to better understand their cars, identify strengths, and pinpoint areas for improvement. Historical data can also play a crucial role in informing race strategies and guiding setup changes. By analyzing past performances, teams can predict tire wear, fuel consumption, and even weather conditions, helping them make more informed decisions during a race. The ability to process and act on real-time data can be the difference between victory and defeat, making data analytics a key factor in modern motorsport success


