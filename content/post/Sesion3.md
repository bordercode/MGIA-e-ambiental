---
title: Teoría del consumidor
date: 2022-10-12
linktitle: El mercado
menu:
  main:
    name: Sesión 3
    weight: 5
---

## Teoría del consumidor y los mecanismos de mercado

### ¿Cómo debe responder la sociedad ante los retos que plantea la escasez  de Recursos hidricos?


Una dirección es mediante los **mecanismos de mercado**. Esto se traduce en el diseño de estrategias que generen los **incentivos** correctos. Por ejemplo mediante el sistema de **precios**

##### Esquema de la economía de los recursos hídricos considerando los sectores demandantes y la oferta o fuentes que rpoveen el recurso. 

+ **3 Fuentes**
+ **4 Sectores**

![](/img/water-economy.jpg)
*Fuente: The economics of water resources*



De manera complementaria podemos incorporar las variables ambientales para integrar un modelo hidro-social-economico.


![](/img/modelo_hydro_soc.jpg)


En términos conceptuales podemos definir la sigueinte relación entre las variables del modelo: 


$$\frac{\partial{S(t)}}{\partial{t}}=R(t)+P(t)-ET(t)-(1-h)x-r(t)$$

Donde: **S(t)**: El volumen del stock de agua en el momento *t*

Este volumen puede correponder tanto con el agua **subterránea** en una **cuenca** específica, la cantidad disponible en un lago o bien el volumen de **agua superficial** correspondiente al caudal de un río.

> R(t): Recarga: La recarga puede ocurrir
por un río que ingresa al área o por flujos subterráneos de agua desde el exterior.

> P(t): Precipitación. Ej lluvia. 

> x(t): El agua usada en una economia local (ej. concesionada)

El parámetro $$h \in [0, 1]$$ indica la porción de **x** que se devuelve a la cuenca local.

Para simplificar, tomamos **R**, **P** y **x** como independientes del tiempo. es decir estan dados para un momento particular. 

> r(t) describe
la **escorrentía, escurriemiento o drenaje** en el tiempo t. 

Las escorrentías, son todas las corrientes, ya sean superficiales o subterráneas, que
abandonan el área. Dependen, por supuesto, de la gestión del agua, de la economía.
y de la hidrología de la zona de captación.



> **ET (t)** representa la **evapotranspiración**. Consiste en esa porción de agua que sale del área en forma de vapor. Bosques, plantas y
los cultivos transpiran y el agua se evapora en la superficie del paisaje. Esta agua verde
sube y es llevada por el viento en varias direcciones. Una parte de ella vuelve
como lluvia.


En particular suponemos que el parámetro de **evapotranspiración** depende linealmente del volumen de agua contenido en la cuenca. 

$$ET(t)=\gamma_{1} S(t)$$

Si por ejemplo, la cantidad de agua en una región o la humedad del suelo aumenta, la **evapotranspiración** aumentará.

De manera similar, la función de escorrentía exhibe lo siguiente relación:

$$r(t)=\gamma_{2}S(t)$$

El modelo dinámico de balance considerando estas relaciones será:

$$\frac{\partial s(t)}{\partial(t)}=R(t)+P(t)−\gamma_{1}S(t)−\gamma_{2}S(t)−(1 − h)x$$




En términos gráficos podemos representar las fuerzas intrinsecas de este modelo dinámico, mediante un **diagrama de fase**.


![](/img/diagrama.jpg)

Precisar que el nivel de utilización por los humanos en una cuenca particular **(1-h)x**  no depende, en este modelo, del stock de agua *S(t)* disponible y por lo tanto es representado como una linea horizontal.  


La **línea de pendiente negativa** muestra la tasa de reposición del stock de agua
a través de las **entradas** de precipitación, aguas superficiales y aguas subterráneas menos los **efluentes** de aguas superficiales y subterráneas, así como efluentes por **evapotranspiración** (agua verde).




Si la reserva de agua **S(t)** es menor que **(1-h)X**

Esto implica que el volumen utilizado es mayor y se tiene una reducción en el **stock o reserva** de agua disponible (flecha en sentido ascendente hacia el punto de equilibrio $$S^{*}$$   A una tasa $$\frac{\partial S(t)}{\partial (t)}$$

Nivel que denotamos como un equilibrio de **estado estacionario** al que el stock retornara a pesar de la existencia de desviaciones temporales (ej. eventos climáticos atípicos que incrementen o disminuyan el stock). 

$$\Omega$$ representa un un umbral de interés desde el punto de vista ambiental.

Que el uso del agua sea sostenible depende de este umbral crítico. Este umbral depende de todo el sistema ecológico y su interacción con el ciclo del agua.

Cuando 

$$x > \Omega$$

se producirán graves daños ecológicos debido a una disminución de las funciones básicas de estabilización del agua más allá de su uso económico. 

Tales como:  estabilización del microclima, control del suelo, retención de nutrientes, apoyo al habitat y la diversidad de especies, control de inundaciones, mediante **humedales**.

Para determinar **cuál es el límite superior** de utilización del recurso por encima del cual, se tendrán afectaciones en el ambiente unicamente resolvemos para **x** en la ecuación dinámica e incluimos el umbral $$S(t)=\Omega$$


$$x^{max}=\frac{R_{0}+P_{0} - \gamma_{1} \Omega- \gamma_{2} \Omega}{1-h}$$


Donde **xmax** es la cantidad limite superior admisible de extracción de agua, asumiendo entonces que hay un entevalo sostenible de extracción [0, xmax].


Actividad revisar la aplicación del modelo en página 19 ejercicio 2.2  Sobre decadencia de los Mayas[The economics of water](https://drive.google.com/file/d/15Bq-rTeSXt5gbIbT3SVu17yt6glRHvGb/view?usp=sharing)


### Actividad para Disquss.

Comente la incorporación de la variable **albedo**. ¿Qué efecto tiene sobre el componente de **Evapotranspiración** y el nivel de precipitación? 

Explique a qué se debe el cambio en la pendiente de la función de reserva de agua y como esto puede dar sustento a la hipótesis sobre el manejo inapropiado de los recursos  en la decadencia de los **Mayas** 


### Determinación del valor de los RH. 

Una cuestión central para economía es la
**determinación del valor** y un principio de asignación de valor desarrollado teóricamente es a través de la **utilidad marginal**, concepto que se entiende como un beneficio derivado del consumo de unidades adicionales de un bien.

Se asume que la **utilidad marginal**   (UM) es decreciente. $$\frac{\partial{UM}}{\partial{Q}}<0$$

Donde $$UM=\frac{\partial{U}}{\partial{Q}}$$

El grado de satisfacción que se obtiene con el **consumo** de unidades adicionales tiende a decrecer. 


**Preguntas para reflexionar.**

¿Cómo debemos valorar el agua?

En las decisiones de política pública, cuando se sopesan **costos** y **beneficios**, ¿qué valor debemos asignar a los **servicios que recibimos de los humedales** que nos protegen de las inundaciones y filtran nuestras aguas subterráneas?

¿Estamos valorando lo suficiente la **estética**, el patrimonio y los usos **recreativos** de los **lagos**?

Y, cuando establecemos precios para el uso del agua, **¿deberíamos cobrar mucho más por el agua subterránea** que por el **agua superficial?**
  
  
Determinar **el valor del agua**, en lugar de fijar su **precio**, es un tema **complejo** que está fuertemente influenciado por **los valores que uno considera**, así como las suposiciones que uno hace acerca de
futuro **suministro** de agua y las **demandas** que probablemente se hagan sobre ese **suministro**.

### Determinantes de la demanda.


La **DEMANDA** representa el nivel mínimo de **recursos (p)** que los consumidores estan dispuestos a pagar por adquirir una determinada **cantidad (q)** de un bien.


Los 4 determinantes principales de la **demanda** son: 

El **precio del propio bien**, el precio de bienes relacionados (**substitutos** o **complementarios**), el ingreso del consumidor, las preferencias, las expectativas del precio, el tamaño de la población y las expectativas del ingreso.


**Dx=f(-px, py, I, Pr)**

Adicionalmente 2 determinates de la demanda son las expectativas y el tamaño de la población. 


Curva de demanda con pendiente negativa expreza la **disposición a pagar** por parte de los consumidores y refleja el fenómeno de **utilidad marginal** **decreciente**.

Unidades adicionales de consumo representan un incremento cada vez menor de la utilidad asociada al consumo.  

##### Utilidad Marginal y Curva de demanda: 
  
La utilidad que obtenemos por el consumo de unidades adicionales es decreciente, esto implica un costo de **oportunidad creciente** por unidad y una relación inversa respecto al precio. 

**El precio refleja la disponibilidad a pagar** por parte del consumidor y dado que la utilidad que obtiene de consumir unidades adicionales de un bien particular **tiende a disminuir**, su disponibilidad a pagar por unidades adicionales decrece. 

Hay una **relación inversa** entre cantidad demandada y el precio.  $$Q=f(P)_{-}$$


### Elasticidad de la demanda.

La sensibilidad que tiene la cantidad demandada de un bien respecto a variaciones en su precio se denomina elasticidad. 

Intuitavamente la definición de **elasticidad** nos permite determinar qué tan **flexible** es la demanda cuando experimentamos un **incremento en el precio** de un bien. 

La expresión queda definida por La expresión: 

$$\epsilon=\frac{ \Delta Q} {\Delta P}\frac{P}{Q}$$

$$\epsilon=\frac{\partial{Q}}{\partial{P}} \frac{P}{Q}$$



Ahora bien, es importante notar que los bienes se pueden clasificar en **substitutos** y **complementarios**


Por ejemplo, en un proyecto productivo de un cultivo como el Aguacate, la infraestructura de riego por aspersión es un bien o  producto **complementario** de los **recursos hídricos** 

Las variacions en los precios en este conjunto de bienes impactan la demanda. 

Un bien **substituto** del **agua azul**, utilizada en un proyecto como un campo de golf, puede tener un bien substituto como el **agua tratada**.

Los recursos hídricos son un recurso **especial** entre otros aspectos, por que **no poseen substitutos** cercanos.

¿Qué recurso puede substituir el **agua**?

Podemos pensar en **agua con distintos grados de calidad** pero esta se orienta a procesos muy específicos y bien diferenciados.

Ejemplo: Agua tratada para riego, vs. agua necesaria para la producción de bebidas como la cerveza o el agua resultante de los procesos de plantas desaladoras. 

En todos los casos podemos observar que cada una tiene su nicho y no son recursos que se identifiquen como **subtitutos perfectos**.

Con base en evidencia empírica podemos observar que, productos que no tienen **substitutos** cercanos, como por ejemplo, el agua, la insulina, etc.  tendrán una **elasticidad menor**,  serán  **inelásticos**.


El rango de interés en este indicador  se ubica en el intervalo $$|(\infty, 0]|$$.

+ Donde  **|e|>1**, representa productos que experimentan **una reducción más que proporcional en la demanda** ante un incremento en su precio.

+ Mientras que valores **|e|<1**, productos cuya reducción en la demanda es menos que proporcional a la magnitud del incremento en el precio. 

La representación siguiente nos muestra los **tres escenarios** relevantes en cuanto al parámetro de **elasticidad precio de la demanda**. 

![](/img/elasticity.jpg)

Considere el caso de los recursos hídricos para uso **doméstico**, ¿qué comportamiento en relación a la elasticidad pueden exhibir? 

Es probable que la elasticidad dependa de la circunstancia (uso consuntivo) pero en general **no se espera una elasticidad elevada**. 

No se espera una reducción en la demanda ante cambios en su **precio** y en última instancia en un escenario de relativa escasez, **la demanda tenderá a ser completamente inelástica.**


Este resultado tiene **implicaciones para la fijación de cuotas**.  

Concretamente en la definición del pago por derechos de agua y tarifas en los diferentes sectores.

En algunos estados de la república Méxicana se establece el pago por servicios  de agua potable y saneamiento como un tema con carácter fiscal.   


*"conforme al artículo 22(1) de la Ley de las Comisiones Estatales de Servicios Públicos del Estado de Baja California, la obligación de pago de las cuotas por consumo de agua, tendrán carácter fiscal."*


*"cuando no se cubran los derechos a que se refiere el artículo 15 de la citada ley, el adeudo se haría efectivo en los términos y condiciones que establezca la legislación fiscal del Estado de Baja California."*



#### Demanda Efectiva y el precio de los RH.

Lectura capitulo 4. [Introduction to the economics of water Resources](https://drive.google.com/file/d/1kGQO1XsnrqKCI5sxthq3Nkwf0NGA3XZd/view?usp=sharing)

  (pp. 50-66, secc.4.1-4.6 y 4.9.)


#### Ejercicio.  Demanda de RH subterrános.

Utilice herramientas de percepción remota para caracterizar la demanda por RHS para el caso del acuífero 819 Laguna la Vieja y Los Juncos 847 en el estado de Chihuahua.


Este es un caso de interés ya que en esta zona se ubica el principal desarrollo agrícola productor de algodón de México,lo que ha generado una intensa utilización de recursos hídricos subterráneos  dadas las condiciones climáticas de estas zonas que presentan regímenes  de precipitación limitada.

La utilización de herramientas de percepción remota permite en este caso evidenciar la demanda generada por RHS en la zona.

Técnica aplicada composición de color (RGB R4 G3 B2 y color natural R3 G2 B1 ) con imagenes de proyecto  Sentinel. 

Software: **QGIS** con el plug-in **SCP**


Insumos: Acuífero 847 Los Juntos, para acuífero Laguna La Vieja 819.



## Determinación de valor de RH en el contexto Mexicano. 

En nuestro país se tienen definidos instrumentos regulatorios que retoman los preceptos de economía para establecer valores. Uno de estos instrumentos se expreza por la Ley federal de derechos LFD. En este se definen criterios para el cobro de cuotas para el otorgamiento de concesiones de aprovecheamiento de aguas nacionales. 


![](/img/LFD_capVII.jpg)

La condición de  escasez influye para la definición de zonas de disponibilidad, estas a su vez implican niveles de cobro diferenciados. El supuesto de partida en esta asignación es la existencia de una relación inversa entre disponibilidad del recurso y monto de la cuota a pagar por usuarios. 

La siguiente tabla muestra un ejemplo de estos montos por zona de disponibilidad. 

![](/img/art_223.jpg)

**Pregunta**. ¿Por qué la cuota para agua subterránea es superior a la correspondiente a aguas superficial si en principio el agua superficial es menos abundante?
  
  Así la LFD publica las definiciones que permiten la estimación de los parámetros de disponibilidad de RH en el país. 

La figura siguiente muestra estas definiciones. 

![](/img/idas.jpg)

![](/img/idas2.jpg)


La aplicación de los principios de economía a la regulación de los RH en México también permite la definición de zonas protegidas o zonas de veda en el caso del aprovechamiento de RHS. 


### Ejercicio    

[Input Data](https://drive.google.com/file/d/1f603buCRTjDuR9Y9-5ulo_OC1ytOhr_A/view?usp=sharing)


Revisar documentación en [Las zonas de disponibilidad de agua subterránea en México: Propuesta para su rediseño.](https://drive.google.com/file/d/1DRzNLaa1tTTuSMMxS1ER9GCr3igPzQtY/view?usp=sharing)

##### E.1 Estimación de sobre-explotación de RH subterráneos por acuífero en México. (ver código en sección Ejercicios)


Estime los siguientes indicadores para los 653 acuíferos en México.

- Volumen concesionado.

- El coeficinte de GINI para medir el grado de inequidad en el volumen concesionado en relación a la proporción de usuarios. 

- Contraste los componentes de Oferta y Demanda de aguas subterránea mediante el Indice de volumen concesionado (IVCAS).


- ¿Cuántos acuíferos por Zona se tienen en México?

- Acorde con el enfoque del índice de volumen concesionado, determine ¿Qué proporción de los acuíferos del país se encuentra en situación de sobre explotación?





### Determinantes de la Oferta. 


La determianción de la oferta se basa en la **teoría del productor**

El supuesto de partida es que el productor busca minimizar un función objetivo: **la función de costos.** 

La producción a su vez es posible debido a la utilización **eficiente** de los factores productivos, dado un proceso **tecnológico concreto**, este último, entendido como una manera de combinar los recursos para producir.


En términos generales ej. **Q= f(tierra, trabajo, capital).** 

El incremento de uno de estos factores (trabajo) manteneindo fijo  (*ceteris paribus*) el resto de los factores, implica una aportación cada vez menor sobre la producción. 

El efecto de esta relación se resume bajo el concepto de prodductividad marginal decreciente,  $$PMD_{L}=\frac{\partial {y}}{\partial{L}}$$

Donde $$y=f(L)$$

La siguiente gráfica muestra esta conceptualización

![](/img/porduction.jpg)
*Producción Marginal decreciente *


Este rasgo **(PMD)** del proceso productivo, asegura que el costo marginal (**CM**) , es decir, el costo de la unidad adicional porducida,  sea una función creciente (relación positiva) respecto al nivel de producción (**Q**).

Por su parte el impacto de una innovación tecnológica, permitirá deslplazar la curva de producción a mayores niveles,  manteniendo (*ceteris paribus*) el resto de insumos  constante.

**Note** en la figura siguiente, el cambio en la pendiente de la curva que representa la función de producción.

![](/img/tecnologia.jpg)



### ¿Qué es el mercado? 

##### El mercado como mecanísmo de asignación de recursos. 

>Es un mecanismo de asignación de recursos y funciona mediante **incentivos**. El incentivo clásico es el sistema de precios. 
Los precios permiten emitir señales a las que reaccionan los agentes (consumidores, productores ej. proveedores de servicios de agua o usuarios en los diferentes segmentos: agrícola, industrial, doméstico, generación de energía).

An **incentive** is something (such as the prospect of a punishment or reward) that 
induces a person to act. Because **rational people** make decisions by comparing 
**costs** and **benefits**, they respond to incentives. 

> We need to keep in mind that decisions are made by **HUMANS** (still...), by that  I mean that as humans we are ruled by **pleasure and pain**, seeking the former and avoiding the latter. 

The **market**, as cold as it may seem, follows rules, set by humans and as such it is subject to **failure**  
  
Dentro de las fallas del mercado veremos un subconjunto referido como **Externalidades** Estos son efesctos no intencionados que un agente económico genera afectando a otros.

Observamos en la siguiente representación gráfica, el comportamiento teórico de las fuerzas del mercado.


![](/img/supply-demmand.jpg)

Equilibrio del mercado y determinación del precio. Este se obtiene por la interacción de los procesos de oferta y demanda. 


#### Equilibrio del mercado.

Los desequilibrios emergentes en el contexto del mercado por RH pueden clasificarse como relacionados al manejo de la Demanda o bien por los mecanismos que promueven la oferta. 


![](/img/eqiilibriox.jpg)

En la práctica, diversas acciones institucionaes inducen modificaciones en la oferta y la demanda. 

![](/img/demand-supply.jpg)

#### Actividad

Observe el siguiente clip y comente en el grupo sobre las obras que impulsan la oferta.

[Supply side. Infraestructura](https://www.youtube.com/watch?v=7zvt49-jEY4)

**Ejercicio**
  
Examine el plan maestro de NL para resolver la crisis hídrica de Monterrey  y clasifique las medidas propuestas como promotoras de demanda o de la oferta. 

[Plan Maestro Nuevo León](https://www.nl.gob.mx/planmaestro-agua)
------------------------


Cuando nos referimos a  menejo de RH, la aplicación del principio de **utilidad marginal**, la noción de valor  requiere de ajustes ya que los RH proveen beneficios (utilidad en el lenguaje de economía) indirectos que se extienden mas allá de los usuarios directos. 

Pensemos en los **servicios ambientales** por ejemplo que proporcionan las corrientes superficiales de agua. 

Otros escenarios comunes de aplicación del instrumental de economía incluyen: 

* La implementación de esquemas de asignación entre usuarios, 

* Diseño de política pública para evitar conflictos entre usuarios competidores por el uso del recurso. 

* Toma de decisiones sobre proyectos de infraestructura (análisis costo-beneficio). 


#### Tarea.


[Book Chapter P.215. El agua en México](http://library.fes.de/pdf-files/bueros/mexiko/14377.pdf) capitulo Cambio y confrontación de proyectos políticos en la gestión del agua en México. Alex Ricardo Caldera Ortega, 2017.   Sección 3.2.1. (en clase, resto de articulo para casa.)

Preguntas para análisis. 

1.- El caso Méxicano en materia del manejo de gestión hídrica es referido como un ejemplo de ideas: 


a) Progresistas.

b) Socialistas

c) Neoliberales.


2.-¿Qué influencia han tendio las ideas de la  **Conferencia Internacional sobre Agua y Medioambiente de Dublín en 1992** respecto a la perspectiva de análisis de la gestión de los recursos hidricos en México. 


3.- Organismos como el **Banco Mundial** han emitido recomendaciones en torno a la GRH, indique tres directrices que han sido emitidas por este organismo y que han tenido influencia en la forma que México diseña su política hídrica? 


4.-¿Cuál era el padrón estimado de concesionarios y  el universo estimado de usuarios hacia 1992 en México? 

5.-¿Qué usuarios pagan los valumens concesionados? 

a) Agrícolas hasta el limite concesionado.

b) Indsutriales.

c) Organismos operadores del servicio de
agua potable.

5.-¿Qué objetivos y finalidades promovió el **Programa Nacional de Agua Potable, Alcantarillado y Saneamiento en Zonas Urbanas** (APAZU)?

6.- ¿Cuántos contratos  **M&L** (*Management and leasing*) y **COT** (*Construcción, Operación, Transferencia*) indica el autor que existian en México al momento de su investigación?   


7.- ¿Acorde con la investigación, ¿Qué municipio en México fue el primer caso que firmó contrato de prestación de servicios para extracción, conducción y cobranza?

8.- ¿Qué concluye el autor en relación a los procesos de asignación de concesiones y dados los resultados obervados en municipios como Saltillo, Coahuila, Aguascalientes, Navojoa, Sonora.

9. Consecuencias  de estrategias de impulso a la oferta de RH en México. 

10. Como caracteriza el autor la crisis del agua que actualmente se tiene en México?
  
11. Comente sobre la siguiente afirmación "La escasez no es una propiedad intrínseca del agua, sino es una construcción social donde se perciben restricciones en el aprovechamiento” (Ávila, 2003: 41)." 

12. Considerando el manejo histórico de los recursos hídricos en México. Comente sobre la disyuntiva desarrollo económico-sustentabilidad.



### Glosario 

**Términos de dominio general para la materia.**


Agua en bloque: Volumen de agua potable que entrega la Comisión al Municipio y al
organismo operador, así como el que éstos a su vez entregan a subdivisiones o
conjuntos habitacionales, industriales, y/o de servicios, o a otros prestadores de los
servicios para los fines correspondientes;

Agua pluvial: La proveniente de la lluvia, nieve o granizo;

Agua potable: Aquella que no contiene contaminantes objetables, ya sean químicos o
agentes infecciosos, que puede ser ingerida o utilizada para fines domésticos sin
provocar efectos nocivos a la salud y que reúne las características establecidas por las
normas oficiales mexicanas, y llega a los usuarios mediante la red de distribución
correspondiente;

Agua residual: La que se vierte al drenaje, alcantarillado o cualquier cuerpo receptor o
cauce, proveniente de alguno de los usos a que se refiere la presente Ley y que haya
sufrido degradación de sus propiedades originales;

Agua tratada: La residual resultante de haber sido sometida a los procesos de
tratamiento para remover sus cargas contaminantes, en términos de las normas
oficiales mexicanas y demás normatividad aplicable;

Aguas alumbradas: Aquellas que son extraídas del subsuelo mediante obras artificiales;

Aguas claras: Aquellas provenientes de una fuente natural o de almacenamientos
artificiales, que no hayan sido objeto de utilización previa;

Aguas residuales estatales: Las que se localicen en los sistemas de drenaje y de
alcantarillado estatal previo a su descarga a un cuerpo receptor federal;

Aguas residuales municipales: Las que se localicen en los sistemas de drenaje y de
alcantarillado municipal previo a su descarga a un cuerpo receptor estatal o federal;

Alcantarillado: El sistema de ductos, accesorios y cuerpos receptores para recolectar y
conducir las aguas residuales y pluviales al drenaje;

Aprovechamiento: Aplicación del agua para usos no consuntivos;

Asignación: Convenio que suscribe el Gobernador del Estado, a través de la Secretaría,
para realizar la explotación, uso o aprovechamiento de las aguas de jurisdicción estatal
destinadas a la prestación de los servicios de agua potable para uso doméstico o público
urbano;

Cauce: Canal natural o artificial con capacidad necesaria para conducir las aguas de
una creciente máxima ordinaria de una corriente;

Certificación de procesos: Acción de constatar que la prestación de los servicios se
ajusta a los criterios de calidad establecidos por la Comisión Técnica;

Consumidor: Personas física o jurídica colectiva que adquiere agua potable o tratada a través de pipas autorizadas;

Cloración: El servicio de suministro, aplicación y recarga de reactivos;

Concesión: Acto administrativo mediante el cual la autoridad competente faculta a las
personas físicas o jurídicas colectivas, para la construcción, explotación, operación,
conservación y/o mantenimiento de obras hidráulicas, y, en su caso, de los bienes inherentes, y/o para la prestación de los servicios a que se refiere esta Ley, de forma
regular y continua y por tiempo determinado, mediante la expedición del título respectivo;

Concesionario: Persona física o jurídica colectiva a quien se le otorga una concesión;

Condiciones particulares de descarga: Concentraciones permitidas de elementos
físicos, químicos y bacteriológicos, que contienen las descargas de aguas residuales;

Contaminación: La presencia de uno o más contaminantes o cualquier combinación de
ellos en los cuerpos de agua o en los ecosistemas;

Contaminante: Toda materia que al mezclarse con aguas claras, agua potable o tratada, altera, corrompe o modifica sus características e impide con ello su uso consuntivo;

Costos del servicio del agua: La suma de las inversiones para la construcción,
ampliación, operación, rehabilitación y mantenimiento de la infraestructura hidráulica y
los recursos económicos necesarios para prestar el servicio de agua potable, así como
los demás servicios a los usuarios, incluyendo el pago por los servicios ambientales
hidrológicos que prestan los ecosistemas, de acuerdo con la política hídrica estatal y los
objetivos y metas propuestos en el programa hídrico integral estatal;

Cultura del agua: Conjunto de creencias, conductas y estrategias comunitarias para la
utilización del agua, que se encuentra en las normas, formas organizativas,
conocimientos, prácticas y objetos materiales que la comunidad se da o acepta tener, así
como el tipo de relación entre las organizaciones sociales y en los procesos políticos que
se concretan en relación con el aprovechamiento, uso y protección del agua;

Depósito o vaso: La depresión natural o artificial de captación o almacenamiento de los
escurrimientos y corrientes de agua;

Derivación: La conexión de cualquiera de los servicios a que se refiere la presente Ley,
de un predio a otro;

Descarga: La acción de vaciar agua o cualquier otra sustancia, de forma continua o
intermitente, al drenaje o alcantarillado, incluyendo los cauces, depósitos y vasos;

Desinfección: Aplicación de métodos físicos o químicos para destruir o eliminar los
gérmenes nocivos a la salud;

Drenaje: Sistema de obras hidráulicas para la descarga y alejamiento de las aguas residuales y pluviales;

**Gestión integral del agua:** Procesos asociados a la prestación de los servicios
relacionados con los recursos hídricos, considerando su calidad, disponibilidad y los
usos a los que se destinan, así como los costos del servicio del agua, y que, sin
comprometer la sustentabilidad de los ecosistemas, deben orientarse a maximizar el
bienestar social y económico de la población;


Dilución: La acción de mezclar dos tipos de agua con diferentes características con
objeto de obtener niveles intermedios de contaminación;

Distribución de agua a través de pipas: Entrega de agua potable o tratada al
consumidor a través de pipas;


Drenaje: Sistema de obras hidráulicas para la descarga y alejamiento de las aguas
residuales y pluviales;

Explotación: Aplicación del agua en actividades encaminadas a extraer elementos
químicos u orgánicos disueltos en la misma, después de lo cual es retornada a su fuente
original sin consumo significativo;

Grupos organizados de usuarios: Conjunto de ciudadanos, constituidos o no bajo una
figura jurídica determinada, diferentes de los prestadores de los servicios, que prestan el
servicio de agua potable;

Infraestructura domiciliaria: Instalaciones hidráulicas y sanitarias en el domicilio del
usuario para la prestación de los servicios que establece esta Ley;







