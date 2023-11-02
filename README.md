# HR-Employee-Attrition-Dashboard

The HR Employee Attrition Dashboard is a Streamlit web application for exploring and analyzing HR data. This dashboard provides a user-friendly interface to filter and visualize HR data, including basic statistics and visualizations.

## Prerequisites

Before running the application, ensure you have the following libraries installed in your Python environment:

- Streamlit
- Pandas
- Matplotlib
- Seaborn

## Usage

1. Clone this repository or download the "HR-Employee-Attrition.csv" dataset to the same directory as your Streamlit script.

2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

1. Open a web browser and navigate to the provided local URL (usually something like http://localhost:8501).

2. Use the sidebar filters to select the department, job role, education level, and gender to filter the HR data.

3. Explore the HR data with the following features:
   - Basic HR statistics such as total employees and average age.
   - A bar chart for employee counts by business travel.
   - A histogram showing the age distribution.
   - A pie chart displaying the attrition rate.

4. Scroll down to view the filtered employee data in a tabular format.

## Features
- Filter HR data based on department, job role, education level, and gender.
- Visualize employee counts by business travel and age distribution.
- Calculate and display the attrition rate as a pie chart.
- View basic HR statistics including total employees and average age.

Feel free to customize the dashboard code to add more features or modify the visualizations to meet your specific HR analysis needs.
