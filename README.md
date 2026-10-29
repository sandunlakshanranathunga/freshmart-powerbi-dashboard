# FreshMart Sales Dashboard (Power BI)

An interactive Power BI dashboard that analyses sales, profit and cost for FreshMart, a supermarket chain with 8 branches in Sri Lanka. The goal is to find which branches, categories and months make money, and where costs are too high.

## Project Overview
FreshMart sells products such as beverages, dairy, bakery items, rice and grains, and fresh produce. This dashboard helps a manager answer three questions:
- How much do we sell, and how much do we earn?
- Which branches and categories perform best and worst?
- Where do costs go, and when are they highest?

## Key Numbers
| Measure | Value |
|---|---|
| Net Sales | 11M |
| Total Cost | 9M |
| Profit | 2M |
| Profit Margin | about 18% |

## Dashboard Pages

### 1. Overview
Net sales by month and year, by branch, and profit compared with gross sales by category.

![Overview](screenshots/1-overview.png)

### 2. Profit Analysis
Profit split by branch, category and product, with a donut chart for category share.

![Profit Analysis](screenshots/2-profit-analysis.png)

### 3. Cost Analysis
Total cost by branch, product and quarter, and the link between delivery days and cost.

![Cost Analysis](screenshots/3-cost-analysis.png)

## Key Insights
- **Profit margin is about 18%.** Net sales of 11M gave 2M profit after 9M cost, so costs take most of the income.
- **Colombo 07 and Nugegoda are the best branches** for both sales and profit. Jaffna and Anuradhapura are the weakest.
- **Beverages is the most profitable category**, with 408K profit (19% of the total).
- **Rice & Grains sells a lot but earns little.** It has the highest gross sales, but its profit is only 250K, which means a low margin on each sale.
- **Fresh Produce and Dairy give the lowest profit share** (about 8-9% each).
- **April and December are the strongest sales months**, so stock and staff planning matter most then.
- **Costs peak in Quarter 2 and Quarter 4**, and are lowest in Quarter 1.
- **Delivery days do not clearly affect cost** in this data.

## Recommendations
- Focus promotions on Beverages and other high-profit categories.
- Review pricing and supplier cost for Rice & Grains to improve its margin.
- Study why Jaffna and Anuradhapura sell less, for example stock, location or customers.
- Prepare extra stock and staff before April and December.
- Look for ways to reduce costs in Quarter 2 and Quarter 4.

## Tools Used
- Power BI (dashboard and visuals)
- DAX (measures such as profit and margin)
- Excel (data source)

## How to Open
1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.
3. Use the page buttons (arrows) to move between pages.

## Author
Sandun Lakshan Ranathunga
Business Analytics Undergraduate
