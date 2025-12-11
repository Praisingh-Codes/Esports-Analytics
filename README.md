## Esports Decision Intelligence Framework: Predictive Models for Players, Teams & Viewership

![Esports Analytics Poster Banner](https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/resources/esports_analytics_poster_bannner.png)

#### Project Overview

<div align="justify">This project delivers a complete analytics + machine learning + forecasting ecosystem for the esports industry combining player earnings, team performance, Twitch ecosystems, and global revenue trends.</div>

#### Architecture Diagram

![Esports Analytics Architecture](https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/resources/esports_analytics_architecture_diagram.png)

#### Key Visual Insights

These visuals represent the core story of esports economics, audience behavior, and predictive intelligence.

1️⃣ Top Games by Player Earnings

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/top%2010%20players%20by%20earnings.png" width="80%">

2️⃣ Top Games by Team Earnings

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/top%2010%20teams%20by%20earnings.png" width="80%">

3️⃣ Continent Share of Player Earnings

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/player%20earnings%20by%20continent.png" width="80%">

4️⃣ Esports Revenue Growth (2020–2025)

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/global%20gaming%20revenue%20trend%20(2020–2025).png" width="80%">

5️⃣ Esports Audience Growth (2020–2025)

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/global%20esports%20audience%20trend%20(2020–2025).png" width="80%">

6️⃣ Top Streamers by Hours Watched

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/average%20vs%20peak%20viewers%20(twitch%20games).png" width="80%">

7️⃣ Average vs Peak Viewers (Twitch Games)

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/team%20clusters%20(k-means)%20prize%20vs.%20tournaments.png" width="80%">

8️⃣ Team Performance Clusters (K-Means)

<img src="https://raw.githubusercontent.com/Praisingh-Codes/Esports-Analytics/main/plots/top%20streamers%20by%20hours%20watched.png" width="80%">

#### What the Full Project Covers

All insights are included in the notebook only the essential visuals appear in the README.

-- Player & Team Ecosystem

✔ Earnings distribution (KDE + histogram)

✔ Genre-based financial analysis

✔ Inequality metrics (skewness, kurtosis)


-- Geographic & Market Intelligence

✔ Continent share of earnings

✔ Regional revenue & audience trends

✔ Country-level esports performance

-- Twitch Ecosystem Analysis

✔ Distribution of followers & viewers

✔ Partner vs non-partner statistical difference (Welch t-test)

✔ Average vs peak viewer correlations

✔ Top streamers and top game categories

-- Advanced Statistical Analysis

✔ QQ plots for normality checks

✔ Outlier detection (z-score)

✔ Variance, skewness, kurtosis metrics

-- Machine Learning Models

✔ Popularity Tier Classifier (Accuracy: 0.89)

✔ Confusion Matrix

✔ K-Means Team Segmentation

Time Series Forecasting (2026–2030)

✔ ARIMA forecast for gaming revenue

✔ Confidence intervals

✔ Forecast volatility analysis

#### Key Metrics Summary

-- Esports Economy (Players & Teams)

| **Metric**                   | **Value**           |
|-----------------------------|----------------------|
| Player Earnings Skewness    | 4.83                 |
| Team Earnings Skewness      | 10.22                |
| Player Earnings Variance    | Very High            |
| Team Prize Inequality       | Extremely High       |

-- Esports Market Growth (2020–2025)

| **Metric**       | **Value** |
|------------------|-----------|
| Revenue CAGR     | 0.30%     |
| Audience CAGR    | 0.87%     |

-- Twitch Ecosystem Insights

| **Insight**                            | **Value**                     |
|----------------------------------------|-------------------------------|
| Welch t-test (partner vs non-partner)  | p = 0.0306 (significant)      |
| Streamer outliers                      | z - value missing             |

#### Machine Learning Performance

-- Popularity Tier Classifier

- Accuracy: 0.89

- High Tier Recall: 0.87

- Low Tier Recall: 0.95

- Medium Tier Recall: 0.83

-- Team Clustering (K-Means)

- Clusters show separation based on:

- Prize pool dominance

- Tournament activity volume

#### Forecast (2026–2030)

| **Year** | **Forecasted Revenue (Billion USD)** |
|---------|---------------------------------------|
| 2026    | 93.14                                 |
| 2027    | 91.89                                 |
| 2028    | 92.07                                 |
| 2029    | 92.04                                 |
| 2030    | 92.05                                 |

Confidence Interval Range: −15.7B to 199.8B (High Volatility)

#### How to Run

pip install -r requirements.txt

jupyter notebook esports_analysis_code.ipynb

#### Key Takeaways

- Esports prize pools are extremely top-heavy — inequality dominates.

- Asia & Europe lead in both player earnings and market revenue.

- Twitch creator ecosystem shows strong top-1% dominance.

- Partnered streamers have statistically higher viewership.

- Forecasting suggests stable but slow growth with high uncertainty.

- ML models provide segmentation & prediction useful for esports orgs.
