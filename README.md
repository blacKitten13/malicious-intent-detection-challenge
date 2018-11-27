# malicious-intent-detection-challenge
https://www.kaggle.com/c/wallarm-ml-hackathon

To do:

- concatenate model with simple features (convert hardcoded rule to nice feature)
- feature generation, TF-IDF
- make diverse models for stacking
- more careful layers addition
- hyperparameters optimization


| Attempt | Mean Validation | Max Validation | Public | Place |Comment|
|---------|-----------------|----------------|--------|-------|-------|
|25 | **0.9997493**    |     **0.99985**    | **0.99985**|  1/11 |[CNN + LSTM + GRU](https://github.com/blacKitten13/malicious-intent-detection-challenge/blob/master/CNN_LSTM_GRU.py)|
|23|0.9997200|0.99980|0.99980|2/11|[CNN + GRU](https://github.com/blacKitten13/malicious-intent-detection-challenge/blob/master/CNN_GRU_full.py)|
