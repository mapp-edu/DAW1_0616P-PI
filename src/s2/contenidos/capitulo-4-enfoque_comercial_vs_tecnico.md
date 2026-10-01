# Adaptación del Mensaje: Enfoque Comercial vs. Técnico

Uno de los mayores desafíos a los que se enfrenta un profesional de la informática al presentar un proyecto es adecuar el registro, la profundidad y los argumentos al tipo de foro ante el que se expone. No requiere la misma estrategia defender un proyecto software ante un tribunal de evaluación o un equipo de arquitectura de sistemas, que presentarlo ante un cliente final, un director de negocio o un inversor.

## El Pitch Comercial: Orientación a Valor y Negocio

El objetivo del enfoque comercial no es explicar *cómo* está construido el software internamente, sino *por qué* es necesario, qué problema resuelve y cómo genera valor o sostenibilidad económica.

> ***A un perfil comercial o directivo no le importa la complejidad del código, sino el impacto positivo que la solución genera en el usuario y en la organización.***

### 1. Propuesta de valor, modelo de negocio y viabilidad

* **Propuesta de valor:** Es el núcleo del mensaje. Debe sintetizar de forma clara qué beneficio único ofrece la aplicación frente a las soluciones existentes.

* **Modelo de negocio:** Explica cómo el proyecto es o será sostenible. ¿Se trata de un modelo SaaS (*Software as a Service*) por suscripción, pago por uso, modelo freemium o desarrollo a medida bajo presupuesto?

* **Viabilidad económica y operativa:** Breve análisis que demuestre que el proyecto se puede llevar a cabo con los recursos, costes y plazos previstos, justificando el retorno de la inversión (ROI).

### 2. Análisis de la competencia y beneficio para el usuario final

* **Análisis de la competencia:** Identificar las alternativas existentes en el mercado y resaltar las diferencias clave (factor diferencial o *core innovation*).

* **Enfoque en el usuario final (*User-Centric*):** Demostrar un conocimiento profundo del perfil de usuario (*buyer persona*), argumentando cómo el diseño de la experiencia de usuario (UX/UI) facilita la adopción del software y mejora su productividad o satisfacción.

---

## La Defensa Técnica: Rigor, Arquitectura y Calidad

En el extremo opuesto, cuando el interlocutor es un tribunal académico, un equipo de *code review* o un *Chief Technology Officer* (CTO), el foco debe desplazarse por completo hacia las decisiones de diseño del sistema y la solvencia del desarrollo.

### 1. Stack tecnológico y arquitectura del sistema

* **Elección del Stack:** No basta con listar los lenguajes, *frameworks* o librerías utilizados (ej. Java, React, Docker). Es imprescindible **justificar el porqué de cada elección** en base a criterios como rendimiento, mantenibilidad, curva de aprendizaje, soporte comunitario o escalabilidad.

* **Arquitectura de software:** Explicación del patrón arquitectónico adoptado (microservicios, arquitectura limpia, MVC, *serverless*). Debe quedar claro cómo interactúan los componentes y cómo se garantiza desacoplamiento y escalabilidad.

### 2. Gestión de datos, seguridad, pruebas y metodologías

* **Diseño y gestión de la base de datos:** Justificación del modelo de datos (relacional vs. no relacional), normalización, rendimiento de consultas, indexación y políticas de respaldo.

* **Seguridad y privacidad:** Explicación de los mecanismos de autenticación y autorización (ej. OAuth2, JWT), cifrado de datos en tránsito y en reposo, y cumplimiento de normativas de protección de datos (RGPD).

* **Estrategia de pruebas (*Testing*):** Cobertura de pruebas unitarias, de integración y *end-to-end* (E2E), demostrando el compromiso con la calidad del software.

* **Metodologías ágiles y ciclo de vida:** Exposición de cómo se ha gestionado el proyecto (Scrum, Kanban), el control de versiones (flujo de Git) y las canalizaciones de integración y despliegue continuos (CI/CD).

---

## Matriz Comparativa de los Dos Enfoques

A modo de resumen, la siguiente tabla refleja la transposición de conceptos entre ambos tipos de discurso:

| Aspecto a comunicar | Enfoque Comercial / Negocio | Enfoque Técnico / Arquitectura |
| :--- | :--- | :--- |
| **Público objetivo** | Clientes, Inversores, Directores | Tribunales, Arquitectos, Desarrolladores |
| **Objetivo clave** | Demostrar valor, ROI y usabilidad | Probar solvencia, calidad y escalabilidad |
| **Pregunta principal** | ¿Qué problema resuelve y cuánto cuesta? | ¿Cómo está construido y por qué así? |
| **Concepto de "Seguridad"** | Confianza para el usuario y cumplimiento legal | Cifrado, JWT, RBAC y prevención de OWASP |
| **Concepto de "Rendimiento"** | Rapidez de carga e higiénica UX | Latencia, optimización de queries y *throughput* |