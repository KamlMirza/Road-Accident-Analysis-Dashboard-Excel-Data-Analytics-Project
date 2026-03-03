# Road Accident Analysis Dashboard

## Project Objective

The primary goal of this project was to transform a complex dataset of road accident records into a structured, interactive visual dashboard. By leveraging Excel’s data processing and visualization capabilities, the project identifies high-risk factors such as road types, vehicle categories, and environmental conditions to generate actionable insights for urban planners and safety investigators.

## Dashboard Preview
<img width="1226" height="673" alt="Screenshot 2026-02-16 183701" src="https://github.com/user-attachments/assets/4eb31273-d1a3-444f-8375-1817f46f0269" />







## Data Analytics Approach

To ensure data accuracy, clarity, and usability, the following structured workflow was implemented:

### 1. Data Cleaning and Preparation
- Standardized date formats for time-series consistency.
- Categorized raw casualty counts into defined severity levels.
- Handled missing values in **Weather** and **Road Surface** columns.
- Verified data consistency across categorical variables.

### 2. Data Modeling
- Used **Pivot Tables** to aggregate casualty data across multiple dimensions:
  - Time (Year, Month)
  - Severity (Fatal, Serious, Slight)
  - Location (Urban, Rural)
- Created calculated fields to determine percentage distribution of each severity level.
- Developed summary metrics to support KPI visualization.

### 3. Visual Design and User Experience
- **KPI Cards:** Displayed total casualties and breakdown by Fatal, Serious, and Slight categories.
- **Trend Analysis:** Implemented a Year-over-Year (YoY) line chart comparing 2021 and 2022 casualty trends.
- **Comparative Analysis:** Used bar charts and treemaps to visualize road type and surface condition impact.
- **Interactive Filter Panel:** Integrated slicers (Year, Weather, Wind) to enable dynamic scenario analysis.

## Key Results and Insights

The analysis of **417,883 total casualties** revealed the following major findings:

### 1. Severity Distribution

- **Slight (84.1%)**: The majority of accidents result in minor injuries.
- **Serious (14.2%)**: A considerable proportion requires medical treatment.
- **Fatal (1.7%)**: Although the smallest percentage (7,135 cases), these incidents demand the highest safety priority.

### 2. Risk Factors by Infrastructure

#### Road Type
- **Single Carriageways** account for approximately **309.7K casualties**, making them the highest-risk road type.
- **Dual Carriageways** account for **67.4K casualties**, significantly lower in comparison.

#### Surface Conditions
- **Dry roads** show the highest number of recorded casualties.
- This suggests potential behavioral factors such as higher speeds or overconfidence in favorable driving conditions.

### 3. Vehicle and Location Insights

#### Vehicle Type
- Cars are involved in nearly **80%** of total casualties, making them the dominant vehicle category in accident statistics.

#### Location Distribution
- **Urban Areas:** 255.9K casualties
- **Rural Areas:** 162.0K casualties

Higher urban casualty rates are likely influenced by traffic density, intersections, and pedestrian activity.

### 4. Temporal Trends

- Casualty patterns in 2022 remained relatively consistent with 2021.
- A recurring peak is observed in **November**, potentially due to:
- Reduced daylight hours
- Weather transitions
- Increased traffic during seasonal periods

# Author & Contact

**Kaml Mirza**  
LinkedIn: www.linkedin.com/in/kaml-mirza-38223034a
