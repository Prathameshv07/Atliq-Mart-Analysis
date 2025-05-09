# Analyze Promotions and Provide Tangible Insights to Sales Director

#### Link to notebook: [Atliq Mart Analysis](https://colab.research.google.com/drive/1DD3BrZoOGeeRZvhqwjUORCr1aD2NFXII?usp=sharing)

## 1. Project Overview:

### Company Info:
AtliQ Mart is a retail giant with over 50 supermarkets in the southern region of India. All their 50 stores ran a massive promotion during the Diwali 2023 and Sankranti 2024 (festive time in India) on their AtliQ branded products. Now the sales director wants to understand which promotions did well and which did not so that they can make informed decisions for their next promotional period.

## 2. Project Info:

### Primary Insights:

#### I. Store Performance Analysis:
- Top 10 stores by Incremental Revenue (IR) from promotions.
- Bottom 10 stores by Incremental Sold Units (ISU).
- Variation of store performance by city. Common characteristics among top-performing stores.

#### II. Promotion Type Analysis:
- Top 2 promotion types for highest Incremental Revenue.
- Bottom 2 promotion types for impact on Incremental Sold Units.
- Comparison of performance: discount-based vs. BOGOF vs. cashback promotions.
- Promotions balancing Incremental Sold Units and healthy margins.

#### III. Product and Category Analysis:
- Product categories with highest sales lift from promotions.
- Specific products' response to promotions.
- Correlation between product category and promotion type effectiveness.

## 3. Work Done:

- Analyzed citywise revenue using bar and line charts, including store counts and revenues before and after promotions.
- Created calculated variables such as Incremental Sold Units (ISU) and percentages for store metrics overview, displaying results in a table.
- Visualized category sales dynamics with donut and pie charts for before and after promotion periods.
- Summarized revenue trends by stores in a table, incorporating calculated metrics like Incremental Revenue (IR) and ISU.
- Used `value_counts()` to get promo type frequencies and created a waterfall chart for visualization.
- Assessed product performance by campaign and promotion in a table, calculating IR% and ISU%.
- Displayed sales and revenue distribution by category using bar and donut charts respectively.

## 4. What I Learned in the Process:

- Enhanced skills in data manipulation and visualization using pandas and matplotlib libraries.
- Developed a deeper understanding of creating calculated variables on the go, similar to measures in Power BI.
- Gained experience in using dual y-axes and annotations for clearer and more informative charts.
- Improved ability to design effective visual representations like bar charts, line charts, donut charts, and pie charts for various types of data.
- Learned to summarize and present complex data metrics in a concise and readable tabular format.
- Acquired proficiency in leveraging `value_counts()` for category analysis and visualizing promo type frequencies with waterfall charts.
- Strengthened ability to compare pre and post-promotion metrics, enhancing data-driven decision-making skills.

## 5. Conclusion:

In conclusion, this project provided valuable insights into the performance of promotions at AtliQ Mart. By analyzing store performance, promotion types, and product categories, actionable recommendations can be made for future promotional campaigns.

## License

[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**.  
You are free to **use, share, and adapt** the material for **non-commercial and educational purposes**, as long as proper **credit is given** and any changes are noted.

Learn more: [http://creativecommons.org/licenses/by-nc/4.0/](http://creativecommons.org/licenses/by-nc/4.0/)
