This repository contains analysis and implementation of sales forecasting for an Online Retail company. The data provided is open source and can be [found here](https://archive.ics.uci.edu/dataset/352/online+retail)

# Quick Start

Since the colab environment was used for development please click below and open the respective notebooks for quick start.

- Exploratory Analysis Notebook  <a href="https://colab.research.google.com/drive/11F-SBtgNCvYmaawm1GyZUscqqGkY3yOm?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a>

- Sales Forecast Experiment <a href="https://colab.research.google.com/drive/1mAIjIW2SgHqdoSxd_DHPvTaqNikSeOv6?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a>

[Sales Forecast Project Report](https://venkatesh-murugadas.notion.site/Sales-Forecast-for-Online-Retailer-8c8bb328fb1444209d3b9d4ee1e7ef57?pvs=4)

# Overview

An online retail historical sales transactions were analyzed for future sales forecasting. To forecast these sales, I employed five machine learning models: Light Gradient Boosted Model (LightGBM), Auto-Regressive Integrated Moving Average (ARIMA), Seasonal Autoregressive Integrated Moving Average with Exogenous Variables (SARIMAX), Prophet (a Generative Additive Model), and Recurrent Neural Network (RNN).

Upon testing these models, I found that the Prophet model outperformed the others in delivering a reliable sales forecast over an extended period, even with a limited dataset. The other models faced challenges in generating accurate and noise-free predictions for such long time horizons.

In this project, I focused solely on univariate analysis. For future work, I recommend exploring multivariate and multiple time series analysis. Additionally, ensemble models could offer improved accuracy in sales forecasting.