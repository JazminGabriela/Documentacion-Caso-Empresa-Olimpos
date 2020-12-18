# Documentacion-Caso-Empresa-Olimpos

## OBJETIVO:
El presente proyecto, tiene como objetivo simular el proceso de la organización Olimpos por medio de la herramienta flexsim, evaluando dos posibles alternativas que podría efectuar la empresa, con el proposito de identificar cuál es la más conveniente.

## FUNCIONAMIENTO:
### Proceso de descarga:

Frente a la descarga de las estibas, se requiere de 8 sources, 1 por cada proveedor, estos presentan una distribución de probabilidad diferente cada uno esta distribución utilizadas hace referencia al tiempo de arribo o tiempo de llegada de cada uno de los ocho tipos de camiones. Esta decisión fue tomada por el equipo consultor teniendo en cuenta que cada source, cabe destacar que cada source se encuentra programado con el fin de tener encuenta los siguientes items:
- *la cantidad de pallets* 
- *Número de cajas que contiene cada tipo de camión.*
- *Tiempo de preparación.*
- *Tiempo de descarga.* 
- *Destino del producto.*

### Proceso de despaletizado:

En el desarrollo de este proceso cuentan con dos separators, el primero en donde cada estiba es separado del producto y el segundo separa el producto en el número de cajas que trae cada estiba, en donde son clasificadas teniendo presente el destino del producto, es decir la tienda a donde se dirige es importante destacar que la información nombrada anteriormente se encuentra en los source inicialmente, que adicionalmente del tiempo de arribo tambien presenta la propoción de producto que contiene cada camión para estas tiendas, dicho camión asimismo en la parte de label se encuentra clasificado por colores que va a ser depende el tipo de camión. 

### Proceso de paletizado:

Dado a que se establecen 10 areas o zonas de paletizado, se establece una zona específica para cada tienda de destino, en las cuales mediante un combiner, son paletizadas cada pallet con setenta cajas, estas se  direccionan a la estación de carga con el fin de se enviados finalmente.



# SUPUESTOS PRESENTADOS:
## - Supuestos para la Alternativa No. 1:
Se trabaja con 4 operarios para el proceso de descarga, 20 para clasificar el producto de acuerdo a su origen, para un total de 24 operarios en sistema.
Se hace uso se 4 transpalet eléctricos, los cuales transportan los pallets de la estación de descarga a la zona P.
Dependiendo el tipo de camión llega a una fuente distinta.
Los pallets a utilizar para paletizar el producto, son los mismos que se obtuvieron en el proceso de despaletización.
Se estima que en promedio llegan 31 estibas y 70 cajas por cada una de ellas, para un total de 2.201 en cada camión, las cuales son utilizadas para el calculo de la proporción de las salidas y llegadas al sistema.

## - Supuestos para la Alternativa No. 2:
Dependiendo el tipo de camión llega a una fuente distinta.
Se trabaja con 4 operarios para el proceso de descarga.
Los pallets a utilizar para paletizar el producto, son los mismos que se obtuvieron en el proceso de despaletización.
Se estima que en promedio llegan 31 estibas y 70 cajas por cada una de ellas, para un total de 2.201 en cada camión, las cuales son utilizadas para el calculo de la proporción de las salidas y llegadas al sistema.


# RESULTADOS OBTENIDOS:
## - Resultados para la Alternativa No. 1:
Se obtiene que en la corrida de la simulacion en el sofware, son 36 camiones los que llegan al transcurrir el día, de los cuales todos son descargados, esto es equivalente  a 79.236 cajas de productos aproximadamente, por otra parte, se obtiene que son cargados 205 pallets o estibas estas que equivalen a 14.350 cajas de producto; con lo dicho anteriomente se presenta una proporción de salidas de producto o cajas respecto a las llegadas de cajas de producto con 18.11%.

## - Resultados para la Alternativa No. 2:
Frente a la alternativa No 2, se obtiene que en la corrida de la simulacion en el sofware, son 33 camiones los que que llegan al transcurrir el día, de los cuales todos son descargados, estos equivalen  a 72.633 cajas de producto aproximadamente; por otra parte, se obtiene que son cargados 204 pallets o estibas que equivalen a 14.280 cajas de producto; se presenta una proporción de salidas de producto o cajas respecto a las llegadas de cajas de producto con 19.66%.

