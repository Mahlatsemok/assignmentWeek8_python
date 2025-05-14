🌍 COVID-19 Global Data Tracker
This project is a comprehensive COVID-19 Global Data Tracker that analyzes and visualizes key pandemic trends using data from Our World in Data. It highlights total cases, deaths, and vaccination progress across selected countries, helping to understand the global and regional impact of the virus.

📁 Dataset
Source: Our World in Data - COVID-19 Dataset
Data File Used: owid-covid-data.csv

🎯 Objectives
Clean and process global COVID-19 data.
Track and visualize pandemic trends over time.
Compare metrics such as infections, deaths, and vaccinations among countries.
Compute and analyze death rates and vaccine coverage.

🌐 Countries Tracked
Zimbabwe
Zambia
Angola
Afghanistan
Albania
Algeria
Andorra
Antigua
Austria
Botswana
Brazil

📊 Key Visualizations
Total COVID-19 Cases Over Time
Total COVID-19 Deaths Over Time
Daily New Cases
Death Rate Over Time (total_deaths / total_cases)
Total COVID-19 Cases by Country (Bar Chart)
Correlation Heatmap between numerical COVID-19 metrics
Cumulative Vaccinations Over Time
Fully Vaccinated Population (% of population)
Vaccinated vs. Unvaccinated (Brazil - Pie Chart)

🧪 Data Handling
Filtered for selected countries of interest.
Handled missing values using linear interpolation.
Converted date columns to datetime objects.
Dropped rows with critical missing values (date, total_cases, etc.).

🛠️ Tools & Technologies
Python
Pandas – Data cleaning and manipulation
Matplotlib – Line, bar, and pie charts
Seaborn – Heatmaps and styled plots

📌 Notes
Latest data for vaccinated/unvaccinated pie chart is pulled for Brazil. If missing, fallback values are used.
Vaccination data shown as percentage of population using people_fully_vaccinated_per_hundred.



