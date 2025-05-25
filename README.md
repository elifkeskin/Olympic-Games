# Olympics Data Analysis with PySpark & SQL

## 🏅 Project Description

This project analyzes over a century of Olympic Games data, spanning from 1896 to 2016. The Olympics is the most prestigious event in the life of athletes and is celebrated worldwide. The dataset provides a comprehensive view of athletes, events, and medal distributions across different years, sports, and countries.

The analysis was implemented on **Databricks** using **PySpark** and **SQL**, enabling scalable data processing and advanced analytics.

## 🎯 Project Purpose

- To explore and analyze historical Olympic data.
- To uncover trends and insights about athletes, teams, sports, and medal distributions.
- To demonstrate the use of PySpark and SQL for big data analytics on Databricks.

## 📂 Dataset Story

The dataset contains detailed records of Olympic athletes and events from 1896 to 2016. It includes demographic information, event details, and medal results for thousands of athletes from around the world.

## 📝 Data Fields

| Field   | Description                                                        |
|---------|--------------------------------------------------------------------|
| ID      | Unique number of each athlete                                      |
| Name    | Athlete's name                                                     |
| Sex     | Male or Female                                                     |
| Age     | Athlete's age                                                      |
| Height  | Athlete's height in centimeters                                    |
| Weight  | Athlete's weight in kilograms                                      |
| Team    | Team's name                                                        |
| NOC     | National Olympic Committee 3-letter code                           |
| Games   | Year and season in which the game was played                       |
| Year    | Year (integer)                                                     |
| Season  | Summer or Winter                                                   |
| City    | Host city                                                          |
| Sport   | Sport in which the event was played                                |
| Event   | Specific event                                                     |
| Medal   | Gold, Silver, Bronze, or NA (no medal)                             |

## 🛠️ Technologies Used

- **Databricks:** Collaborative data analytics platform.
- **PySpark:** Distributed data processing with Python.
- **SQL:** Querying and aggregating large datasets.

## 🚦 Project Workflow

1. **Data Ingestion:**  
   - Load the Olympics dataset into Databricks using PySpark.

2. **Data Cleaning & Preprocessing:**  
   - Handle missing values and data inconsistencies.
   - Convert data types as needed.

3. **Exploratory Data Analysis (EDA):**  
   - Analyze athlete demographics (age, sex, height, weight).
   - Explore medal distributions by country, sport, and year.
   - Identify trends and patterns in Olympic history.

4. **SQL Analytics:**  
   - Use SQL queries for aggregations, filtering, and advanced analytics.

5. **Visualization:**  
   - Generate charts and graphs to illustrate key findings (optional, e.g., using Databricks display functions or matplotlib).

## 🚀 Getting Started

1. **Upload the Dataset:**  
   - Import the Olympics dataset into your Databricks workspace.

2. **Open the Notebook:**  
   - Launch the Databricks notebook provided in this repository.

3. **Run the Analysis:**  
   - Execute the cells step by step to perform data analysis and view results.

## 📊 Example Analysis Questions

- Which countries have won the most medals over time?
- What is the age distribution of Olympic medalists?
- How has participation in different sports evolved?
- Are there trends in athlete physical characteristics by sport or era?

## 🤝 Contributing

Contributions are welcome!  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit your changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature-branch`)  
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

---

**For questions or suggestions, feel free to open an issue or contact the maintainer.**

