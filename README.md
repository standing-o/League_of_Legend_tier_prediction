# League of Legend tier prediction (20201104 ~ 20201130)  
- Simple estimation of League of Legend tier and Data analysis
- Softmax Regression, XGB Classifier  

### First project with newcomer of data analysis club
- This project is maintained by 오서영, 장민수, [이수빈](https://github.com/I-SUBIN)

[[Code]](https://github.com/OH-Seoyoung/League_of_Legend_tier_prediction/blob/master/League_of_Legends_tier_estimation.ipynb) | [[Presentation]](https://github.com/OH-Seoyoung/League_of_Legend_tier_prediction/blob/master/presentation.pdf)

## Dataset
- 300 dataset with DPS, cs, runtime, KDA, Ward, tier features
```
[1] OP.GG: LoL Stats, Record Replay, Database, Guide, op.gg
```

## Data Analysis
- Correlation Analysis
<div align="center">
<img src="https://github.com/OH-Seoyoung/League_of_Legend_tier_prediction/blob/master/fig/pairplot.jpg?raw=True" width="48%">
<img src="https://github.com/OH-Seoyoung/League_of_Legend_tier_prediction/blob/master/fig/correlation%20analysis.jpg?raw=True" width="48%"> <br>
</div>  

- Feature Importance
<img src="https://github.com/OH-Seoyoung/League_of_Legend_tier_prediction/blob/master/fig/XGB%20Feature%20importance.jpg?raw=True" width="48%">
