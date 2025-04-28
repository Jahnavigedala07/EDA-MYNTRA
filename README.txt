In this project, I performed web scraping to collect data about clothes(shirts) from Myntra, a popular e-commerce website. The goal was to gather information about various shirts, their features, and pricing, then clean and analyze the data for insights.

Web Scraping:

Using Python and the BeautifulSoup and selenium library, I scraped data from Myntra’s Shirts category. This included details like the model name, brand, price, ratings, and key features.
I used requests to fetch the HTML of the product pages and BeautifulSoup to parse and extract relevant data into a structured format.

Creating a Dataset:

The scraped data was organized into a pandas DataFrame, which was then converted into a CSV file for easy analysis and further processing. This dataset contained key attributes such as product name, brand, price, ratings, and features of the Shirts.

Data Cleaning:

I carefully explored and cleaned the dataset to ensure the data was usable for analysis and visualization:
Removed Null Values: Missing or incomplete data was handled by identifying and dropping rows with missing values.
Data Transformation: Data was transformed where necessary, such as converting prices to a numerical format, parsing ratings into numeric values, and correcting inconsistencies in the dataset.

Data Visualization Preparation:

After cleaning, I created a cleaned DataFrame that was ready for visualization. This included creating visual representations of key aspects such as:
Distribution of Shirt  prices.
Popular brands and their market share.
Ratings distribution and features comparison.

Tools & Libraries Used:
Python for web scraping and data manipulation.
BeautifulSoup and requests for web scraping.
Pandas for data cleaning and manipulation.

Matplotlib/Seaborn (optional, if you included visualization in the project) for data visualization.
Outcome:
By the end of this project, I successfully built a cleaned dataset from Myntra's Shirt listings and was able to use this data to extract insights, perform statistical analysis, and prepare it for visualization. The cleaned data could now be used for deeper analysis, feature selection, or even predictive modeling.

POWER-BI Dashboard:-
  The Power BI dashboard provides key insights into washing machines on Myntra:

📊 Overall Metrics:
Maximum Star Rating achieved is now 5.00 (compared to 3.9 previously).
Total Sum of Prices for all products is significantly higher at ₹217K.
Minimum Discount available remains 20%.

🏷️ Brand-wise Insights:
RARE RABBIT and PEPE JEANS have the highest average product prices compared to other brands.
POWERLOOK, DENNIS LINGO, and THOMAS SCOTT also have above-average pricing.
Brands like CAMPUS SUTRA, HIGHLANDER, and GLITCHEZ have more affordable pricing.

⭐ Ratings Insights:
Category Rating Frequencies show:
Excellent ratings account for the largest share (~33.6%).
Average ratings account for around 30.86%.
Poor ratings are also visible (~30%), indicating a broader spread of product ratings this time compared to the earlier dashboard (where everything was just "Average").
CAMPUS SUTRA has multiple products under both "Average" and "Excellent" rating categories.

