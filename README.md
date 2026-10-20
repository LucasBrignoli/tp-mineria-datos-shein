¿Qué distingue a un producto caro de uno barato?
Trabajo práctico de Aprendizaje de Máquina y Minería de Datos de la Universidad Nacional de Lanús.
En este Colab se analizan productos de SHEIN para identificar qué diferencia a un producto caro de uno barato dentro de su categoría. Primero, se limpian los datos: se unen los 20 archivos del dataset, se eliminan duplicados y valores inválidos, y se convierten los datos al formato necesario. Después, se exploran los precios, descuentos, ventas y títulos mediante gráficos.

A continuación, se utiliza K-Means para agrupar los productos según su precio relativo, descuento, ventas y cantidad de palabras en el título. Luego, se entrena una red neuronal para clasificar los productos como Baratos, Medios o Caros sin utilizar el precio como dato de entrada. Se evalúan los resultados de ambos métodos para analizar qué características ayudan a diferenciar los productos y qué tan bien funciona la clasificación.

Para ejecutarlo, hay que abrir el notebook en Colab y correr las celdas en orden. El dataset se descarga automáticamente desde Kaggle, por lo que no hace falta cargar los archivos manualmente.
