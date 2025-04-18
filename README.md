# ML_CASE_STUDY
Email analysis case study for Quantacus.Ai
This project analyzes the performance of an e-commerce email marketing campaign and builds a predictive model to optimize future email sends for maximum click-through rates (CTR).

## 📌 Project Overview

The marketing team sent emails to a random sample of users about a new feature. This analysis:
1. Calculates key performance metrics (open rates, click rates)
2. Identifies patterns in different user segments
3. Builds a machine learning model to predict which users are most likely to click
4. Estimates potential CTR improvements from optimized targeting

## 📂 Dataset

Three tables are used:
1. `email_table.csv` - Information about each sent email
   - `email_id`, `email_text` (long/short), `email_version` (personalized/generic)
   - `hour`, `weekday`, `user_country`, `user_past_purchases`
2. `email_opened_table.csv` - IDs of opened emails
3. `link_clicked_table.csv` - IDs of emails where links were clicked

