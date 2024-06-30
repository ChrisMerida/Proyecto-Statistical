# Proyecto Fase 2
A partir del proceso de ingeniería de características desarrollado en la Fase 1 del proyecto, se desarrollaron varios modelos utilizando distintos algoritmos y variando hiper-parámetros. Cada modelo fue evaluado para determinar su desempeño, lo que permitió seleccionar el más preciso, que en este caso fue XGBoost. Posteriormente, se optimizaron los hiper-parámetros del modelo seleccionado y se registraron los resultados obtenidos. Finalmente, se planteó el modelo definitivo para la predicción de la variable Satisfaction, asegurando que el modelo final fuera robusto y preciso para su implementación en el análisis predictivo.

## Archivos 
1. data_encoded.csv
    - Dataset obtenido al finalizar la Fase 1. 
2. note_tres.ipynb
    - Creación de modelos.
    - Optimización de hiper-parámetros.
    - Planteamiento de modelo final.
    - Predicción.
3. model_results.csv
    - Listado de modelos generados calificados, tiempo de entrenamiento, fecha y hora de entrenamiento. 
4. predicciones_xgboost.csv 
    - Predicciones generadas. 

## Librerias requeridas
- pandas
- numpy
- matplotlib
- seaborn
- xgboost
- lightgbm
- datetime
- sklearn

## Paquetes - clases
Sklearn:
- linear_model - LogisticRegression
- naive_bayes - GaussianNB
- ensemble - RandomForestClassifier
- discriminant_analysis - LinearDiscriminantAnalysis as LDA
- tree - DecisionTreeClassifier
- discriminant_analysis - QuadraticDiscriminantAnalysis
- svm - SVC
- ensemble - AdaBoostClassifier, GradientBoostingClassifier
- metrics - accuracy_score, roc_auc_score, classification_report
- model_selection - train_test_split, GridSearchCV
- preprocessing - MinMaxScaler, LabelEncoder
- impute - SimpleImputer

## Estructura
1. División de datos (Train, Test). 
2. Escalado y ajuste.
3. Algoritmos. 
4. Optimización de hiper-parámetros.
5. Registro de modelos. 
6. Modelo final.
7. Predicciones.

## Modelos
Se desarrollaron un total de 11 modelos de clasificación, cada uno variando sus hiper-parámetros para explorar distintas configuraciones y mejorar el rendimiento. Posteriormente, cada modelo fue evaluado para determinar su precisión y efectividad en la tarea de clasificación. Este proceso exhaustivo de prueba y evaluación permitió identificar el modelo más preciso y adecuado para predecir la variable Satisfaction. 

## Algoritmo y clalificación 
1. Regresión logística: 0.867179339418228
2. Naive Bayes: 0.850895181970724
3. Random Forest: 0.947785154180773
4. SVM: 0.938239727865861
5. LDA: 0.866815851365546
6. Árboles de decisión: 0.93935219111631
7. Análisis de discriminante cuadrático (QDA): 0.852700348350262
8. AdaBoost: 0.927808133842478
9. Gradient Boosting: 0.954685122563784
10. XGBoost: 0.954989521590834
11. LGMB: 0.954466841935045




