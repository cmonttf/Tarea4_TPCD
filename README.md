# Tarea 4

## Enunciado

Se solicita desarrollar una aplicación en Jupiter Notebook que muestre una historia del proceso de desarrollo de un análisis de regresión sobre algún conjunto de datos utilizanndo las herramientas que provee el lenguaje de programación Python. Se deberá ocupar bibliotecas vistas en clases y debe considerar lo siguiente:

- Seleccionar un conjunto de datos para realizar un análisis de regresión.
- Definir cuál va a ser el atributo, variable de predicción y/o dependiente.
- Realizar un análisis de los atributos del conjunto de datos que serán seleccionados para realizar el modelamiento del problema. Considerar lo siguiente:
    - df.dtype(), df.corr(), df.describe(), df.value_counts(), df.groupby(), df.pivot().
    - sns.regplot(), sns.boxplot().
    - stats.pearsonr(), stats.f_oneway(). Para calcular el valor-P, F-test y coeficiente de correlación.
- Realizar el desarrollo de un modelo seleccionando cuál modelo de regresión es el que mejor se ajusta para realizar un pronóstico del atributo de predicción. Considerar lo siguiente:
    - Regresión lineal, regresión lineal múltiple, regresión polinomial, regresión polimonial multivariable.
    - Gráficos de regresión (regplot), gráficos de residuos (residplot), gráficos de distribución (kdeplot).
    - R-cuadrado (score, r2.score), MSE o error cuadrático medio (mean_square_error).
    - fit(), predict(), intercept, coef, np.polyfit(), np.poly1d(), PolinomialFeature, transform(), fit_transform(), StandarScaler(), Pipeline().
- Aplicar alguna técnica de refinamiento y evaluación del modelo para controlar el subajuesto o sobreajuste del modelo. Para ello, considere alguno de los siguientes elementos:
    - train_test_split(): x-entrenamiento, x-prueba, y-entrenamiento, y-prueba, test_size.
    - Validación cruzada: cross_val_score(), cross_cal_predict().
    - Gráficos de distribución.
    - Regresión de Cresta: Ridge().
    - Búsqueda de Grilla: GridSearchCV().

Nota:
    Debe ser desarrollado utilizando bloques de Markdown y Python contando una historia del desarrollo.