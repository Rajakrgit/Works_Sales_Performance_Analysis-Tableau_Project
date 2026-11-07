# Works Sales Performance Analysis
# 1. Project Overview
The Sales Performance Analysis project uses Tableau to analyse product profitability, customer segmentation and product returns. The packaged workbook contains three interactive dashboards:

• Product Quality & Return Intelligence

• Customer Segmentation & Behaviour

• Product Portfolio & Profitability Matrix

Together, these dashboards provide a view of product sales and profit, customer characteristics, product attributes and return patterns. The aim is to help business users identify high-contributing products, understand customer segments and investigate areas that may require product or service improvements.

# 2. Business requirements
• Compare product profit and profit margin across categories and products.

• Analyse product colour, size, cost and selling price.

• Segment customers by income, occupation, education, gender and lifestyle attributes.

• Monitor total returns, return rate, returned products and categories.

• Analyse monthly and country-level return patterns.

• Provide filters to explore selected products, categories, customer groups and return years.

# 3. Tools & Technologies
• Tableau Desktop: data connections, calculated fields, worksheets, filters and dashboards.

• Tableau calculations: product profit, selling value, cost value, profit margin, distinct customer count, income segment and return rate.

• Packaged workbook: Works Sales Performance Analysis.twbx, containing a Tableau workbook and embedded extract.

# 4. Challenges Faced
• Cleaning annual income values by removing currency symbols and commas before numeric conversion.

• Keeping profit, selling value, cost and margin calculations consistent.

• Connecting sales and returns data without duplicating quantities.

• Investigating the large NA product-colour group and O product-size label.

• Reconciling occupation chart values with the distinct customer count.

• Comparing returned quantity with sold quantity before interpreting return trends.

• Reconnecting local CSV paths when moving the packaged workbook to another computer.

# 5. Key Business Insights
• Profitability: Product Profit is 10,457,715 and Product Profit Margin is 41.97%.

• Category: Bikes is the dominant category by displayed product profit; Accessories and Clothing are much smaller.

• Product colour: NA has 51,080 units, substantially more than other colour groups. Check whether NA means missing, unknown or not applicable.

• Gender: Male 8,766; Female 8,527; NA 123 – a relatively balanced male/female distribution.

• Income: Middle Income is the largest segment (7,863), followed by Low Income (7,482) and High Income (2,071).

• Occupation: Professional is the largest displayed group (5,424).

• Education: Bachelors is the largest displayed group (5,101).

• Returns: Accessories account for 1,130 returned units, Bikes 429 and Clothing 269.

• Monthly returns: May is highest at 190; July is lowest at 48; December is 176.

# 6. Recommendations
• Investigate high-return products such as Water Bottle, Patch Kit and Mountain Tire using return reasons and quality information, if available.

• Calculate return rates by product and category, not just returned quantity.

• Investigate Accessories, which has the highest returned quantity in the category chart.

• Compare July returns with July sales quantity to understand the sharp monthly drop.

• Standardise missing or unclassified product colour and size values.

• Review low-margin products, pricing and costs using the profitability matrix.

• Validate customer counts and document the calculation logic behind each KPI.
