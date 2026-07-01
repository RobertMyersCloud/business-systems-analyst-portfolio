# Inventory Analysis Workbook

## Dashboard Preview

![Inventory Analysis Dashboard](inventory_analysis_dashboard_preview.png)

## Project Overview

This is my first Excel proof project for my Business Systems Analyst portfolio.

The goal of this project was to take inventory data, clean it up, analyze it, and turn it into something leadership could actually use. I wanted this to look less like a basic Excel exercise and more like the type of workbook an analyst would build to support purchasing, inventory planning, warehouse operations, or ERP decision-making.

This workbook focuses on inventory value, low-stock risk, overstock risk, aging inventory, warehouse distribution, category summaries, and business findings.

The data used in this project is sample data created for portfolio purposes. No company, customer, vendor, employee, or private business data is included.

## Business Problem

Leadership needs a clear view of inventory across multiple warehouses.

The main questions this workbook is designed to answer are:

- What is the total value of inventory on hand?
- Which warehouses are carrying the most inventory value?
- Which items are below reorder point?
- Which items are overstocked?
- Which inventory categories represent the highest value?
- Which items may require management attention due to aging, low stock, or excess stock?
- What should leadership review first?

In a real business environment, this type of workbook could help purchasing, supply chain, operations, or warehouse leadership make better decisions about replenishment, working capital, and inventory risk.

## Tools Used

- Microsoft Excel
- Excel tables
- Structured data cleanup
- Formulas
- SUMIFS
- COUNTIFS
- Conditional formatting
- Pivot-style summaries
- Dashboard layout
- Charts
- Data dictionary documentation

## Skills Demonstrated

This project demonstrates practical Excel skills that are useful for Business Analyst, Business Systems Analyst, Supply Chain Analyst, ERP Analyst, and Operations Analyst roles.

Key skills shown:

- Cleaned and structured inventory data
- Organized raw data into a usable analysis format
- Calculated total inventory value
- Identified low-stock items
- Identified overstock items
- Flagged aging inventory risk
- Built warehouse-level summaries
- Built category-level summaries
- Used formulas to summarize business data
- Applied conditional formatting to highlight risks
- Created an executive-style dashboard
- Documented workbook fields in a data dictionary
- Added business findings and talking points

## Workbook Files

| File | Description |
|---|---|
| `inventory_analysis_workbook.xlsx` | Main Excel workbook with raw data, cleaned data, dashboard, data dictionary, and supporting lists |
| `inventory_analysis_dashboard_preview.png` | Dashboard preview image for quick viewing in GitHub |
| `README.md` | Project explanation and documentation |

## Workbook Structure

The workbook includes the following tabs:

| Tab | Purpose |
|---|---|
| `README` | High-level workbook instructions and purpose |
| `Raw_Data` | Original sample inventory dataset |
| `Clean_Data` | Structured data used for analysis and dashboard reporting |
| `Dashboard` | Executive-style summary of inventory value, risk, and key findings |
| `Data_Dictionary` | Definitions for workbook fields and calculated columns |
| `Lists` | Supporting lookup lists and validation values |

## Key Metrics Included

The dashboard includes the following metrics:

- Total inventory value
- Total SKU count
- Low-stock item count
- Overstock item count
- Aging risk item count
- Average lead time
- Inventory value by warehouse
- SKU count by warehouse
- Low-stock items by warehouse
- Overstock items by warehouse
- Inventory value by category
- SKU count by category
- Low-stock items by category
- Overstock items by category

## Business Logic Used

The workbook uses simple but practical business logic to support inventory analysis.

### Inventory Value

Inventory value is calculated using quantity on hand and unit cost.

```text
Inventory Value = Quantity On Hand x Unit Cost
```

### Reorder Risk

An item is flagged for reorder review when quantity on hand is at or below the reorder point.

```text
If Quantity On Hand <= Reorder Point, then Reorder Needed
```

### Overstock Risk

An item is flagged as overstocked when quantity on hand is above the maximum stock level.

```text
If Quantity On Hand > Max Stock Level, then Overstock
```

### Aging Inventory Risk

Items are flagged for aging review when the last receipt date indicates the item may have been sitting too long without movement.

```text
If item age exceeds the aging threshold, then Aging Risk
```

## Key Outputs

This workbook produces several useful outputs:

- Inventory dashboard
- Warehouse inventory summary
- Category inventory summary
- Low-stock risk indicators
- Overstock indicators
- Aging inventory indicators
- Executive talking points
- Data dictionary

## Business Value

This workbook helps leadership identify inventory issues before they become bigger operational problems.

The value of this project is that it gives the business a quick way to see:

- Where inventory value is concentrated
- Which warehouses may be carrying too much stock
- Which items may need to be reordered
- Which items may be tying up working capital
- Which categories need closer review
- Where purchasing or planning decisions may need adjustment

In a real company, this type of analysis could support better purchasing decisions, reduce stockout risk, reduce excess inventory, and improve inventory planning.

## Analyst Findings / Talking Points

Based on the dashboard structure, the analyst should be prepared to discuss:

1. Which warehouse carries the highest inventory value
2. Which categories have the most inventory exposure
3. Which items are below reorder point
4. Which items are overstocked
5. Which items may be aging and need disposition review
6. How this workbook could support purchasing, planning, or ERP reporting
7. How this type of analysis could be expanded into Power BI or connected to SQL data

## How This Connects to Business Systems Analysis

This project is not just an Excel file. It is meant to show how Excel can support business systems work.

A Business Systems Analyst may need to:

- Pull inventory data from an ERP system
- Validate that the data is complete
- Clean and organize the data
- Identify exceptions
- Build summaries for stakeholders
- Document business findings
- Support user acceptance testing
- Help leadership understand what the data is saying

This project supports that type of work.

It also connects to ERP and supply chain systems because inventory data often comes from systems such as SAP, Microsoft Dynamics 365, Oracle, NetSuite, or other warehouse and procurement platforms.

## Career Portfolio Context

This project is part of my larger Business Systems Analyst portfolio.

The portfolio is focused on practical proof of skills in:

- Excel
- SQL
- Power BI
- Business analysis
- ERP processes
- Supply chain systems
- IAM
- GRC and audit controls

My goal is to show real analyst-style work instead of only listing training or certifications.

## What I Would Improve Next

Future improvements for this workbook could include:

- Add Power Query for automated data cleanup
- Add more detailed supplier performance data
- Add purchase order history
- Add inventory movement history
- Add reorder recommendations
- Add aging buckets
- Add slicers for warehouse and category
- Build a matching Power BI dashboard
- Connect the workbook to SQL-based inventory data
- Add a formal findings and recommendations tab

## Why I Built This

I built this project to show that I can use Excel to solve real business problems.

The focus was not just on formulas or charts. The focus was on taking business data, organizing it, identifying risks, and presenting the information in a way that leadership could use.

This is the type of work I want to continue building on as I move deeper into Business Systems Analyst, ERP Analyst, Supply Chain Systems Analyst, and controls-focused analyst roles.
