Tratamiento a los datos
Algunos de los tratamientos de datos más frecuentes son:

Eliminar las observaciones (líneas) con entradas de datos inválidos;
Eliminar observaciones donde hay datos perdidos (missing data);
Filtros própios de la investigación.
Importando pandas y leyendo el dataset del projecto
https://pandas.pydata.org/

import pandas as pd
datos = pd.read_csv("/content/datos.csv")
datos.sample(10)

1.2 Tipos de datos
Clasificación de una variable

Variables cualitativas ordinales
► Variables que pueden ser ordenadas o que responen algun tipo de jerarquía

La variable edad puede ser clasificada de tres formas diferentes:
CUANTITATIVA DISCRETA - cuando representa años completos (números enteros);
CUANTITATIVA CONTINUA - cuando representa la edad exacta, siendo representada por fracciones de años;
CUALITATIVA ORDINAL - cuando representa intervalos de edad.
