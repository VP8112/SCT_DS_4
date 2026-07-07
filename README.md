# Traffic Accident Pattern Analysis using US Accidents Dataset

## About the Project

This project analyzes the **US Accidents Dataset** to identify patterns in road accidents across the United States. The analysis focuses on understanding how factors such as **weather conditions, road features, and time of day** influence accident occurrence and severity.

Several visualizations are created to explore accident trends, identify accident hotspots, and study the impact of environmental and road-related conditions.

---

## Project Goal

The main objectives of this project are:

- Analyze accident patterns based on time and weather conditions.
- Study the effect of road features on accident occurrence.
- Identify accident hotspots using geographical coordinates.
- Explore relationships between important numerical variables.
- Present the findings through informative visualizations.

---

## Dataset

**Dataset:** US Accidents Dataset (March 2023)

The dataset contains traffic accident records collected from multiple traffic monitoring sources across the United States.

### Features Used

| Feature | Description |
|---------|-------------|
| Severity | Accident severity level |
| Start_Time | Time when the accident occurred |
| Start_Lat | Latitude |
| Start_Lng | Longitude |
| Temperature(F) | Temperature during the accident |
| Visibility(mi) | Visibility in miles |
| Humidity(%) | Humidity level |
| Wind_Speed(mph) | Wind speed |
| Weather_Condition | Weather condition |
| Junction | Junction nearby |
| Crossing | Crossing nearby |
| Railway | Railway crossing nearby |
| Stop | Stop sign nearby |
| Traffic_Signal | Traffic signal nearby |

---

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn

---

## Data Preparation

Before performing the analysis, the dataset was cleaned by:

- Handling missing values in weather-related columns.
- Converting the accident start time into datetime format.
- Extracting the hour of the day and day of the week.
- Preparing road feature information for analysis.

---

## Analysis Performed

The following analyses were carried out:

- Accident Severity Distribution
- Accident Frequency by Hour
- Accident Frequency by Day of Week
- Weather Condition Analysis
- Visibility Distribution
- Temperature Distribution
- Road Feature Analysis
- Correlation Heatmap
- Accident Hotspot Visualization

---

## Visualizations

The project includes the following visualizations:

- Severity Distribution
- Hourly Accident Trend
- Weekly Accident Trend
- Weather Condition Distribution
- Visibility Analysis
- Temperature Analysis
- Road Feature Distribution
- Correlation Heatmap
- Geographic Accident Hotspots

---

## Folder Structure

```
PRODIGY_DS_04/
│
├── US_Accidents_500k.csv
├── Task04.ipynb
├── README.md
└── output.png
```

---

## Key Findings

Some important observations from the analysis include:

- Most accidents occur during peak commuting hours.
- Poor visibility and unfavorable weather conditions are associated with a higher number of accidents.
- Junctions and traffic signals are among the most common road features near accident locations.
- Accident hotspots are concentrated around densely populated urban regions.
- Weather conditions have a noticeable impact on accident frequency, while severity is influenced by multiple factors.

---

## Conclusion

This project demonstrates how exploratory data analysis can be used to better understand traffic accident patterns. By analyzing weather conditions, road infrastructure, and temporal trends, valuable insights can be obtained that may support road safety improvements and traffic management strategies.

---

## Author

**Vijay Prakash**

Dr. B. R. Ambedkar National Institute of Technology (NIT Jalandhar)  
Jalandhar, Punjab
