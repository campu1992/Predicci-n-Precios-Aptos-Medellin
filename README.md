Predicción de Precios de Apartamentos en Medellín, Colombia
Este proyecto tiene como objetivo predecir los precios de los apartamentos en Medellín, Colombia, utilizando técnicas de web scraping, procesamiento de datos y modelos predictivos. A continuación, se detallan los pasos realizados y los resultados obtenidos.

Descripción del Proyecto
Web Scraping: Se realizó scraping a la página web de Finca Raíz para obtener datos de apartamentos en venta en Medellín.
Procesamiento de Datos: Los datos fueron limpiados y preprocesados para asegurar su calidad y adecuación para el modelado.
Modelado Predictivo: Se entrenaron varios modelos para predecir el precio de los apartamentos.
Contenido del Proyecto

1. Web Scraping
Se extrajeron los siguientes datos de la página de Finca Raíz:

Descripción
Número de habitaciones
Número de baños
Número de parqueaderos
Área construida
Área privada
Estrato
Estado de conservación
Antigüedad
Piso
Administración
Precio por metro cuadrado
Barrio
2. Procesamiento de Datos
El procesamiento de datos incluyó los siguientes pasos:

Carga de datos usando pandas.
Limpieza de datos para manejar valores nulos y formatos inconsistentes.
Conversión de variables categóricas a variables dummy.
Normalización y transformación de variables numéricas.
Análisis exploratorio de datos (EDA) para identificar patrones y relaciones.
3. Modelado Predictivo
Se utilizaron dos modelos principales:

Regresión Lineal:

Entrenamiento y evaluación del modelo.
Métricas de rendimiento:
Error Cuadrático Medio (MSE): 6.60e+16
Coeficiente de Determinación (R²): 0.79
Random Forest:

Entrenamiento y evaluación del modelo.
Métricas de rendimiento:
Error Cuadrático Medio (MSE): 8.08e+16
Coeficiente de Determinación (R²): 0.74
4. Predicción de Precios

Resultados
Los modelos desarrollados permiten predecir con un buen grado de precisión los precios de los apartamentos en Medellín. La regresión lineal mostró un mejor desempeño en comparación con el modelo de Random Forest.

Requisitos
Python 3.x
Pandas
NumPy
Seaborn
Matplotlib
Scikit-learn
