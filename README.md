Bitcoin Epoch Analysis

📋 Project Overview

This project analyses Bitcoin's price data across different halving epochs to study trends and predict future price peaks. It includes:

Data preprocessing to resample hourly price data into daily high prices.

Segmentation of data into epochs based on Bitcoin halving dates.

Visualisation of price trends for each epoch.

Polynomial regression to predict future price peaks.

🔧 Features

Preprocessing: Converts raw hourly price data into daily highs.

Epoch Segmentation: Groups data into Bitcoin halving epochs.

Visualisation: Plots daily high prices for each epoch.

Prediction: Uses polynomial regression to estimate future peaks.

Install Dependencies

📂 Dataset Requirements

The dataset must be a CSV file containing at least the following columns:

Open time: Date and time in a format convertible to datetime.

High: High price of Bitcoin during the interval.

Example dataset snippet:

Open time,High
2023-01-01 00:00:00,16850.25
2023-01-02 00:00:00,16870.50
...

Predicted peak price printed in the terminal.

📊 Results

Example Output

Processed Data:

Open time

Daily High

Epoch

2011-08-18

10.90

Epoch 1

2012-11-28

1168.69

Epoch 2

Visualisations: Daily high prices for each epoch.

Predicted Peak for Epoch 5: $149,818.55

📈 Future Work

Incorporate volume data for deeper analysis.

Extend predictions beyond Epoch 5.

Add support for different cryptocurrencies.

🤝 Contributions

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

📜 License

This project is licensed under the MIT License. See LICENSE for details.

🛠️ Acknowledgments

Bitcoin price data provided by [Kaggle dataset].

Visualisation powered by Matplotlib.

Feel free to reach out with questions or suggestions!


