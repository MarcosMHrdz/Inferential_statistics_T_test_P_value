![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Estadísticas inferenciales: prueba t y valor p

### Instrucciones

1. Tendremos otro ejemplo simple sobre una prueba t de dos muestras (agrupada, cuando las varianzas son iguales). Pero esta vez se trata de una prueba t unilateral.

En una planta empacadora, una máquina empaca cajas de cartón con frascos. Se supone que una nueva máquina empacará más rápido en promedio que la máquina que se usa actualmente. Para probar esa hipótesis, se registran los tiempos que tarda cada máquina en empacar diez cajas de cartón. Los resultados, en segundos, se muestran en las tablas del archivo `files_for_lab/machine.txt`.
Supongamos que hay evidencia suficiente para realizar la prueba t, ¿los datos proporcionan evidencia suficiente para mostrar si una máquina es mejor que la otra?

2. Un problema adicional (no obligatorio): en este caso no podemos suponer que las varianzas de la población sean iguales. Por lo tanto, en este caso no podemos agrupar las varianzas.
   Muestras aleatorias independientes de 17 estudiantes de segundo año y 13 de tercer año que asisten a una universidad grande arrojan los siguientes datos sobre promedios de calificaciones. Los datos se proporcionan en el archivo `files_for_lab/student_gpa.txt`.
   Con un nivel de significancia del 5%, ¿los datos proporcionan evidencia suficiente para concluir que los promedios de calificaciones de los estudiantes de segundo y tercer año de la universidad difieren?

   Las estadísticas de prueba se pueden calcular como: [enlace a la imagen - Cálculo de estadísticas de prueba para el caso de varianza no agrupada](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/7.04/7.04-unpooled_variances.png)

   Los grados de libertad son `(n1-1)+(n2-1)`.