# USHousing_DecisionTrees
This is a study I did on a dataset provided by Escola DNC (https://www.escoladnc.com.br/)

This dataset lists 5000 entries of houses with their addresses and some related quantitative variables:

Those variables are: ```Avg_Area_Income```,	```Avg_Area_House_Age```,	```Avg_Area_Number_of_Rooms```,	```Avg_Area_Number_of_Bedrooms```,	```Area_Population``` and	```Price```.

![](images/head().png)

Here are their correlations:

![](images/corr().png)

By using Random Forest without hyperparameter tuning, it was possible to achieve an accuracy of $R² = ~88%$
