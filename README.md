# Indian-Airline-Customer-Sentiment-Analysis
Indian Airline Customer Sentiment Analysis, uses Python and popular data science libraries (Pandas, Matplotlib, Seaborn) to analyze customer review data for major Indian airlines. The goal is to extract actionable business intelligence by visualizing rating distributions, sentiment trends over time, and identifying key pain points
# ✈️ Indian Airline Customer Sentiment Analysis

## Project Overview

This data analysis project provides strategic business insights by analyzing customer reviews for several major Indian airlines. The core objective is to move beyond simple descriptive statistics to identify **actionable metrics** for future decision-making in areas like customer retention, operational investment, and marketing strategy.

The analysis is performed entirely within a Jupyter Notebook (`AirLineProject.ipynb`) and relies on standard Python data science libraries.

## Key Features & Insights

* **Polarization Analysis:** Uses Violin Plots and Swarm Plots to visualize the highly polarized nature of customer ratings (dense clusters at 1/10).
* **Time-Series Tracking:** Employs Stacked Area Charts and Heatmaps to monitor shifts in positive vs. negative sentiment over time.
* **Strategic Decision Queries:** Generates three core tables designed to drive immediate business action:
    1.  **Detractor Volume:** Identifies which airline has the highest count of 1/2 star reviews (Retention Priority).
    2.  **Staff Issue Count:** Pinpoints airlines where low ratings frequently mention staff/crew (Operational Focus).
    3.  **Recommendation Rate Trend:** Tracks monthly changes in sentiment to inform marketing efforts.
* **Verification Bias:** Compares rating distributions between verified and unverified reviews using Faceted Histograms.

## 💾 Repository Structure
## 🛠️ Setup and Installation

### Prerequisites

You must have **Python 3.x** installed. We highly recommend using the **Anaconda** distribution, which includes all necessary libraries.

### 1. Clone the Repository

```bash
git clone [https://github.com/1Ibraheem7/Indian-Airline-Customer-Sentiment-Analysis]
cd Indian-Airline-Customer-Sentiment-Analysis
