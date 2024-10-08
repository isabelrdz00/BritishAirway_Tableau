# British Airways Review Analysis Dashboard 
### Project Overview
This Tableau project showcases a comprehensive interactive dashboard built to analyze British Airways (BA) customer reviews data. The dataset contains detailed feedback from travelers, including their overall experience, service ratings, and specific aspects like food, entertainment, and seat comfort. The purpose of this dashboard is to provide insights into how BA performs across various metrics, which can help identify areas of improvement and highlight positive aspects of the airline's services.

### Key Features
#### Interactive Dashboard with Dynamic Filters: 
- The dashboard is highly interactive, allowing users to select and filter metrics such as overall ratings, food, seat comfort, and more with a simple click.
- Various filters like timeline, seat type, traveler type, and aircraft model are available to narrow down specific insights.

#### Custom Parameters and Metrics:
- The project uses a custom parameter, “Pick a Metric,” to toggle between different metrics like entertainment, food, and service ratings dynamically.
- The parameter-driven dashboard ensures all visuals update simultaneously based on the selected metric, providing a smooth and cohesive user experience.

#### Geographic Analysis:
- A map visual is used to display average ratings by country, with color coding to indicate satisfaction levels.
- The tooltips show the number of reviews for each country, giving more context to the ratings.

#### Review Volume and Satisfaction Analysis:
- Bar charts are used to compare the average ratings for specific metrics (e.g., cabin staff service) against the volume of reviews for each aircraft type.
- A line chart illustrates the average ratings over time, allowing the user to identify trends or seasonality in customer satisfaction.

#### Detailed Filter Options:
- Users can filter reviews by traveler type (e.g., business travelers, couples, solo leisure) and seat type (e.g., economy class, business class).
- Additional filters for aircraft models and continent ensure the user can drill down into specific segments.
  ![Screenshot 2024-10-08 163411](https://github.com/user-attachments/assets/e7bfaa88-7c96-4425-b507-f86cc011b149)


### Tools & Techniques
- **Tableau**: Used for building the dashboard, creating calculated fields, and adding interactivity with parameters and filters.
- **Custom Calculated Fields:** Implemented for creating the "Pick a Metric" parameter and dynamically updating all visualizations based on the selected metric.
- **Data Preparation & Cleansing:** Data was processed to remove null values, group aircraft types with fewer reviews, and format fields for use in Tableau.

### Visualizations
**Map Visualization:**
- Displays average ratings by country.
- The tooltips show both the average rating and the number of reviews per country.

**Line Chart:**
- Shows average ratings over time.
- Helps identify patterns or changes in ratings over months or years.

**Bar Chart:**
- Compares average ratings for selected metrics by aircraft type.
- Shows the volume of reviews alongside the average rating for context.

**Summary Metrics:**
- Key summary metrics at the top of the dashboard for a quick overview of the airline's performance on various aspects (e.g., cabin staff, food, value for money).

**Dynamic Filters:**
- Filters allow users to explore the data from different perspectives (e.g., continent, seat type).
