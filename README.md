flotCandleCharts
================

This is my attempt at creating a candle charts plugin for flot. 


Demo: 
http://htmlpreview.github.io/?https://github.com/obeleh/flotCandleCharts/blob/master/Candlestick.html

Expected data format:

    [dt, open, close, low, high]

Make sure that the prices are correctly aggregated and put into evenly sized "buckets".
There's an example on how to convert trading data into chart data in CandleStick.html.
Note that you have to compensate for existing "gaps" where no trade data is available.
I've solved it by remembering the last close and put a 0-height candle in the gap.

Plugin is not finished yet. So input is welcome!
