# Olympics Medal Tally Dashboard (1896–2024)

This project is an interactive Power BI dashboard that visualizes Olympic medal data from 1896 to 2024 (excluding 2018). It provides insights into country-wise performance, medal distribution by type, gender-based trends, sport-wise medal patterns, and changes over time.

## 📊 Dashboard Features

The Power BI report includes multiple pages with the following key insights:

### 1. Overall Medal Tally
- Total medals won by each country
- Medal distribution by type (Gold, Silver, Bronze)
- Key statistics: total medals, countries, and Olympic events

### 2. Trends Over Time
- Year-wise medal count progression
- Gender participation and medal trends
- Sport-wise medal trends over decades

### 3. Country Profiles
- Detailed view of a selected country's Olympic performance
- Top athletes, sport-specific medal counts, and performance over time
- Map visualization of host cities where medals were won

## 🧹 Data Preparation

The dataset used was sourced primarily from the [Kaggle Olympic History Dataset](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results). Additional cleaning and merging steps were taken:

- Filtered out rows with no medal awarded
- Standardized fields (e.g., NOC, Sport, Event)
- Merged supplementary files to enrich NOC-region mappings
- Excluded 2018 Winter Olympics due to unavailability of clean, consistent data

Final cleaned data was loaded into Power BI and modeled with DAX measures for key metrics and interactivity.

## 🧠 Key Technologies Used

- **Power BI** – For data visualization and interactive reporting
- **DAX** – For calculated fields, KPIs, and filtered measures
- **Power Query** – For data cleaning and transformation


## 🔍 Limitations

- 2018 Winter Olympics data is not included due to lack of reliable structured data
- Medals-per-capita analysis not implemented due to the absence of integrated population data

## 📎 License

This project is open-source and available under the [MIT License](LICENSE), unless the original dataset source specifies otherwise.

## 🔗 References

- [Kaggle: Olympic History Dataset](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
- [International Olympic Committee (IOC)](https://olympics.com/en/)

## 📬 Contact

For questions, suggestions, or collaborations, feel free to reach out:
- **Name**: Atharva Amrutkar 
- **Email**: atharvaamrutkar5@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/atharva-amrutkar-a51656329?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
