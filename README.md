### Actividad en clase: "SMART Debugging: Optimizando Requerimientos" (30 min)

**Matriculas y nombres**: A01567335 Francisco Javier Huerta Trujillo A01564170 Abraham Cuahtemoc Olivas Meza

**Objetivo:** Que l@s estudiantes identifiquen fallas en la redacción de requerimientos de software y sea capaz de transformarlos en declaraciones específicas, medibles, alcanzables, relevantes y temporales.

#### 1. Introducción y Repaso Crítico (2 minutos)

Repasa los conceptos de la presentación de tu profesor sobre los 5 pilares SMART aplicados a la computación:

* **Específico:** Evitar términos como "muchos" o "varios" y usar terminología consistente.

* **Medible:** Definir exactamente cuándo se considera "cumplido" (ej. mediante una prueba exitosa).

* **Alcanzable:** Validar la factibilidad técnica y económica (ej. no pedir un 100% de disponibilidad, que es técnicamente irreal).

* **Relevante:** Asegurar que la función abone al objetivo general del sistema y no desperdicie recursos.

* **Limitado en el Tiempo/Rastreable:** Definir plazos y asegurar que el requisito se pueda seguir desde el diseño hasta la implementación.

#### 2. Taller de "Refactorización" de Requerimientos (20 minutos)

Cada equipo recibe una lista de 10 requerimientos "malos" (vagos o imposibles) que deben transformar en requerimientos SMART.

| # | Requerimiento "Defectuoso" | Desafío SMART (Edita esta columna para poner el requerimiento refactorizado). |
| :--- | :--- | :--- |
| **1** | "El sistema debe ser capaz de manejar a **muchos** usuarios al mismo tiempo." | **Específico:** Sustituir "muchos" por una cifra de usuarios concurrentes. **Requerimiento refactorizado**: El Sistema debe tener la capacidad de manejar 200 usuarios de forma continua.| 
| **2** | "La interfaz debe ser amigable e intuitiva para **varios** tipos de personas." | **Medible:** Definir una métrica objetiva de éxito o prueba de usuario. **Requerimiento refactorizado**: La interfaz debe de contar con letra legible, un tono amigable para los daltónicos. Además de esto debe pasar las pruebas de usuario con mínimo una persona de cada grupo de edades (Adolescente, Adulto y Mayor de Edad).| 
| **3** | "El software se terminará lo más pronto posible para cumplir con el cliente." | **Limitado en el tiempo:** Definir un plazo o fecha límite específica. **Requerimiento refactorizado**: El software se llevará a cabo en un total de 8 semanas con un total de 4 sprints de 2 semanas cada uno.| 
| **4** | "La base de datos deberá guardar el historial de ventas, clientes, **etcétera**." | **Específico:** Listar todos los elementos; evitar el uso de "etcétera". **Requerimiento refactorizado**: La base de datos deberá guardar el historial de ventas, clientes, historial de humedad.| 
| **5** | "El sistema debe funcionar con un 100% de disponibilidad sin errores." | **Alcanzable:** Ajustar a un nivel de disponibilidad técnicamente factible. **Requerimiento refactorizado**: El Sistema debe tener la capacidad de funcionar un 75% del tiempo, además de esto debe ser capaz de solucionar errores específicos para indicar al usuario las problemáticas.| 
| **6** | "Se requiere que el sistema envíe **algunos** correos de notificación al administrador." | **Específico:** Definir los eventos exactos que disparan la notificación. **Requerimiento refactorizado**: Al llegar a condiciones críticas para el cultivo como falta de agua, enviar un email al administrador para que este pueda actuar. | 
| **7** | "El módulo de contabilidad debe estar listo para usarse algún día." | **Limitado en el tiempo:** Establecer una fecha para priorizar y programar la tarea. **Requerimiento refactorizado**: El Módulo de contabilidad se debe llevar a cabo en la última parte del cuarto sprint del proyecto.| 
| **8** | "La aplicación debe ser rápida, cargando los reportes en un instante." | **Medible:** Definir el tiempo de carga en segundos o milisegundos. **Requerimiento refactorizado**: La aplicación debe ser capaz de cargar en un tiempo de 150-300 milisegundos.| 
| **9** | "El sistema debe incluir un juego de naves para que los empleados se distraigan." | **Relevante:** Evaluar si contribuye a los objetivos generales del proyecto. **Requerimiento refactorizado**: No es un requisito funcional. En vez de esa solución enfocarse en la escalabilidad y responsabilidad del software (Tablets, Celulares y Computadoras).| 
| **10** | "El software debe ser escalable de forma automática y global." | **Rastreable/Alcanzable:** Asegurar que sea factible económica y operativamente.  **Requerimiento refactorizado**: El software debe de tener documentación adecuada que permita que se pueda escalar en un futuro de ser necesario.
| 
##### Instrucciones para los estudiantes:

1. **Identificar el error:** Localizar qué letra de las siglas **S.M.A.R.T.** se está violando.

2. **Refactorizar:** Redactar de nuevo el requerimiento usando terminología consistente y criterios cuantificables. Modifica este archivo README, para indicar el nuevo requerimiento.

3. **Validar:** Utilizar a un compañero como "revisor" para confirmar que la nueva redacción no tiene ambigüedades.

#### 3. Co-evaluación: "Equipo Revisor" (8 minutos)

Siguiendo la recomendación de usar un "revisor" para validar la claridad, los equipos intercambian sus requerimientos redactados. El equipo receptor debe intentar encontrar una ambigüedad o una falta de métrica en el trabajo de sus compañeros.
