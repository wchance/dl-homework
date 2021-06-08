# Deep Learning homework

We used Long Short-Term Memory (LSTM) to predict next day closing pricing using previous closing prices and also compared the results to using Fear Index alone.

We loaded closing prices and fng values and concat into a single dataframe

Using closing prices is much more accurate than using FNG alone.



# Learning Loss
| Window | Closing | Fear Index |
| ------ | ------- | ---------- |
| 1      | 0.01949 | 0.09930 |
| 2      | 0.01870 | 0.10235 |
| 3      | 0.02165 | 0.10477 |
| 4      | 0.02231 | 0.10713 |
| 5      | 0.02230 | 0.10548 |
| 6      | 0.02078 | 0.13533 |
| 7      | 0.01863 | 0.10497 |
| 8      | 0.01730 | **0.09863** |
| 9      | **0.01696** | 0.20598 |
| 10     | 0.02103 | 0.12443 |
