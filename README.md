# Sales Analysis Project - Electronics Sales Data

Welcome to the **Sales Analysis Project**! This project provides valuable insights into sales data for electronic products using data analysis tools like **Python**, **Pandas**, and **Matplotlib**. If you're interested in uncovering hidden patterns in sales trends, optimizing product pricing strategies, or figuring out the best time to run advertisements, this project is for you!

### 🚀 **Project Overview**
The goal of this project is to analyze a dataset containing sales information for electronic products and generate actionable insights to drive better business decisions. From identifying the most profitable product categories to determining when to display advertisements, this analysis will help guide strategies to boost sales performance.

### 🔑 **Key Features**
- **Sales Trends**: Track sales over time to understand patterns and seasonality. 
- **Price vs Sales Analysis**: Investigate how the pricing of products impacts sales performance. 
- **Optimal Advertising Times**: Identify the best times to display advertisements to maximize sales.
- **Product Category Comparison**: Compare sales across various product categories like smartphones, laptops, and accessories.
- **Data Visualizations**: Visualize trends, patterns, and correlations using tools like line charts, scatter plots, and bar graphs.

### 🔧 **Technologies Used**
- **Python**: The core language for implementing data analysis and visualizations.
- **Pandas**: For data manipulation and analysis, including cleaning and transforming data.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Jupyter Notebooks**: For documenting the entire data analysis process in an interactive environment.

### 📊 **Data**
The dataset includes sales data for various electronic products, containing the following attributes:
- `Product Name`: The name of the product.
- `Price`: The price of the product.
- `Sales Volume`: The number of units sold.
- `Date of Sale`: The date when the product was sold.
- `Category`: The category of the product (e.g., smartphones, laptops, accessories).
### Background information:
- start by cleaning the data. Tasks during my section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once I have cleaned up our data a bit, I move the data exploration section. In this section I explore 5 high level business questions related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should I display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions I walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

### 🎯 **Project Goals**
This project seeks to:
- **Analyze sales trends**: Identify key periods when sales peak or dip, and uncover seasonality trends.
- **Understand pricing strategies**: Assess how product pricing impacts sales volume.
- **Optimize advertising**: Pinpoint the best times to run ads based on customer purchasing patterns.
- **Provide recommendations**: Generate actionable recommendations for pricing, promotions, and advertising to help businesses increase sales.

### 💡 **Why This Project?**
This project provides an in-depth analysis that could help businesses better understand their sales data, optimize marketing strategies, and improve profitability. It can be particularly useful for marketing professionals, business analysts, and data scientists who are interested in eCommerce and sales analytics.
