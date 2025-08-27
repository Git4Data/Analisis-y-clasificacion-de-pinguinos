1) Objetivos: Realizar un análisis exploratorio y estadístico de las variables.
Aplicar pruebas estadísticas y tablas de contingencia para entender relaciones entre variables categóricas y continuas.
Explorar correlaciones entre variables numéricas.
Probar técnicas de clustering no supervisado (KMeans con método del codo).
Reducir dimensionalidad con PCA.
Entrenar y evaluar diferentes modelos de clasificación supervisada.
Comparar desempeño y analizar posibles problemas de overfitting.
Aplicar modelos a datos sintéticos para validar la generalización.

2)Metodología: 
Análisis exploratorio: Estadística descriptiva de variables continuas y categóricas. Visualización de distribuciones.
Tablas de contingencia para analizar asociaciones entre variables categóricas. Correlaciones entre variables numéricas.
Pruebas estadísticas: Aplicación de pruebas paramétricas y no paramétricas según corresponda. 
Modelado no supervisado: KMeans para agrupar pingüinos.
Uso de la prueba del codo para determinar el número óptimo de clusters.
PCA para reducción de dimensionalidad y visualización de clusters.
Modelado supervisado (clasificación): Se entrenaron y compararon los siguientes modelos:
RandomForestClassifier (excelente desempeño, pero con riesgo de overfitting).
LogisticRegression
KNN
SVM
GradientBoostingClassifier
Aplicación en datos sintéticos: Se generaron registros ficticios de pingüinos para evaluar la capacidad de predicción de los modelos en casos nuevos.

3)Resultados principales: Random Forest alcanzó el mejor desempeño, aunque con riesgo de sobreajuste (overfitting).
Modelos como Logistic Regression y KNN tuvieron buen balance entre desempeño y simplicidad.
XGBoost y Gradient Boosting lograron resultados competitivos.
KMeans + PCA permitió observar una separación clara entre especies de pingüinos sin usar etiquetas.
