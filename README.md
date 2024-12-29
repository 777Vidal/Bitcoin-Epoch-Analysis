# Bitcoin Epoch Analysis: Trends and Predictions Across Halving Cycles

## Overview
This project analyses Bitcoin's price data across multiple halving epochs to uncover trends and predict future price peaks. By segmenting the data based on Bitcoin halving dates, we identify patterns in price behavior and use polynomial regression for predictive modeling.

The analysis focuses on:
- Resampling raw hourly price data into daily high prices.
- Grouping data into halving epochs for trend visualisation.
- Using regression models to estimate future price peaks.

## Goals
1. Understand price behavior across Bitcoin halving epochs.
2. visualise trends in daily high prices for each epoch.
3. Predict future price peaks based on historical data.

## Dataset
The dataset should be in CSV format with at least the following columns:
- `Open time`: The date and time of the data point, convertible to a datetime format.
- `High`: The highest price of Bitcoin during the given interval.

### Example Dataset Snippet
```csv
Open time,High
2023-01-01 00:00:00,16850.25
2023-01-02 00:00:00,16870.50
```

---

## Features
- **Data Preprocessing**: Converts raw hourly price data into daily high prices.
- **Epoch Segmentation**: Groups data into distinct Bitcoin halving epochs.
- **visualisations**: Plots daily high prices for each epoch.
- **Prediction Models**: Uses polynomial regression to estimate future price peaks.

---

## Analysis & visualisations
### Key visualisations:
1. **Price Trends by Epoch**:
   - Line plots for each halving epoch, showing the progression of daily high prices.
   
2. **Future Price Predictions**:
   - Polynomial regression models to forecast potential price peaks for upcoming epochs.
   
3. **Comparative Analysis of Epoch Peaks**:
   - Scatter plots comparing the peak prices across different epochs.

### Example Output:
**Processed Data:**
| Open Time       | Daily High | Epoch    |
|------------------|------------|----------|
| 2011-08-18      | 10.90      | Epoch 1  |
| 2012-11-28      | 1168.69    | Epoch 2  |

**Predicted Peak for Epoch 5**: `$149,818.55`

---

## Tools Used
- **Python**: For data processing and predictive modeling.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating visualisations.
- **Scikit-learn**: For polynomial regression and predictive analysis.

---

## Results
- visualisation of price trends reveals consistent patterns of growth within epochs.
- Polynomial regression provides robust estimates for future price peaks, offering insights into Bitcoin's potential value.

---

## Future Work
1. Incorporate volume data to assess market behavior more comprehensively.
2. Extend predictions beyond Epoch 5 to anticipate long-term price trends.
3. Adapt the analysis for other cryptocurrencies to expand its scope.

---

## Contributions
Contributions are welcome! If you have ideas for improvement or additional analyses, feel free to:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
- Bitcoin price data sourced from [Kaggle dataset].
- visualisations powered by **Matplotlib**.



