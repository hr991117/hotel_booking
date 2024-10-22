# Hotel Booking Data Analysis

This project focuses on analyzing hotel booking data to gain insights into customer behavior, booking cancellations, and pricing strategies. The data spans multiple years and includes key features like hotel type, lead time, customer demographics, booking status, and more.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Analysis Highlights](#analysis-highlights)
- [Conclusion](#conclusion)

## Project Overview
The goal of this project is to:
- Explore booking trends in city and resort hotels.
- Analyze cancellation patterns and identify the factors influencing them.
- Visualize key metrics like Average Daily Rate (ADR), booking status by month, and cancellation rates.

## Technologies Used
- **Python 3.8+**
- **Pandas**: Data manipulation.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Jupyter Notebook**: For code and data exploration.

## Dataset
The dataset contains 119,390 entries and 36 features, including:
- **Hotel types** (City Hotel, Resort Hotel)
- **Lead time**: The number of days between the booking date and the arrival date.
- **Booking status**: Whether the booking was canceled or not.
- **Customer details**: Country, number of adults, children, etc.
- **Pricing information**: ADR (Average Daily Rate) and total of special requests.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Hotel_Booking_Data_Analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Hotel_Booking_Data_Analysis
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Hotel_Booking_Analysis.ipynb
   ```

## Project Structure
```
├── data/                           # Contains dataset
├── Hotel_Booking_Analysis.ipynb    # Main Jupyter Notebook for analysis
├── README.md                       # Project description and setup instructions
├── hotel.csv                       # Raw Data Set
└── report.pdf                      # Redport file
```

## Usage
- Open the `Hotel_Booking_Analysis.ipynb` notebook.
- Run the code cells to load the dataset, clean the data, and generate insights.
- Visualize booking trends, cancellation patterns, and other important metrics.

## Analysis Highlights
Some key insights from the analysis:
- **Cancellation Rates**: Approximately 37% of the bookings are canceled.
- **Hotel Type Analysis**: Resort hotels have a lower cancellation rate (28%) compared to city hotels (42%).
- **Average Daily Rate (ADR)**: City hotels generally have a higher ADR than resort hotels, especially during peak seasons.
- **Monthly Analysis**: The busiest months for hotel bookings are August and July, with higher cancellation rates in these months.
- **Top Canceling Countries**: The top 10 countries with the highest cancellation rates are visualized using a pie chart.

## Visualizations
- **Reservation Status by Hotel Type**: Compares cancellation rates between resort and city hotels.
- **ADR Trends**: Visualizes ADR over time for both canceled and non-canceled bookings.
- **Booking Cancellations by Month**: Shows seasonal trends in cancellations.
- **Country-wise Cancellations**: Displays the top countries contributing to hotel booking cancellations.

## Conclusion
Based on the analysis, several trends emerge:
- **Resort hotels** experience fewer cancellations, which could be attributed to their appeal for longer leisure stays, as opposed to city hotels that might see more last-minute or business-related cancellations.
- **Higher lead times** are generally linked to a lower cancellation rate, indicating that customers who plan their trips well in advance are more likely to complete their stay.
- **Seasonal trends** suggest that pricing and cancellation policies should be adjusted during peak booking months to manage the higher volume of cancellations and optimize revenue.
- **Country-specific cancellations** highlight the need for targeted strategies to reduce cancellation rates, especially for customers from top canceling regions.

These insights can help hotel management refine their marketing strategies, adjust pricing, and implement better cancellation policies to reduce the number of cancellations and optimize revenue.

