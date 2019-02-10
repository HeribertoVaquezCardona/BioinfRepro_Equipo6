# BioinfRepro_Equipo6

#README

##Este repositorio contiene el resultado del ejercicio 3 "software iteresante" del Equipo 6.

##**Integrantes del equipo:**
Gabriela Aridai Borja Martínez
Heriberto Vázquez Cardona

###**Bedassle**
Bedassle [(Bayesian Estimation of Differentiation in Alleles by Spatial Structure and Local Ecology) ](http://www.genescape.org/uploads/7/2/2/0/72206611/bradburd_ralph_coop_2013.pdf) es un paquete de R desarrollado por [Gideon Bradburd](http://www.genescape.org/), que usa un método Bayesiano conCadenas de Markov Monte-Carlo (MCMC) para inferir la contribucion relativa de las distancias ecológicas y geográficas en los patrones de estructura y flujo genético a traves del paisaje, calculando la FST entre individuos o entre poblaciones y modelando la covarianza de las frecuencias alelicas a traves de un espacio Gausiano.

Estos analisis pueden ayudar a determinar si hay otros procesos que esten influenciando los patrones de estructura, sugiriendo que hay otras variables ecologicas no medidas involucradas, o bien son procesos ddemográficos.

Para realizar estos analisis requerimos una base de datos geneticos (SNP) no ligados organizados por poblaciones, una matriz de distancias geográficas y una matriz de distancias ecológicas (las variables ambientales pueden ser discretas o continuas).
