This data comes from kaggle https://www.kaggle.com/datasets/sherrytp/stress-testing/data
I cleaned the data, using forward fill and backward fill for null values
I created new columns for total income and total expenses and profit
I added in the dates for the rows based on the year and quarter
I then split the data into JP Morgan and Citibank
I calculated the capital ratio then used linear regression to find the relationship between various indicators and each bank's profit
I then created two stress scenarios, moderate and severe, and ran the model to check how those scenarios impacted profit
Following this, I attempted a reverse stress test on various values of the capital ratio. None of the values gave me any results, which leads me to believe the banks are sound.
Do keep in mind, this is a linear test, and only on a few features. Other possibly significant events like widespread credit defaults have not been tested
