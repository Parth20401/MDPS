# Multiple Disease Prediction System


This webapp was developed using Flask Web Framework. Several ML models were used and were trained on large Datasets. The algorithm with best accuracy was used for disease prediction. All the links for datasets are mentioned below. The webapp can predict following Diseases:

- Diabetes
- Heart Disease
- CKD
- Breast Cancer
- Liver Disease
- Malaria
- Pneumonia

## Sample images of the website

### Home Page
![Screenshot (257)](https://github.com/Parth20401/MDPS/assets/97301303/085973fb-149c-446f-8794-5c0846560513)

### Heart Disease Prediction page
![Screenshot (258)](https://github.com/Parth20401/MDPS/assets/97301303/26943161-038a-437f-8177-1a8adaf3cefb)

### Pneumonia prediction page
![Screenshot (259)](https://github.com/Parth20401/MDPS/assets/97301303/00d5410c-c215-4dc0-a372-c35ee98eb58b)

### Result Page
![Screenshot (260)](https://github.com/Parth20401/MDPS/assets/97301303/1d47ab97-8a5b-467e-906c-6496c148a2c9)




## Models with their Accuracy of Prediction

| Disease        | Best Algorithm           | Accuracy |
| -------------- | ------------------------ | -------- |
| Diabetes       |  Logistic Regression      | 76.62%   |
| Breast Cancer  |  Logistic Regression      | 96.49%   |
| Heart Disease  |  Logistic Regression      | 88.52%   |
| Kidney Disease |   RF Classifier           | 99%      |
| Liver Disease  |   RF Classifier           | 79.66%   |
| Malaria        |     CNN                   | 95.65%   |
| Pneumonia      |     CNN                   | 91.35%   |

## NOTE

==> Python version 3.6.8 was used for the whole project.<br>
==> You can find all the models in [models](https://github.com/venugopalkadamba/Multi_Disease_Predictor/tree/master/models) folder.

## Steps to run this application in your system

1. Clone or download the repo.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:

```
pip install -r requirements.txt
```

5. Run the application

```
python app.py
```

## Dataset Links

All the datasets were used from kaggle.

- [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
- [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
- [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
- [Malaria Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)
- [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)


