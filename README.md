# Zomato-Data-Set-Analysis-and-Visualization


This repository contains exploratory data analysis (EDA) and visualization of the Zomato dataset. The dataset comprises information about restaurants, cuisines, user ratings, and more from the Zomato platform.

## Dataset Description

The Zomato dataset used for this analysis contains the following columns:

- `Restaurant ID`: Unique identifier for each restaurant
- `Restaurant Name`: Name of the restaurant
- `Country Code`: Code representing the country where the restaurant is located
- `City`: City in which the restaurant is situated
- `Address`: Address of the restaurant
- `Locality`: Locality of the restaurant
- `Locality Verbose`: Verbose locality description
- `Longitude`: Longitude coordinate of the restaurant
- `Latitude`: Latitude coordinate of the restaurant
- `Cuisines`: Types of cuisines offered by the restaurant
- `Average Cost for two`: Average cost for two people to dine at the restaurant
- `Currency`: Currency used for the average cost
- `Has Table booking`: Whether the restaurant offers table booking or not
- `Has Online delivery`: Whether the restaurant provides online delivery or not
- `Is delivering now`: Whether the restaurant is delivering food at the time of data collection
- `Switch to order menu`: Whether the restaurant allows switching to order menu
- `Price range`: Range of prices for dining at the restaurant
- `Aggregate rating`: Overall rating of the restaurant
- `Rating color`: Color representation of the aggregate rating
- `Rating text`: Textual representation of the aggregate rating
- `Votes`: Number of votes received by the restaurant

## Analysis and Visualization

In this project, I have performed exploratory data analysis to gain insights into the Zomato dataset. The analysis includes but is not limited to:

- Distribution of restaurants across different cities and countries
- Analysis of cuisines offered by restaurants
- Relationship between average cost and aggregate rating
- Correlation between various features such as average cost, aggregate rating, and votes
- Visualization of rating distribution, cost distribution, etc.

The analysis and visualizations are carried out using popular Python libraries such as Pandas, Matplotlib, and Seaborn.

## Files Included

- `zomato_data_analysis.ipynb`: Jupyter notebook containing the Python code for EDA and visualization
- `zomato.csv`: CSV file containing the Zomato dataset

## Dependencies

The following Python libraries are required to run the analysis code:

- Pandas
- Matplotlib
- Seaborn

These dependencies can be installed via pip using the following command:

```
pip install pandas matplotlib seaborn
```

## How to Use

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/Zomato-Data-Set-Analysis-and-Visualization.git
```

2. Navigate to the cloned directory:

```
cd Zomato-Data-Set-Analysis-and-Visualization
```

3. Open and run the Jupyter notebook `zomato_data_analysis.ipynb` to explore the analysis and visualizations.

## Credits

The Zomato dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/shrutimehta/zomato-restaurants-data).

