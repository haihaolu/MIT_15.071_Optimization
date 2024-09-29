The repository contains data for the online advertising final project for MIT 15.093 Optimization.

We utilize the display advertisement dataset introduced in [1]. They consider publishers who have agreed to deliver ad slots (impressions) to different advertisers to maximize the cumulative click-through rates of the assignment. This publisher has 29 advertisers, and we consider a period of time with 100,000 impressions. ``budget.txt`` file specifies the number of ad slots (impressions) each advertiser is willing to buy. The t-th row of ``ctr.csv`` file is the predicted click-through rate of the t-th impression for the 29 advertisers. 

[1] Balseiro, Santiago, et al. "Yield optimization of display advertising with ad exchange." Proceedings of the 12th ACM conference on Electronic commerce. 2011.
