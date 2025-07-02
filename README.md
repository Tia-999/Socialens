📌 Project Overview
Sociolens is an interactive data analysis dashboard built using Panel, hvPlot, and Plotly, aimed at exploring Twitter data from a CSV export (tweetActivity.csv). The project enables visual, exploratory analysis of tweet engagement, impressions, and more—empowering users to understand trends over time in a highly visual and user-friendly manner.

🔍 Features
📈 Time Series Visualization of tweet impressions

📊 Interactive Filtering and Selection using panel and panel.tabulator

📌 Dynamic Dashboards with integrated Plotly and hvPlot for in-depth visual exploration

🧠 Modular and clean design to explore trends in social media activity

🧰 Technologies Used
Python 3.x

Pandas

NumPy

Panel

hvPlot

Plotly

Tabulator (via Panel extension)

📂 Files
Sociolens.ipynb: Main Jupyter Notebook containing all analysis and dashboard logic.

tweetActivity.csv: (Required) CSV file containing the Twitter analytics data to be loaded and analyzed.

🚀 How to Run
Install required libraries (if not already installed):

bash
Copy
Edit
pip install pandas numpy panel hvplot plotly
Launch the Notebook:

bash
Copy
Edit
jupyter notebook Sociolens.ipynb
(Optional) Serve as a Panel App:
You can also serve the dashboard via:

bash
Copy
Edit
panel serve Sociolens.ipynb
🗃️ Data Columns Used
The notebook processes a DataFrame with columns like:

Date

impressions

...and others based on Twitter analytics

📌 Example Visualization
The app includes:

📉 Line chart of impressions over time

📋 Interactive data tables using panel.tabulator
