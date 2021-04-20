# heatflow
---

Este proyecto hace parte del curso de **Sistemas Inteligente enfocados a Geociencias** de la Universidad Nacional de Colombia 
dictado por el profesor Luis Hernan Ochoa Gutierrez.

## Resumen
A partir de datos de Flujo de Calor, grosor sedimentario y edades de la corteza oceánica en la Cuenca Panamá, se realizó un 
tratamiento de datos utilizando el lenguaje de programación Python para luego emplear herramientas que permiten relacionar estas
tres variables y analizar su comportamiento. Se contrastaron las observaciones de Flujo de Calor con los valores teóricos arrojados 
por modelos matemáticos, que postulan la existencia de una relación lineal entre el Flujo de Calor y el inverso de la raı́z cuadrada de
la edad de la corteza oceánica. Finalmente, se aplicó algoritmos de aprendizaje supervisado de máquina, como clasificador de flujos de
calor neutros, calientes o frı́os, respecto al modelo matemático, con el fin de determinar zonas geográficas frı́as, calientes y neutras,
para ası́ analizar su comportamiento y relación con las variables de grosor sedimentario y edad cortical oceánica.

Los datos utilizados para este estudio fueron obtenidos del <a href="https://www.ihfc-iugg.org/products/global-heat-flow-database">Global Heat Flow Database</a>
y los utilizados en <a href="https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/93RG01249">Pollack, Hurter, & Johnson (1993)</a>  consultados el 22/09/2020; 
de estas bases de datos globales se descargaron los puntos comprendidos en un polı́gono con coordenadas 7.998877 N,
-76.603526 E, -2,766262 S, -102,882063 W (D WGS 1984 Datum)

Los datos de grosor sedimentario fueron obtenidos del <a href= "https://www.ngdc.noaa.gov/mgg/sedthick/"> Total Sediment Thickness of the World’s Oceans and Marginal Seas (Version 3 GlobSed)</a> 
Straume et al. (2019) y Los datos de edades de la corteza Oceánica fueron obtenidos del 
<a href="https://www.ngdc.noaa.gov/mgg/ocean_age/ocean_age_2008.html"> Age, spreading rates and spreading symmetry of the world’s ocean crust (Version 3)</a> 
Müller et al. (2008) para el área comprendida en el estudio.

