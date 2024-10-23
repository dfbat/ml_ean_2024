# Proyecto 1 Relación Minutos Ingreso

**Diego Benavides**

Este trabajo tiene la finalidad de explicar la relación entre las variables teniendo en cuenta la información de la base de datos, identificando si hay una relación entre el total de minutos usados por el cliente con la compañía y el ingreso total de los clientes, la idea es identificar si es posible afirmar que, cuando una persona tiene un mayor ingreso, entonces es mayor la utilización de minutos o todo lo contrario.

Para esto, se han realizado las siguientes acciones:

- Importar librería y cargar los datos.
- Establecer la dimensión del conjunto de datos (shape) y la información general del dataframe (info).
- Identificación de valores faltantes y realizar método de imputación.
- Creación de histograma para cada variable numérica y diagrama para la variable categórica (con comentarios de cada una).
- Diagrama de dispersión entre totrev y totmou con interpretación del mismo.
- Actualización de diagrama de dispersión entre totrev y totmou esta vez incluyendo a creditcd con interpretación de resultados.
- toma de medidas estadísticas descriptivas y comentarios de resultados.

Conclusiones:

- Hay una gran concentración de los datos en los valores mínimos de las variables, lo que nos dice que los usuarios de la base de datos, en su mayoría, cuentan con ingresos entre 0 y 4000.
  Entendiendo esto, vemos que existe una leve relación lineal entre tener un ingreso alto y consumir más minutos, aunque cabe notar que si existe una gran diversidad en el uso de minutos e
  ingresos, al tener en cuenta que algunos de los datos que están por encima de 4000 en la variable ingreso, consumen pocos minutos.
  Esto me lleva a concluir que hay, aunque leve, una tendencia lineal.
  
- La mayoría de clientes (69%) usa tarjeta de crédito, pero vemos una alta dispersión en el gráfico, lo que lleva a pensar que la mayoría de usuarios, independientemente del nivel de ingreso,
  usa tarjeta de crédito, aunque hay un punto a resaltar y es que se ve una leve tendencia a que, de todos los clientes que consumen bastantes minutos y tienen ingresos altos, la mayoría
  usen tarjeta de crédito.

  