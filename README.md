# Milky-Mist-Pricing-Comparison-Dashboard
Competitive Pricing Analysis of Milky Mist vs Amul & Hatsun

This project presents a Power BI–based pricing comparison of Milky Mist, benchmarked against two major competitors — Amul and Hatsun — across five core dairy products.
The analysis reveals premium pricing patterns, competitive insights, and SKU-level opportunities for strategic decision-making.

🚀 1. Project Overview
The goal of this project is to analyze the pricing strategy of Milky Mist by comparing its MRP (Maximum Retail Price) with direct competitors.
The dashboard highlights:
Brand-level average price differences
SKU-level pricing gaps
Premium vs. competitive categories
Pricing position of Milky Mist in the market
This enables stakeholders to quickly understand how the brand is positioned relative to competition.

🧪 2. Exploratory Data Analysis (EDA)

(Performed using Python)

Summary Statistics (MRP)
| Statistic | Value  |
| --------- | ------ |
| Min       | 28     |
| Max       | 345    |
| Mean      | 111.07 |
| Median    | 58     |
| Std Dev   | 111.83 |

3. EDA Highlights:
Dataset is clean and balanced (5 SKUs × 3 brands)
No missing values or datatype issues
MRP column properly treated as numerical
Clear price variation across product categories.

📊4. Dashboard Features
| Feature                      | Description                                                 |
| ---------------------------- | ----------------------------------------------------------- |
| **KPI Cards**                | Avg MRP, Competitor Avg MRP, Premium %, Highest/Lowest SKUs |
| **Brand Comparison Chart**   | Average MRP per brand                                       |
| **Product Comparison Chart** | MRP comparison of 3 brands per product                      |
| **Donut Chart**              | Average MRP contribution by product                         |
| **Slicer**                   | Interactive product filter                                  |
| **Brand Theming**            | Milky Mist color palette + professional layout              |

🔍 5. Key Insights
| Insight                          | Description                                                                                           |
| -------------------------------- | ----------------------------------------------------------------------------------------------------- |
| **Premium Positioning**          | Milky Mist’s average MRP (₹113) is ~2.6% higher than competitors—reflecting a premium brand strategy. |
| **Highest-Priced SKUs**          | Milky Mist leads in Milk, Curd, and Butter—high-volume, high-trust SKUs.                              |
| **Competitive in Others**        | Milky Mist avoids premium pricing in Paneer and Ghee, where competitors dominate pricing.             |
| **Brand Strength Pattern**       | Amul strongest in Ghee; Hatsun in Paneer; Milky Mist in fresh dairy.                                  |
| **Consistent Pricing Structure** | Balanced SKU representation suggests stable pricing architecture across categories.                   |

🎯 6. Business Impact
This dashboard helps FMCG and dairy companies:
| Impact Area                  | How This Dashboard Helps                 |
| ---------------------------- | ---------------------------------------- |
| **Pricing Strategy**         | Identify overpriced/underpriced SKUs     |
| **Competitive Intelligence** | Compare Milky Mist vs Amul vs Hatsun     |
| **Promotional Planning**     | Understand where discounts are necessary |
| **Brand Positioning**        | Validate premium or competitive stance   |
| **Market Strategy**          | Understand consumer-sensitive categories |

🧠 7. Methodology
| Step | Process                                   |
| ---- | ----------------------------------------- |
| 1    | Dataset preparation (CSV)                 |
| 2    | Python EDA (summary, structure check)     |
| 3    | Data modeling in Power BI                 |
| 4    | Created DAX measures for KPIs             |
| 5    | Built dashboards with brand-level theming |
| 6    | Extracted insights & recommendations      |

📌 8. Conclusion
Milky Mist follows a controlled premium strategy, pricing higher in fresh dairy staples while remaining competitive in categories where rivals dominate.
The brand maintains strong SKU-level consistency and demonstrates intentional market positioning.

🚧 9. Future Improvements
Add sales volume to study price elasticity
Include retailer-level pricing (BigBasket, Blinkit, D-Mart)
Expand to more SKUs (cheese, flavored milk, yogurt, etc.)
Add state-wise pricing variations
Introduce trend analysis (yearly/seasonal pricing changes)

👩🏻‍💼 About the Creator
A data analytics enthusiast focused on FMCG insights, dashboard storytelling, and business analytics — actively seeking opportunities in data analysis, BI, and market analytics.
