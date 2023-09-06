  ![Universidad Aplicada de Ciencias Aplicadas](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Carrera: 
Ingeniería de Software

Nombre del curso: 
Desarrollo de  Soluciones IOT

Sección: 
SW71

Nombre del profesor: 
Angel Augusto Velasquez Nuñez

"Informe de Trabajo Final"
						 
Nombre del startup: 
DevIOT

Nombre del producto: 
AgriPure

Relación de integrantes:

 - Diego Talledo Sanchez
 - Bruno Moisés Palomino Santa Cruz 
 - Andres Christian Reynoso (U202010196)
 - Frank Yamil Alva Cordova (U
- Franchesco Alexis Soto Morales

Mes y año: 
Agosto 2023
						   
Ciclo: 
2023-2

## Registro de Versiones del Informe

| Version | Fecha| Autor | Descripción de la Modificación |
|-----------|-----------|-----------|-----------|
| 1.0 | 22/08/2023 | Andres Christian Reynoso | Se está desarrollando la primera versión del archivo TB1, estructurando el formato del entregable. |
| 1.1 | 24/08/2023 | Andres Christian Reynoso | Se ha completado la estructura del archivo, asi mismo, se han agregado las preguntas para la entrevista, al igual que se inicio con el proceso de EventStorming |
| 1.2 | 31/08/2023 | Andres Christian Reynoso | Se desarrollaron las preguntas para las entrevistas, de igual manera se esta finalizando el proceso de Eventstorming |
| 1.3 | 06/09/2023 | Andres Christian Reynoso |  |

## Project Report Collaboration Insights

**Enlace del Project Report: [https://github.com/DevIOT-AgriPure/AgriPure-Report.git](https://github.com/DevIOT-AgriPure/AgriPure-Report.git)**
## Contenido
- [Tabla de contenidos](#tabla-de-contenidos)
- Capítulo I: Introducción 
	- 1.1. Startup Profile
		- 1.1.1. Descripción de la Startup 
		- 1.1.2. Perfiles de integrantes del equipo 
	- 1.2. Solution Profile 
		- 1.2.1 Antecedentes y problemática 
		- 1.2.2 Lean UX Process. 
		- 1.2.2.1. Lean UX Problem Statements. 
		- 1.2.2.2. Lean UX Assumptions. 
		- 1.2.2.3. Lean UX Hypothesis Statements. 
		- 1.2.2.4. Lean UX Canvas. 
	- 1.3. Segmentos objetivo. 
- Capítulo II: Requirements Elicitation & Analysis 
	- 2.1. Competidores. 
		- 2.1.1. Análisis competitivo. 
		- 2.1.2. Estrategias y tácticas frente a competidores. 
	- 2.2. Entrevistas. 
		- 2.2.1. Diseño de entrevistas. 
		- 2.2.2. Registro de entrevistas. 
		- 2.2.3. Análisis de entrevistas. 
	- 2.3. Needfinding. 
		- 2.3.1. User Personas. 
		- 2.3.2. User Task Matrix. 
		- 2.3.3. User Journey Mapping. 
		- 2.3.4. Empathy Mapping. 
		 - 2.3.5. As-is Scenario Mapping. 
- Capítulo III: Requirements Specification 
	 - 3.1. To-Be Scenario Mapping. 
	- 3.2. User Stories. 
	- 3.3. Impact Mapping. 
	- 3.4. Product Backlog.
- Capítulo IV: Solution Software Design 
	- 4.1. Strategic-Level Domain-Driven Design. 
		- 4.1.1. EventStorming. 
			- 4.1.1.1 Candidate Context Discovery. 
			- 4.1.1.2 Domain Message Flows Modeling. 
			- 4.1.1.3 Bounded Context Canvases. 
		- 4.1.2. Context Mapping. 
		- 4.1.3. Software Architecture. 
			- 4.1.3.1. Software Architecture System Landscape Diagram. 
			- 4.1.3.2. Software Architecture Context Level Diagrams. 
			- 4.1.3.2. Software Architecture Container Level Diagrams.
			- 4.1.3.3. Software Architecture Deployment Diagrams. 
	- 4.2. Tactical-Level Domain-Driven Design 
		- 4.2.X. Bounded Context: 
			- 4.2.X.1. Domain Layer. 
			- 4.2.X.2. Interface Layer. 
			- 4.2.X.3. Application Layer. 
			- 4.2.X.4. Infrastructure Layer. 
			- 4.2.X.6. Bounded Context Software Architecture Component Level Diagrams. 
			- 4.2.X.7. Bounded Context Software Architecture Code Level Diagrams. 
				- 4.2.X.7.1. Bounded Context Domain Layer Class Diagrams. 
				- 4.2.X.7.2. Bounded Context Database Design Diagram.

# Student Outcome

## Capítulo I: Introducción
### 1.1. Startup Profile
- 1.1.1. Descripción de la Startup

	Hoy en día, uno de los pilares fundamentales en nuestra sociedad que adquiere una importancia trascendental es el sector agrícola. En especial en el contexto peruano, los agricultores desempeñan un papel crucial al impulsar la economía del país. Sin embargo, es evidente que a menudo enfrentan obstáculos significativos, careciendo de las oportunidades y herramientas tecnológicas necesarias para maximizar sus ganancias y optimizar la producción.

	Es ante esta coyuntura de carencias que afectan a miles de agricultores que emerge una solución innovadora: la Startup denominada "AGRIPURE". Esta iniciativa surge con el objetivo de cerrar las brechas existentes y ofrecer un apoyo sustancial a la comunidad agrícola.

	AGRIPURE se presenta como una solución revolucionaria que se materializa a través de una aplicación móvil. Esta aplicación no solo actúa como una asistencia en línea para los agricultores, sino que también proporciona una serie de alternativas, guías y consejos que apuntan a elevar los estándares de la agricultura y, en consecuencia, incrementar la eficiencia y las ganancias de los agricultores.

	Uno de los aspectos destacados de AGRIPURE es su capacidad para unir al agricultor con el mundo exterior, superando las barreras geográficas y facilitando un acceso fluido a información relevante y servicios de alta calidad. A través de su presencia en una Aplicación Móvil, AGRIPURE pone al alcance de los agricultores una plataforma rica en contenido y herramientas que respaldan el desarrollo y el éxito de cada usuario.

	En línea con su misión, AGRIPURE tiene como propósito fundamental asistir a las personas en su empeño por llevar a cabo una siembra eficiente, ya sea en gran escala o incluso en entornos domésticos. Esto se logra a través de una plataforma segura que proporciona recomendaciones y guías adaptadas a las necesidades individuales de cada agricultor.

	Mirando hacia el futuro, AGRIPURE persigue una visión audaz: convertirse en una empresa líder que desempeñe un 				papel esencial en la reducción de la prevalencia de alimentos transgénicos. Esta visión se materializa al ofrecer una plataforma fiable y accesible que permite a cualquier persona involucrarse en la creación y el cultivo de su propio alimento. Al mismo tiempo, AGRIPURE busca contribuir al mejoramiento de los cultivos a gran escala, propiciando la producción de alimentos de mayor calidad y valor nutricional.
	
- 1.1.2. Perfiles de integrantes del equipo

| Nombre| Descripción| 
|-----------|-----------|
|Andres Christian Reynoso  | |
|Bruno Moisés Palomino Santa Cruz|  |
|Diego Talledo Sanchez|  |
|Franchesco Alexis Soto Morales|  |
|Frank Yamil Alva Cordova|  |

### 1.2. Solution Profile
- 1.2.1 Antecedentes y problemática

Para este segmento utilizaremos la tecnica de las 5W y 2H

| Pregunta | Descripcion |
|-----------|-----------|
| When | La situación se presenta cuando alguien carece de la capacitación adecuada para llevar a cabo un cultivo apropiado de las plantas que se van a sembrar, lo que resulta en un impacto negativo en la producción de productos agrícolas. Como consecuencia de la baja calidad de los productos y la escasa cantidad producida, se experimenta una reducida rentabilidad económica. |
| What | De acuerdo al sitio web gubernamental, se observaron marcadas disminuciones en la producción agrícola de varios productos, tales como el café (-84,9%), el ajo (-28,3%), la cebolla (-21,0%), entre otros. Este desafío tiene un impacto directo en la situación económica de las familias de los agricultores, quienes esperan una solución que les brinde la posibilidad de acceder rápidamente a asistencia para hacer frente a esta situación. |
| Who | Personas que se dediquen a la agricultura y no sepan cómo cultivar plantas frutales o vegetales. |
| Where | El problema puede ocurrir en cualquier lugar donde se dediquen al cultivo agrícola. |
| Why | La producción de las plantas se ve perjudicada debido a la carencia de conocimientos técnicos, además de situaciones en las que no se aplican los fertilizantes en los momentos adecuados. |
| How | Mediante las diversas utilidades disponibles en nuestra aplicación, como la medición del pH del suelo, la selección del fertilizante adecuado y la gestión del tiempo de aplicación, así como la visualización de la vegetación en el terreno. |
| How Much | Este desafío suele surgir en aproximadamente un 60% de las ocasiones en las que el agricultor carece de conocimientos técnicos sobre cómo cultivar una planta específica. Por esta razón, nuestra aplicación incluirá herramientas de apoyo que le asistirán en tomar decisiones más acertadas al seleccionar el lugar adecuado para sembrar el producto. |

- 1.2.2 Lean UX Process.
  - 1.2.2.1. Lean UX Problem Statements.
  
**Problem Statement 1:**  
 La sostenibilidad y la seguridad alimentaria son preocupaciones globales crecientes en la agricultura. La agricultura sostenible implica prácticas que conserven los recursos naturales y reduzcan al mínimo el impacto ambiental, mientras que la seguridad alimentaria implica la producción de alimentos seguros y nutritivos en cantidades adecuadas para la población.

Un desafío crítico radica en la falta de acceso de los agricultores a información actualizada y estrategias para adoptar prácticas agrícolas sostenibles y garantizar la seguridad alimentaria. Esto puede dar lugar a prácticas insostenibles y a una menor calidad de los alimentos producidos.

¿Cómo podemos empoderar a los agricultores con conocimientos y herramientas que promuevan la agricultura sostenible y mejoren la seguridad alimentaria en nuestras comunidades agrícolas?

  **Problem Statement 2:**
 
  En nuestro contexto, se hace necesario el acceso a datos relacionados con la siembra, las condiciones climáticas y el tipo de terreno en el que se pretende llevar a cabo la actividad agrícola. Gracias a la información proporcionada por el usuario, es posible mostrar las condiciones a las que están expuestas sus cosechas y, además, suministrar las indicaciones esenciales para llevar a cabo los procesos de cultivo adecuados para cada especie de planta.

Hemos encontrado un factor crítico que tiene un impacto significativo en los resultados finales generados por el sistema. Este factor radica en la introducción de datos inexactos o que no se ajustan a los valores correctos relativos al terreno, el clima y la siembra.

¿Cómo podemos garantizar que el sistema pueda operar con información más precisa para ofrecer resultados favorables al agricultor?  

  **Problem Statement 3:**
 
En el contexto de nuestra aplicación, se busca proporcionar a los agricultores una plataforma tecnológica eficiente y útil. 

Sin embargo, uno de los desafíos identificados es la adopción y el uso efectivo de la aplicación por parte de los agricultores, en particular aquellos que pueden tener limitaciones tecnológicas o resistencia al cambio.

¿Cómo podemos superar las barreras tecnológicas y fomentar una mayor adopción y uso de nuestra aplicación entre la comunidad agrícola para que puedan aprovechar al máximo sus beneficios?

  - 1.2.2.2. Lean UX Assumptions.
  
 Business Assumptions:
1. **Los usuarios necesitan** una herramienta que permita mejorar los procesos y tratamientos de agricultura, que a corto o largo plazo genere ganancias económicas durante cada producción.

2. **Esta necesidad se puede solventar** con una aplicación móvil que indica las condiciones en las que se encuentra su siembra. Asimismo, brindar recomendaciones para cada tipo de planta, métodos de cómo tratar enfermedades, regadíos y fumigación.

3. **Nuestros clientes serán** los agricultores de 18 a 80 años que desean conocer nuevos métodos para mejorar su producción agrícola, por medio de nuevas tecnologías.

4. **El valor #1 que un cliente desea sobre nuestro servicio** es que todos sus terrenos y tipo de plantas (siembra) puedan trabajarse en la aplicación mostrando los resultados correctos y satisfactorios

5. **Los beneficios a los que accede nuestros usuarios** es el acceso a una versión gratuita donde el máximo de terrenos que podrá registrar es de solo uno, pero el usuario puede limitar el área de este sin restricciones.

6. **Atraeremos a la mayoría de los clientes a través de** la diferencia entre nuestra competencia. Aparte de mostrar todos los datos de ubicación, clima, nivel de pH, nuestro producto mostrara una guía de plantas que tiene como objetivo orientar a los agricultores para conocer los pasos correctos de siembra y el tratamiento que debe tener para el terreno en donde este sembrando.

7. **Mi mayor riesgo de producto** son resultados erróneos que terminen provocando una mala recomendación de la siembra y llegue a empeorarla.

8. **Resolveremos esto a través de** los _feedback_ de usuarios para lanzar constantes actualizaciones que buscan corregir y mejorar el producto en busca de satisfacer las expectativas de los usuarios.

9. **Para usuarios con plan de registro,** todas las dudas y recomendaciones serán atendidas por un técnico agrícola, a su vez ingenieros ambientales, que utilizarán sus conocimientos profesionales para dar realce a una mejor producción agraria.

 
  - 1.2.2.3. Lean UX Hypothesis Statements.
  - 1.2.2.4. Lean UX Canvas.
  
  

### 1.3. Segmentos objetivo.

En nuestro proyecto se hacen presente dos segmentos objetivos:

- Agricultores: Son nuestro principal segmento objetivo
- Asesores: 

## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores.

Presentamos 3 competidores, los cuales son: 

| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Fila 1, C1 | Fila 1, C2 | Fila 1, C3 |
| Fila 2, C1 | Fila 2, C2 | Fila 2, C3 |

- 2.1.1. Análisis competitivo.
- 2.1.2. Estrategias y tácticas frente a competidores.

	- Liderazgo en costes:
	Contamos con la capacidad de producir y ofrecer nuestro producto de forma totalmente gratuita, sin añadir ninguna limitación a sus características principales. Igualmente, en lo que respecta a las suscripciones de pago, estamos en posición de ofrecer precios que son considerablemente más bajos que los de nuestros competidores, con la clara intención de hacer de nuestra aplicación una opción sumamente atractiva para los usuarios. Nuestra principal meta es satisfacer las necesidades de aquellos clientes que basan su elección en el factor precio.

	- Estrategia de diferenciación:
		Reconocemos que, para destacar de forma sobresaliente entre nuestros competidores, es imperativo que introduzcamos funcionalidades que no se encuentren disponibles en otras aplicaciones o que mejoremos sustancialmente las ya existentes. Una de las características más destacadas en nuestra aplicación que nos diferencia es nuestra completa guía de siembra, adaptada según el tipo de árbol frutal o vegetal que se esté cultivando. De esta manera, garantizamos que la calidad y producción sean óptimas. Además, proporcionamos una exhaustiva recopilación de información que permitirá a nuestros usuarios tomar decisiones informadas sobre cómo cultivar de manera adecuada sus plantas.

	- Estrategia de enfoque:
		Somos plenamente conscientes de que el auge de la tecnología y el aumento en el uso de computadoras y smartphones han dado lugar a una creciente demanda de servicios de gestión y asesoramiento agrícola. Por lo tanto, nos dirigimos exclusivamente a todas aquellas personas involucradas o interesadas en la agricultura que requieran un software que los asista en el cultivo adecuado de árboles frutales y vegetales.

	- Táctica de expansión:
		A pesar de que nuestra aplicación opera de manera gratuita, no planeamos saturarla con anuncios en cada acción que realicen los usuarios. Nuestra estrategia de expansión se fundamenta en la obtención de valoraciones positivas por parte de los usuarios y en la promoción efectiva de la aplicación.
### 2.2. Entrevistas.
 - 2.2.1. Diseño de entrevistas.
			
	Cuestionario para Entrevistas

	¡Saludos y buen día! Permítame introducirme y compartir un poco sobre mi proyecto. Soy [...], un estudiante de Ingeniería de 		Software.

		1. ¿Podría proporcionarme su nombre, por favor?
		2. ¿Cuantos años tiene?
		3. ¿Cual es su nacionalidad?
		4. ¿Donde vive?
		5. ¿Cuál es su ocupación actual?
		6. ¿Que carrera estudia/estudio?	
		7. Aprendizaje guiado o autodidacta		
		8. Banco preferido		
		9. ¿Cuales son sus redes sociales más utilizadas?
		10. ¿Windows, Linux o Mac?
		11. ¿Android o Apple?
		12. Menciona 2 otras apps (diferente a redes sociales, pueden ser juegos de celular también) que utilices frecuentemente		
		13. ¿Con cuales marcas se identifica usted mas?

		Si tuvieras que calificarte en donde 0 fuera inexperto y 10 experto
		¿Cómo te calificarías en el uso de los smartphones?
		¿Cómo te calificarías en el uso de computadoras?
		¿Cómo te calificarías en el uso de los navegadores de internet en
		smartphones?
		¿Cómo te calificarías en el uso de los navegadores de internet en
		computadora?
		¿Cómo te calificarías en el uso de las aplicaciones de escritorio?
		¿Cómo te calificarías en el uso de las aplicaciones móviles?
		¿Qué dispositivo utilizas? ¿Celular, Tablet o una computadora?
		¿Qué buscador conoces? ¿Google Chrome, Firefox, Internet Explorer?

***Preguntas para Segmento 1: Agricultores***
	
En relación al grupo de agricultores a los que apuntamos:
	
		a. ¿Dónde se ubica su área de cultivo?
		b. ¿Tiene conocimiento acerca del tipo de suelo en el que realiza sus siembras?
		c. ¿Cuánto tiempo dedica a sus actividades de cultivo o jardinería?
		d. ¿Cómo decide la distancia adecuada entre las plantas que siembra? ¿Conoce métodos para establecer la separación y profundidad ideales para el desarrollo de las plantas?
		e. ¿Cómo calificaría la calidad de su conexión a internet en el área donde cultiva?
		f. ¿Ha identificado cuándo es necesario utilizar fertilizantes o métodos de control de plagas para diferentes tipos de plantas?
		g. ¿Dispone de conocimiento sobre los fertilizantes, repelentes y pesticidas adecuados para cada tipo de planta?
		h. ¿Tiene en cuenta la necesidad de podar las plantas que cultiva? ¿Con qué frecuencia considera que es necesario realizar la poda?
		i. ¿Está al tanto de los climas propicios para cultivar un tipo específico de cultivo? ¿O encuentra dificultades en esta área?
		j. ¿Esta familiarizado con el uso de dispositivos que monitorean sus cultivos?
		k. ¿Cuenta con un espacio extenso, como un jardín, para sus cultivos, o se trata de áreas más limitadas, como macetas?
		l. ¿Estaria dispuesto a invertir en dispositivos IOT para mejorar la calidad de sus cultivos?
		m. ¿Considera que una aplicación móvil que le ayude a visualizar su área de cultivo podría ser beneficiosa en su actividad?
   
***Preguntas para Segmento 2: Especialistas***

Estas son algunas preguntas diseñadas para comprender mejor su perspectiva y experiencia en el ámbito de la agricultura. Agradecemos su tiempo y sus respuestas, ya que contribuirán al desarrollo de nuestro proyecto.
	
		a. ¿Cuál es su experiencia en el asesoramiento de proyectos de cultivo?
		b. ¿Cuáles son las principales áreas de especialización de su asesoría?	
		c. ¿Cómo evalúan las necesidades de los agricultores a los que asesoran?
		d. ¿Cuáles son las principales recomendaciones que suelen dar a los agricultores?
		e. ¿Cuáles son los principales retos a los que se enfrentan los agricultores en la actualidad?
		f. ¿Qué opinan de las tendencias actuales en el sector agrícola?
		g. ¿Qué consejos les daría a los agricultores que están pensando en iniciar un nuevo proyecto de cultivo?
		h. ¿Esta familiarizado con el uso de dispositivos IOT?
		i. ¿Considera que una aplicación móvil que le ayude a asesorar a multiples agricultores resultaria ser beneficiosa?
		j. ¿Estaria dispuesto a invertir en dispositivos IOT para realizar el asesoramiento?
					
- 2.2.2. Registro de entrevistas.

***Segmento 1: Agricultores***

Entrevista #1:
Enlace:
Descripcion:

***Segmento 2: Especialistas***

- 2.2.3. Análisis de entrevistas.

### 2.3. Needfinding.
- 2.3.1. User Personas.

***Segmento 1: Agricultores***

***Segmento 2: Especialistas***

- 2.3.2. User Task Matrix.

***Segmento 1: Agricultores***

***Segmento 2: Especialistas***

- 2.3.3. User Journey Mapping.

***Segmento 1: Agricultores***

***Segmento 2: Especialistas***
- 2.3.4. Empathy Mapping.

***Segmento 1: Agricultores***

***Segmento 2: Especialistas***

- 2.3.5. As-is Scenario Mapping.

***Segmento 1: Agricultores***

***Segmento 2: Especialistas***

## Capítulo III: Requirements Specification
- 3.1. To-Be Scenario Mapping.

***Segmento 1: Agricultores***

***Segmento 2: Especialistas***

- 3.2. User Stories.
- 3.3. Impact Mapping.
- 3.4. Product Backlog.

## Capítulo IV: Solution Software Design 
- 4.1. Strategic-Level Domain-Driven Design. 
	- 4.1.1. EventStorming. 
			Enlace de Miro para el desarrollo de Event Storming: https://miro.com/welcomeonboard/aHBvTVNKeFh6SGF4elVQYmtXM0FjTmkxcGYzOGN0VjdONVBOamljTkwxbmdUMmVZSFM3RGRUMFkzek5SSTJkd3wzMDc0NDU3MzQ4MzE3NTkyMDkwfDI=?share_link_id=426406113622		
			- 4.1.1.1 Candidate Context Discovery. 
		- 4.1.1.2 Domain Message Flows Modeling. 
		- 4.1.1.3 Bounded Context Canvases. 
https://miro.com/welcomeonboard/WHprVTI0dlZqQlRKa3JIOGVrRnZwb2RXcGRZWHlpcDQ3ejI2ZWx3T2IwWm9pNk04RzNrTnZFWEhiSURGUWIwZnwzNDU4NzY0NTIzMzUwNTAxMDQ1fDI=?share_link_id=579006095436
	- 4.1.2. Context Mapping. 
	- 4.1.3. Software Architecture. 
		- 4.1.3.1. Software Architecture System Landscape Diagram. 
		- 4.1.3.2. Software Architecture Context Level Diagrams. 
		- 4.1.3.2. Software Architecture Container Level Diagrams.
		- 4.1.3.3. Software Architecture Deployment Diagrams. 
- 4.2. Tactical-Level Domain-Driven Design 
	- 4.2.X. Bounded Context: 
		- 4.2.X.1. Domain Layer. 
		- 4.2.X.2. Interface Layer. 
		- 4.2.X.3. Application Layer. 
		- 4.2.X.4. Infrastructure Layer. 
		- 4.2.X.6. Bounded Context Software Architecture Component Level Diagrams. 
		- 4.2.X.7. Bounded Context Software Architecture Code Level Diagrams. 
			- 4.2.X.7.1. Bounded Context Domain Layer Class Diagrams. 
			- 4.2.X.7.2. Bounded Context Database Design Diagram.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMjAwMDgzOCwtMjEwODgzOTMyXX0=
-->