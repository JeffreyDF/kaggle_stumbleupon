Kaggle StumbleUpon Challenge solution
==================

This is [my](https://www.kaggle.com/jeffreydf) solution for the [Kaggle StumbleUpon Evergreen Classification Challenge](https://www.kaggle.com/c/stumbleupon). It got 8th place on the final leaderboard but can get top 3 scores on the private leaderboard (which is maybe not that spectacular given how noisy the data was). 

The code is fairly messy (and probably somewhat inefficient) since it was my first serious experience with Python and scikit-learn. Since it does a lot of preprocessing, the script will take a long time to run for the first time (the processed results are dumped to the dump/-folder and thus only have to be generated once). Also, you will first need to convert the raw html with [html2text](http://www.aaronsw.com/2002/html2text/) (different encodings can sometimes make this process a little cumbersome). 

A relatively detailed description of the final model and its results can be found in [stumbleupon_doc_defauw.pdf](https://github.com/JeffreyDF/kaggle_stumbleupon/blob/master/stumbleupon_doc_defauw.pdf). 
