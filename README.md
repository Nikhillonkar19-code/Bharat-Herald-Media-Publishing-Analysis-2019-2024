# Bharat Herald Media & Publishing Analysis (2019–2024)

## 📖 Project Overview
Bharat Herald, a 70+ year-old legacy newspaper company in India, faced a steep decline in print circulation and ad revenue between 2019–2024.  
The company struggled to adapt to the post-COVID digital era, leading to failed digital pilots, bureau shutdowns, and advertiser loss.  

This project uses **SQL** and **Power BI** to analyze Bharat Herald’s operational and financial data, with the goal of identifying what went wrong and providing insights for a **phased digital transformation strategy**.

---

## 📊 Business Problem
- Print circulation dropped from **1.2M daily → under 560K (2019–2024)**.
- Competitors (DigiHindi Post, NewsZilla, InShorts) adapted quickly with mobile-first and WhatsApp delivery models.
- Bharat Herald’s **2021 e-paper pilot failed** due to poor mobile usability.
- Ad revenue declined, vendor payments delayed, multiple bureaus shut down, employees laid off.
- Urgent need to regain **readership, advertiser trust, and digital engagement**.

---

## 📌 Business Requests (SQL Analysis)
1. **Monthly Circulation Drop Check**  
   Find top 3 months (2019–2024) with sharpest month-over-month net circulation declines.  

2. **Yearly Revenue Concentration by Category**  
   Identify ad categories contributing >50% of yearly ad revenue.  

3. **2024 Print Efficiency Leaderboard**  
   Rank top 5 cities by print efficiency (net_circulation / copies_printed).  

4. **Internet Readiness Growth (2021)**  
   Find the city with the highest Q1→Q4 improvement in internet penetration.  

5. **Consistent Multi-Year Decline (2019–2024)**  
   Detect cities with strictly decreasing net circulation & ad revenue.  

6. **2021 Readiness vs Pilot Engagement Outlier**  
   Find cities with high digital readiness but low pilot engagement.  

---

## 📂 Datasets
- **fact_print_sales** (copies printed, copies sold, net circulation)  
- **fact_ad_revenue** (ad revenue by category & city)  
- **fact_city_readiness** (internet, literacy, smartphone penetration)  
- **fact_digital_pilot** (pilot engagement metrics)  
- **dim_city**, **dim_ad_category**  

---

## ⚙️ Tech Stack
- **SQL (MySQL)** → Data modeling & business request analysis  
- **Power BI** → Dashboards, data visualization  
- **Excel** → Data cleaning & validation  

---

## 📈 Key Insights
- 📉 **Print Decline**: Total printed copies fell from **44M (2019) → 33M (2024)**.  
- 📰 **Top Efficient Cities (2024)**: Ranchi, Jaipur, Kanpur, Mumbai, Bhopal (all ~90% efficiency).  
- 💰 **Ad Revenue**: Some categories still strong (private + commercial), but overall growth stagnated (only +1.38% over 5 years).  
- 🌐 **Digital Readiness**: Cities like **Kanpur & Varanasi** show strong readiness (>74) but weak engagement → prime targets for digital relaunch.  
- 📊 **Revenue per Copy**: Increasing in Varanasi & Jaipur → better monetization potential.  

---

## 🚀 Recommendations
1. **Phase-1 Digital Relaunch** → Prioritize Kanpur, Varanasi, and Lucknow.  
2. **Advertiser Strategy** → Rebuild trust in high-revenue cities (Patna, Mumbai, Jaipur).  
3. **Product Strategy** → Mobile-first content (WhatsApp bulletins, bite-sized news, optimized e-paper).  
4. **Revenue Models** → Subscription bundles, pay-per-article, loyalty programs.  
5. **Community Engagement** → Use local influencers/journalists for digital credibility.  

---

## 📊 Power BI Dashboard
You can view the interactive Power BI dashboard here:  
👉 [Bharat Herald Power BI Dashboard](https://app.powerbi.com/your-dashboard-link-here)  


---

## 📑 Documentation Download  
You can also download the project documentation with links here:  
📂 [Bharat_Herald_Project_Links.docx](https://github.com/Nikhillonkar19-code/Bharat-Herald-Media-Publishing-Analysis-2019-2024/blob/main/Business%20Request%20bharat%20herald.docx)  

---

## 📁 Repository Structure  
```plaintext
├── datasets/                 # Raw and processed datasets (fact & dimension tables)  
├── sql_queries/              # SQL scripts for all 6 business requests  
├── dashboard/                # Power BI dashboard (.pbix)  
├── docs/                     # Documentation & supporting reports  
│   └── Bharat_Herald_Project_Links.docx  
├── screenshots/              # Key visuals & result screenshots  
└── README.md                 # Project documentation (this file)  

