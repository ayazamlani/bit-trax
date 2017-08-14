# bit-trax

This is a simple python program that will gather the pricing of
any crypto currency that you have at least 1 whole coin/share of on Bittrex
(using @ericsomdahl's [python-bittrex](https://github.com/ericsomdahl/python-bittrex)).

Next, This program will then collect the USD value from Coin Market Cap API of the currencies currently owned on bittrex.

Finally it will save the data to an excel file called **'Bittrex_Data.xlsx'**.


###Instructions###
1. Open the bit-trax.py file

2. Change your API_KEY and API_SECRET.<br>-I recommend using read-only access for security purposes.

3. Run bit-trax.py

4. Open 'Bittrex_Data.xlsx' to see the data


*You can run this program multiple times and it will create a new sheet every time.*


To Comply with Coin Market Cap API
* Please limit requests to no more than 10 per minute.
* Endpoints update every 5 minutes.

Note:

Currently working on also creating a reporting spreadsheet to analyze the data being pulled in to Bittrex_Data.xlsx

Follow me on [twitter](https://twitter.com/ayazamlani)
for updates

######Donations Are Appreciated######

If you use this excel to track your progress and would like to donate :)

* BTC: 161UkWiXmsgTXrNzJRzQDTwPJwxLDANT6g
* ETH: 0x3ae1976496Ed1757e82ba3C362d284F1E7514FB7
* LTC: LPsAokUUzksyBH85vwrMc7gL29ojj8HCVo

Thank You! Best of luck with all your investing!

> A guy walks into a bar and asks for 1.4 root beers. The bartender says "I'll have to charge you extra, that's a root beer float". The guy says "In that case, better make it a double."
> -/u/ttchoubs
