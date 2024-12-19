## Comando Free

El comando **free** (que nada tiene que ver con ofertas) es un comando que muestra información detallada sobre la memoria del sistema, incluyendo tanto la memoria física (RAM) como la memoria swap. 
Proporciona un desglose de la memoria total, utilizada, libre, compartida, buffers y caché.
![comando free](/img/free.png)

Simple, sencillo y para toda la familia, pero... mucho número y tampoco es que nos sirva a nosotros para reconocer gran cosa, no es lenguaje humano, aquí entra la mejor opción del free, uno que exprésamente
fue hecho para que las mentes simples de los humanos puedan leer, el lenguaje máquina es simple pero para la propia máquina.

## free -h
Es la misma que el comando free, pero la salida se presenta en un formato más humano-legible, utilizando unidades como kilobytes, megabytes o gigabytes en lugar de bytes.

![comando free](/img/freeh.png)

Facilita la interpretación de los resultados, ya que muestra los valores de memoria en unidades más comprensibles. Ahora sí que se puede entender sin tanto dígito ensuciando la pantalla
al menos ahora tienes entendimiento de la cantidad más agradable.

## free -s
Muestra la información de la memoria de forma continua, actualizando la salida cada cierto intervalo de tiempo.

![comando free](/img/frees.png)

Proporciona una visualización dinámica del uso de la memoria a lo largo del tiempo. En el ejemplo podemos observar que hay un **3** y esto indica que actualizará cada 3 segundos la información mostrada, este tiempo se puede
establecer a gusto del usuario, recomendable expresarla en segundos.

***

[Volver](README.md)
