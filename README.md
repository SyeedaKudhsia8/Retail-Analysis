# 📊 Campaign Performance & Sales Analysis

This project involves analyzing marketing and sales data to uncover insights about product performance, campaign impact, and customer behavior over time.

---

## 📁 Datasets Overview

### `fact_events.csv`
Contains transaction-level data related to customer interactions. Each row represents a unique event, which may include product views or purchases. Key fields include:
- `event_id` – Unique identifier for each event
- `user_id` – The customer interacting with the product
- `product_code` – Foreign key to the products table
- `campaign_id` – Foreign key linking to the campaign table
- `event_time` – Timestamp of the event
- `quantity` – Number of units sold
- `sale_price` – Price at the time of sale

### `dim_products.csv`
Provides details about individual products:
- `product_code` – Unique product identifier
- `product_name`
- `category`
- `brand`

### `dim_campaigns.csv`
Metadata about marketing campaigns:
- `campaign_id` – Unique identifier
- `campaign_name`
- `start_date`
- `end_date`

---

## 🔍 Key Insights

- **Campaign Effectiveness Varies Significantly**  
  Some campaigns drove a clear uplift in sales volume and revenue, while others showed minimal impact, highlighting the importance of strategic timing and targeting.

- **Category-Level Differences**  
  Categories like **Electronics** and **Home Decor** demonstrated strong promotional responsiveness, while others remained relatively flat, suggesting differences in customer price sensitivity or demand elasticity.

- **Seasonal Trends Detected**  
  Clear seasonality was observed, with revenue peaking during major festival periods, indicating the need for inventory and marketing alignment during high-demand months.

- **Incremental Revenue Variance by Product**  
  A small number of products accounted for the majority of incremental revenue gains during promotions — suggesting the value of focused product-level campaign planning.

---

## 💡 Recommendations

1. **Double Down on High-Performing Products**  
   Identify and prioritize top products that consistently generate higher revenue during campaigns.

2. **Tailor Promotions by Category**  
   Implement targeted strategies per category — some categories benefit more from discounts, while others may perform better with bundling or loyalty offers.

3. **Leverage Festival Seasons**  
   Allocate greater marketing budget and inventory ahead of key seasonal spikes (e.g., Diwali) to capitalize on increased customer demand.

4. **Refine Underperforming Campaigns**  
   Evaluate campaigns with low ROI and experiment with adjusted messaging, timing, or channel mix to improve effectiveness.

5. **Use Data to Personalize Offers**  
   Analyze user behavior patterns in the `fact_events.csv` to create segmented, personalized campaign offers based on past interactions.

---

## 📈 Outcome

This analysis equips marketing and product teams with data-driven insights to make more informed decisions about campaign design, product promotion strategies, and inventory planning — ultimately maximizing ROI and enhancing customer engagement.

---

