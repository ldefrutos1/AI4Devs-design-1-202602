# LTI ATS — Índice de documentación

> **LTI ATS** es una plataforma SaaS de Applicant Tracking System diseñada para optimizar de extremo a extremo el proceso de captación y selección de talento. Combina automatización de flujos de trabajo, colaboración en tiempo real y asistencia de IA para ayudar a las organizaciones a contratar mejor, más rápido y con mayor trazabilidad.

---

## Documentos del proyecto

### 1. Presentación comercial e inversora
**[`LTI_ATS_Investor_Commercial_Presentation.md`](docs/LTI_ATS_Investor_Commercial_Presentation.md)**

Presentación ejecutiva del producto orientada a inversores y audiencia comercial. Incluye propuesta de valor, modelo de negocio, ventajas competitivas, segmentación de mercado y hoja de ruta del producto.

> Audiencia recomendada: dirección, inversores, comercial, stakeholders de negocio.

---

### 2. Product Requirements Document (PRD)
**[`LTI_ATS_PRD.md`](docs/LTI_ATS_PRD.md)**

Documento de requisitos de producto que define el alcance funcional del sistema, sus capacidades estratégicas, los requisitos funcionales y no funcionales, las integraciones previstas y los criterios de aceptación. Referencia central para product management y desarrollo.

> Audiencia recomendada: product management, tecnología, UX, arquitectura, operaciones.

---

### 3. Modelo de Casos de Uso
**[`LTI_ATS_Modelo_Casos_de_Uso_Canonico.md`](docs/LTI_ATS_Modelo_Casos_de_Uso_Canonico.md)**

Especificación funcional canónica del sistema. Describe los actores del sistema, los casos de uso de alto nivel y su desglose detallado por fase del proceso de selección, así como las relaciones funcionales entre capacidades. Sirve de base para historias de usuario, diseño técnico y pruebas.

> Audiencia recomendada: negocio, análisis funcional, arquitectura, UX, desarrollo, QA.

---

### 4. Modelo de Datos
**[`LTI_ATS_Modelo_Datos_Canonico.md`](docs/LTI_ATS_Modelo_Datos_Canonico.md)**

Especificación del modelo de datos relacional del sistema. Define las entidades del dominio, sus atributos, las relaciones y reglas de cardinalidad, los criterios de normalización y las decisiones de diseño de persistencia. Incluye el diagrama entidad-relación en PlantUML ([`docs/uml/LTI_ATS_Modelo_Datos_ER_PlantUML.puml`](docs/uml/LTI_ATS_Modelo_Datos_ER_PlantUML.puml)).

> Audiencia recomendada: arquitectura, desarrollo, QA, DevOps, seguridad.

---

### 5. Diseño de Alto Nivel del Sistema
**[`LTI_ATS_Diseno_Alto_Nivel_Sistema_Mermaid.md`](docs/LTI_ATS_Diseno_Alto_Nivel_Sistema_Mermaid.md)**

Documento de arquitectura de solución que define el diseño de alto nivel del sistema mediante diagramas C4 en formato Mermaid. Cubre la descomposición lógica en microservicios, la interacción entre frontend, backend e integraciones externas, la estrategia de persistencia y búsqueda, y las capacidades de colaboración en tiempo real e IA.

> Audiencia recomendada: arquitectura, product management, desarrollo, QA, DevOps.

---

## Orden de lectura sugerido

| # | Documento | Propósito |
|---|-----------|-----------|
| 1 | [Presentación comercial](docs/LTI_ATS_Investor_Commercial_Presentation.md) | Entender el producto y su propuesta de valor |
| 2 | [PRD](docs//LTI_ATS_PRD.md) | Profundizar en los requisitos y el alcance del producto |
| 3 | [Casos de Uso](docs//LTI_ATS_Modelo_Casos_de_Uso_Canonico.md) | Comprender el comportamiento funcional del sistema |
| 4 | [Modelo de Datos](docs//LTI_ATS_Modelo_Datos_Canonico.md) | Conocer la estructura de datos que soporta el dominio |
| 5 | [Diseño de Alto Nivel](docs//LTI_ATS_Diseno_Alto_Nivel_Sistema_Mermaid.md) | Explorar la arquitectura técnica de la solución |

---

## Prompts de generación

Los prompts utilizados para generar esta documentación con asistencia de IA están registrados en [`LTI-LFR/prompts.md`](prompts.md).
