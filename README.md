# 💄 Sephora Product Value Analysis

Welcome to my data storytelling project! This analysis explores the *Sephora product catalog* with a focus on how much *value* customers get for the price they pay. We dig into product ratings, review counts, pricing insights, and category trends to discover meaningful patterns and business-worthy takeaways.

---

## 📌 Objective
To analyze Sephora's product data and uncover which products and categories offer the best value for money, attract the most customer engagement, and maintain *high customer satisfaction*.

---

## Dataset Overview
- *Rows:* 9,179
- *Columns:* Product info like brand, category, price, value_price, rating, number_of_reviews, and likes
- *Focus Metric:* best_value_score = value_price / price

---

## 📈 Best Value Score vs Customer Rating

![Image](https://github.com/user-attachments/assets/99031113-9486-487f-af95-ce4d205783cb)

 *Insight:*  
 Interestingly, products with a *lower best value score* (i.e., fair pricing without major discounts) still tend to receive *higher customer ratings*. This suggests that *product quality and satisfaction may matter more than discount size alone*.

---

##  Top 10 Brands by Average Rating

![Image](https://github.com/user-attachments/assets/cc08a803-01a9-4bb7-8fe8-3c5a48cdb6b8)

 *Insight:*  
 *The Art of Shaving* appears to have the highest customer ratings, followed closely by *Carolina Herrera* and *Better Not Younger*. These brands demonstrate strong customer satisfaction even without being the most reviewed.

📌 *Business Context:*  
- These brands may be strong candidates for *"Top Rated Picks"* sections or promotional campaigns based on quality-focused appeal.

---

##  Top 10 Brands by Total Reviews

![Image](https://github.com/user-attachments/assets/877cc985-11ac-4374-b61a-a01620745c2f)

 *Insight:*  
 Brands like *Sephora Collection*, *Rare Beauty*, and *Tarte* lead in *total review count*, suggesting broad customer engagement and visibility.

📌 *Business Context:*  
- These high-visibility brands could be considered for *homepage placement*, *brand partnerships*, or customer loyalty initiatives.

---

## Average Best Value Score by Category

![Image](https://github.com/user-attachments/assets/45ec95f5-4db7-412c-a353-8100b96c39e2)

 *Insight:*  
 Categories such as *Curls & Coils*, *Value & Gift Sets*, and *Eye Sets* reflect a higher average best_value_score, indicating these categories tend to offer greater perceived value.

📌 *Business Context:*  
- These categories may benefit from additional promotion in *"Best Value Deals"* or *holiday campaigns*, given their perceived savings potential.

---

##  Distribution of Best Value Score

![Image](https://github.com/user-attachments/assets/c04ade4f-b69f-4565-a3c4-8ccfeedcee16) 
*Insight:*  
 The majority of products cluster around a best value score of *1.0*, indicating that most products are priced close to their perceived value. A smaller set of products offers higher scores, often bundles or special sets that offer more for less.

📌 *Business Context:*  
- Products with high best value scores might be effective candidates for *value-driven campaigns* or featured in *budget-friendly filters*.

---

## Final Takeaways

✅ *Product quality matters more than deep discounts*: High ratings occur even at fair pricing levels.  
✅ *Gift sets and bundles deliver value*: Bundled categories tend to outperform in terms of best value score.  
✅ *Popularity vs satisfaction*: Some brands attract reviews through reach, while others earn loyalty through satisfaction — both offer strategic strengths.

---

## 📌 About This Project
This analysis was done using *Python (Pandas, Seaborn, Matplotlib)* in Jupyter Notebook. It's part of my *data analyst portfolio*, showcasing how I turn raw data into strategic insights for business and product decisions.

> ✨ If you're a recruiter, hiring manager, or just someone who loves data — I hope you enjoyed reading this! Let's connect on LinkedIn or GitHub to chat more about data storytelling and analytics.

---

Thanks for stopping by! 🙌
