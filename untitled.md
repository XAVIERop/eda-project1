Analysis.ipynb

1. Imported all the necessary libraries
2. Loaded the file sales.csv
3. Converted the date cols to datetime format for calculations

## DISTRIBUTION OF AVERAGE DAYS BETWEEN ORDERS :
1. initialzed size of graph (width and height)
2. took data from 'AVGDAYSBETWEENORDERS' col and divided them into 30  intervals for good visualization and set kde as True, to show the curve for good understanding
3. Defined title, xlabel, ylabel and displayed the graph

### Key Takeaways from histogram of AVERAGE DAYS BETWEEN ORDERS :
1. Smallest avg number of days bw orders is around 1000 days
2. Spread of the graph is big that means we have varied customer ordering patterns
3. left skewed - frequent repeat buyers
4. Right Skewed - some customers take long time bw placing orders
5. how frequently customers place repeat orders

## Key takeaways from Histogram of DAYSSINCELASTORDER:
1. right skewed : alot of customers who havent ordered in a while

## Scatterplot
1. Identify diff types of customers
2. Clusters in low left corner - customers who placed few orders and generate low revenue
3. Clusters in upper right corner - customers who placed many orders and generate high revenue
4. Outliers - bulk buyers - who order less times but high revenue orders

Types of customers : 
1. High value , high freq
2. Low freq, high value
3. Low value, low frequency




1. How Customers Behave (Behavioral Patterns)

- Some customers order frequently, while others take a long time between purchases.

- Most orders happen in the afternoon (12 PM - 6 PM) and evening (6 PM - midnight).

- The beginning and end of the month see the highest sales, while the middle of the month is slower.


2. Comparing Different Types of Customers (Comparative Insights)

- Some customers buy often (every 10-50 days), while others may only buy once or twice a year.

- High-spending customers place fewer orders but buy in large amounts, while smaller buyers order more frequently but spend less each time.

- Customers who haven't ordered in over 200 days are less likely to return 

- A few customers place large, high-value orders but don’t buy often.

- Afternoon and evening sales are highest

  

