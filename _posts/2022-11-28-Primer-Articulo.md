---
layout: post
title: Reco-blog
published: true
---
## Recsys - Magister Inteligencia Artificial 2022

### Justicia, Explicabilidad y Transparencia en Sistemas de Recomendación

Durante el año 2002 se estrenó una pelicula llamada Sentencia Previa (o en ingles [Minorty Report](https://es.wikipedia.org/wiki/Minority_Report)), la cual se basó en un relato corto del **año 1956** del escritor  Philip K. Dick. La trama de esta pelicula se desarrolla en Washington, donde un departamento de policía -conocido como Precrimen- detiene a delincuentes basándose en el conocimiento previo que le otorgan tres psiquicos llamados "precognitivos". 

Años despues del estreno de Minorty Report, en el 2016, la Corte Suprema de Wisconsin, aprobó el uso de [COMPAS](https://en.wikipedia.org/wiki/COMPAS_(software)), un algoritmo que segun sus creadores, es capaz de determinar la probabilidad de reincidencia de los reos. A priori, lo anterior puede sonar bien, dictar sentencias basado en que tan probable es que una determinada persona vuelva a cometer un crimen puede hacer la diferencia entre una sentencia como reclusion nocturna, por ejemplo o, una prision preventiva, con todos los costos asociados a la persona y a la sociedad.

Ahora bien. **¿Que tiene que ver la pelicula con COMPAS?** La similitud radica en que en ambos casos se intenta predecir comportamiento criminal.Para esto, en la pelicula utilizan *"siquicos precognitivos"* mientras que, en COMPAS se utiliza un algoritmo del cual sabemos pocos al estar protegido por **secreto comercial**. Como sea, en ambos casos es una caja negra el sistema utilizado para las predicciones.

La pregunta que cabe hacerse es: ¿Es etica la utilización de este algoritmo para castigar a individuos basado la predicción de un comportamiento futuro?. Pueden existir diversas respuestas para la pregunta anterior,en lo que si deberia existir consenso, es que su uso sea aplicado de manera homogenea y sus beneficios o costos se repartan de manera equitativa sin ningun tipo de sesgo.

Lo anterior no parece cumplirse al revisar los resultados de la aplicación de COMPAS, por ejemplo, tenemos el siguiente caso.

![imagen1](https://miro.medium.com/max/720/1*z8RVzTeMFsQ5LSOoXQpyyw.webp)

Donde Borden tenia antecedentes por desordenes cuando era menor de edad, mientras que Praten tenia antecedentes por robo armado. Pese a lo anterior, COMPAS le da  a Borden  una probabilidad mas alta de reincidencia. Finalmente, Praten fue quien presentó nuevamente comportamiento criminal. Lo anterior no ocurre tan solo a nivel individual, un estudio de 7.000 sentencia en Florida fue posible observar el siguiente comportamiento.

![imagen1](https://miro.medium.com/max/1100/1*9_gbsEwskO_fBUEedbXYAA.webp)

#### Puntajes asignados gente de color

![iamgen](https://static.propublica.org/projects/algorithmic-bias/assets/img/risk-scores-black2.min.svg)

#### Puntajes asignados gente blanca

![fasd](https://static.propublica.org/projects/algorithmic-bias/assets/img/risk-scores-white2.min.svg)

En general, gente de raza blanca se le asigna riesgo mucho menor.

Cuando [PROPUBLICA](https://www.propublica.org/) realizó un estudio donde se aislaron otros factores que podian explicar las condenas, se encontró que personas de color se les asignaba un riesgo mucho mayor.

Un minimo exigible a estos sistemas es que sean explicables y entendidos por las personas sobre las que tiene repercusiones, en el ejemplo anterior, vemos que no es posible explicar porque COMPAS tiende a asignarle mayor riesgo a gente de raza negra. El caso anterior es critico por las consecuencias de su aplicación y lo marcado de sus sesgo. Sin embargo, no hay que olvidar que cada vez es mayor la influencia que tienen los algoritmos de inteligencia artificial sobre el día a día de toda la sociedad. Por lo que cada vez es mas critico que sean justos, auditables y transparentes.

#### FUENTES:

* https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing


### Sistemas Recomendadores Conversacionales

### Dominios de aplicación e investigación reciente
