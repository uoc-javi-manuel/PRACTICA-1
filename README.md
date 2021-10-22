# PRACTICA-1


## 1. CONTEXTO

El mercado eléctrico está sufriendo una revolución a nivel mundial, la aparición de nuevas fuentes de energía más limpias y la concienciación de la población frente a la contaminación y al calentamiento global están obligando al mismo a tener que adaptarse. Esta adaptación pasa, principalmente, por tener que ir abandonando las fuentes de generación de energía eléctrica convencionales y más contaminantes, como el carbón o el fuel, por otras más respetuosas con el medio ambiente como la energía solar, la eólica, etc.

Además en la actualidad uno de los temas más incandescentes es el precio de la luz, el cual está sufriendo unas subidas históricas y alcanzando precios de récord debido al augmento del precio del gas y al augmento de la cotización de los derechos de emisión de CO2. Esto está obligando a que se planteen ciertas preguntas como si realmente es conveniente el cierre de las centrales nucleares o si por el contrario se debería seguir apostando por ellas, si se puede evitar tener tanta dependencia energética en el gas, cómo deberíamos seguir apostando por las energías renovables, etc.

Así pues, teniendo en cuenta esta situación en este dataset se pretende recopilar la estructura de generación eléctrica de España en la península para cada día desde enero del 2021 hasta el presente, así como las emisiones de CO2 asociadas. Para la obtención de esta información se realizará web scraping sobre la página oficial de Red Eléctrica de España (ree) https://demanda.ree.es/visiona/peninsula/demanda/total/2021-10-18. En esta página web se ofrecen los datos de generación por tecnología para cada día cada 10 min, así como las emisiones de CO2 asociadas, en dos tablas distintas. Por tanto, el análisis consistirá en realizar web scraping para poder obtener de forma automática los datos de 1 año completo, así como generar un único dataset con los datos de ambas tablas.

Con estos datos podremos analizar cómo afectan las distintas épocas del año a la generación de electricidad, y cómo son las variaciones que sufren en la generación de electricidad las distintas tecnologías durante un año. También podremos obtener resultados sobre qué tecnologías son las que más energía producen, y cuáles son las que más emisiones de CO2 generan.
