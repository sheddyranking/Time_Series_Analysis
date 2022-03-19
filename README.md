# Time_Series_Analysis
This is a Time Series Analysis Project involving ( Stock Market Case-Study)

###  Problem Statment => Analyse Closing Price of all the Stocks.

The Stocks to be Analysed are `AAPL`,`GOOG`,`MSFT` and `AMZN`. 
Covert the `date` column to `datetime` before ploting, it's a object initially

![Closing_price](https://user-images.githubusercontent.com/42388234/158672516-99f52c26-65bd-4dca-872b-d85580deb0b5.png)


###  Problem Statment => Analyse the Total Volume of Stock being Traded each day.

![AAPL](https://user-images.githubusercontent.com/42388234/158672799-bf4caea6-1799-4dec-a172-a70d52dca461.png)

![AMZN](https://user-images.githubusercontent.com/42388234/158672819-05d79f44-abe9-414f-8e3d-0bdf0dc762b8.png)

![GOOG](https://user-images.githubusercontent.com/42388234/158672825-0b7b2764-9508-49fb-93d9-5706b99e51f2.png)

![MSFT](https://user-images.githubusercontent.com/42388234/158672837-f08d401a-1743-4fa8-a64f-7b170aebaf70.png)


###  Problem Statment => Analysing  the daily price change.

 To archieve the daily price change create a column containing the change in  `df['close']` and `df['open']`. 
 
 `1day % return`  = `((df['close']-df['open'])/df['close'])*100` 
 
 #### 1day % return
 ![1day % return plot](https://user-images.githubusercontent.com/42388234/159098458-17e0ade2-7b25-460b-b5ac-1f770f8430f0.png)

 
###  Problem Statment => Analysing  Monthly/Yearly mean close feature.
 
you can `Choose a date range` optional, set_index of any `key` your using before `Resampling` the data according to the month `(M)` or Year `(Y)`.

#### Resamppled Monthly mean close features
![mean_close_month_f](https://user-images.githubusercontent.com/42388234/159098726-d5dc38e3-cfc1-44d2-9453-b486309173e3.png)


#### Resamppled Year mean close features
![mean_close_year_f](https://user-images.githubusercontent.com/42388234/159098549-2d069df2-9750-490e-b034-b2bb3777eb64.png)


###  Problem Statment => Analyse Whether Stock Prices of these Tech companies (Amazon,Google,Microsolft,Apple) are correlated or not.

Create a new `df` to contiain informations of `[close]` columns from `Amzn,Goog,Msft` and `Appl` Dataframe. 

#### corr plot
![corr_plot](https://user-images.githubusercontent.com/42388234/159132542-84bc1024-5547-4315-8d16-67b39b025330.png)

#### heatmap
![corr_heatmap](https://user-images.githubusercontent.com/42388234/159132609-dc1a35b7-0660-4885-ba66-bcfef1e7610d.png)

###  Problem Statment => Analyse Daily Return of each Stock and how they are correlated.

Stocks to be analysed are `Amzn,Goog,Msft` and `Appl` create a new `df` and store changes in % daily return in the new `df`.

#### changes in % daily return plot
![daily_per_change_plot](https://user-images.githubusercontent.com/42388234/159132644-fc6eb067-9e81-451d-8729-dd876416744a.png)

#### heatmap of changes in % daily return 
![percentage_daily_return_corr](https://user-images.githubusercontent.com/42388234/159132665-bd5079c6-c4a5-414d-873e-a7274a368af5.png)

### Problem Statment => Value at Risk Analysis for Tech Companies.

use `displot` from `seaborn` to visualized the change in `percentage daily return` of each stock and use `std` to analyse the `value Risk` on the stocks. Also you can use `quantile()` on the percentage daily return to discover the minimum daily return.

#### displot visualized changes in percentage daily return of appl.
![appl_change_value_risk](https://user-images.githubusercontent.com/42388234/159132679-8feea396-390e-4c2b-88ac-7a0ca15df5fd.png)

#### std Value Risk Analysis sample
![std_value_risk_analysis](https://user-images.githubusercontent.com/42388234/159132738-531d37e9-96b7-452d-93c6-3866ef312391.png)












