# Challenge 14: Machine Learning Trading Bot 


1) What impact resulted from increasing or decreasing the training window?

For this section, I adjusted the training window into 3 different periods: 

a) 2015-04-02 - 2015-09-02,
b) 2015-10-02 - 2016-02-02, and 
c) 2017-01-02 - 2018-06-02.

- In period a, both the SMA_Fast and SMA_Slow had a value of around 24 during 2015-04-02. Once it had reached 2015-09-02, the value had decreased to aproximately 21 within the SMA_Fast, and 22 for the SMA_Slow.

- In period b, both the SMA_Fast and SMA_Slow had a value of around 21 during 2015-10-02. However, once it had reached 2016-02-02, the value had decreased to aproximately 19 within the SMA_Fast, and 18 for the SMA_Slow.

- In period c, both the SMA_Fast and SMA_Slow had a value of around 21 during 2017-01-02. Once it had reached 2018-06-02, the value had increased to 26 for both SMA_Fast and SMA_Slow. 

2) What impact resulted from increasing or decreasing either or both of the SMA windows?

After increasing both the short and long windows to (50) and (1000), the results had shown that the closing price had actually decreased, from $24.92 in 2015-04-02, to $21.56 in 2016-12-12. 

I then decided to decrease the short and long windows to (1) and (50). The closing price for both windows, was still lower than the original long and short windows, with a price of $21.08 on 2016-12-27.

