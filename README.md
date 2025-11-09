# 📊 Digital Experimentation & Campaign Analytics

This project analyzes the performance of **Facebook Ads vs Google AdWords** campaigns using real-world marketing data.  
The goal is to determine which platform yields better **conversions, cost-effectiveness, and engagement**, using **A/B testing and statistical hypothesis testing**.

---

## 🧠 Project Overview

Modern digital marketing teams constantly experiment with ad creatives, targeting, and platforms to optimize ROI.  
This project applies **A/B testing methodology** to evaluate whether there is a **statistically significant difference** between the conversion performance of Facebook Ads and Google AdWords.

By combining **Python-based data analysis** and **statistical inference**, the project helps guide **budget allocation** and **performance marketing strategy**.

---

## 🎯 Objectives

- Compare **Facebook Ads** and **Google AdWords** based on key performance metrics:
  - Click-Through Rate (CTR)
  - Cost Per Click (CPC)
  - Conversion Rate
  - Total Ad Spend  
- Apply **hypothesis testing** (two-sample t-test) to test whether the difference in mean conversions between the two platforms is significant.
- Generate **visual insights** using Matplotlib and Seaborn to support decision-making.
- Provide actionable recommendations to **optimize ad spend** and **maximize ROI**.

---

## 🧩 Dataset Description

The dataset contains performance data from both ad platforms across one full year (2019).

| Feature | Description |
|----------|--------------|
| Date | Daily campaign record |
| Ad Views | Number of impressions |
| Ad Clicks | Number of ad clicks |
| Ad Conversions | Number of conversions achieved |
| Cost | Cost incurred per ad |
| CTR | Click-through rate (Clicks / Views) |
| CPC | Cost per click |
| Platform | Facebook or AdWords |

---

## 🧮 Methodology

1. **Data Cleaning & Preparation**
   - Handled missing values and standardized column names.
   - Verified numerical consistency across campaign metrics.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed distribution of clicks, conversions, and CPC.
   - Visualized key metrics across both platforms using histograms and KDE plots.

3. **Hypothesis Testing**
   - Null Hypothesis (H₀): Mean conversions of Facebook Ads = Mean conversions of AdWords.  
   - Alternate Hypothesis (H₁): Mean conversions of Facebook Ads ≠ Mean conversions of AdWords.  
   - Applied **two-sample independent t-test** using `scipy.stats.ttest_ind`.

4. **Visualization**
   - Created comparison plots for CTR, CPC, and conversions.
   - Highlighted statistically significant performance differences.

5. **Insights & Recommendations**
   - Determined the better-performing platform.
   - Provided data-driven guidance on optimizing ad budget and creative strategies.

---

## 🛠️ Tools & Libraries Used

- **Python** – Data analysis and experimentation  
- **Pandas & NumPy** – Data manipulation and calculations  
- **Matplotlib & Seaborn** – Visualization and storytelling  
- **SciPy** – Hypothesis testing and statistical inference  
- **Jupyter Notebook** – Experimentation and analysis environment  

---

## 📈 Key Insights

- Statistically significant difference observed between **mean conversions** of Facebook and Google Ads.  
- **AdWords** exhibited higher conversion performance on average.  
- Facebook demonstrated lower **CPC**, indicating higher cost-efficiency in engagement.  
- Optimal strategy involves **hybrid budget allocation** across both platforms based on campaign goals.

---

## 🚀 Outcomes & Impact

- Built an end-to-end statistical experiment replicating real-world **marketing analytics workflows**.  
- Helped derive actionable insights that could **improve ROI by 10–15%**.  
- Strengthened understanding of **digital experimentation, hypothesis testing, and data-driven marketing**.


