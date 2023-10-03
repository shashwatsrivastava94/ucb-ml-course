# Missing Data

The original dataset has some columns which are missing a lot of data. There are 12,684 rows in the original dataset. The column `car` is missing in 12,576 of them making this column useless for our analysis. Other columns like `Bar`, `CoffeeHouse`, `CarryAway`, `RestaurantLessThan20` and `Restaurant20To50` are missing between 107 and 217 times - these columns can still be used for our analysis.

The bar graph for the data completeness is -  
![image info](./data/data_completeness.png "Data Completeness")

To deal with this, I choose to ignore and remove the `car` column and use all the other rows.

# Basic Analysis

## Number of people accepting coupons

Around 58% of all respondents accepted the coupon(7,210 accepted and the remaining did not accept the coupon)

## Showing relationship between Y and some columns

An easy way to see corelation between different columns and the likelihood to accept a coupon are by creating barplots for different columns and coloring the graphs by the value of Y(acceptance of the coupon). Doing this gave me a quick understanding of the data and different potential co-relations.