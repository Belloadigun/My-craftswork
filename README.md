
# Project Description
 Analysis of Company XYZ supermarket branches across the country

![istockphoto-1412353022-1024x1024](https://github.com/user-attachments/assets/a3f31939-7c00-4a47-a654-1015c3c8220d)


# Project Details
 Pandas package was imported
 Data for the three branches were read in and concatenated into a single data after which the data was read in to csv.
 
 The attributes of the data like shape, columns, missing values, information and statistical summary were sought.
 The datetime feature that was lacking in the data was added to it then it was confirmed by checking the datatype of the previous 'Date' column.Similar processes as described above were implemented on the 'Time' column.
 Features like day, month, year and hour were extracted from the 'Date' and 'Time' column and new individual columns were created for each of the feature. The unique hours of sale were sought from the new 'Hour' column and a list was printed displaying those time of the day.
 
 A list of categorical columns was printed by iterating through the columns. It was  saved as a list. The unique values in each of the categorical columns sought earlier are called into a list. The count figure of the values in each categorical columns is printed in a series format.
 The data was grouped by making the 'City' column the row variable while the sum and mean of all other quantitative variables were aggregated. The table displayed the gross income of each city and the city with highest gross income was highlighted.
 
 Using seaborn, the branch with highest quantity sale is displayed in a chart. In the same method, the most used method of payment and the city with most sales are also displayed on the chart. The highest and lowest product line are plotted in a countplot chart of seaborn. We displayed the most used payment channel for each of the product line on a chart using seaborn. The payment channel for each branch was displayed in a chart. With boxplot, we plotted a chart that gives a statistical summary of the branch ratings thereby allowing us to discover the branch with the lowest rating. A categorical plot was made to display in what way the gender type influenced the kind of product being purchased in the supermarket. With a categorical plot we displayed the interaction of unit price and the quantity of goods purchased. 

# Insights
I was able to find out that Port-harcourt is the city with the highest gross income of # 1,895,463
I was able to infer that the Abuja branch had the lowest rating of the three branches of the supermarket.
I was able to conclude from the visualizations that :
- The quantity of Food and Beverages,fashion accessories, electronic accessories and home and lifestyle purchased was greater
for the female than the male.
- The quantity of Sports and travel items purchased were equally by both male and female.
- The quantity of Health and beauty products purchased by male was greater than the female.
- Food and beverages and home and lifestyle products were purchased by more female than male.
- Electronic accessories, fashion accessories were equally purchased by both male and female.
- Health and beauty items and sports and travel items were purchased by more male than female.
- The product line with the highest unit price was purchased the least in quantity.
- The product line with the lowest unit price was purchased the most in quantity.

# Future Work

# Standout Section

# Executive Summary.
The sole purpose of the analysis is to uncover the trends in the transactions carried out in the branches of company XYZ.
The analysis has uncovered the quantities of products and the type of products purchased on a gender bases. It has also made clear the quantity of products purchased in relation to the unit price of the products. The analysis uncovers to us the method of payment used the most and in what branch it is most used. It also reveals the cutomers rating of their experience in each branch of the supermarket. 
My proposed suggestion is that the company get close details of the factors influencing the low customer rating of the Abuja branch of the company. 

