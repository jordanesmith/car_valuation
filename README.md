Experimentation for ML model to predict value of a car sold on autotrader, to be used by traders.


# Results
```
{
    "AM": "Aston Martin",
    "JAG": "Jaguar",
    "BMW": "BMW",
    "MB": "Mercedes-Benz",
    "LT": "Lotus",
    "AR": "Alfa Romeo",
    "LR": "Land Rover",
    "BTL": "Bentley",
    "PSC": "Porsche",
}
```

| Make | Model | MSE        | MAE  | R3    | Dataset Size |
|------|-------|------------|------|-------|--------------|
| AM   | xgb   | 1.098e+08  | 5431 | 0.9045| 715          |
| JAG  | xgb   | 4.105e+06  | 1335 | 0.9570| 1128         |
| BMW  | xgb   | 1.382e+06  | 785.0| 0.9848| 1097         |
| MB   | xgb   | 1.869e+06  | 921.5| 0.9650| 900          |
| LT   | xgb   | 8.313e+07  | 5315 | 0.8015| 162          |
| AR   | xgb   | 3.420e+06  | 1226 | 0.8619| 167          |
| LR   | xgb   | 4.403e+06  | 1273 | 0.9724| 551          |
| BTL  | xgb   | 1.973e+08  | 7537 | 0.8501| 768          |
| PSC  | xgb   | 2.675e+07  | 3303 | 0.8669| 692          |


