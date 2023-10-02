# Pizza-Sales-Analysis
Maven Analytics

📢 Analyzing Pizza Sales Data: Unveiling Insights and Trends!



Continuing with comprehensive analysis of pizza sales data by Maven Analytics I'm thrilled to share my latest findings. I uncovered intriguing insights into customer preferences, sales trends, and popular pizza types and sizes. Join me as we explore the exciting world of pizza sales and discuss the implications for the industry.



Sales Analysis: Unveiling the Numbers



The merged dataset, consisting of 48,620 entries and 12 columns, allowed me to perform in-depth sales analysis. Here are some key highlights from my findings:



1️⃣ Total Sales Revenue

By multiplying the price of each pizza by its corresponding quantity and summing up these values, I calculated a total sales revenue of $817,860.05. This figure reflects the financial impact of the pizza business during the analyzed period.



2️⃣ Sales Trends

Analyzing sales trends over time is essential for understanding customer behavior and identifying patterns. I delved into the dataset, and the results were intriguing. By grouping the data by date and summing the quantities, I discovered fluctuations in daily pizza sales. This information can help businesses optimize their operations, identify peak hours, and adapt their strategies accordingly.



3️⃣ Popular Pizza Types and Sizes

Understanding customer preferences is crucial for inventory management and menu optimization. By examining the frequency of different pizza types and sizes ordered, I gained valuable insights into customer preferences. The top 20 popular pizza combinations were determined by analyzing the counts of pizza type and size combinations. This knowledge empowers businesses to tailor their offerings to meet customer demands and enhance customer satisfaction.



Visualizing the Insights: Line Plots and Bar Charts



To provide a visual representation of the sales trends, I created a line plot showcasing the variations in pizza sales over time. This plot enables us to grasp the overall trend, identify seasonal patterns, and gain a deeper understanding of the dynamics within the pizza industry.



Additionally, I plotted a bar chart displaying the top 20 popular pizzas, ranked by the frequency of orders. This visually appealing chart gives us a snapshot of the most preferred pizza types and sizes, guiding businesses in making informed decisions regarding inventory management and menu design.

🔹 Customer Segmentation:
Using the power of data, I segmented the customers based on their ordering patterns and preferences. By grouping the data by order_id, I calculated key metrics to better understand our customer base:

1️⃣ Order Count: I determined the number of orders placed by each customer, gaining valuable insights into their engagement and loyalty.

2️⃣ Total Spending: By summing the prices of all pizzas ordered by each customer, I identified their total spending, helping us understand their value to the business.

3️⃣ Preferred Pizza Types: Leveraging the mode function, I discovered the most frequently ordered pizza types for each customer. This information helps us personalize our offerings and enhance customer satisfaction.

🔹 Customer Lifetime Value (CLV):
To gain a deeper understanding of customer value over time, I calculated the Customer Lifetime Value (CLV). By aggregating the total spending for each customer, I quantified the cumulative value they bring to the business throughout their relationship with us.

📈 The results were astounding, revealing valuable insights into customer behavior and preferences. This information will guide strategic decisions to enhance customer satisfaction and optimize our menu offerings.

📊 Ingredient Analysis and Cross-Selling Opportunities in Pizza Sales 🍕📈



In my quest for deeper insights into the pizza sales industry, I delved into the data to uncover fascinating trends and opportunities. Let's take a closer look at two key analyses: Ingredient Analysis and Cross-Selling Opportunities! 🧮🔍



🔹 Ingredient Analysis:

To understand customer preferences, I analyzed the frequency of ingredients used in pizzas. Using data magic, here's what I did:



1️⃣ Ingredient Frequency: By splitting the comma-separated values in the 'ingredients' column and exploding them into individual rows, I obtained the frequency of each ingredient. This allowed me to identify the most commonly used ingredients.



📊 The results were visually stunning! I plotted a bar chart showcasing the ingredient analysis, revealing the ingredients that make our pizzas truly irresistible. 🍅🧀🌶️ Check it out!



🔹 Cross-Selling Opportunities:

To boost sales and explore new avenues, I explored potential cross-selling opportunities based on pizza types and sizes:



1️⃣ Pizza Combinations: I grouped the data by 'pizza_type_id' and 'size' columns, determining the count of each combination. This valuable insight helps us identify the most popular cross-selling opportunities.



📈 The power of visualization! I plotted a grouped bar chart showcasing the top 10 cross-selling opportunities, highlighting the pizza types and sizes that complement each other perfectly. 🍕🔀

📈 Unlocking Insights from Pizza Sales: Time Series Analysis 🍕⏰



In my pursuit of understanding the dynamics of pizza sales, I dived into the realm of time series analysis to reveal fascinating patterns and trends. Let's walk through the steps together! 🧑‍💻📊



1️⃣ Importing the Essentials: I imported the essential libraries - pandas, matplotlib, and seasonal_decompose from statsmodels.tsa. These powerhouses would help me unleash the true potential of the data.



2️⃣ Dataset Preparation: I prepared the dataset for analysis by performing the following actions:



  a. Created a copy of the original dataset, preserving its integrity.

  b. Converted the 'date' column to datetime format for time-based operations.

  c. Set the 'date' column as the index, allowing for seamless time-based indexing.

  d. Sorted the dataset by the index (date) in ascending order, ensuring chronological consistency.



3️⃣ Resampling for Daily Frequency: To gain insights at a daily level, I resampled the data using the 'quantity' column. Aggregating the quantity sold on a daily basis provides a clearer picture of the sales pattern.



4️⃣ Visualizing the Time Series: I created an alluring visualization of the time series to grasp the overall trend. With a figure size of 10x6, I plotted the time series, adorned it with appropriate labels, and enabled gridlines for clarity.



5️⃣ Smoothing with Moving Average: To reduce noise and uncover underlying patterns, I employed the magic of moving averages. By applying a rolling mean to the 'quantity' column, I obtained a smoothed representation of the data. A mesmerizing plot showcased both the original data and the smoothed version.



6️⃣ Decoding the Components: Unraveling the time series further, I delved into decomposition. Employing the seasonal_decompose() function, I decomposed the time series into its distinct components: observed, trend, seasonal, and residual. These components shed light on various aspects of the sales pattern.



7️⃣ Visualizing the Decomposition: A captivating visualization came to life! With a new figure size of 10x8, I crafted subplots for each decomposition component. These visuals unveiled the observed, trend, seasonal, and residual patterns, enabling a deeper understanding of the data.



📊 Time series analysis opens doors to remarkable insights within the realm of pizza sales. By analyzing and decoding the data, we can unearth valuable trends and make data-driven decisions to elevate the customer experience. 🚀🍽️