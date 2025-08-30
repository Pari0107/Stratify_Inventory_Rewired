# STRATIFY
## Business Analytics Bootcamp – 2025
## Inventory Rewired


### Project Overview
Inventory Rewired aims to optimize inventory and replenishment decisions across a fictional retail supply chain to reduce stockouts and excess inventory holding costs by 10% over a simulated 3-month horizon. The project focuses on Retail Craft Pvt. Ltd., which operates 3 urban stores in India with a portfolio of 10 SKUs, dealing with issues of stockouts for fast movers and overstock for slow-moving SKUs.

### Code Summary

**1. Inventory Control Policy Computation (Ss_policy script)**

- Loads sales and SKU master data from Excel.
- Calculates average demand and demand variability per SKU.
- Applies a (s, S) reorder policy incorporating lead times and supplier delay rates.
- Considers SKU shelf life constraints in order calculations.
- Outputs reorder points, order-up-to levels, and suggested order quantities per SKU.
- Saves results into an Excel file Ss_policy_results.xlsx.

**2. Replenishment Simulation and Inventory Tracking**

- Loads inventory, SKU parameters, demand comparison data from Excel.
- Integrates reorder points and lead time adjustments (including delay rates).
- Simulates daily inventory movements and customer demand fulfillment across three store locations.
- Implements order placement logic based on reorder points and current stock.
- Distributes incoming inventory equitably across stores.
- Tracks stock-outs, purchase orders, and daily inventory levels.
- Outputs detailed Excel reports: stockouts_full_report.xlsx, purchase_orders_full_report_expanded_distribution.xlsx, and daily_inventory_report.xlsx.
