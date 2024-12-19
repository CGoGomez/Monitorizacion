#TCPDump

Cosas de la red; **tcpdump** captura paquetes de red en la interfaz predeterminada y muestra información en tiempo real en la terminal. Pero ojo, este comando captura todo
sin absolutamente ni un solo filtro, por lo que podrías acabar teniendo una lista de direcciones que hace que el hacer scroll para encontrar lo que buscas se vuelva tedioso.

![tcpdump](/img/tcpdump.png)

En la captura, se ve que ha capturado tanto como podía por segundo hasta hacer uso de Crtl + C para detenerlo con un total de 600 paquetes recibidos. Muy complejo revisar tanto
paquete y más por segundo desde que lanzas el comando hasta que lo cancelas, mucho lío.

## TCPDump -i 
Comando muy sencillo, especifica la interfaz de red en la que se realizará la captura de paquetes... no hay más, ese es el comando

![tcpdump](/img/tcpdumpi.png)

## TCPDump -i -w
Guarda los paquetes capturados en un archivo para su análisis posterior. ¿Te acuerdas de como podías capturar 600 paquetes? Pues esto pueden ser 600 paquetes, pero al menos
podrás usar un parámetro de búsqueda.

![tcpdump](/img/tcpdumpeno.png)

## TCPDump -r
Si bien el comando anterior funciona, no es recomendable usarlo constantemente pues reemplaza todas las líneas de el archivo donde lo guardamos por nuevas líneas.
¿Solución? Guardarlo en un archivo que ya existe, si hay algún problema guardas y haces un registro del momento.

![tcpdump](/img/tcpdumpr.png)
