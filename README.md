# B2C Customer Segmentation Using RFM Analytics
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brigitterincon07-hub/ReglasasociacionTADC.ipynb/blob/main/RFM_B2_ADC.ipynb)
## 📌 Business Overview
In the B2C and retail sectors, understanding customer behavior is critical for designing effective marketing strategies, improving retention, and maximizing Customer Lifetime Value (CLV). This project implements an **RFM (Recency, Frequency, Monetary) Analytics Framework** to segment a B2C customer base. By evaluating how recently a customer purchased, how often they buy, and how much they spend, this model identifies high-value loyalists, customers at risk of churning, and opportunities for targeted re-engagement.

## 📊 The RFM Framework Explained
The dataset was processed to calculate three core metrics for each individual customer:
* **Recency (R):** Days since the customer's last purchase.
* **Frequency (F):** Total number of purchases made by the customer within the analyzed timeframe.
* **Monetary (M):** Total financial value spent by the customer.

Each metric was scored using quintiles (1 to 5), creating a combined RFM matrix to classify the customer base into actionable behavioral segments (e.g., *Champions, Loyal Customers, At Risk, Hibernating*).

## 🛠️ Methodology & Tech Stack
* **Language:** Python 3
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Data Engineering:** Automated aggregation of raw transaction logs into customer-level analytical records.
* **Statistical Segmentation:** Outlier detection and binning methods utilizing quantiles to establish robust boundaries for scoring R, F, and M.
* **Data Visualization:** Distribution analysis histograms and segment profiles to translate numeric boundaries into business context.

## 📈 Practical Business Applications & Insights
The outcomes of this model allow data-driven marketing and operations teams to execute:
1. **VIP Loyalty Campaigns:** Identifying "Champions" (555 scores) to offer exclusive previews or rewards, securing core revenue.
2. **Churn Prevention Pipelines:** Detecting "At Risk" segments (high monetary/frequency value but low recency) to launch automated win-back discount triggers.
3. **Reactivation Strategies:** Isolating "Hibernating" users to assess if re-acquisition costs are mathematically justified based on historical Monetary value.

## 🚀 How to Run the Project
1. Clone this repository.
2. Ensure you have the required libraries installed (`pip install -r requirements.txt` or standard data science environments).
3. Open the `.ipynb` file in Google Colab or Jupyter Notebook to view the complete pipeline, data profiles, and segmentation logic.
