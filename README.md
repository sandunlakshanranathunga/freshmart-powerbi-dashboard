# FreshMart Sales Dashboard (Power BI)

An interactive Power BI dashboard that analyses sales, profit and cost for FreshMart, a supermarket chain with 8 branches in Sri Lanka. The goal is to find which branches, categories and months make money, where costs are too high, and what the business should do next.

## Business Questions
- How much does FreshMart sell, and how much does it earn?
- Which branches and categories perform best and worst?
- Do the biggest-selling categories also give the most profit?
- When are sales and costs highest?

## Key Numbers
| Measure | Value |
|---|---|
| Net Sales | 11M |
| Total Cost | 9M |
| Profit | 2M |
| Profit Margin | about 18% |

## Dashboard Pages

### 1. Overview
Net sales by month and year, net sales by branch, and profit compared with gross sales by category.

![Overview](screenshots/1-overview.png)

### 2. Profit Analysis
Profit by branch, category and product, with a donut chart for each category's share of profit.

![Profit Analysis](screenshots/2-profit-analysis.png)

### 3. Cost Analysis
Total cost by branch, product and quarter, and the link between delivery days and cost.

![Cost Analysis](screenshots/3-cost-analysis.png)

## Key Findings

1. **Profit margin is about 18%.** Sales of 11M gave 2M profit after 9M cost, so cost takes about 82% of every sale. A small cost saving makes a big difference.
2. **Sales grew from 2024 to 2025.** The 2025 line is higher in most months. April and December are the peak months.
3. **Two branches carry the business.** Colombo 07 and Nugegoda each sell about 2M (about 37% of all sales together). Jaffna sells about 0.7M, so the top branch sells about 3 times more than the lowest. Branches mainly earn more by selling more, not by having better margins.
4. **Big sales do not mean big profit.** Beverages, Rice & Grains and Dairy make about 60% of sales but have the lowest margins.
5. **Small categories earn the most per sale.** Household and Personal Care have the best margins, but their sales are small.
6. **Rice & Grains is the weak spot.** It has the highest sales but only about a 9% margin. On the product chart, its products sit below the profit trend.
7. **Costs rise in Quarter 2 and Quarter 4.** These are the same quarters when sales peak, so the rise is probably because of higher volume.
8. **Delivery days show no clear link to cost** in this data.

### Margin by Category (approximate)
| Category | Gross Sales | Approx. Margin |
|---|---|---|
| Household | ~1.0M | ~32% |
| Personal Care | ~1.0M | ~30% |
| Bakery | ~0.7M | ~26% |
| Snacks | ~1.1M | ~24% |
| Fresh Produce | ~0.8M | ~23% |
| Beverages | ~2.6M | ~15% |
| Dairy | ~1.5M | ~13% |
| Rice & Grains | ~2.7M | ~9% |

*Margin = Profit ÷ Gross Sales, read from the dashboard charts.*

## Recommendations for FreshMart

1. **Fix the price or supplier cost of Rice & Grains.** It is the biggest seller with the smallest margin, so even a small improvement adds a lot of profit.
2. **Grow Household and Personal Care.** Give them more shelf space and promotions, because every sale earns more profit.
3. **Keep Beverages strong, but review its cost.** It is the top profit maker in total, but its margin is low.
4. **Learn from Colombo 07 and Nugegoda.** Find what they do well (location, stock, customers) and copy it in Jaffna and Anuradhapura.
5. **Plan for April and December.** Stock up and add staff early, because sales are highest then.
6. **Watch costs in Quarter 2 and Quarter 4.** Check if cost grows faster than sales in those quarters, and find the reason if it does.

## Tools Used
- Power BI (dashboard and visuals)
- DAX (measures such as profit and margin)
- Excel (data source)

## How to Open
1. Download `freshmart-sales-dashboard.pbix` from this repository.
2. Open it in Power BI Desktop.
3. Use the arrow buttons to move between pages.

## Author
Sandun Lakshan Ranathunga
Business Analytics Undergraduate
