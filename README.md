Problem Statement (Diwali Sales Data)

Retailers experience strong, short-term demand spikes around festivals such as Diwali, but often lack consolidated, timely analysis that quantifies which products, customer segments, and regions drive the majority of sales and margin during the event. This project analyzes the Diwali Sales Data dataset to provide an actionable dashboard and insights that answer: (1) total festival revenue and trend over the Diwali period, (2) top-performing SKUs and categories, (3) customer cohort behaviour and retention following promotions, and (4) inventory pressure points (stockouts / overstocked SKUs). The objectives are to reduce time-to-insight for merchandising and marketing decisions, prioritize SKUs for promotion and replenishment, and recommend targeted retention strategies for high-value customer cohorts.

Scope & inputs

Input: Diwali Sales Data.csv (expected columns: order_date, invoice_id/order_id, product_name / sku, category, quantity, price/unit, total_amount, customer_id, store/region, discount).

Outputs: cleaned dataset, EDA visuals, KPIs (total revenue, average order value, top SKUs contribution, cohort retention), and an interactive dashboard.

Success metrics

Identify top 10 SKUs that together contribute ≥ X% of festival revenue.

Reduce unclear inventory decisions by surfacing the top stockout SKUs.

Provide ≥ 3 actionable recommendations (promotions, reorder rules, retention campaigns).

Analysis outcome / Conclusion (templated for Diwali Sales dataset)

Replace bracketed placeholders below with numbers produced by the analysis script.

Key findings

Festival revenue & trend. Total sales revenue during the Diwali window was ₹[TOTAL_REVENUE]. Revenue peaked on [PEAK_DATE] with ₹[PEAK_DAY_REVENUE] and the top three peak days account for [PEAK_DAYS_PERCENT]% of total festival revenue — demonstrating strong short-term demand concentration.

Top SKUs drive most revenue. The top 10 SKUs by revenue generated ₹[TOP_10_SKUS_REVENUE], contributing [TOP_10_SKUS_PERCENT]% of total festival revenue. The top 10% of SKUs (by SKU count) account for [TOP_10PCT_CONTRIB]% of revenue — a high Pareto concentration that suggests targeted promotions and stock prioritization for those SKUs.

Customer behaviour & cohorts. New customers acquired during promotional days had an average order value of ₹[AOV_NEW] and a 30-day repeat rate of [REPEAT_30DAY]%, lower than the baseline repeat rate of [BASELINE_REPEAT]% for pre-festival customers. This suggests retention campaigns for festival-acquired cohorts could materially increase CLTV.

Inventory & fulfillment pressure. [N_STOCKOUT] SKUs experienced repeated stockouts during the peak window; conversely [N_SLOW] slow-moving SKUs tied up working capital. Rebalancing safety stock by velocity would reduce lost sales and holding costs.

Promotion effectiveness. Discounted transactions increased unit sales by [PROMO_LIFT]% on average for promoted SKUs, but margin per unit fell by [MARGIN_COMPRESSION]%. Recommend converting high-lift, high-margin promotions into bundles or loyalty offers rather than across-the-board percent discounts.

Recommendations

Prioritize replenishment and higher safety stock for the top 10% revenue-driving SKUs during festival windows.

Run retention-focused follow-ups (targeted coupons or cross-sell emails) for customers acquired during Diwali to raise 30–90 day retention.

Convert successful discount patterns into targeted, margin-preserving offers (bundles, free-shipping thresholds).

Instrument automated daily ETL and dashboards for next festival to reduce manual reporting time and enable real-time stock decisions.

Conclusion
Analysis of the Diwali Sales Data shows that a small set of SKUs and peak days drive the bulk of revenue. With targeted inventory prioritization and cohort-specific retention actions, the business can capture more sales during peak windows while protecting margin. Operationalizing the dashboard and automating key KPIs will convert these insights into measurable revenue and margin improvements for the next festival cycle.
