

# Fitbit Activity and Health Data Analysis

## Overview

This project contains a comprehensive analysis of Fitbit user data, focusing on daily activity metrics such as steps taken, distance traveled, and calories burned. The dataset is sourced from Kaggle and contains activity data from multiple users over a period of time. The goal of this analysis is to explore activity patterns, identify trends, and categorize users based on their physical activity levels.

## Contents

* **Data Preprocessing**: Handling missing values, duplicates, and irrelevant data.
* **Exploratory Data Analysis (EDA)**: Analyzing activity trends over time, categorizing users based on activity levels, and exploring patterns.
* **Visualization**: Various visualizations to display activity trends, categorization, and comparisons of weekday and weekend activities.
* **Code**: Python code to preprocess and analyze the data using libraries like Pandas, Seaborn, and Matplotlib.

## Dataset

The dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit/data). The dataset includes columns like:

* `Id`: Unique user ID
* `ActivityDate`: Date of activity log
* `TotalSteps`: Total number of steps taken
* `TotalDistance`: Total distance traveled
* `Calories`: Total calories burned

## Project Structure

```
/Fitbit-Activity-Analysis
├── README.md              # Project overview
├── fitbit_analysis.py     # Python script for data preprocessing and analysis
├── fitbit_data.csv        # Raw dataset (CSV)
├── figures/               # Folder containing saved visualizations
```

## Installation and Setup

### Prerequisites

You need the following Python libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`

To install the required libraries, you can use the following command:

```bash
pip install pandas numpy matplotlib seaborn
```

### How to Run the Code

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/sibe20/Fitbit-Activity-Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Fitbit-Activity-Analysis
   ```

3. Run the analysis script:

   ```bash
   python fitbit_analysis.py
   ```

4. Visualizations will be saved in the `figures/` folder.

## Key Insights

* **Average Activity**: The project calculates the average daily steps, distance, and calories burned across all users.
* **Weekday vs. Weekend Activity**: An analysis of activity patterns across weekdays and weekends, showing that activity levels are generally higher on weekdays.
* **User Categorization**: Users are categorized into various activity levels based on their daily step counts (e.g., Very Low, Low, Moderate, High, Very High).
* **Data Cleaning**: Outliers and incomplete data were identified and handled appropriately to ensure analysis accuracy.

## Future Work

* Predictive modeling to forecast future activity levels based on historical data.
* Integrate external data such as weather patterns to analyze activity variations.
* Build a user recommendation system for health improvement based on activity data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
