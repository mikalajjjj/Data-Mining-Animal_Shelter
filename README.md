# Data-Mining-Animal_Shelter
# This is project to determine whether an animal in the Austin Animal Shelter has a good chance of being adopted or not by someone

{
    "Decision Tree (initial)": {
        "accuracy": 0.6771478160254556
    },
    "Decision Tree (tuned)": {
        "best_accuracy": 0.6967891235175008,
        "best_params": {
            "max_depth": 10,
            "max_features": 10,
            "min_samples_leaf": 5
        }
    },
    "Naive Bayes": {
        "mean_cv_accuracy": 0.7211917847844951,
        "confusion_matrix": [
            [
                20296,
                41682
            ],
            [
                6510,
                104362
            ]
        ],
        "classification_report": "              precision    recall  f1-score   support\n\n       False       0.76      0.33      0.46     61978\n        True       0.71      0.94      0.81    110872\n\n    accuracy                           0.72    172850\n   macro avg       0.74      0.63      0.63    172850\nweighted avg       0.73      0.72      0.69    172850\n"
    },
    "KNN": {
        "mean_cv_accuracy": 0.6665374602256292
    },
    "Logistic Regression": {
        "mean_cv_accuracy": 0.7322823257159387,
        "confusion_matrix": [
            [
                22113,
                39865
            ],
            [
                6410,
                104462
            ]
        ],
        "classification_report": "              precision    recall  f1-score   support\n\n       False       0.78      0.36      0.49     61978\n        True       0.72      0.94      0.82    110872\n\n    accuracy                           0.73    172850\n   macro avg       0.75      0.65      0.65    172850\nweighted avg       0.74      0.73      0.70    172850\n"
    }
}
