# Flight Price Prediction

This project explores the dynamic nature of flight pricing using real-time data scraped from EaseMyTrip over 15 days. It employs data analytics and machine learning to provide insights into pricing patterns and make reliable price predictions.



## Project Overview

The airline industry experiences frequent price fluctuations, making it challenging for travelers to book cost-effective flights. This project utilizes big data techniques to analyze and predict airfare trends, offering valuable insights for passengers and airlines.



## Objective

- Collect live flight data for 15 days from six major Indian cities.
- Identify key pricing patterns based on flight parameters like travel class, stops, and destinations.
- Predict flight prices using machine learning algorithms to aid in cost-effective travel planning.



## Dataset

The dataset includes:
- **Source and Destination Cities**: Delhi, Mumbai, Bangalore, Hyderabad, Goa, and Kolkata.
- **Flight Details**: Airline name, departure and arrival times, flight duration, total stops, travel class.
- **Pricing Information**: Ticket prices segmented by class (Economy, Premium Economy, First Class).

**Data Collection Tools**:
- **Selenium**: For automated scraping from EaseMyTrip.
- **openpyxl**: For data storage in Excel files.



## Technologies Used

- **Programming Languages**: Python
- **Libraries**: Selenium, pandas, matplotlib, seaborn
- **Visualization Tools**: Boxplots, histograms, line charts, sunburst charts



## Key Features

- **Dynamic Pricing Analysis**: Captures real-time fluctuations over 15 days.
- **Visualization of Insights**: Provides trends in pricing, stops, and departure times.
- **Class-Specific Analysis**: Highlights distinctions among Economy, Premium Economy, and First Class pricing.



## Data Cleaning Process

- **Missing Values**: Imputed or removed columns based on the extent of missing data.
- **Flight Names**: Corrected inconsistencies in airline names.
- **Standardization**: Reformatted passenger configurations for clarity.
- **Stops Information**: Simplified stop details to numeric values (e.g., "Nonstop," "1 Stop").
- **Consolidation**: Combined daily datasets into a unified dataset for analysis.



## Visualization Insights

1. **Ticket Price Distribution**:
   - Economy dominates low-price ranges, while First Class caters to high-income travelers.
   - Premium Economy shows broader price variability.

2. **Stops Analysis**:
   - 57.9% flights have 1 stop; 42% are nonstop.
   - Nonstop flights cater to time-sensitive travelers.

3. **Departure Times**:
   - Peak departures occur at 7 AM and 2 PM.
   - Minimal flights during late-night hours (12–4 AM).

4. **Class vs. Price**:
   - Economy has consistent pricing across hours.
   - Premium Economy and First Class show significant variability during peak hours.



## Future Scope

- **Advanced Pricing Models**: Dynamic price prediction based on demand and seasonality.
- **Machine Learning**: Enhanced predictions using algorithms to optimize travel planning.
- **Sustainability Insights**: Analysis of flight patterns to promote eco-friendly practices.
- **Personalized Recommendations**: Tailored suggestions based on passenger preferences.

---
