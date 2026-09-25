# Inventory & Supply Chain Analysis | Power BI

## Project Overview
An operations analytics project built in Power BI to explore inventory and supply-chain performance. The dashboard uses a dataset of **1,200 records** to examine inventory levels, sales, supplier and warehouse activity, order fulfillment, backorders, lead times, and transportation costs.

The goal is to turn operational data into clear KPIs and interactive views that help users monitor supply-chain performance and investigate patterns across regions, categories, suppliers, and warehouses.

## Business Questions
- How do inventory levels and units sold vary by region, category, and date?
- Where are backorders occurring, and how do they relate to inventory and order activity?
- How do lead times and order accuracy vary across suppliers and warehouses?
- How do transportation costs and cost of goods sold vary across operational segments?
- How can users compare supply-chain metrics using interactive filters?

## Dataset
The project uses `Inventory_SupplyChain_Dataset.csv`. The available fields include:

`Date`, `Region`, `Category`, `Supplier`, `Warehouse`, `Order Status`, `Units Sold`, `Inventory Level`, `Transportation Cost`, `Order Accuracy`, `Lead Time (Days)`, `Backorder`, `Cost of Goods Sold (COGS)`, `Average Inventory`, and `Warehouse Capacity`.

## Tools & Skills
- **Power BI Desktop** — dashboard development and data visualization
- **Power Query** — data import, profiling, cleaning, and transformation
- **DAX** — measures and KPI calculations (where implemented in the report)
- **Supply Chain Analytics** — inventory, fulfillment, supplier, warehouse, and logistics analysis
- **Data Visualization** — KPI cards, charts, slicers, and interactive report design

## Project Workflow

### 1. Understand the data
Reviewed the dataset fields and their business meaning, including inventory, order, supplier, warehouse, and logistics measures.

### 2. Prepare the data
Imported the CSV into Power BI and inspected data types, date fields, numeric measures, Boolean fields, and categorical values. Data preparation should be documented according to the transformations actually applied in Power Query.

### 3. Build the report
Organized supply-chain metrics into interactive visual analysis. The data supports slicing and comparison by date, region, product category, supplier, warehouse, and order status.

### 4. Analyze operational performance
Used the available fields to examine inventory and sales patterns, backorders, lead times, order accuracy, transportation costs, and COGS across relevant segments.

### 5. Communicate findings
Designed the report to help users explore performance patterns and identify areas that may warrant further operational investigation.


