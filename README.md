# 🛍️ E-Commerce Customer Segmentation - RFM Analysis

Customer segmentation project using RFM (Recency, Frequency, Monetary) analysis 
on real UK e-commerce data from Kaggle.

## 📊 What is RFM?
- **Recency** → How recently did the customer purchase?
- **Frequency** → How often do they purchase?
- **Monetary** → How much do they spend?

## 👥 Customer Segments Found
| Segment | Count | Description |
|---------|-------|-------------|
| 👑 Champions | 1300 | Best customers - buy often, spend most |
| 💚 Loyal Customers | 1403 | Buy regularly |
| ⚠️ At Risk | 824 | Used to buy often, haven't returned |
| 🔴 Lost | 1275 | Haven't purchased in a long time |
| 🌱 New Customers | 443 | Bought recently but not often |
| 🔵 Potential | 633 | In between segments |

## 🔍 Key Findings
- Champions spend on average **8000+ GBP** and order **16+ times**
- At Risk customers are high value but haven't returned in **300+ days**
- 21.7% of customers are completely **Lost**

## 🛠️ Tools Used
- Python, Pandas, Matplotlib, Seaborn, NumPy

## 📁 Dataset
- [UCI Online Retail II Dataset](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci) via Kaggle
- 1,067,371 transactions from a UK online retailer
