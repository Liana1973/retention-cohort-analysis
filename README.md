# 📊 User Retention & Cohort Analysis for a Subscription App  
# 📊 Анализ удержания пользователей и когорт для подписочного приложения  

---

## 🧠 Project Overview / Обзор проекта

**EN:**  
This project simulates a real-world product analytics scenario for a subscription-based mobile application.  
The goal is to analyze user retention, churn behavior, and subscription patterns to identify actionable insights that can improve user engagement and reduce churn.

**RU:**  
Проект моделирует реальную задачу продуктовой аналитики для мобильного приложения с подпиской.  
Цель — проанализировать удержание пользователей, отток и поведение подписчиков, чтобы найти инсайты для повышения вовлеченности и снижения оттока.

---

## 🎯 Business Problem / Бизнес-проблема

**EN:**  
The product team observed declining retention and high churn rates but lacked clarity on the key drivers.  
This analysis aims to identify factors influencing retention and provide data-driven recommendations.

**RU:**  
Команда продукта столкнулась с высоким оттоком пользователей и снижением удержания.  
Цель анализа — определить ключевые факторы и предложить решения на основе данных.

---

## 📊 Key Business Metrics / Ключевые метрики

- Retention Rate  
- Churn Rate  
- User Lifetime  
- Conversion to Paid  

---

## 📂 Dataset / Данные

The dataset includes three tables:

- **users.csv** — user demographics & acquisition channel  
- **activity.csv** — daily user activity  
- **subscriptions.csv** — subscription plans and payments  

---

## 📈 Key Analyses / Основные анализы

- Cohort Analysis (Retention Matrix)  
- Churn Analysis  
- Subscription Behavior Analysis  
- Statistical Testing:
  - T-test  
  - ANOVA  
  - Chi-Square  
- Correlation Analysis  

---

## 🔍 Key Insights / Ключевые выводы

- Organic users show **2x higher retention** compared to paid users → marketing efficiency should be reviewed  
- Monthly plan users churn significantly faster than annual users → pricing strategy impacts retention  
- Early user activity strongly correlates with long-term retention → onboarding experience is critical  

---

## 🚀 Business Recommendations / Рекомендации

- Focus on organic acquisition channels to improve retention quality  
- Improve onboarding experience to increase early engagement  
- Promote annual subscription plans to reduce churn  
- Monitor early user activity as a leading indicator of retention  

---

## 🛠 Tech Stack

- Python (Pandas, NumPy)  
- Data Visualization (Matplotlib, Seaborn)  
- Statistical Analysis  
- Cohort Analysis  

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/cohort_analysis.ipynb
