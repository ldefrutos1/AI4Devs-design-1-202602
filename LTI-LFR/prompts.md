# prompts.md

## Prompt 1
Estoy lanzando una startup al mercado y quiero diseñar un Applicant Tracking System ATS que brille
por encima de mis competidores:

El sistema debe contemplar las fases del proceso incluidas la imagen adjunta. Como puntos importantes a cumplir por el sistema, he identificado los siguientes requisitos; además de estos propón los puntos que consideres que añaden un valor diferencial: 
- Aumentar la eficiencia para los departamentos de HR 
- Mejorar la colaboración en tiempo real entre reclutadores y managers 
- Automatizaciones 
- Asistencia de IA en diversas tareas 

Con la información anterior actúa como Product Manager experto para generar la siguiente documentación:
✅ Descripción breve del software LTI, valor añadido y ventajas competitivas.
✅ Explicación de las funciones principales.
✅ Añadir un diagrama Lean Canvas para entender el modelo de negocio.

La tecnología en la que desarrollar el proyecto está abierta, pero dado que mi equipo tiene experiencia en Vue y Microservicios con Srping Boot hemos pensado en usar esta tecnología para implmentar el sistema.

Si tienes alguna duda, pregúntame antes de empezar a generar la documentación.

---

## Prompt 2
Prepárame un documento formal y muy profesional con estilo PRD, luego te pediré otro orientado a inversores y presentación comercial

---

## Prompt 3
Genérame también un documento con toda esta información en formato markdown; cuida de que el resultado final sea atractivo y muy profesional

---

## Prompt 4
Crea una infografía profesional, elegante y moderna que represente un Applicant Tracking System (ATS) enfocado en la eficiencia del reclutamiento. El diseño debe transmitir rapidez, organización, automatización, control del proceso y optimización del tiempo en la selección de talento. Utiliza un estilo corporativo premium, minimalista y tecnológico, con una apariencia limpia, ejecutiva y visualmente atractiva para una presentación empresarial de Recursos Humanos o Talent Acquisition.

La composición debe ser horizontal, tipo timeline o diagrama de flujo, con las etapas conectadas de forma clara y ordenada mediante flechas, líneas o nodos. Incluir iconos profesionales y minimalistas para cada fase, con jerarquía visual clara, buena legibilidad y una estructura que facilite la comprensión inmediata del proceso completo de reclutamiento.

Representar estas 7 fases del Applicant Tracking System de forma secuencial:

1. Creación de vacantes
2. Publicación en portales, web corporativa y redes
3. Recepción de candidaturas
4. Revisión de solicitudes
5. Pruebas online
6. Planificación de entrevistas
7. Selección y contratación

El diseño debe destacar visualmente que el ATS mejora la eficiencia operativa del reclutamiento, reduce tiempos de gestión, agiliza la evaluación de candidatos y aporta orden al proceso de contratación. Incluir elementos visuales que refuercen la idea de automatización, flujo continuo y productividad.

Usar un fondo sobrio y profesional, una estética tecnológica de alto nivel y una composición equilibrada, sofisticada y fácil de presentar ante directivos o equipos de RR. HH. El resultado debe parecer una infografía ejecutiva de transformación digital aplicada al reclutamiento.

Título sugerido: ATS Recruitment Workflow
Subtítulo sugerido: Proceso eficiente de selección de talento

---

## Prompt 5
utiliza esta imagen en para generar un documento orientado a inversores y presentación comercial. Por ahora me sirve con que el documento esté en markdown con un diseño profesional y acorde a las características de la imagen

---

## Prompt 6
Genérame la imagen del diagrama Lean Canvas; el estilo e infografía debe ser coherente con el empleado en infografía ATS y la información la misma que se ha incluido en los documentos ya generados

---

## Prompt 7
Actúa como un experto analista de negocio con experiencia de 10 años en la definición de casos de uso y amplios conocimientos en el ámbito de RRHH y en selección de candidatos y genera el modelo de casos de uso del sistema. El modelo resultante debe ser completo pero entendible a simple vista por lo que una opción es modelar dos niveles. El primer nivel sería el sistema completo con casos de uso generales. El segundo nivel se centraría en cada fase modelando los casos de uso de dicha fase. El sistema debe ser coherente por lo que al modelar el nivel 2 se deben respetar las nomenclaturas establecidas en el nivel 1 

---

## Prompt 8
genérame el modelo en sintaxis PlantUML para poder representarlo como un UML estandar. Quiero que me permitas descargar los ficheros asociados a cada diagrama por separado

---

## Prompt 9
Genérame un documento markdown con la información del Modelo de Casos de Uso que has generado. El documento va a ser el canónico que tenga los casos de uso del sistema por lo que dale una redacción formal y profesional acorde a un entregable del proyecto. Los diagramas de mermaid inclúyelos en un Anexo al final del documento no en el punto correspondiente.

---

## Prompt 10
Actúa como un experto arquitecto de datos con 10 años de experiencia en el modelado de bases de datos relacionales y genérame el modelo de datos de datos de la aplicación. Como aslida quiero un documento en markdown que será un entregable del proyecto y el documento canónico del Modelo de Datos. Genérame también el diagrama correspondiente de entidad-relación

---

## Prompt 11
si, genera la versión PlantUML del E/R

---

## Prompt 12
revisa el diagrama, cunado lo intento importar en una herramienta de visionado da error de sintaxis y no especifica el tipo de diagrama UML que es

---

## Prompt 13
dame una versión class diagram

---

## Prompt 14
Vamos con el diseño del sistema, actúa como un arquitecto experto y genera el documento con el diseño de alto nivel del sistema coherente con el análisis que hemos realizado y con el PRD creado. Antes de proceder pregúntame todas las dudas que tengas.

---

## Prompt 15
1.- Empezamos con single-tenant
2.- Arquitectura 100% microservicios desde el principio
3.- El proveedor de cloud será AWS
4.- Como BD usaremos PostgreSQL
5.- Contempla desde el uso de Elasticsearch/OpenSearch en los casos de uso oportunos
6.- Si la colaboración en tiempo real es un requisito de MVP real
7.- Para la integración con IA debe incluirse desde la primera version
8.- En la primera versión son obligatorias la integración con correo, calendarios y linkdIn 
9.- No necesito requisitos explícitos de seguridad en el documento 
10.- workflows configurables por cliente desde el inicio 
11.- No es necesario incluir decisiones de observabilidad y operación pero si tener en cuenta que el diseño debe permitir su implementación en producción siguiendo las buenas practicas del mercado
12.- Debe incluir un diagrama C4 completo. Para el nivel de código del digrama C4 usa el caso de uso UC 01 Gestionar vacantes 
13.- No hay restricciones corporativas, pero si se desea usar API Gateway, IAM,
14.- Una visión target completa

---

## Prompt 16
genérame el documento con los diagramas C4 en formato mermaid

---

## Prompt 17
Quiero un diagrama de la arquitectura que incluya todas las capas del sistema hasta el nivel de microservicio. Al estar desplegado a AWS quiero que se muestre el CDN, el front, el Gateway, etc además de los microservicios y sus respectivas bases de datos. Utiliza para generar este diagrama la librería Diagrams Python

---

## Prompt 18
quiero que me generes un documento prompts.md con todos los prompt que he usado en esta conversacion, incluye solo mi parte de la conversación no tus respuestas
