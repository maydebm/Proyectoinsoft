# PROYECTO FINAL DE INGENIERIA DE SOFTWARE

este programa realiza el ajuste de poligonales cerradas y abiertas

## LECTURA DE DATOS
La lectura de datos se realiza desde un arhivo plano con un formato predefinido

> el tipo de poligonal se ingresa por pantalla

> la ruta del archivo con las mediciones de la poligonal se digita en pantalla

## VALIDACIONES
El programa valida si el archivo con las mediciones cumple con el formato que el programa lee

## AJUSTES

###  Poligonal cerrada
si la poligonal es cerrada los posibles metodos de ajuste seran:

-Metodo de Brujula
-metodo de transito

> se solicitara por pantalla al usuario las coordenadas de los puntos de la linea de referencia

### Poligonal abierta
Si la poligonal es abierta el metodo de ajuste sera **crandall*

> Se solicitara por pantalla al usuario las coordenadas de los puntos de la linea de referencia de inicio y fin

## SALIDA
Los resultados de los calculos y los ajustes se guardan en un archivo plano en la misma ruta  del archivo de entrada

## GRAFICOS
La poligonal se dibuja a traves  de uno de los siguientes metodos

- Un archivo **Geojson** o *json**
- En consola a traves de una libreria grafica 
-En un archivo CAD


