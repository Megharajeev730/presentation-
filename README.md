
# Flipkart Laptop Reviews – Data Analysis Project

## About the Project

This project explores real customer reviews of laptops sold on Flipkart. Using Python and Jupyter Notebook, the goal is to understand what drives good or bad reviews and how customer feedback can support better business decisions. It combines data analysis with ideas from Decision Support Systems (DSS) to turn raw data into useful insights.

## What’s Included

The notebook provides a full exploratory data analysis (EDA) of the review dataset. The focus is on:

* Cleaning and preparing the review data
* Understanding trends in customer sentiment
* Connecting those trends to business insights using DSS concepts

All work was done in Python, with visualizations created to clearly explain the results.

## Dataset Information

* **Source**: Flipkart Laptop Reviews (from Kaggle)
* **Size**: Around 24,000 reviews covering nearly 600 laptop models
* **Key Columns**:

  * `product_name`: Laptop name and specs
  * `overall_rating`: Average product rating
  * `no_ratings`: Total number of ratings
  * `no_reviews`: Number of written reviews
  * `rating`: Individual user score
  * `title`: Short review title
  * `review`: Full review text

## Key Highlights

* Checked and fixed text encoding issues
* Cleaned the data (removed duplicates, converted strings to numbers)
* Explored and visualized:

  * How ratings are distributed
  * Which laptops got the most reviews
  * Top-rated laptop models
  * The link between review count and ratings
  * How review length relates to rating
* Used DSS concepts to interpret findings in a business context
* All charts and visuals saved in a separate **Visual Analysis** folder
* Includes proper citations in Harvard style

## Tools Used

* **Python**
* **Libraries**: pandas, numpy, matplotlib, seaborn, textblob, re (regular expressions)
* **Environment**: Jupyter Notebook