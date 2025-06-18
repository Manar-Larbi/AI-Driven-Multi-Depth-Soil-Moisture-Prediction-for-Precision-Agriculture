# AI-Driven-Multi-Depth-Soil-Moisture-Prediction-for-Precision-Agriculture
This project explores the use of Artificial Intelligence (AI) to estimate soil humidity at multiple depths using data from just one or two sensor levels, combined with meteorological and time-based features. Using data from an apple orchard collected via DunavNet’s AgroNet platform (2023–2025), we analyze soil moisture across six depths (10–60 cm) to reduce sensor deployment costs.

We benchmarked over 350 models across 72+ scenarios using Extra Trees, Random Forest, XGBoost, and LSTM architectures. Random Forest consistently delivered the best performance (RMSE, R²), revealing that sensors at 10 cm and 50 cm offer optimal predictive coverage. We also evaluated the contribution of environmental and temporal variables, and tested multi-output and stacked LSTM models. While LSTM underperformed compared to tree-based models, it shows promise for future refinement.

This work demonstrates how AI can support cost-effective, scalable soil monitoring in precision agriculture.
