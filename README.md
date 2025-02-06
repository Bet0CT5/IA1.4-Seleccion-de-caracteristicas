# IA1.4-Seleccion-de-caracteristicas
Actividad 4 del curso Inteligencia Artificial I

## Descripción
En la lectura interactiva de este módulo trabajamos con la base de datos de calidad de vino. Ahí,
programamos “a mano”, métodos de selección de características. Pero, al final, te comenté que
existen otras funciones que te permiten realizar este proceso de forma más sencilla y veloz. En
esta actividad deberás generar un modelo de regresión lineal múltiple que contenga solamente
las variables seleccionadas por un proceso de selección hacia adelante y eliminación hacia atrás.

Utilizaremos el archivo de nombre “A1.4 Vino Tinto.csv”, donde podrás encontrar información
para 1,599 observaciones distintas, con 11 mediciones para cada una de ellas, así como con una
variable de salida, la calidad asignada a dicho vino. Los datos se descargaron del UCI Machine
Learning Repository, y originalmente se reportaron en una publicación científica para la revista
Decision Support Systems.

La base de datos cuenta con la siguiente información:
- **acidezFija**. La acidez fija del vino, medida en gramos de ácido tartárico por decímetro
cúbico.
- **acidezVolatil**. La acidez volátil del vino, medida en gramos de ácido acético por
decímetro cúbico.
- **acidoCitrico**. Gramos de tácito cítrico por decímetro cúbico.
- **azucarResidual**. Gramos de azúcar por decímetro cúbico.
- **cloruros**. Gramos de cloruro de sodio por decímetro cúbico.
- **dioxidoAzufreLibre**. Miligramos de dióxido de azufre libre por decímetro cúbico.
- **dioxidoAzufreTotal**. Miligramos de dióxido de azufre total por decímetro cúbico.
- **densidad**. Medida en gramos por centímetro cúbico.
- **pH**. Valor del vino en la escala de pH.
- **sulfatos**. Gramos de sulfato de potasio por decímetro cúbico.
- **alcohol**. Volúmen percentil de alcohol en el vino.
- **calidad**. Mediana de la calidad otorgada por al menos tres catadores, en escala del 0
(muy malo) al 10 (excelente).

## Indice
El trabajo está conformado por 3 archivos los cuales son los siguientes:
- [Reporte en formato ipynb](./A1.4%20531712.ipynb)
- [Reporte en formato html](./A1.4%20531712.html)
- [Base de datos](./A1.4%20Vino%20Tinto.csv)
