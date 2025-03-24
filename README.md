# Retail Sales Data Analysis

This repository contains two exploratory data analysis (EDA) projects focused on retail sales data:

1. **Walmart Sales Analysis** - Analysis of weekly sales data from Walmart stores
2. **Avocado Sales Analysis** - Analysis of avocado sales across different regions

## Repository Structure

```
.
├── data/
│   ├── raw/                # Original unmodified data
│   │   ├── walmart/        # Raw Walmart sales data
│   │   └── avocado/        # Raw avocado sales data
│   └── processed/          # Cleaned and preprocessed data
│       ├── walmart/        # Processed Walmart data
│       └── avocado/        # Processed avocado data
├── jupyter-notebooks/      # Jupyter notebooks for analysis
│   ├── walmart/            # Walmart sales analysis notebooks
│   └── avocado/            # Avocado sales analysis notebooks
└── README.md               # This file
```

## Getting Started

### Prerequisites

- Python 3.x
- Required packages: pandas, numpy, matplotlib, seaborn, scikit-learn

### Running the Analysis

1. Clone this repository
2. Navigate to the appropriate notebook directory:
   - `jupyter-notebooks/walmart/` for Walmart sales analysis
   - `jupyter-notebooks/avocado/` for avocado sales analysis
3. Run the Jupyter notebooks or use the Python scripts in the `scripts/` directory

## Project Details

### Walmart Sales Analysis

This project analyzes weekly sales data from different Walmart stores to identify trends and factors influencing sales.

#### Dataset

The Walmart dataset includes:

- `Store`: The store number
- `Date`: The week of sales data
- `Weekly_Sales`: Sales for the given store in the given week
- `Holiday_Flag`: Whether the week was a holiday week (1) or not (0)
- `Temperature`: Average temperature in the region during the week
- `Fuel_Price`: Cost of fuel in the region during the week
- `CPI`: Consumer Price Index for the region during the week
- `Unemployment`: Unemployment rate for the region during the week

#### Analysis Highlights

- Impact of holidays on sales
- Store-wise sales performance
- Seasonal trends in sales
- Correlation between sales and economic factors

### Avocado Sales Analysis

This project analyzes avocado sales data across different regions to understand regional preferences and market trends.

#### Dataset

The avocado dataset includes:

- `Region`: The market region
- `Date`: The observation date
- `AveragePrice`: Average price of avocados
- `Total Volume`: Total number of avocados sold
- `4046`, `4225`, `4770`: Sales volumes for different avocado types
- Various packaging information (bags)

#### Analysis Questions

This analysis addresses questions such as:

1. Average number of avocados with PLU 4046 sold in each region
2. Top ten regions organized by total volume
3. Best regions for millennials based on avocado prices and budget constraints
4. Best regions for avocado sellers based on day-of-week sales volume

## Tools Used

- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## References

- [Walmart EDA Reference](https://medium.com/analytics-vidhya/a-data-science-project-for-beginners-exploratory-data-analysis-eda-d334f58f94ee)