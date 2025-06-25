# 🔍 Data Dictionary

This document explains each variable used in the dataset and how it was recorded or derived for visualizations and insights.

---

## 🧑‍💼 Demographic Variables

| Column | Description |
|--------|-------------|
| `gender` | 0 = Male, 1 = Female |
| `age` | Age of respondent (in years) |
| `age_group` | Age range categories: '18–25', '26–35', '36–45', '46+' |
| `income_level` | Income level brackets (1 = below min wage, 7 = above 6x min wage) |
| `education_level` | Education level (1 = High School, 2 = College/University, 3 = Master's or PhD) |

---

## 🛍️ Purchase Behavior Variables

| Column | Description |
|--------|-------------|
| `purchase_frequency` | How often the person buys denim (e.g., once/year, 2–3 times/year) |
| `purchase_channel` | Where they buy denim: "Mağazalardan", "Online alışveriş siteleri", or both |
| `brand_preference` | Preferred brand type: "Hızlı moda markası", "Sürdürülebilir moda markası", "Yeşil koleksiyonlar", or "Emin değilim" |

---

## 🔒 Barriers to Sustainable Denim

Each barrier were multiselected by each consumers among various statements reasons not to buy a new sustainable jeans.

| Column | Description |
|--------|-------------|
| `barrier_awareness` | Selected: "Nereden alabileceğimi bilmiyorum" |
| `barrier_price` | Selected: "Çok pahalılar" |
| `barrier_new_concept` | Selected: "Sürdürülebilir kot diye bir şey ilk defa duyuyorum" |
| `barrier_habit` | Selected: "Alışveriş alışkanlıklarımı değiştirmek istemiyorum" |
| `barrier_variety` | Selected: "Hızlı moda markalarının seçenekleri daha fazla" |
| `barrier_knowledge` | Selected: "Kotun sürdürülebilir olup olmadığını anlamakta zorlanıyorum" |

---

## 🌱 Sustainability Feature Importance Ratings (Likert Scale 1–7)

Respondents rated how important each feature was when buying denim jeans
 (1 = Not Important, 7 = Extremely Important)

| Column | Description |
|--------|-------------|
| `importance_durability` | Durability of the jeans |
| `importance_organic_materials` | Use of organic materials |
| `importance_recycled_materials` | Use of recycled materials |
| `importance_biodegradable` | Biodegradable components |
| `importance_eco_friendly_dyeing` | Eco-friendly dyeing processes |
| `importance_ethical_production` | Ethical production practices |

---

## 🧠 Behavioral & Analytical Variables

| Column | Description |
|--------|-------------|
| `sustainable_purchase_history` | Evet = has bought sustainable denim before, Hayır = never |
| `sustainable_purchase_history_binary` | Recoded version: 0 = Hayır, 1 = Evet |
| `lack_of_awareness`, `price`, `habit`, etc. | Binary flags from barrier selection (1 = selected, 0 = not selected) |
| `Respondent Count` | Custom field for visualization (counts per group) |

---
