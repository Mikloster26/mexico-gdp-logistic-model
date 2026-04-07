This project models the historical Gross Domestic Product (GDP) of Mexico using a logistic growth function based on World Bank data. The goal is to estimate model parameters, address numerical instability issues, and generate future GDP forecasts.

Objectives
Fit a logistic model using non-linear least squares
Identify challenges in parameter estimation
Apply normalization to improve model stability
Evaluate model performance and forecasting capability

Methodology
Loaded historical GDP data for Mexico
Applied a logistic growth model
Estimated parameters using least squares
Identified convergence issues due to scale
Normalized data to improve numerical stability
Refit the model and compared results

Key Results
Initial model struggled with parameter estimation due to large data scale
Normalization significantly improved convergence
The logistic model provided a reasonable approximation of GDP growth trends

Insights
Data scaling plays a critical role in non-linear optimization
Logistic models can approximate macroeconomic growth patterns
Model stability improved after normalization

Forecast

GDP forecast for 2022 was obtained using the fitted logistic model and later transformed back to the original scale.
