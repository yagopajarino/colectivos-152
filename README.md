# Colectivos linea 152

Análisis de datos linea 152 de colectivos de la Ciudad de Buenos Aires

## Motivación

El 21/01/2023 me tomé un colectivo de la línea 152 de la Ciudad de Buenos Aires, me había quedado sin batería en el teléfono asi que me dediqué a divagar durante el viaje.

En un momento, encuentro pegado en arriba de una ventana un cartel titulado **CRONOGRAMA DE SERVICIOS DESDE LA BOCA** que detallaba los horarios de salida de colectivos.

Lo primero que noté es que en horas pico llegan a salir colectivos cada 3 minutos o 20 colectivos por hora. Automáticamente me pregunté:

**¿Cuántos colectivos son necesarios para cumplir con ese cronograma de servicios?**

Así, me propuse definir y formalizar el problema, determinar los datos necesarios para responder la pregunta e intentaro conseguirlos con información pública.

## Desarrollo

Lenguaje: python

Análisis: jupyter notebook con las siguientes librerías y módulos nativos: requests, os, dotenv, pandas, numpy, datetime, time, matplotlib, sklearn

Extracción de datos: [api transporte](https://buenosaires.gob.ar/desarrollourbano/transporte/apitransporte) del GCBA

## Notebook

[ver en nbviewer.org](https://nbviewer.org/github/yagopajarino/colectivos-152/blob/main/Colectivos.ipynb)
