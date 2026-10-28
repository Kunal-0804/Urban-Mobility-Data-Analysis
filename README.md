# 🚕 Urban Mobility Data Analysis

### End-to-End Data Analytics Project | Python • Pandas • NumPy • MySQL • Power BI

## 📌 Project Overview

This project focuses on analyzing urban ride-booking data to understand booking patterns, ride cancellations, revenue, vehicle performance, customer behavior, and operational trends.

The project follows an end-to-end data analytics workflow, starting with data quality assessment and cleaning in Python, followed by feature engineering, SQL analysis using MySQL, and interactive dashboard visualization using Power BI.

The objective is to transform raw ride-booking data into meaningful insights that can help understand operational performance and ride-booking trends.

## 🎯 Project Objectives

* Analyze overall ride-booking performance.
* Understand completed, cancelled, and incomplete rides.
* Identify booking patterns across different vehicle types.
* Analyze booking value and ride distance.
* Examine customer and driver cancellation reasons.
* Explore booking trends by month, hour, and day type.
* Analyze pickup and drop locations.
* Evaluate driver and customer ratings.
* Build an interactive Power BI dashboard for data visualization.

## 🛠️ Tools & Technologies

| Tool             | Purpose                                   |
| ---------------- | ----------------------------------------- |
| Python           | Data analysis and preprocessing           |
| Pandas           | Data manipulation and cleaning            |
| NumPy            | Conditional logic and feature engineering |
| Jupyter Notebook | Data exploration and analysis             |
| MySQL            | SQL queries and business analysis         |
| SQLAlchemy       | Connecting Python with MySQL              |
| MySQL Connector  | Database connectivity                     |
| Power BI         | Interactive dashboard and visualization   |
| CSV              | Storing the cleaned dataset               |

## 📂 Project Files

| File                            | Description                                                                                 |
| ------------------------------- | ------------------------------------------------------------------------------------------- |
| `urban_mobility_analysis.ipynb` | Data exploration, data quality checks, cleaning, feature engineering, and MySQL integration |
| `urban_mobility_analysis.sql`   | SQL queries for ride-booking and operational analysis                                       |
| `cleaned_urban_mobility.csv`    | Cleaned dataset containing original fields and additional analytical features               |
| `urban_mobility_dashboard.pbix` | Power BI dashboard file for exploring ride-booking performance                              |

## 🔄 Project Workflow

### 1. Data Exploration

Performed initial exploration of the ride-booking dataset to understand its structure and data quality.

Key activities:

* Inspected rows, columns, and data types.
* Checked missing values and duplicate records.
* Examined booking IDs and customer IDs.
* Analyzed booking status distribution.
* Validated numeric values and rating ranges.
* Reviewed date, time, location, and vehicle information.

### 2. Data Cleaning Using Python

Used Pandas and NumPy to prepare the dataset for analysis.

Key activities:

* Created a working copy to preserve the original dataset.
* Handled missing cancellation and incomplete-ride reasons.
* Standardized missing payment information where appropriate.
* Preserved missing ratings and operational metrics when they were not applicable.
* Validated numeric, date, and time columns.
* Reviewed the final missing-value status.

### 3. Feature Engineering

Created additional analytical features to support deeper analysis and dashboard development.

New features include:

* `Booking Datetime`
* `Ride Outcome Category`
* `Booking Month`
* `Booking Hour`
* `Booking Day`
* `Day Type`

Binary indicators were also standardized to represent ride-related events consistently.

These features support time-based analysis, ride outcome comparisons, and operational reporting.

### 4. SQL Analysis Using MySQL

Imported the cleaned dataset into MySQL and performed business-oriented analysis using SQL queries.

The SQL analysis covers:

* Total ride bookings.
* Completed rides and completion rate.
* Cancelled bookings and cancellation rate.
* Total booking value.
* Booking distribution by vehicle type.
* Average booking value by vehicle type.
* Average ride distance.
* Driver and customer ratings.
* Payment method distribution.
* Top pickup and drop locations.
* Monthly booking trends.
* Hourly booking patterns.
* Weekday versus weekend performance.
* Customer and driver cancellation reasons.
* Incomplete ride reasons.
* Average VTAT and CTAT by vehicle type.
* Popular pickup-to-drop routes.
* Monthly cancellation rates.

SQL concepts used include `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `LIMIT`, aggregate functions, `CASE WHEN`, and date/time functions.

### 5. Power BI Dashboard

Developed a Power BI dashboard to visualize ride-booking data and support performance analysis.

The dashboard file is included in this repository.

Open the `.pbix` file in Power BI Desktop to explore the dashboard.

## 📊 Key Analysis Areas

| Analysis Area           | Business Questions                                                        |
| ----------------------- | ------------------------------------------------------------------------- |
| Booking Performance     | How many bookings were completed or cancelled?                            |
| Vehicle Performance     | Which vehicle types received the most bookings?                           |
| Revenue Analysis        | How does booking value vary across vehicle types and booking statuses?    |
| Cancellation Analysis   | What are the cancellation rates and common cancellation reasons?          |
| Time-Based Analysis     | How do bookings vary by month, hour, and day type?                        |
| Location Analysis       | Which pickup locations and routes have the highest booking volumes?       |
| Customer Experience     | How do customer ratings vary across booking statuses and vehicle types?   |
| Operational Performance | How do vehicle arrival and customer trip times vary across vehicle types? |

## 💡 Skills Demonstrated

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Data Quality Assessment
* Feature Engineering
* Python Data Analysis
* SQL Query Writing
* MySQL Database Integration
* Business-Oriented Data Analysis
* Data Visualization
* Power BI Dashboard Development
* Analytical Thinking

## 🚀 How to Explore This Project

1. Clone or download this repository.
2. Open the Jupyter Notebook using Jupyter Notebook or VS Code.
3. Install the required Python libraries.
4. Update the dataset path in the notebook if necessary.
5. Execute the notebook cells in sequence.
6. Set up MySQL and create the required database.
7. Configure the database connection before running the MySQL integration cells.
8. Execute the SQL queries against the imported `rides` table.
9. Open the Power BI `.pbix` file in Power BI Desktop.

**Note:** The original raw dataset is not included in this repository. The notebook may require the original dataset for reproducing the initial exploration and cleaning steps. Update file paths and database connection settings according to your environment.

## 📌 Project Outcome

This project demonstrates an end-to-end data analytics workflow, combining Python-based data preparation, MySQL-based analytical queries, and Power BI visualization.

It showcases practical skills in data cleaning, feature engineering, database integration, business analysis, and dashboard-based reporting.

## 👨‍💻 Author

**kunal Pandey**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

BCA Graduate | MCA Student at IGNOU

---

⭐ If you find this project useful, consider giving the repository a star!
