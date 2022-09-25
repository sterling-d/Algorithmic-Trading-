# Challenge 14: Machine Learning Trading Bot 


1) What impact resulted from increasing or decreasing the training window?

For the initial training_begin and training_end parameters (2015-04-02, 2015-07-02), the accuracy score for both was 0.55. 

After adjusting the size of the training set to parameters that were both above and below the original timestamps, the following results occurred. 

First, I adjusted the training_end parameter to a value 2 months below the original timestamp, and kept training_begin to it's initial timestamp. (2015-04-02, 2015-05-02). The resulting accuracy score still maintained 0.55. 

I then increased training_begin to 2015-11-02 by adding 7 periods, and training_end to 2015-05-02 by adding 12 periods. The resulting accuracy score ended up decreasing to 0.51. 

After increasing training_begin to 2015-10-02 by adding 6 periods, and training_end to 2015-11-02 by adding 7 periods, the final accuracy score was 0.56.


2) What impact resulted from increasing or decreasing either or both of the SMA windows?


After increasing both the short and long windows to (50) and (1000), the accuracy score had risen from 0.55 to 0.56. 

Decreasing the short and long windows to (1) and (10) ultimately ended up lowering the accuracy score to 0.48. 

