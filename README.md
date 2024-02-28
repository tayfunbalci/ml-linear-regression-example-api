# Lineer Regression Example API

## Installing packages with conda

```conda install --file requirements.txt```

## Running api application

```python app.py```

## Postman Kullanımı

BASE_URL = http://localhost:5000


| Method | Url                                                | Açıklama                              | Parametreler                                 |
|--------|----------------------------------------------------|---------------------------------------|----------------------------------------------|
| POST   | /predict                                           | Model Tahmini                         | { "X": [[4,4]] }                             |