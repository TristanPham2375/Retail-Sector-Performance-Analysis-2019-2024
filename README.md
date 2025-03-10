# Retail-Sector-Performance-Analysis-2019-2024

This project analyzes various retail sectors' performance, focusing on the impact of COVID-19 and market trends over the past few years. It includes the analysis of the **automobile retail sector** to determine the best time to sell a car, an exploration of the **fashion retail sector** to identify the most impacted sub-categories, and a study on the **revenue trends** across industries.

## 📊 Project Overview

### Data Sources:
- The data is sourced from historical retail sales data, specifically for sectors like **automobile dealers** and **fashion retailers**.
- The dataset covers the period from **2019 to 2024**, which includes pre- and post-COVID periods.

### Analysis Focus:
- **Automobile Retail (Car Sales)**: Identifying the best months to sell a car based on demand trends.
- **COVID Impact on Retail Sectors**: Comparing the revenue drops between pre-COVID and COVID periods, and identifying the sectors most affected.
- **Fashion Retail Sectors**: Analyzing the recovery of various fashion sub-categories post-COVID.

### Deliverables:
- Cleaned and pre-processed data.
- Visualizations that depict retail trends across different industries.
- Insights into the best times to sell a car and which sectors were most impacted by COVID.

## 💻 Technologies Used

### Language:
- **Python**: The primary language used for data analysis and visualization.

### Libraries:
- **pandas**: For data manipulation, cleaning, and analysis.
- **numpy**: For numerical operations and calculations.
- **seaborn**: For statistical data visualizations.
- **matplotlib**: For general plotting and customizing visualizations.

## 📂 Getting Started

### Prerequisites:
Before running the code, make sure you have Python and the necessary libraries installed.

1. **Install Python**: [Download Python](https://www.python.org/downloads/)
2. **Install the required libraries**: Run the following command to install all necessary libraries.

   ```bash
   pip install numpy pandas seaborn matplotlib
3. **Install Data File**: Ensure that the dataset file Data_File.csv is placed in the correct directory. Update the file path in the code accordingly:
python
Copy
Edit
data_temp = pd.read_csv(r"C:\path\to\your\data\Data_File.csv")
