# Gold Price Prediction using LSTM Neural Networks

## Project Overview
This project aims to predict gold prices using Long Short-Term Memory (LSTM) neural networks. It's designed to assist in stock trading and gold futures ("qihuo") market analysis by providing accurate price forecasts.

## Motivation
Gold price predictions have significant impacts on various financial markets:
- Stock trading: Informing investment strategies, especially for mining sector companies.
- Gold futures trading: Providing a competitive edge in the 'qihuo' market.
- Risk management: Aiding in portfolio diversification and risk mitigation.
- Economic forecasting: Indicating broader economic trends.

## Dataset
- Historical gold price data from 2015 to early 2024
- Features include daily closing prices

## Model Architecture
- LSTM (Long Short-Term Memory) neural network
- Multiple LSTM layers with dropout for regularization
- Dense layers for final prediction
- 60-day window for sequence prediction

## Key Features
- Data preprocessing and cleaning
- Time series analysis
- LSTM model implementation
- Performance visualization

## Results
- Model accuracy: 96.5%
- Detailed loss and prediction visualizations

## Limitations and Future Work
- Incorporate additional features (economic indicators, market sentiment)
- Explore longer-term predictions
- Implement more advanced architectures (hybrid models, ensemble methods)
- Improve handling of market volatility
- Enhance model interpretability

## How to Use
1. Clone the repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook or Python script

## Dependencies
- numpy
- pandas
- matplotlib
- plotly
- scikit-learn
- keras
- tensorflow

## Contributors
Eddy Lin

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
