# myproject
An analysis of the Smart TV market using web-scraped Flipkart data to uncover trends in pricing, display technology, and customer ratings.

# Project Overview: Smart TV Market Analysis 📺
This project involves a comprehensive analysis of the Smart TV market using data scraped directly from Flipkart 🛒. The objective is to extract, clean, and analyze product data to uncover market trends and understand how various features (like display type 🖥️, screen size, and sound 🔊) influence pricing 💰 and customer satisfaction ⭐.

Methodology 🛠️
Web Scraping: Data for 616 unique Smart TV listings was collected from Flipkart's search results pages using Python 🐍 with the requests and BeautifulSoup libraries.

Data Extraction: Key attributes were extracted for each product, including Brand, Product_Name, Display_inches, Display_Type, Model_Id, Launch_Year 📅, Sound_Output_Watt, Warranty, Resolution, Original_Price, Discounted_Price, and Ratings.

Data Analysis: The scraped data was cleaned and structured into a pandas DataFrame. A new feature, Discount_Percentage 📉, was engineered. The project then uses univariate, bivariate, and multivariate analysis (with matplotlib and seaborn) to find key insights.

Key Insights from the Analysis 💡
Market Landscape: The market is heavily dominated by Budget Segment TVs (under ₹50K), which account for 433 of the 616 models. LED is the most common display technology (349 models), followed by QLED (214 models).
Product Trends: There is a strong market focus on new models, with a significant number of TVs launched in 2024 and 2025 🚀. The standard for audio is 20W, but a clear positive correlation shows that larger screens (55"+) consistently offer higher-powered sound.
Customer Satisfaction: Customer satisfaction is overwhelmingly high, with most ratings clustered between 4.0 and 4.5 😄.

Key Correlations:
Warranty & Ratings: A strong link was found between longer warranties (3+ years) 👍 and higher, more consistent customer ratings.
Price & Features: Display technology is a major price driver, with Mini LED and OLED models being the most expensive 💸. Sony and TCL were identified as the priciest brands among the top 10.
Discount & Ratings: A slight negative correlation (-0.26) was found between the discount percentage and customer ratings, suggesting deeper discounts do not necessarily lead to higher satisfaction 🤔.
