# Tutorial : Preprocessing + XGBoost to predict time series 

This work is inspired and the algorithm is replicated from the research paper "Do we really need Deep Learning models for time series forecasting" of S.Elsayed et al. 

Source of the paper :

```
@unknown{unknown,
author = {Elsayed, Shereen and Thyssens, Daniela and Rashed, Ahmed and Schmidt-Thieme, Lars and Jomaa, Hadi},
year = {2021},
month = {01},
pages = {},
title = {Do We Really Need Deep Learning Models for Time Series Forecasting?}
}
```

I replicate the described algorithm on a time series of 10392 periods. On a test sample, I compare the results with classical Prophet algorithm, specialized for time series. The results of this algorithm is better than Prophet.



![alt text](https://github.com/AntoinePinto/XGB-for-timeseries/blob/main/images/visu.png)

The evaluation metrics confirm this result.

<p align="center">
  <img src="https://github.com/AntoinePinto/XGB-for-timeseries/blob/main/images/eval.png?raw=true" width="300" alt="image"/>
</p>
