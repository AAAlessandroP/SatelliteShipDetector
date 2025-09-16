# Ship Satellite Image Classifier

Induction of two different _machine learning_ models with the purpose of classifying __satellite images__ containing __ships__ in two classes:
- __Class 0__: __NO SHIP__ (or __PARTIAL SHIP__);
- __Class 1__: __SHIP__;

Possible applications of this include Ship Tracking, Ship Rescue, AShM seekers.

The two models developed are respectively:
- Single hidden-layer __Neural Network__;
- __Support Vector Machine (SVM)__

The training & evaluation of the models is perfermed on a __K-Fold__ of the dataset, in order to get more reliable evaluation results.

After the __optimization__ of the models it's performed an __Ablation Study__ to verify that the preprocessing of the data is not creating performance losses.

Read the presentation we gave in [here](./relazione%20e%20presentazione%20progetto/presentazione.pdf), or the full Project Relation [here](./relazione%20e%20presentazione%20progetto/relazione%20progetto.docx).

More informations about _dataset_, _training_ and _performance evaluation_ avaible in the folder _relation_ of the repository (currently only in italian).
