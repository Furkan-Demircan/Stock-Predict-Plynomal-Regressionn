# Stock-Predict-Plynomal-Regresson

This project predicts Amazon's stock prices using a polynomial regression model. It fetches historical stock prices, trains a regression model based on the closing prices, and forecasts future prices.

[**Bu dokümanı Türkçe oku**](./README_TR.md)

## Features

- **Data Retrieval**: Fetches historical stock price data for Amazon using `yfinance`.
- **Polynomial Regression Model**: Trains a regression model based on the closing prices to predict future prices.
- **Data Visualization**: Plots historical stock data and prediction results for easy interpretation.

## Requirements

- Python 3.8 or above
- Required Python packages:
    - `yfinance`
    - `pandas`
    - `numpy`
    - `matplotlib`
    - `scikit-learn`

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/Furkan-Demircan/amazon-stock-prediction.git
    cd amazon-stock-prediction
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open the notebook file `Stock-Predict-Plynomal-Regression.ipynb` and execute the cells step by step.

## Usage

1. The notebook fetches Amazon's historical stock price data using the `yfinance` library.
2. A polynomial regression model is trained based on the closing prices.
3. Visualizations of the historical prices and predictions are generated.
4. Predictions for future dates are displayed based on the trained model.

## Contribution

Contributions are welcome! Please open an issue to discuss your changes before making them.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to your branch (`git push origin feature/new-feature`).
5. Open a pull request (PR).

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact

For any questions or suggestions about this project, feel free to reach out:

- **Email**: goooglenudle@gmail.com
- **GitHub**: [Furkan-Demircan](https://github.com/Furkan-Demircan)

---

Happy analyzing and predicting!
