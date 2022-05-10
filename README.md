# Regression
Лаба по ЦТ

## Download dataset 
```
$ curl https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank.zip -so bank.zip
$ unzip bank.zip -d data
```

## Install and run

```
$ python3 -m venv env
$ . env/bin/activate
(env) $ pip install -r requirements.txt
(env) $ chmod a+x script.py
(env) $ ./script.py
```

## Output 

```
(env) regression % ./script.py 
0.9079646017699115
Positive cases: 11.524% of all
              precision    recall  f1-score   support

           0       0.92      0.97      0.94      1006
           1       0.57      0.30      0.40       125

    accuracy                           0.90      1131
   macro avg       0.74      0.64      0.67      1131
weighted avg       0.88      0.90      0.88      1131
```
