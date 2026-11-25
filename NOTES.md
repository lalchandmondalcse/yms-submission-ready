# YMS Financials assignment

I use the open-time `vix_zscore_smooth` feature and flag a stock when it exceeds
0.4153. Missing values are conservative negatives.

The threshold was selected using only training dates, requiring training precision
above 70% and then maximizing training score. The supplied baseline reports 68.9%
precision, 16.3% recall, and a 0.617 score on held-out test dates. No test labels
or future-date information are read.
