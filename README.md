# Stock Price Analysis Project

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

**Course:** Statistics | **Department:** Applied Mathematics and Statistics (AMS) | **Year:** 3  
**University:** Institute of Technology of Cambodia  
**Academic Year:** 2023-2024  

## Project Overview

This project provides a comprehensive statistical analysis of stock market data, specifically focusing on Acleda Bank's stock performance and investment strategy comparison. The study demonstrates the application of statistical methods including hypothesis testing, data visualization, and investment strategy analysis using Python.

## Objectives

1. **Market Fundamentals Analysis**: Understanding stock market basics and key influencing factors
2. **Data Analysis**: Comprehensive analysis of Acleda Bank stock data over a 3-year period
3. **Strategy Comparison**: Statistical comparison between Lump Sum and Dollar-Cost Averaging investment strategies
4. **Hypothesis Testing**: Applying statistical tests to validate investment strategy performance claims

## Dataset Information

- **Stock:** Acleda Bank (Cambodia Securities Exchange)
- **Period:** May 25, 2020 - May 25, 2023 (3 years)
- **Exchange:** CSX Trade (8:00 AM - 3:00 PM, Monday-Friday)
- **Key Metrics:** 
  - Average closing price: 13,322.93
  - Average trading volume: 65,794.07 shares
  - Notable event: Volume spike (15,342,879 shares) on April 25, 2022


## Technologies Used

- **Python 3.x**
- **Libraries:**
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `matplotlib` - Static data visualization
  - `seaborn` - Statistical data visualization
  - `plotly` - Interactive visualizations
  - `scipy.stats` - Statistical hypothesis testing

## Key Findings

### Investment Strategy Analysis

| Strategy | Advantages | Disadvantages | Risk Level |
|----------|------------|---------------|------------|
| **Lump Sum** | Higher potential returns, simpler management, single transaction fee | High market timing risk, liquidity impact, psychological pressure | **Higher** |
| **Dollar-Cost Averaging** | Volatility mitigation, disciplined approach, reduced emotional bias | Possible missed gains, higher cumulative costs | **Lower** |

### Statistical Results

**Hypothesis Testing (α = 0.05):**

1. **Returns Difference**: Significant difference found between Strategy A and Strategy B average annual returns
   - Strategy B returns > Strategy A returns (p < 0.05)

2. **Risk Analysis**: Significant difference in risk distribution between strategies
   - Strategy A risk > Strategy B risk (p < 0.05)

### Data Distribution Analysis

- **Finding**: None of the price or volume variables followed normal distribution
- **Implication**: Non-parametric statistical tests were required for accurate analysis

nd conclusions

## Key Visualizations

The project includes various visualizations:
- Time series plots of stock prices and volumes
- Distribution histograms for normality testing
- Interactive charts for better data exploration
- Comparative analysis charts for investment strategies

## Statistical Methods Applied

1. **Descriptive Statistics**: Mean, median, standard deviation, quartiles
2. **Hypothesis Testing**: Two-sample t-tests for comparing strategies
3. **Distribution Analysis**: Normality testing and visualization
4. **Risk-Return Analysis**: Standard deviation as risk measure
5. **Performance Metrics**: Annual returns calculation and comparison

## References

- Cambodia Securities Exchange (CSX) data
- Financial statistics and investment theory literature
- Python documentation for statistical libraries

## License

This project is created for educational purposes as part of the Statistics course in the Applied Mathematics and Statistics department.

---

**Note**: This project demonstrates the practical application of statistical concepts in financial analysis. The findings should not be considered as investment advice.