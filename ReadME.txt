"Hello There"..... :P
Aquí encontraran un trabajo practico integrador del 1er modulo que se dicta en la UTN (Universidad Técnica Nacional - Argentina). 

Que debía hacer?:

#---------------- Consigna -------------------

La idea principal es que puedan generar valores aleatorios de presiones y temperaturas para un
 rango de fechas (tomaremos como rango de oct22-oct23). 
Entonces deberán: 
1) Crear una lista que incluya todas las fechas anteriormente mencionadas, ej: (01-10-2022, 02
10-2022,…,30-09-2023) 
2) Crearan una lista con temperaturas aleatorias en grados Fahrenheit asumiendo que puede 
tomar valores posibles para una ciudad de Argentina (la idea es especificar el rango de 
aleatoriedad en números no tan extremos, como por ej: -76) 
3) Crearan una lista con valores de presión atmosférica en pascales asumiendo el mismo criterio 
que el punto anterior. 
4) Como recomendación, es buena idea setear una semilla (seed) para poder obtener siempre los 
mismos resultados. 
5) Deberán crear una función (o utilizar las de la guía de ejercicios) para poder pasar la lista de 
temperaturas a grados Celsius y la de presiones a atmosferas. 
6) Con la ayuda de la librería pandas que vimos en clase, tienen que unificar las listas creadas en
 un DataFrame y nombrarlo “df_temp_y_pres”
 7) Ya teniéndolo, deben hacer un análisis de integridad para verificar que este todo correcto y que
 las variables toman valores lógicos, pueden usar los siguientes métodos o cualquiera que
 consideren necesario: info(), describe(), isna(), shape, etc.
 8) Deberán realizar los siguientes gráficos usando matplotlib o cualquier librería de visualización:
    a- Gráficos de líneas para ver las temperaturas y presiones a lo largo del tiempo (eje x debe ser fecha)
    b- Un diagrama de dispersion entre temperatura y presión
    c- Un boxplot para cada variable continua para detectar outliers 
    d- Matriz de correlación
Todos los gráficos deben estar comentados y analizados, pueden sumar cualquier tipo de atributo que les 
parezca interesante como por ejemplo: obtener el mes o estación del año a partir de la fecha para encontrar patrones.