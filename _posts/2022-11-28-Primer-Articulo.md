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

#### Fuente:

* https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing


### Sistemas Recomendadores Conversacionales

#### Recipes for building an open-domain chatbot

A proposito de la clase en que se revisaron chatbots conversacionales, al final de esta se mencionó a ParlaIAI, un framework de Python, para entrenar y testear algoritmos conversacionales. Averiguando un poco mas acerca del tema, me encontre con un paper lanzado por el equipo de Facebook Research, llamado [Recipes for building an open-domain chatbot](https://arxiv.org/pdf/2004.13637.pdf), en el que, mas que lanzar un nuevo modelo o arquitectura, se dan consejos para entrenar un buen chatbot.

En este paper se señala que, las caracteristicas que ellos consideran que hacen un buen chatbot son: 

1. Personality
2. Engagingness
3. Knowladge
4. Empathy

De acuerdo a los autores, enfocandose en estos aspectos es posible entrenar mejores modelos, algo que a priori parece dificil enseñarle a las maquinas. Uno de los aspectos que se recalca debe considerarse a la hora de armar un chatbot es el largo de las respuestas que este da. En efecto, respuestas demasiado cortas podrian considerarse como bajas en los aspectos de personality y compromiso del bot. Por otro lado, respuestas demasiado largas hacen que el usuario se aburra o el bot empiece a divagar. Lo que tambien le quita puntaje en algunos de los aspectos mencionados anteriormente.

Otro aspecto relevante son los metodos de evaluación de los dialogos. Dentro de los mencionados estan:

* **ACUTE-Eval** se hace una comparacion entre dos dialogos, donde el evaluador debe señalar su preferencia por uno de los dos presentados. Mas especificamente se le hacen dos preguntas al evaluador para evaluar distintas areas:
	* *Engagingness Question*: "Who would you prefer to talk for a long conversation?"
    * *Humaness Question*: "Which speaker sounds more human?"
    
Se busca que las preguntas anteriormente planteadas permitan cuantificar algunas de las dimensiones anteriormente planteadas.

* **Self-Chat ACUTE-Eval** Debido a que las evaluaciones hechas por humanas serian mas costosas, lentas y subjetivas. Por lo que en este tipo de evaluacion se busca que el chatbot ocupe el rol de ambas partes en una conversacion, luego el dialogo generado es comparado por uno hecho por humanos. Se recalca que este metodo no sirve para evaluar todo tipo de dimension.

Finalmente, los autores testean bajo varios metodos distintos algoritmos y pese a que se llega a la conclusion de que aun falta un largo camino para obtener resultados satisfactorios, el paper presenta una buena guia acerca de aspectos a los que hay que estar atentos a la hora de evaluar nuestras IA´s conversacionales.

**** Fuente:

* https://arxiv.org/pdf/2004.13637.pdf
* https://parl.ai/about/



### Dominios de aplicación e investigación reciente
