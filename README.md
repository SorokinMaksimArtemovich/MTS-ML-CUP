# solution for MTS-ML-CUP (https://ods.ai/competitions/mtsmlcup/leaderboard/private) - 49th place
![alt text](https://github.com/SorokinMaksimArtemovich/MTS-ML-CUP/blob/main/private_score.png)
public score: 1,706045271
<br>private score: 1,7061886202
<br>In "data preprocessing" directory I generate features:
<ul>
  <li>by aggregation, encoding and making ALS embanding</li>
  <li>by splitting data to month, weak and day of month and aggregation it</li>
  <li>by using word-to-vec for url_hosts and categorical features</li>
  <li>and by counting distribution of target variables on urls and other features</li>
</ul>
And assemble it to 3 datasets (by hand selection, by feature importance and only simple features)
<br>In "models" directory I use DaNet with avereging in 10 folds and with avereging on 3 datasets
<br>In this compitition parsing of sites didn't affect on score
