## 📁 Retail Campaign Analytics 

### 📂 Dataset Overview

This project leverages a collection of retail datasets designed to evaluate campaign effectiveness and sales performance across various stores and products. The datasets are structured to simulate a realistic retail environment with promotions, stores, products, and transactional events.

#### Included Dataset Files:

1. **`fact_events.csv`**
   - Contains the primary transactional data.
   - Includes event metadata such as event type, store ID, product code, campaign ID, and timestamp.
   - Used to analyze purchase behavior, link events to campaigns, and compute revenue.

2. **`dim_products.csv`**
   - Metadata for each product.
   - Fields include product code, name, category, sub-category, brand, base price, etc.
   - Essential for revenue calculation and category-wise insights.

3. **`dim_campaigns.csv`**
   - Contains campaign-related information.
   - Includes campaign ID, campaign name, start and end dates, and promotion type.
   - Key for determining before/after campaign metrics.

4. **`dim_stores.csv`**
   - Metadata about each store.
   - Fields include store ID, store type, city, and zone.
   - Useful for zone-level and store-type-specific performance evaluations.

5. **`retail_events_db.sql`**
   - SQL schema definition used for creating the database structure if working with SQL instead of CSVs.
   - Defines relationships between fact and dimension tables.

---

### 📈 Key Insights Derived

- **Promotional Effectiveness**:
  - Certain campaigns demonstrated a clear uplift in revenue and quantity sold post-promotion, especially those involving discount-based promos.
  - Promotional types like "BOGO" and "Discount" led to higher incremental sales in specific product categories.

- **Category Performance**:
  - High-impact categories during peak campaigns like "Diwali" include electronics and personal care.
  - Some low-performing categories revealed poor promotional ROI, highlighting areas for either improvement or deprioritization.

- **Store and Zone Trends**:
  - Urban zones had more consistent revenue trends across months, while Tier 2 zones showed higher seasonal spikes.
  - Certain store formats (e.g., Supermarkets) performed better in promotions compared to convenience stores.

- **Seasonal Trends**:
  - Revenue trends showed clear seasonality, with spikes in revenue during festive months like October and December.
  - Post-campaign months often saw slight dips, suggesting the importance of sustained marketing strategies.

---

### 📌 Recommendations

- **Focus on Data-Driven Promotions**:
  - Use past promotional performance to design future campaigns. Invest more in high-ROI categories and revise strategies for underperforming ones.

- **Category Optimization**:
  - Prioritize promotional efforts for categories with consistent incremental revenue lift. Reevaluate or rotate underperforming categories.

- **Geo-Targeted Campaigns**:
  - Personalize campaigns based on store location and zone performance. For example, launch high-discount campaigns in Tier 2 zones during festivals.

- **Inventory and Resource Planning**:
  - Leverage seasonal revenue trends to align inventory stocking and workforce management with demand surges.

- **Long-Term Retention Strategy**:
  - Create loyalty programs to convert promo-based buyers into regular customers, reducing revenue dips post-campaigns.

