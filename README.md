

# Inventory-Optimization-Analysis
This project analyzes stock inflows, outflows, and balances across multiple retail stores using Power BI. The goal was to reduce overstocking, prevent stockouts, and improve overall supply efficiency.
# Inventory Optimization Analysis Report
## Executive Summary

This project analyzes stock inflows, outflows, and balances across multiple retail stores using data from the Inventory transactions table. Key findings reveal that Kano store received the highest inflow of Beans, while Rice is the most frequently moved product with the highest movement ratio. Beans showed risks of stockouts in some months, and seasonal trends significantly impacted inventory levels. By leveraging Power BI visuals and DAX measures, management can make informed decisions, avoid under/overstocking, and improve operational efficiency.

## Business Understanding

Business Challenge: Inefficient inventory distribution across stores.

Goals: Reduce carrying costs, minimize overstocking and understocking, and improve profitability through optimized stock management.

Importance: Inventory optimization ensures products are available when needed without tying up too much capital in excess stock.

## Data Understanding

Source: Inventory transactions table.

Key Fields: Date, Store, Product, Quantity In, Quantity Out, Unit Price.

Scope: Data covers multiple months across all stores.

Cleaning Steps: Removed null values, standardized product names, ensured correct date formatting.

## Methodology

Imported dataset into Power BI.

Cleaned data using Power Query.

Created calculated columns and DAX measures:

Net Stock = In – Out

Movement Ratio = Out ÷ In

Built visuals: bar charts, matrices, slicers.

Applied filters for store-level analysis.

## Insights & Recommendations

Rice: Most frequently moved product with strong customer demand.
🔹 Recommendation: Increase Rice supply to Kano and Lagos stores, especially during peak months. Negotiate bulk procurement to reduce costs.

Beans: Kano store recorded the highest inflow, but shortages occurred in some months.
🔹 Recommendation: Distribute Beans more evenly across stores and use transfers between stores to balance supply.

Maize: Some stores held excess stock while others faced shortages.
🔹 Recommendation: Redistribute excess stock, reduce future orders for overstocked stores, and use promotions to drive sales.

Seasonal Trends: Spikes during harvest and festive periods.
🔹 Recommendation: Plan procurement cycles in alignment with seasonal demand, use predictive models, and allocate extra logistics during peaks.

Net Stock Variation: Some stores were overstocked while others understocked.
🔹 Recommendation: Implement centralized monitoring in Power BI, automate redistribution, and train store managers on proactive practices.

## Conclusion

This analysis provided actionable insights into product inflows, outflows, and stock balances across stores. The findings help management reduce inefficiencies, prevent stockouts, and optimize supply.

<img width="1236" height="702" alt="Screenshot 2025-09-01 135722" src="https://github.com/user-attachments/assets/5584523c-5fac-4281-aafc-c69873c77dc7" />






