# FreshCart Supply Chain Performance Analysis

## Overview
This project analyzes 488 orders across 9 suppliers, 5 warehouses, 
and 5 product categories for FreshCart, a fictional grocery supply 
chain operator, to identify performance gaps and recommend improvements.

## Business Problem
FreshCart's supply chain shows signs of delivery unreliability and 
poor inventory efficiency. This analysis quantifies the gaps, 
identifies root causes, and provides actionable recommendations.

## Tools Used
- Microsoft Excel (data cleaning, KPI calculation, 
  pivot tables, dashboard)

## Dataset
FreshCart Internal Order Data — 488 records | January–December 2023
Fields: Order ID, Supplier, Product Category, Warehouse, Units 
Ordered, Units Shipped, Revenue, COGS, Lead Time, Delivery Days

## Key Findings
- Overall On-Time Delivery Rate is 88.7% against a 95% target
- Nova Cold Logistics is the worst performing supplier at 71% OTDR
- Frozen products have the highest revenue per unit ($22.11) but 
  the most late deliveries (11) — highest risk category
- Inventory Turnover of 2.03 is critically below the 8-12 target 
  — FreshCart is carrying 179 days of stock vs a 30-45 day target
- WH-D handles 49% of all Bakery shipments this can turn into a single point of 
  failure 

## KPI Summary
| KPI | Result | Target | Status |
|-----|--------|--------|--------|
| On-Time Delivery Rate | 88.7% | 95% | Needs Improvement |
| Order Fill Rate | 99.4% | 98% | Target Reached |
| Inventory Turnover | 2.03x | 8-12x | Below Target |
| Days of Stock | 179.7 days | 30-45 days | Above Target |

## Files in this Repository
- `FreshCart_SCAnalysis_Saffan_Nagani.pdf` — full case study
- `FreshCart_SCAnalysis_Saffan.xlsx` — Excel workbook with 
  cleaned data, KPI calculations, pivot tables, and dashboard

## Author
Saffan Nagani | www.linkedin.com/in/saffan-nagani-966995361
