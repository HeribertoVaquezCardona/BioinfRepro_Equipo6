# BioinfRepro_Equipo6

#README

##Este repositorio contiene el resultado del ejercicio 3 "software iteresante" del Equipo 6.

##**Integrantes del equipo:**
Gabriela Aridai Borja Martínez y
Heriberto Vázquez Cardona


##**Bedassle**
Bedassle [(Bayesian Estimation of Differentiation in Alleles by Spatial Structure and Local Ecology) ](http://www.genescape.org/uploads/7/2/2/0/72206611/bradburd_ralph_coop_2013.pdf) es un paquete de R desarrollado por [Gideon Bradburd](http://www.genescape.org/), que usa Cadenas de Markov Monte-Carlo (MCMC) para inferir la contribucion relativa de las distancias ecológicas y geográficas en los patrones de estructura y flujo genético a traves del paisaje, modelando la covarianza de las frecuencias alelicas a traves de un espacio Gausiano. Esta paqueteria calcula  FST entre individuos o entre poblaciones. Como input requiere:
1. Datos ambientales de las localidades muestreadas y coordenadas geográficas
2. Archivo con ID de los induviduos muestreados o las poblaciones
3. Datos genéticos

![Input](https://raw.githubusercontent.com/HeribertoVaquezCardona/Imagen2/master/Bedassle_input.png)



[He aqui un tutorial ](http://petrelharp.github.io/popgen-visualization-course/)

##**ANGSD**
ANGSD [(Analysis of Next Generation Sequencing Data)](https://www.ncbi.nlm.nih.gov/pubmed/25420514) es un [software](https://github.com/ANGSD/angsd) en lenguaje C++ para analizar datos GBS. Puede calcular varias estadísticas de resumen y realizar mapas de asociación y análisis genéticos poblacionales trabajando directamente en los datos de secuenciación sin procesar o utilizando las probabilidades de genotipo. Puede utilizar como input datos geneticos en los formatos <span style="color:purple">*VCF, BAM, GLF, m pileup, beagle.*</span> 
Liga para descarga: https://github.com/ANGSD/angsd

![Analisis realizados por ANGSD](https://raw.githubusercontent.com/HeribertoVaquezCardona/Imagen1/master/Analysis.png)



