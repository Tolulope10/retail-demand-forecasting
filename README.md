# Retail Demand Forecasting & Product Substitution

### Baseline results (28 days holdout)
I evaluated multiple baseline forecasting approaches using a 28-day holdout window and retail-relevant metrics (MAE, RMSE, WAPE).

| Model | MAE | RMSE | WAPE |
|------|-----|------|------|
| Moving Average (28 days) | 4.44 | 7.16 | **0.50** |
| Naive | 4.58 | 7.65 | 0.51 |
| Seasonal Naive (7 days) | 4.65 | 7.63 | 0.52 |

A 28-day moving average performed best, reflecting the benefit of smoothing short-term demand volatility at daily item level. This baseline is used as the benchmark for subsequent ML models.
