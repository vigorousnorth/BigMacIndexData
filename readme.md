Price data from The Economist's Big Mac Index
---------------------------------------------

Here's a CSV file with prices (expressed in local currencies) of Big Macs since 2000, pulled from [The Economist's Big Mac Index interactive charts](http://www.economist.com/content/big-mac-index).

These data were compiled by hand for [a project to compare American Big Mac prices against the price of Maine lobster](http://www.pressherald.com/2017/05/13/how-much-would-you-pay-for-a-lobster-roll/). As such, only U.S. and Canadian prices were collected.

However, if anyone's feeling more ambitious to scrape more data, The Economist's raw price and exchange rate data for 32 nations are stored in separate JSON files for each date, with the following convention:

`http://infographics.economist.com/2017/bigmacindex_jan2017/public/bigmac_[Abbreviated month][Year].js`

[Here, for instance, are the prices and exchange rates for January 2017](view-source:http://infographics.economist.com/2017/bigmacindex_jan2017/public/bigmac_Jul2013.js).

Note that prices are collected 1-2 times a year, typically in January and July. 