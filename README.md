# Stock Portfolio Optimizer

This project presents a stock portfolio optimization model developed using historical stock price data and mathematical optimization techniques. It was completed as part of the *Business Decision Modeling (OPIM 5641)* course at the University of Connecticut.

## 📌 Project Overview

The goal of this project is to build a sector-diversified stock portfolio by:

- Analyzing historical data (2017–2022) for selected stocks in **healthcare**, **communication**, and **real estate** sectors
- Performing exploratory data analysis (EDA) to understand trends and correlations
- Constructing an **optimization model** using [Pyomo](http://www.pyomo.org/) to find the best portfolio weights
- Balancing return maximization with risk constraints

## 💼 Stock Tickers Used

- **Healthcare:** CVS, ABT, JNJ  
- **Communication:** T, NFLX, EA  
- **Real Estate:** OHI, PK, EXR

## ⚙️ Tech Stack

- **Python** (pandas, matplotlib, seaborn)
- **Yahoo Finance API** via `yahoo_fin`
- **Optimization** using `pyomo`
- **Google Colab / Jupyter Notebook` environment

## 📊 Key Features

- Automated stock data retrieval (2017–2022)
- Portfolio return and volatility calculations
- Customizable constraints for portfolio selection
- Linear programming-based optimization for investment allocation

## 📁 File Contents

- `Final_BDM_project.ipynb`: Complete notebook with data acquisition, EDA, and optimization logic

## 🧠 Authors

- Yash Parihar  
- Priyanka Garg

## 📅 Date

June 24, 2025

## 📜 License

This project is for educational purposes only. No investment advice is implied.
