![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

# Universidad Peruana de Ciencias Aplicadas

**Facultad de Ingeniería**

**Carrera de Ingeniería de Software**

**Ciclo:** 2026-01 | **Sección:**

**Código del curso:** 1ASI0729

**Nombre del curso:** Desarrollo de Aplicaciones Open Source

**NRC:** 11881

**Profesor:** Ing. Bautista Ubillús Efraín Ricardo

## Informe de Trabajo Final

**Startup:** GreenSpot

**Producto:** KAMPO

### Relación de Integrantes

U202517474 | Hurtado Balcazar, Rommel Daniel.
U202018427 | Ramos Fuentes Rivera, Adriana Nicole.
U20251I477 | Tuesta Girón, Kiara Lucia.
U202311469 | Arroyo Gonzales, Emily Juliette.
[Codigo de Alumno] | [Apellidos, Nombres].

**Marzo, 2026**

### Registro de Versiones del Informe

---

|Versión| Fecha        |Autor|Descripción de Modificación|
|---|--------------|---|---|
|1.0.0| 12 Abr. 2026 |Rommel H.| Creación del documento Markdown|

### Project Report Collaboration Insights

---

# Tabla de Contenidos


- [Student Outcome](#student-outcome)

## [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
- [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)

## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. User Stories](#31-user-stories)
- [3.2. Impact Mapping](#32-impact-mapping)
- [3.3. Product Backlog](#33-product-backlog)

## [Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)

## [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.X. Sprint n](#52x-sprint-n)
        - [5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)
        - [5.2.X.2. Aspect Leaders and Collaborators](#52x2-aspect-leaders-and-collaborators)
        - [5.2.X.3. Sprint Backlog n](#52x3-sprint-backlog-n)
        - [5.2.X.4. Development Evidence for Sprint Review](#52x4-development-evidence-for-sprint-review)
        - [5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
        - [5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
        - [5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
        - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
- [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](#54-video-about-the-product)

## [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

## [Bibliografía](#bibliografía)

## [Anexos](#anexos)

---
### Student Outcome
---

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

|Criterio Específico|Acciones Realizadas|Conclusiones|
|---|---|---|
|**Comunica oralmente con efectividad a diferentes rangos de audiencia.**|---|---|
|**Comunica por escrito con efectividad a diferentes rangos de audiencia**|---|---|

---

### Capítulo I: Introducción
#### 1.1. Startup Profile
##### 1.1.1. Descripción de la Startup

**GreenSopt** es una starup de tecnología agrícola fundado por estudiantes universitarios peruanos, con la misión de digitalizar la gestión del campo para pequeños y medianos agricultores del Perú. Nuestro producto principal, **KAMPO**, es una plataforma SaaS que combina el monitoreo de cultivos y control de rentabilidad en una sola herramienta accesible y diseñada para el contexto local.
La mayoría de agricultores peruanos apun gestionan sus cultivos y finanzas de forma manual, sin acceso a herramientas digitales especializadas. KAMPO busca cerrar esa brecha ofreciendo tres planes adaptados a distintos niveles de adopción tecnología:
**Semilla** ( gestión básica ), **Cosecha** ( integración IoT y reportes ) y **Hacienda** ( Inteligencia Artificial y gestión multi-parcela ).

##### 1.1.2. Perfiles de integrantes del equipo

<!-- Remplaza con tu foto: ![Foto](ruta/a/tu/foto.jpg) -->

#### 1.2. Solution Profile
##### 1.2.1. Antecedentes y problemática

###### Antecedentes
La agricultura peruana representa el 4.6% del PBI nacional y es uno de los pilares históricos de la economía del país (BCRP, 2024). En la última década, las exportaciones agrícolas crecieron de US$4,400 millones en 2013 a US$10,500 millones en 2023, evidenciando el enorme potencial del sector (MIDAGRI, 2024). Sin embargo, este crecimiento ha sido desigual: mientras las grandes empresas agroexportadoras adoptan tecnología de precisión, sensores y análisis de datos, el agricultor pequeño y mediano sigue gestionando su campo y sus finanzas de forma manual, con cuadernos o herramientas genéricas como hojas de cálculo.

Según el MIDAGRI, el 85% de los agricultores peruanos trabaja en parcelas de menos de 10 hectáreas, predominando unidades productivas de entre 3 y 10 ha. Este segmento mayoritario enfrenta una profunda brecha tecnológica: según la Encuesta Nacional Agropecuaria del INEI (2022), solo el 7% de los pequeños y medianos productores utiliza sistemas de riego tecnificado, frente al 53% entre los grandes productores. A nivel nacional, apenas el 20% de la superficie agrícola cuenta con riego tecnificado (Business Empresarial, 2024).

La transformación digital del agro es reconocida como una necesidad urgente. La CEPAL señala que para que la agricultura digital sea una realidad en América Latina se requiere conectividad, acceso a tecnología a costos accesibles y alfabetización digital. Aun así, el acceso, la capacitación y la conectividad digital siguen siendo retos clave para la adopción masiva por parte de pequeños y medianos productores (ADAMA, 2025).

---

###### Problematica

**¿Quién?** Pequeños y medianos agricultores peruanos, que representan el 85% del total de productores del país, con parcelas de entre 3 y 50 hectáreas. Se ubican en las tres regiones naturales del Perú: costa, sierra y selva, y gestionan cultivos de consumo interno y exportación. En la sierra, el 63.6% son pequeños productores que trabajan con tierras de menor extensión (EY, 2025).

**¿Qué?** Los agricultores no cuentan con herramientas digitales accesibles para gestionar dos aspectos fundamentales de su actividad: el monitoreo de sus cultivos (condiciones del suelo, riego, etapas del ciclo productivo) y el control de su rentabilidad (costos, ingresos, análisis por cultivo). Esta doble carencia les impide tomar decisiones informadas tanto sobre el campo como sobre su negocio, generando pérdidas evitables por mala gestión del riego, uso ineficiente de insumos y desconocimiento real de si su actividad es o no rentable.

**¿Dónde?** En todo el territorio peruano, con especial impacto en zonas rurales con limitado acceso a servicios de asesoría técnica y financiera. La costa, responsable del 68% de la producción agrícola nacional, dispone de menos del 2% del agua total del país (BCRP, 2024), lo que hace crítica la gestión inteligente del riego. La sierra, con mayor concentración de pequeños agricultores, enfrenta además barreras de conectividad y baja adopción tecnológica.

**¿Cuándo?** El problema es estructural y viene agravándose en los últimos años por el impacto del cambio climático (lluvias erráticas, retroceso glaciar), el alza de costos de insumos agrícolas y la creciente exigencia de los mercados. La urgencia se intensifica en cada campaña agrícola, cuando el agricultor debe tomar decisiones críticas de inversión sin datos confiables.

**¿Por qué?** Las soluciones tecnológicas existentes en el mercado están diseñadas para grandes empresas agroindustriales, con precios y complejidad fuera del alcance del agricultor promedio. No existe una plataforma integral, accesible y en español que combine monitoreo de cultivos con gestión de rentabilidad, adaptada a la realidad del pequeño y mediano productor peruano. La brecha tecnológica entre el gran agroexportador y el agricultor familiar sigue siendo una barrera estructural no resuelta.

**¿Cómo?** La problemática se manifiesta de forma concreta en tres patrones recurrentes:
- El agricultor riega por intuición o experiencia, sin datos de humedad del suelo, generando desperdicio hídrico o estrés hídrico en el cultivo. Hasta el 45% del agua se pierde por canales en mal estado o mala gestión (ANA, 2023). 
- El agricultor no lleva un registro ordenado de sus costos e ingresos por campaña, por lo que no puede determinar con precisión si su cultivo fue rentable ni en qué rubros puede optimizar. 
- Al no tener alertas ni seguimiento del ciclo del cultivo, reacciona tarde ante plagas, enfermedades o condiciones climáticas adversas, incrementando pérdidas evitables.

**¿Cuánto?** La brecha en infraestructura agrícola en el Perú es de US$37,000 millones según el Banco Mundial (EY, 2025). El mercado global de agricultura inteligente pasará de US$12,400 millones en 2020 a US$34,100 millones en 2026 (CEPLAN). En Perú, solo el 7% de los pequeños y medianos productores usa tecnología de riego avanzada, lo que representa una oportunidad de mercado masiva aún sin atender con soluciones digitales accesibles y localizadas.

---

El pequeño y mediano agricultor peruano opera con información insuficiente, toma decisiones por experiencia empírica y no dispone de herramientas que le permitan monitorear su cultivo y conocer la rentabilidad real de su negocio. KAMPO surge como respuesta directa a esta doble necesidad: una plataforma SaaS integral, accesible y diseñada para el contexto peruano, que traduce datos en decisiones y convierte el campo en un negocio gestionable.

##### 1.2.2. Lean UX Process
###### 1.2.2.1. Lean UX Problem Statements
###### 1.2.2.2. Lean UX Assumptions
###### 1.2.2.3. Lean UX Hypothesis Statements
###### 1.2.2.4. Lean UX Canvas
#### 1.3. Segmentos objetivo

---

## Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
##### 2.1.1. Análisis competitivo
##### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
##### 2.2.1. Diseño de entrevistas
##### 2.2.2. Registro de entrevistas
##### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
##### 2.3.1. User Personas
##### 2.3.2. User Task Matrix
##### 2.3.3. User Journey Mapping
##### 2.3.4. Empathy Mapping
## 2.4. Big Picture Event Storming
## 2.5. Ubiquitous Language

---

## Capítulo III: Requirements Specification
## 3.1. User Stories
## 3.2. Impact Mapping
## 3.3. Product Backlog

---

## Capítulo IV: Product Design
## 4.1. Style Guidelines](#41-style-guidelines)
##### 4.1.1. General Style Guidelines
##### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
##### 4.2.1. Organization Systems
##### 4.2.2. Labeling Systems
##### 4.2.3. SEO Tags and Meta Tags
##### 4.2.4. Searching Systems
##### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
##### 4.3.1. Landing Page Wireframe
##### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
##### 4.4.1. Web Applications Wireframes
##### 4.4.2. Web Applications Wireflow Diagrams
##### 4.4.3. Web Applications Mock-ups
##### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
##### 4.6.1. Design-Level Event Storming
##### 4.6.2. Software Architecture Context Diagram
##### 4.6.3. Software Architecture Container Diagrams
##### 4.6.4. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
##### 4.7.1. Class Diagrams
## 4.8. Database Design
##### 4.8.1. Database Diagrams

---

## Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
##### 5.1.1. Software Development Environment Configuration
##### 5.1.2. Source Code Management
##### 5.1.3. Source Code Style Guide & Conventions
##### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
##### 5.2.X. Sprint n
###### 5.2.X.1. Sprint Planning n
###### 5.2.X.2. Aspect Leaders and Collaborators
###### 5.2.X.3. Sprint Backlog n
###### 5.2.X.4. Development Evidence for Sprint Review
###### 5.2.X.5. Execution Evidence for Sprint Review
###### 5.2.X.6. Services Documentation Evidence for Sprint Review
###### 5.2.X.7. Software Deployment Evidence for Sprint Review
###### 5.2.X.8. Team Collaboration Insights during Sprint
## 5.3. Validation Interviews
##### 5.3.1. Diseño de Entrevistas
##### 5.3.2. Registro de Entrevistas
##### 5.3.3. Evaluaciones según heurísticas
## 5.4. Video About-the-Product

## Conclusiones
#### Conclusiones y recomendaciones
#### Video About-the-Team

## Bibliografía

## Anexos


