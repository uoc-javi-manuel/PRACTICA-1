# PRACTICA-1

En esta prácica crearemos un dataset mediante técnicas de web scraping.

### Integrantes

- Francisco Javier Corrales Estrella
- Manuel Cubertorer Gumbau

## 1. CONTEXTO

El mercado eléctrico está sufriendo una revolución a nivel mundial, la aparición de nuevas fuentes de energía más limpias y la concienciación de la población frente a la contaminación y al calentamiento global están obligando al mismo a tener que adaptarse. Esta adaptación pasa, principalmente, por tener que ir abandonando las fuentes de generación de energía eléctrica convencionales y más contaminantes, como el carbón o el fuel, por otras más respetuosas con el medio ambiente como la energía solar, la eólica, etc.

Además en la actualidad uno de los temas más incandescentes es el precio de la luz, el cual está sufriendo unas subidas históricas y alcanzando precios de récord debido al augmento del precio del gas y al augmento de la cotización de los derechos de emisión de CO2. Esto está obligando a que se planteen ciertas preguntas como si realmente es conveniente el cierre de las centrales nucleares o si por el contrario se debería seguir apostando por ellas, si se puede evitar tener tanta dependencia energética en el gas, cómo deberíamos seguir apostando por las energías renovables, etc.

Así pues, teniendo en cuenta esta situación en este dataset se pretende recopilar la estructura de generación eléctrica de España en la península para cada día **desde enero del 2021 hasta el presente**, así como las emisiones de CO2 asociadas. Para la obtención de esta información se realizará web scraping sobre la página oficial de Red Eléctrica de España (ree) https://demanda.ree.es/visiona/peninsula/demanda/total/2021-10-18. En esta página web se ofrecen los datos de generación por tecnología para cada día cada 10 min, así como las emisiones de CO2 asociadas, en dos tablas distintas. Por tanto, el análisis consistirá en realizar web scraping para poder obtener de forma automática los datos de **1 año completo**, así como generar un único dataset con los datos de ambas tablas.

Con estos datos podremos analizar cómo afectan las distintas épocas del año a la generación de electricidad, y cómo son las variaciones que sufren en la generación de electricidad las distintas tecnologías durante un año. También podremos obtener resultados sobre qué tecnologías son las que más energía producen, y cuáles son las que más emisiones de CO2 generan.


## 2. TÍTULO

Teniendo en cuenta las consideraciones anteriores sobre el contexto en el que se obtienen los datos el nombre que se propone dar al dataset es: *Estructura de generación eléctrica peninsular española diaria en **2021***.


## 3. DESCRIPCIÓN DEL DATASET

En este dataset se recopilarán los datos de generación de electricidad en la zona peninsular española para cada día durante un **periodo de tiempo de 1 año** desglosado por tecnología, así como las emisiones de CO2 acumuladas diarias.


## 4. DESCRIPCIÓN GRÁFICA


## 5. CONTENIDO

El dataset contiene las siguientes columnas:
- Fecha: Indica la fecha de los datos recogidos
- Hora: Indica la hora de los datos recogidos
- Eólica: Energía eólica en MW producida en la fecha y hora indicada
- Nuclear: Energía nuclear en MW producida en la fecha y hora indicada
- Fuel/gas: Energía de fuel/gas en MW producida en la fecha y hora indicada
- Carbón: Energía de carbón en MW producida en la fecha y hora indicada
- Ciclo combinado: Energía de ciclo combinado en MW producida en la fecha y hora indicada
- Hidráulica: Energía hidráulica en MW producida en la fecha y hora indicada
- Intercambios int: Energía de intercambios internacionales en MW en la fecha y hora indicada
- Enlace balear: Energía del enlace balear en MW perdida en la fecha y hora indicada
- Solar fotovoltaica: Energía solar fotovoltaica en MW producida en la fecha y hora indicada
- Solar térmica: Energía solar térmica en MW producida en la fecha y hora indicada
- Térmica renovable: Energía térmica renovable en MW producida en la fecha y hora indicada
- Cogeneración y residuos: Energía de cogeneración y residuos en MW producida en la fecha y hora indicada
- Emisiones: Emisiones de CO2 totales derivadas de la producción de electricidad en la fecha y hora indicada

Los datos se han recogidos corresponden a un periodo de tiempo de **1 año**, recogidos mediante técnicas de web scraping y **selenium** sobre la siguiente url: https://demanda.ree.es/visiona/peninsula/demanda/total/2021-10-18


## 6. AGRADECIMIENTOS

Se agradece a Red Eléctrica de España por proporcionar los datos de una manera accesible para los usuarios que deseen extraerlos para poder realizar análisis y desarrollar estudios y/o trabajos sobre ellos.


## 7. INSPIRACIÓN

Este dataset tiene una multitud de usos y explotar sus datos puede llevar a conclusiones muy interesantes. Se puede analizar cuáles han sido las tecnologías que más han contribuido a la generación eléctrica en un periodo de tiempo dado, se puede estudiar las posibles variaciones de generación de cada tecnología con el tiempo (día-noche, estaciones, de forma histórica con un espectro de tiempo más amplio, etc.), buscar relaciones entre las emisiones de CO2 y el porcentaje de generación de cada tecnología, entre otros.

Además, todos estos estudios podrían servir a nivel informativo o periodístico, para poder realizar un seguimiento del mercado eléctrico, seguir los objetivos planteados en cuanto a generación de energía eléctrica e incluso predictivos, ya que se podrían emplear para predecir cuáles puede que sean los porcentajes de generación de cada tecnología en un par de años o en un periodo establecido estudiando el histórico de producción.


## 8. LICENCIA

La licencia que hemos escogido para este dataset es *Released Under CC0: Public Domain License* ya que se considera que interesante que la comunidad pueda realizar aportaciones al dataset, incorporando datos para mejorar los análisis y estudios realizados.


## 9. CÓDIGO

Se adjunta el código en Python de la práctica.


## 10. DATASET

El enlace a Zenodo del dataset extraído es:


## 11. CONTRIBUCIONES

| Contribuciones              | Firma |
| --------------------------  | ----------- |
| Investigación previa        | Title       |
| Redacción de las respuestas | Text        |
| Desarrollo del código       | Text        |
