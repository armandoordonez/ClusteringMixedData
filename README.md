Clustering de Datos Mixtos
Muchos conjuntos de datos contienen una combinación de datos categóricos y continuos. Sin embargo, no es sencillo agrupar conjuntos de datos con diferentes tipos de datos. Este repositorio contiene un notebook que explora dos formas simples de abordar este problema utilizando Python.

Lee el artículo completo en Medium aquí:

https://ryankemmer.medium.com/clustering-on-mixed-data-types-in-python-7c22b3898086

Conjunto de Datos
En este repositorio, agrupo un pequeño conjunto de datos que creé, el cual combina características categóricas y continuas. Mis datos ficticios representan información de clientes que podría usarse para comprender a los usuarios de un sitio web o aplicación de comercio electrónico. Nuestro conjunto de datos falso tiene cuatro características:

OS — Sistema operativo del cliente ficticio (Categórico)

ISP — Proveedor de servicios de Internet del cliente ficticio (Categórico)

Age — Edad del cliente (Continuo)

Time Spent — Tiempo que los usuarios ficticios pasaron en nuestro sitio web (Continuo)

Método 1: K-Prototypes
El primer método de clustering que probaremos se llama K-Prototypes. Este algoritmo es esencialmente una combinación entre los algoritmos K-means y K-modes.

Método 2: K-Means con One Hot Encoding
Una alternativa al uso del algoritmo K-Prototypes es aplicar el algoritmo K-means junto con one-hot encoding para las variables categóricas.

Conclusión
Usando nuestro conjunto de datos ficticio, observamos diferencias significativas en los grupos determinados por estos dos métodos. K-Prototypes parece considerar de manera equilibrada tanto las características categóricas como las continuas. Por otro lado, K-means parece dar mucho más peso a las características categóricas, lo cual podría no ser deseable en ciertos casos.





