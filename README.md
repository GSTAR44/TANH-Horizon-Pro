TANH Horizon Pro: Advanced Time Series Forecasting for Crypto Markets
Overview
TANH Horizon Pro is a cutting-edge time series forecasting model designed for accurate ETH and BTC spot price predictions. Leveraging state-of-the-art machine learning techniques and the robust ONNX framework, TANH Horizon Pro delivers high-precision forecasts while optimizing for the MZTAE metric. This model is fine-tuned to effectively predict extreme price movements while maintaining minimal error for mid-range values, making it highly useful for crypto traders and analysts.
Key Features
Optimized for Crypto Forecasting: Specially trained on ETH and BTC market data, capturing key price movements and trends.
TANH-Based Error Minimization: Implements the ZTAE (tanh absolute error) function to reward accurate extreme value predictions.
Scalable and Efficient: Supports real-time inference through ONNX, ensuring seamless integration with OpenGradient’s Model Hub.
Robust Preprocessing: Includes feature engineering steps like volatility indexing, volume-weighted trends, and moving averages within the ONNX model for standalone execution.
Freestyle Flexibility: Can be adapted to additional financial time series data for broader market forecasting applications.
Data and Training
TANH Horizon Pro is trained using the ETH and BTC spot price datasets provided in the OG Modelthon repository. The model incorporates various features such as:
Historical price action (candlestick data: open, high, low, close, volume)
Market momentum indicators (RSI, MACD, Bollinger Bands)
Sentiment-driven variables (if applicable)
ONNX Conversion
To ensure compatibility with OpenGradient, TANH Horizon Pro is exported to ONNX format. Preprocessing steps, including feature transformations, are embedded within the ONNX model to guarantee accurate real-time inference.
Sample Input
The model requires input data formatted as a structured time series tensor, labeled "candles", in the following structure:
{
  "candles": [[timestamp, open, high, low, close, volume],
               [timestamp, open, high, low, close, volume],
               ...]
}

This ensures seamless integration with OpenGradient’s live data input format.
Usefulness in Web3
TANH Horizon Pro contributes significantly to the Web3 space by providing:
Decentralized trading intelligence for DeFi platforms
Automated risk assessment for crypto hedge funds
Enhanced market transparency through open-access predictive analytics
License
TANH Horizon Pro is released under the Apache 2.0 License, allowing for broad usage, modification, and distribution while ensuring proper attribution and protection for contributors. This license ensures that the model remains accessible for innovation while maintaining legal clarity.
Conclusion
TANH Horizon Pro stands out as a high-performance forecasting model optimized for crypto volatility and extreme price movement detection. With its ONNX-based deployment, innovative loss function, and structured feature engineering, it is poised to set a new standard in financial time series forecasting on OpenGradient.

Competitor: Bruce (fibon) Submission Track: ETH/BTC Spot Forecast or Freestyle Track Model Type: Time Series Forecasting Framework: ONNX
