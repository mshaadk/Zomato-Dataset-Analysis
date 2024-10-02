# Zomato Dataset Analysis Project
This project performs Exploratory Data Analysis (EDA) on a Zomato dataset, focusing on data cleaning, processing, and visualization. The aim is to derive meaningful insights about restaurant ratings, locations, cuisines, and more.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Usage](#installation)
3. [Dataset](#dataset)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Data Cleaning](#data-cleaning)
6. [Data Visualization](#data-visualization)
7. [Conclusion](#conclusion)
8. [License](#license)

# Project Overview
This project demonstrates:

- **Data Cleaning**: Handling missing values, duplicate records, and normalizing columns.
- **Data Processing**: Cleaning specific columns like ratings, restaurant types, and costs.
- **Visualization**: Using `matplotlib` and `seaborn` for visualizing relationships and distributions across various restaurant features.

## Usage
To run this project locally, follow these steps:

1. **Clone the repository**:

```bash
git clone https://github.com/mshaadk/Zomato-Dataset-Analysis.git
```

2. **Navigate to the project directory**:

```bash
cd Zomato-Dataset-Analysis
```
3. Open `Zomato Dataset Analysis.ipynb` in jupyter notebook and run all cells one by one.

## Dataset
The dataset used in this project is Zomato restaurant data, which contains information like restaurant names, locations, cuisines, ratings, and more.

**Columns used**:

- Restaurant name
- Location
- Online order availability
- Booking table facility
- Ratings, Votes
- Cuisines, etc.

## Exploratory Data Analysis
We start by understanding the dataset with:

  - Checking dataset shape and columns.
  - Displaying the first few records using `data.head()`.

## Data Cleaning
Data cleaning steps include:

 - Dropping redundant columns such as URL, address, phone number, etc.
 - Handling missing values in the `rate` column by removing unwanted characters and filling missing values with the mean rating.
 - Cleaning other columns like `cost2plates`, `location`, `rest_type`, and `cuisines` to ensure data consistency.

## Data Visualization
Using `matplotlib` and `seaborn`, we visualize key insights:

  - Count of restaurants per location.
  - Availability of online ordering and table booking facilities.
  - Restaurant types and their ratings.
  - Distribution of votes across different locations and cuisines.

Sample visualizations include:

  - Count plots of restaurant locations.
  - Boxplots comparing online ordering facilities with ratings.
  - Bar charts for location-based restaurant facilities and vote counts.

## Conclusion
This project provided insights into various features of restaurants in the dataset. By cleaning and visualizing the data, we observed patterns related to restaurant ratings, the availability of online orders, and location-specific trends. These insights could help users in making informed decisions about their dining preferences.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.
