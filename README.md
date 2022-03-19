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
 
 
###  Problem Statment => Analysing  Monthly/Yearly mean close feature.
 
you can `Choose a date range` optional, set_index of any `key` your using before `Resampling` the data according to the month `(M)` or Year `(Y)`. 

###  Problem Statment => Analyse Whether Stock Prices of these Tech companies (Amazon,Google,Microsolft,Apple) are correlated or not.

Create a new `df` to contiain informations of `[close]` columns from `Amzn,Goog,Msft` and `Appl` Dataframe. 





