# bitcoinの価格推移予測
cryptowatchのAPIを使い、15分ごとのデータを用いて学習させた。  
scikit-learnのMLPClassifierを使用した。

## 結果
```
[~/bitcoin-prediction-py]$ python main.py                                                                      [master]
Scores:  [ 0.54545455  0.54545455  0.55555556  0.55555556  0.55555556]
Accuracy: 0.55 (+/- 0.01)
```

## LSTM
- https://gist.github.com/mute1997/61923b2ecffc25978b0c33bcda69737f
