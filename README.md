# Car Market Trends Analysis

A Python-based analysis of CarDekho used-car data to understand pricing patterns and market trends.

## Objective

- Analyze used-car market data
- Study factors affecting selling price
- Compare cars based on fuel type, seller type, and transmission
- Identify relationships between car features and selling price

## Dataset

The dataset contains information about car name, year, selling price, present price, kilometers driven, fuel type, seller type, transmission, and previous ownership.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Key Findings

- Present Price has the strongest relationship with Selling Price.
- Present Price and Selling Price have a correlation of **0.879**.
- Newer cars generally have higher selling prices.
- Selling prices vary across fuel type, seller type, and transmission.
- Kms Driven has a very weak relationship with Selling Price.

## Project Structure

```text
car-market-trends-analysis/
├── README.md
├── car_market_analysis.ipynb
├── dataset/
├── Results/
│   ├── dataset_overview.png
│   ├── fuel_type_distribution.png
│   ├── market_segmentation.png
│   ├── present_vs_selling_price.png
│   ├── price_correlation.png
│   ├── average_selling_price_by_year.png
│   ├── year_vs_selling_price_data.png
│   ├── selling_price_correlations.png
│   └── correlation_heatmap.png
└── presentation/
