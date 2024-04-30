# Machine-Learning-with-Tree-Based-Models-in-Python

## Main goal of study: 

Training different models on the same dataset, let each model make its predictions. 

## Output

The output shows that the highest accuracy has classifier Logistic Regression with 94.7% accuracy.
However, the best performance we have with a Voting Classifier is 95.3% accuracy. We instantiate a voting classifier vc by setting the estimators parameter to classifiers.
Fitting vc to the training set yields a test set accuracy of 95.3%. This accuracy is higher than that achieved by any of the individual models in the ensemble.


## Side conclusions

We used the MSE function to evaluate the training and test set mean squared errors. Taking into account that the error of the training set is smaller than the Cv error, we can
deduce that dt overfits the training set and that it suffers from high variance.

## Polish version: 

## Cel badania

Trenując różne modele na tym samym zbiorze danych, pozwoli każdemu modelowi dokonać swoich przewidywań.

## Wynik

Z badań wynika, że ​​największą dokładność posiada klasyfikator Regresja Logistyczna z dokładnością 94,7%.
Jednak najlepszą wydajność mamy dzięki klasyfikatorowi Voting Classifier z dokładnością 95,3%. Tworzymy instancję klasyfikatora głosowania vc, ustawiając parametr estymatorów na klasyfikatory.
Dopasowanie vc do zbioru uczącego daje dokładność zestawu testowego na poziomie 95,3%. Dokładność ta jest wyższa niż osiągana przez którykolwiek z poszczególnych modeli w zestawie.

## Wnioski poboczne

Użyliśmy funkcji MSE do oceny zbioru treningowego i testowego błedów średniokwadratowych. Biorąc pod uwagę że błąd zbioru uczącego jest mniejszy niż błąd Cv możemy
wywnioskować że dt przepełnia zestaw treningowy i ma dużą wariancję.

