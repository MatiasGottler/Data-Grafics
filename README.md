# Data-Grafics
Description
This project creates a SQLite database and populates it with sample sales data. It then generates a dashboard with multiple plots using matplotlib and seaborn to visualize the sales data.

Steps
Create and Populate Database: Connects to a SQLite database example.db, creates a sales table, and inserts 100 days of sample sales data with random amounts.
Generate Dashboard: Connects to the database, retrieves the sales data, and uses pandas to process it. It then creates a dashboard with four different plots:
Line Plot: Shows daily sales over time.
Bar Plot: Displays daily sales as bars.
Scatter Plot: Visualizes sales with varying point sizes and colors.
Area Plot: Fills the area under the sales line.
