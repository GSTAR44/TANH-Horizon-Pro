# Model Hub Description: TANH Horizon Pro

## Model Overview
**TANH Horizon Pro** is a high-performance time series forecasting model optimized for cryptocurrency price prediction (BTC/ETH). Built with a neural network architecture and converted to ONNX format, it leverages the **TANH-activated ZTAE loss function** to prioritize accurate directional forecasting of extreme price movements while maintaining precision for near-zero returns. The model is designed for short-to-medium-term horizons (1-24 hours) and is ideal for algorithmic trading strategies.

---

## Data Sources
- **Primary Data**: Historical OHLCV (Open/High/Low/Close/Volume) data for BTC/ETH from the OG Modelathon repository (1-minute and 1-hour granularity).
- **Augmented Features**:
  - Social media sentiment scores (Twitter/Reddit) aggregated hourly.
  - On-chain metrics
