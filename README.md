# ML---PROYECTO

Primera parte es la Carga del dataset, luego mostrar su informacion.
En el paso 2 es el analisis de los datos estadisticos, aqui mostramos con df.describe().T
donde nos muestra el promedio, cuartiles, desviacion estandar y el coeficiente de variacion.

Mostramos el coeficiente de variacion nos da que la variacion mas alta son en Bilirubin y ALK_Phos.
Usamos msnm.matrix(df)
para un grafico de los nulos de las columnas, ya con eso observamos los nulos que hay. tambien los sacamos con: null_counts = df.isnull().sum()
print(null_counts)

que nos dice las columnas y la cantidad que los tienen, que son varias.
Tambien mostramos las distribuciones de las columnas numericas.
Mostramos las columnas numericas y tambien las que pueden ser categorizadas.
Mostramos la correlacion de los datos numericos con la columna status. se contestaron las preguntas
Pasamos a la parte de la manipulacion y tratamiento
Tratamos los datos nulos, mostramos los excesos y eliminamos,
Mostramos que no hay ningun nulo
Tratamos las anomalias que haigan, pasamos a la categorizacion, categorizamos lo que ya habiamos visto que se podian categorizar y lo mostramos
Volvemos a contestar las preguntas.
tambien lo mostramos graficamente.
Convertimos todo a numerico, ya que tengamos todo en numerico pasamos la parte 3 de machine learning
dividimos en "x" y "y", mostramos los datos en entrenamiento y pruebas.
Ya hacemos el importe del modelo simple de ML use la regresion logistica.