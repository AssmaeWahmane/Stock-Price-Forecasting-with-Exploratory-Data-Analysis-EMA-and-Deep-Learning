# General Introduction

Over the past few decades, financial markets have undergone a profound transformation driven by digitalization, the exponential growth of available data, and the increasing complexity of economic systems. In this context, forecasting stock price movements has become a major challenge for investors, financial institutions, and researchers. Since stock prices are influenced by a wide range of economic, political, and psychological factors, predicting future market behavior remains a complex task.

Recent advances in **Artificial Intelligence (AI)**, particularly **Deep Learning**, have opened new perspectives for analyzing and forecasting financial time series. Deep learning models are capable of automatically extracting meaningful patterns and capturing complex non-linear relationships from large volumes of historical market data, making them well suited for stock market prediction.

Among these models, **Long Short-Term Memory (LSTM)** networks, a specialized type of **Recurrent Neural Network (RNN)**, have demonstrated strong performance in modeling sequential financial data. Their ability to learn long-term temporal dependencies enables them to produce more robust predictions for stock price movements.

This project investigates the application of deep learning techniques to stock market forecasting. Beyond its academic interest, the study also addresses practical challenges faced by financial professionals in an increasingly competitive investment environment.

---

# Research Question

The primary objective of this project is to evaluate the predictive performance of deep learning models, particularly **LSTM neural networks**, in forecasting stock prices.

The main research question addressed in this study is:

> **To what extent can LSTM models capture the temporal dynamics of financial time series and provide accurate and reliable stock price predictions in both the short and long term?**

---

# Project Structure

This repository is organized into several sections that reflect the complete workflow of the project:

- **Exploratory Data Analysis (EDA):** Data collection, preprocessing, visualization, and statistical analysis of Société Générale (GLE.PA) historical stock prices.
- **Technical Analysis:** Analysis of stock price trends and market behavior using financial indicators and visualization techniques.
- **EMA Forecasting:** Implementation of the Exponential Moving Average (EMA) model for short-term stock price forecasting.
- **Deep Learning:** Theoretical background and implementation of the Long Short-Term Memory (LSTM) neural network for stock price prediction.
- **Model Evaluation:** Performance comparison of the forecasting models using **Mean Squared Error (MSE)** and graphical analysis of predicted versus actual closing prices.

---

# Dataset

The study is based on daily historical stock market data for **Société Générale (Ticker: GLE.PA)** covering the period **2000–2025**.

The dataset includes the following variables:

- **Date** – Trading date
- **Open** – Opening stock price
- **High** – Highest trading price
- **Low** – Lowest trading price
- **Close** – Closing stock price
- **Volume** – Number of traded shares

---

# Objectives

The objectives of this project are to:

- Perform an exploratory analysis of historical stock market data.
- Identify price trends through technical analysis.
- Forecast stock prices using the **Exponential Moving Average (EMA)**.
- Develop and train an **LSTM deep learning model**.
- Evaluate and compare forecasting performance.
- Demonstrate the potential of deep learning techniques for financial time series prediction.
