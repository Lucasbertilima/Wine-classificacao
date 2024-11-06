# Wine-classificacao

## importação das bibliotecas e analise dos dados do dataset
Inicialmente fazemos a importação de todas as bibliotecas que serão utilizadas para a leitura dos dados e no treinamento do modelo.
Em sequencia fazemos uma analise dos dados para entender como eles estão distrivuidos e quais são as caracteristicas.

## Separação de treino e teste
Realizamos a separa de treino e teste, 70% para treino e 30% para teste

## Treinamento dos modelos e comparação dos resultados
A seguir temos o treinamento dos modelos, para este dataset utilizamos 3 modelos de machine learning diferentes, o KNN, o DecisionTree e o RandomForest. Para cada um deles utilizamos diferentes parametros para poder ter uma melhor visualização dos resultados

## DecisionTree
====================================================================================================
Profundidade da Árvore: 1
Acurácia: 0.6111111111111112
====================================================================================================
Matriz de Confusão:
 [[17  2  0]
 [ 5 16  0]
 [14  0  0]]
====================================================================================================
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.47      0.89      0.62        19
         1.0       0.89      0.76      0.82        21
         2.0       0.00      0.00      0.00        14

    accuracy                           0.61        54
   macro avg       0.45      0.55      0.48        54
weighted avg       0.51      0.61      0.54        54

====================================================================================================
====================================================================================================
Profundidade da Árvore: 2
Acurácia: 0.8518518518518519
====================================================================================================
Matriz de Confusão:
 [[17  2  0]
 [ 5 16  0]
 [ 1  0 13]]
====================================================================================================
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.74      0.89      0.81        19
         1.0       0.89      0.76      0.82        21
         2.0       1.00      0.93      0.96        14

    accuracy                           0.85        54
   macro avg       0.88      0.86      0.86        54
weighted avg       0.87      0.85      0.85        54

====================================================================================================
====================================================================================================
Profundidade da Árvore: 3
Acurácia: 0.9629629629629629
====================================================================================================
Matriz de Confusão:
 [[18  1  0]
 [ 0 21  0]
 [ 0  1 13]]
====================================================================================================
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       1.00      0.95      0.97        19
         1.0       0.91      1.00      0.95        21
         2.0       1.00      0.93      0.96        14

    accuracy                           0.96        54
   macro avg       0.97      0.96      0.96        54
weighted avg       0.97      0.96      0.96        54

## RandomForest 
====================================================================================================
Profundidade da Árvore: 1
Acurácia: 0.8333333333333334
Matriz de Confusão:
 [[17  2  0]
 [ 5 16  0]
 [ 2  0 12]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.71      0.89      0.79        19
         1.0       0.89      0.76      0.82        21
         2.0       1.00      0.86      0.92        14

    accuracy                           0.83        54
   macro avg       0.87      0.84      0.84        54
weighted avg       0.85      0.83      0.84        54

====================================================================================================
====================================================================================================
Profundidade da Árvore: 2
Acurácia: 0.8888888888888888
Matriz de Confusão:
 [[19  0  0]
 [ 5 16  0]
 [ 1  0 13]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.76      1.00      0.86        19
         1.0       1.00      0.76      0.86        21
         2.0       1.00      0.93      0.96        14

    accuracy                           0.89        54
   macro avg       0.92      0.90      0.90        54
weighted avg       0.92      0.89      0.89        54

====================================================================================================
====================================================================================================
Profundidade da Árvore: 3
Acurácia: 0.9074074074074074
Matriz de Confusão:
 [[18  1  0]
 [ 2 19  0]
 [ 0  2 12]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.90      0.95      0.92        19
         1.0       0.86      0.90      0.88        21
         2.0       1.00      0.86      0.92        14

    accuracy                           0.91        54
   macro avg       0.92      0.90      0.91        54
weighted avg       0.91      0.91      0.91        54

====================================================================================================

## KNN
====================================================================================================
Número de vizinhos: 1
Acurácia: 0.7962962962962963
Matriz de Confusão:
 [[17  0  2]
 [ 3 16  2]
 [ 1  3 10]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.81      0.89      0.85        19
         1.0       0.84      0.76      0.80        21
         2.0       0.71      0.71      0.71        14

    accuracy                           0.80        54
   macro avg       0.79      0.79      0.79        54
weighted avg       0.80      0.80      0.80        54

====================================================================================================
====================================================================================================
Número de vizinhos: 2
Acurácia: 0.7037037037037037
Matriz de Confusão:
 [[17  0  2]
 [ 4 16  1]
 [ 2  7  5]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.74      0.89      0.81        19
         1.0       0.70      0.76      0.73        21
         2.0       0.62      0.36      0.45        14

    accuracy                           0.70        54
   macro avg       0.69      0.67      0.66        54
weighted avg       0.69      0.70      0.69        54

====================================================================================================
====================================================================================================
Número de vizinhos: 3
Acurácia: 0.7407407407407407
Matriz de Confusão:
 [[17  0  2]
 [ 1 15  5]
 [ 1  5  8]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.89      0.89      0.89        19
         1.0       0.75      0.71      0.73        21
         2.0       0.53      0.57      0.55        14

    accuracy                           0.74        54
   macro avg       0.73      0.73      0.73        54
weighted avg       0.74      0.74      0.74        54

====================================================================================================
====================================================================================================
Número de vizinhos: 4
Acurácia: 0.7222222222222222
Matriz de Confusão:
 [[17  0  2]
 [ 1 16  4]
 [ 2  6  6]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.85      0.89      0.87        19
         1.0       0.73      0.76      0.74        21
         2.0       0.50      0.43      0.46        14

    accuracy                           0.72        54
   macro avg       0.69      0.70      0.69        54
weighted avg       0.71      0.72      0.72        54

====================================================================================================
====================================================================================================
Número de vizinhos: 5
Acurácia: 0.7407407407407407
Matriz de Confusão:
 [[17  0  2]
 [ 1 15  5]
 [ 1  5  8]]
Relatório de Classificação:
               precision    recall  f1-score   support

         0.0       0.89      0.89      0.89        19
         1.0       0.75      0.71      0.73        21
         2.0       0.53      0.57      0.55        14

    accuracy                           0.74        54
   macro avg       0.73      0.73      0.73        54
weighted avg       0.74      0.74      0.74        54

====================================================================================================

# Conclusão
O modelo de randomForest foi o que obteve o melhor resultado, acredito que seja por ele utilizar mais parametros para o treinamento, fazendo com que ele seja menos afetado por dados outliers e que ele possa realizar mais treinos com o dataset, aumentando a acuracia do resultado
