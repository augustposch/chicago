# chicago
Ridership prediction on the Chicago 'L' train.

I used the Chicago 'L' daily rides by station dataset. I explored what kinds of time series exist for these stations, and then for selected stations I did supervised prediction of the next day's ridership based on the preceding 35 days of ridership as inputs. I found that an Extra Trees model always performed best - although this was measured by RMSE and next time I'd like to use upper-tail error.

Please read the paper (June 23rd PDF) for further insight.

