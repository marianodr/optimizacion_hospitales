# optimizacion_hospitales
Notebook de optimización (geográfica) realizado en la cátedra "IC314 Inteligencia Computacional" de la Facultad de Ingeniería Oberá (FIO UNaM).

## Consigna: 
* A través del dataset 'Datos_Misiones.csv' determinar la ubicación (latitud y longitud) de 9 hospitales en el territorio de la [Provincia de Misiones](https://es.wikipedia.org/wiki/Provincia_de_Misiones).
* El método y función costo utilizados son de libre elección.

## Solución propuesta:
* Se abstrae la problemática ignorando la existencia de otros hospitalkes en el territorio.
* Solamente se tiene en cuanta la distancia a las distintas ciudades y cantidad de población. 
* Para lograr el objetivo se utilizó el método Montecarlo para generar las diferentes coordenadas. A través de una función por tramos se valida que las coordenadas se generen en terriotorio misionero.
