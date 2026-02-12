# 🏆Mapping-Innovation-trends-A-Time-Series-Analysis-of-Nobel-Prize-Winners

**A comprehensive audit of global achievement (1901–2023) utilizing longitudinal data to identify shifts in geographic dominance and demographic evolution.**

## 📌 Project Overview
Since 1901, the Nobel Prize has tracked the frontiers of human knowledge. This project leverages a century-scale dataset from the Nobel Prize API to conduct a **Time-Series Analysis**, uncovering how the "landscape of genius" has evolved across six categories. By binning data into decades, we can visualize the rise and fall of national dominance and the slow progress toward gender parity.

---

## 🛠️ Technical Arsenal
- **Analysis:** Python (Pandas for time-series binning, NumPy for statistical operations)
- **Visualization:** Seaborn & Matplotlib (Multi-line trend plots)
- **Key Techniques:** Time-Series Binning, Boolean Indexing, Proportion Analysis, Multi-variate Aggregation..

## 📈 Policy Insights
1. The Geographic Shift (1940s–1950s): The data reveals a massive "inflection point" post-1940. By analyzing the usa_born_winner metric, we can see the rise of the US as the global hub for scientific innovation, largely correlating with increased R&D investment during the mid-20th century.
2. The Diversity Velocity: While gender representation is increasing, the Time-Series Analysis identifies specific "lag categories" (e.g., Physics). This insight is vital for organizations aiming to direct funding toward under-represented fields in STEM.
3. Repeat Innovation Patterns: We isolated an elite $0.5\%$ of winners who have won multiple prizes. From a "Human Capital" perspective, these individuals represent the ultimate ROI in scientific mentorship.

## 📂 Project Structure
- `/data`: `nobel.csv` (Records from 1901-2023).
- `/notebooks`: Interactive Time-Series Analysis.
- `/src`: Python scripts for data cleaning.
- `requirements.txt`: Environment configuration.

## 🚀 Key Results
| Metric | Historical Trend |
| :--- | :--- |
| **Peak US Dominance** | 2000s (Highest proportion of winners) |
| **First Female Milestone** | Marie Curie (1903 - Physics) |
| **Highest Female Growth** | Peace and Literature (21st Century) |

---
![Global Innovation Trends](images/nobel_trends.png)

## 👩‍💻 Author
**Olayinka Agbaje** | Data Scientist
[LinkedIn](www.linkedin.com/in/olayinka-agbaje-188102224) | [Email](mailto:olayinkaagbaje01@gmail.com)
