  ![Universidad Aplicada de Ciencias Aplicadas](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Carrera: 
Ingeniería de Software

Nombre del curso: 
Desarrollo de  Soluciones IOT

Sección: 
SW71

Nombre del profesor: 
Angel Augusto Velasquez Nunez

"Informe de Trabajo Final"
 
Nombre del startup: 
DevIOT

Nombre del producto: 
AgriPure

Relación de integrantes:

 - Diego Talledo Sanchez
 - Bruno Moisés Palomino Santa Cruz 
 - Andres Christian Reynoso 
 - Frank Yamil Alva Cordova
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
|  |  |  |  |
|  |  |  |  |

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

- 1.2.2 Lean UX Process.
  - 1.2.2.1. Lean UX Problem Statements.
  
  **Problem Statement 1:**
  En nuestro contexto, se hace necesario el acceso a datos relacionados con la siembra, las condiciones climáticas y el tipo de terreno en el que se pretende llevar a cabo la actividad agrícola. Gracias a la información proporcionada por el usuario, es posible mostrar las condiciones a las que están expuestas sus cosechas y, además, suministrar las indicaciones esenciales para llevar a cabo los procesos de cultivo adecuados para cada especie de planta.

	Hemos encontrado un factor crítico que tiene un impacto significativo en los resultados finales generados por el sistema. Este factor radica en la introducción de datos inexactos o que no se ajustan a los valores correctos relativos al terreno, el clima y la siembra.

	¿Cómo podemos garantizar que el sistema pueda operar con información más precisa para ofrecer resultados favorables al agricultor?  

  **Problem Statement 2:**
  En nuestro contexto, se hace presente el desarrollo de 

  - 1.2.2.2. Lean UX Assumptions.
  - 1.2.2.3. Lean UX Hypothesis Statements.
  - 1.2.2.4. Lean UX Canvas.

### 1.3. Segmentos objetivo.

## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores.

- 2.1.1. Análisis competitivo.
- 2.1.2. Estrategias y tácticas frente a competidores.

### 2.2. Entrevistas.
 - 2.2.1. Diseño de entrevistas.
			
	Cuestionario para Entrevistas

	¡Saludos y buen día! Permítame introducirme y compartir un poco sobre mi proyecto. Soy [...], un estudiante de Ingeniería de 		Software.

		1. ¿Podría proporcionarme su nombre, por favor?
		2. ¿Cuantos anios tiene?
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
		d. ¿Estaria dispuesto a invertir en dispositivos IOT para mejorar la calidad de sus cultivos?
		e. ¿Cómo decide la distancia adecuada entre las plantas que siembra? ¿Conoce métodos para establecer la separación y profundidad ideales para el desarrollo de las plantas?
		f. ¿Cómo calificaría la calidad de su conexión a internet en el área donde cultiva?
		g. ¿Ha identificado cuándo es necesario utilizar fertilizantes o métodos de control de plagas para diferentes tipos de plantas?
		h. ¿Dispone de conocimiento sobre los fertilizantes, repelentes y pesticidas adecuados para cada tipo de planta?
		i. ¿Tiene en cuenta la necesidad de podar las plantas que cultiva? ¿Con qué frecuencia considera que es necesario realizar la poda?
		j. ¿Está al tanto de los climas propicios para cultivar un tipo específico de cultivo? ¿O encuentra dificultades en esta área?
		k. ¿Esta familiarizado con el uso de dispositivos que monitorean sus cultivos?
		l. ¿Cuenta con un espacio extenso, como un jardín, para sus cultivos, o se trata de áreas más limitadas, como macetas?
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

- 2.2.3. Análisis de entrevistas.

### 2.3. Needfinding.
- 2.3.1. User Personas.
- 2.3.2. User Task Matrix.
- 2.3.3. User Journey Mapping.
- 2.3.4. Empathy Mapping.
- 2.3.5. As-is Scenario Mapping.

## Capítulo III: Requirements Specification
- 3.1. To-Be Scenario Mapping.
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

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The Gamma function satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about *LaTeX* mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?


And this will produce a flow chart:

mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTUxNjUzODExMiwtOTYzODk3NDRdfQ==
-->