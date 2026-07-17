# Umico-E-commerce-Data-Analysis

## Project Overview

This project analyzes sales and order cancellation data for **Umico**, an e-commerce/marketplace platform, through a 3-page interactive Power BI report (**Introduction, Main Dashboard, Problem Analysis**). The main objective is to help business stakeholders understand *why* orders get cancelled, quantify the resulting revenue loss, and identify which categories, brands, partners, and payment methods carry the highest cancellation risk.

## Technical Analysis & Key Work

- **Data Modeling & DAX Measures:** Beyond basic reporting, custom DAX measures were built to translate raw order data into business KPIs — including **Total Sales**, **Order Count**, **Cancellation Rate (Ləğv%)**, and **Lost Revenue (İtirilmiş gəlir)** — enabling stakeholders to see the direct financial impact of cancellations at a glance.
- **Risk & Root-Cause Analysis:** Cancellation patterns were cross-analyzed across **product category, brand, partner, payment method, and day of the week**, using a dedicated Risk Filter to isolate high-risk segments driving the majority of lost revenue.
- **Advanced Visualizations:** Standard bar/line charts weren't enough to tell this story, so custom visuals were used to reveal deeper patterns:
  - **Tornado Chart** — to compare cancellation rates across categories/partners side-by-side.
  - **Heatmap** — to spot cancellation concentration by day of week and category.
  - **Radial Chart** — to visualize proportional contribution of each cancellation type.
  - **Sankey Diagram** — to trace the flow of orders from placement through to cancellation or completion.

## 💡 Business Impact

This dashboard gives operations and category managers a clear, data-backed view of where cancellations are concentrated and how much revenue they cost — supporting targeted action (e.g., partner-level quality checks, payment-method friction fixes) instead of broad, unfocused fixes.

## Tools Used

Power BI · DAX · Power Query · Data Modeling · Custom Visuals (Tornado Chart, Heatmap, Radial Chart, Sankey Diagram)
