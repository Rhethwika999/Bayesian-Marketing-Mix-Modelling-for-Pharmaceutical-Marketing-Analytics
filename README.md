# 📈 Bayesian Marketing Mix Modelling for Pharmaceutical Marketing Analytics

## Overview

This project demonstrates the development of a **Bayesian Marketing Mix Model (MMM)** to evaluate the effectiveness of marketing investments and quantify the contribution of different media channels towards product sales.

Using Google's **LightweightMMM** framework, I built an end-to-end Bayesian Marketing Mix Model on a realistic pharmaceutical sales dataset to estimate channel contribution, analyse media effectiveness, understand diminishing returns, and optimise marketing budget allocation.

Unlike traditional predictive models, Marketing Mix Modelling focuses on explaining **why sales change over time** by incorporating marketing activities, seasonality, and external business drivers into a statistically interpretable framework.

---

# Business Problem

Marketing teams invest significant budgets across multiple channels, but determining which channels genuinely contribute to incremental sales remains challenging.

Sales are influenced not only by advertising, but also by external factors such as seasonality, consumer behaviour, and market conditions. The objective of this project is to separate these effects and quantify the contribution of each marketing channel, enabling data-driven marketing investment decisions.

---

# Project Objectives

- Develop an end-to-end Bayesian Marketing Mix Model.
- Analyse pharmaceutical sales and marketing investment data.
- Measure the effectiveness of multiple marketing channels.
- Model advertising carry-over effects using Bayesian techniques.
- Estimate marketing channel contribution and Return on Investment (ROI).
- Analyse diminishing returns through response curves.
- Optimise future marketing budget allocation.
- Generate actionable business insights to support strategic decision-making.

---

# Dataset

This project uses realistic **synthetic pharmaceutical sales datasets** designed to simulate real-world over-the-counter (OTC) product sales and marketing behaviour.

### Datasets Included

### • cough_and_cold_sales.csv

Represents weekly sales of an OTC cough and cold product.

Features include:

- Weekly sales
- Marketing channel investments
- External business drivers
- Seasonal demand patterns
- COVID-19 market impact

---

### • pain_killer_sales.csv

Represents weekly sales of an OTC pain relief product with lower seasonal variation.

Includes:

- Sales
- Marketing investments
- Marketing cost information
- External business variables

---

### • simple_data_sample.csv

A simplified dataset used for understanding the core principles of Marketing Mix Modelling.

---

# Tech Stack

### Programming

- Python

### Data Manipulation

- Pandas
- NumPy

### Bayesian Marketing Mix Modelling

- Google LightweightMMM

### Numerical Computing

- JAX
- JAX NumPy

### Visualisation

- Matplotlib

---

# Project Workflow

## 1. Data Loading

- Imported historical sales data.
- Loaded marketing investment variables.
- Integrated external business factors.

---

## 2. Exploratory Data Analysis

Performed exploratory analysis to understand:

- Sales trends
- Marketing spend distribution
- Seasonal patterns
- Relationships between variables
- Data quality issues

---

## 3. Data Preparation

Prepared model-ready data through:

- Missing value assessment
- Feature scaling
- Data normalization
- Media variable selection
- Control variable preparation

---

## 4. Bayesian Marketing Mix Modelling

Developed a Bayesian Marketing Mix Model using Google's LightweightMMM framework to estimate the contribution of each marketing channel while accounting for uncertainty in model parameters.

The model estimates:

- Baseline sales
- Media contribution
- Seasonal effects
- Marketing effectiveness
- Posterior parameter distributions

---

## 5. Model Diagnostics

Evaluated model quality using Bayesian diagnostics, including:

- Posterior distributions
- Credible intervals
- Convergence analysis
- Parameter uncertainty

---

## 6. Marketing Effectiveness Analysis

Analysed:

- Channel contribution
- Marketing ROI
- Incremental sales
- Response curves
- Diminishing returns
- Channel efficiency

---

## 7. Budget Optimisation

Applied Google's optimization framework to recommend improved allocation of marketing budgets across different channels in order to maximise expected sales while considering diminishing returns.

---

# Key Marketing Mix Modelling Concepts

This project demonstrates practical implementation of:

- Bayesian Marketing Mix Modelling
- Bayesian Regression
- Adstock Transformations
- Media Carry-over Effects
- Saturation (Diminishing Returns)
- Marketing Response Curves
- Channel Attribution
- Incremental Sales Estimation
- Marketing ROI
- Budget Optimisation
- Bayesian Inference
- Posterior Distributions
- Credible Intervals

---

# Skills Demonstrated

### Data Analytics

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Visualisation

### Machine Learning & Statistics

- Bayesian Statistical Modelling
- Marketing Mix Modelling
- Econometric Modelling
- Marketing Analytics
- Predictive Analytics
- Model Evaluation

### Business Analytics

- Marketing Performance Analysis
- Media Effectiveness Measurement
- ROI Analysis
- Budget Optimisation
- Business Insight Generation

---

# Key Outcomes

This model enables businesses to:

- Quantify the contribution of individual marketing channels.
- Understand which channels generate the highest return on investment.
- Measure the impact of diminishing returns on media spend.
- Optimise future marketing budget allocation.
- Support data-driven marketing strategy and investment decisions.

---

# Repository Structure

```text
.
├── mmx_linear_model_example.ipynb
├── mmx_bayesian_model_example.ipynb
├── datasets
│   ├── cough_and_cold_sales.csv
│   ├── pain_killer_sales.csv
│   └── simple_data_sample.csv
└── README.md
```

---

# Future Enhancements

- Compare Bayesian MMM with traditional OLS, Ridge, and Lasso regression models.
- Incorporate real-world marketing datasets.
- Integrate incrementality testing and Geo experiments.
- Extend the framework to multi-brand marketing optimisation.
- Build an interactive dashboard for marketing scenario planning.

---

## References

- Google LightweightMMM
- JAX
- Bayesian Marketing Mix Modelling
