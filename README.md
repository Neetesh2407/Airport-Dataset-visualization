# Airport-Dataset-visualization
🛫 Airport Data Analysis using SQL, Python & Power BI
📌 Project Overview
This project involves analyzing a large airport dataset using SQL, Python, and Power BI.

SQL: Querying and extracting insights

Python: Connecting to the SQL database and visualizing data using Pandas, Matplotlib, and Seaborn

Power BI: Creating interactive dashboards

📂 Dataset
The dataset contains detailed information about airports, including location, capacity, passenger traffic, and more.
📌 Download Dataset: Google Drive Link

🔗 Tech Stack
✅ SQL – MySQL for querying the dataset
✅ Python – Pandas, Matplotlib, Seaborn, SQLAlchemy, PyMySQL
✅ Power BI – Interactive visualizations

⚙️ Setup Instructions 
1️⃣ Clone the Repository
  git clone https://github.com/Neetesh2407/Airport-Data-Analysis.git
  cd Airport-Data-Analysis

2️⃣ Install Dependencies
  pip install pymysql mysql-connector-python sqlalchemy pandas matplotlib seaborn

3️⃣ Set Up MySQL Database
 1.Create Database
    CREATE DATABASE airport_db;
    USE airport_db;
 2.Import Dataset into MySQL
   LOAD DATA INFILE '/path/to/airport_data.csv' 
   INTO TABLE airports
   FIELDS TERMINATED BY ',' 
   IGNORE 1 ROWS;

4️⃣ Run Python Script
  python analyze_airports.py

📊 Power BI Dashboard
The Power BI dashboard visualizes key airport insights, such as:
✔ Passenger Traffic Trends
✔ Top Airports by Capacity
✔ Regional Comparisons

📸 Sample Visualizations
🔹 SQL Query Results
🔹 Python Data Plots
🔹 Power BI Dashboard Screenshots


📬 Connect With Me
🔗 GitHub: Neetesh2407
📧 Email: your.email@example.com

