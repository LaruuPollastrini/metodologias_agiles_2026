# Ejercicio Nro: 18

## Enunciado
### Contexto del Caso
Una empresa de desarrollo de software ha decidido adoptar la metodología Scrum para mejorar la eficiencia y calidad de sus proyectos. Tu equipo ha sido seleccionado para liderar la implementación de Scrum en un nuevo proyecto de desarrollo de una aplicación web para una empresa de logística.

---

### Instrucciones:
1. **Construye una serie de prompts** que simulen las diferentes etapas y actividades de Scrum en este proyecto.
2. **Cada prompt debe tener una entrada** que corresponda a la salida de otro prompt, formando una secuencia lógica de ejecución.
3. **Los prompts a desarrollar son:**
   * **a. Prompt 1: Definición del Product Backlog**
     * **Entrada:** Requerimientos iniciales del proyecto proporcionados por el cliente.
     * **Salida:** Product Backlog inicial con las historias de usuario prioritarias.
   * **b. Prompt 2: Planificación del Sprint**
     * **Entrada:** Product Backlog.
     * **Salida:** Plan del Sprint con las tareas a realizar y los responsables.
   * **c. Prompt 3: Ejecución del Sprint**
     * **Entrada:** Plan del Sprint.
     * **Salida:** Incremento de software funcional.
   * **d. Prompt 4: Revisión del Sprint**
     * **Entrada:** Incremento de software funcional.
     * **Salida:** Retroalimentación del cliente y lecciones aprendidas.
   * **e. Prompt 5: Retrospectiva del Sprint**
     * **Entrada:** Retroalimentación del cliente y lecciones aprendidas.
     * **Salida:** Plan de mejora para el siguiente Sprint.

4. **Cada prompt debe:**
   * Describir claramente la actividad Scrum a simular.
   * Explicar la entrada y salida requeridas.
   * Solicitar a los alumnos que generen o completen la información de cada etapa.

---

### Guía de Estructura de los Prompts

#### 1. Prompt 1: Definición del Product Backlog
* **Entrada:** El cliente ha proporcionado los siguientes requerimientos iniciales para una aplicación web de gestión de envíos logísticos:
  * Registro y autenticación de usuarios.
  * Creación y seguimiento de envíos.
  * Generación de reportes de estado de envíos.
  * Integración con sistemas de terceros para rastreo de envíos.
* **Salida:** Product Backlog inicial con las siguientes historias de usuario prioritarias:
  1. Como usuario, puedo registrarme e iniciar sesión en la aplicación.
  2. Como usuario, puedo crear un nuevo envío y seguir su estado.
  3. Como usuario, puedo generar reportes de estado de mis envíos.

#### 2. Prompt 2: Planificación del Sprint
* **Entrada:** Product Backlog.
* **Salida:** Plan del Sprint con las siguientes tareas y responsables:
  * **Tarea 1:** Desarrollar la funcionalidad de registro e inicio de sesión. (Desarrollador A)
  * **Tarea 2:** Implementar la funcionalidad de creación y seguimiento de envíos. (Desarrollador B)
  * **Tarea 3:** Diseñar e implementar la generación de reportes de estado de envíos. (Desarrollador C)
  * **Tarea 4:** Integrar la aplicación con los sistemas de terceros para rastreo de envíos. (Desarrollador D)

#### 3. Prompt 3: Ejecución del Sprint
* **Entrada:** Plan del Sprint.
* **Salida:** Incremento de software funcional con las siguientes funcionalidades implementadas:
  * Registro e inicio de sesión de usuarios.
  * Creación y seguimiento de envíos.
  * Generación de reportes de estado de envíos.
  * Integración con sistemas de terceros para rastreo de envíos.

#### 4. Prompt 4: Revisión del Sprint
* **Entrada:** Incremento de software funcional.
* **Salida:** Retroalimentación del cliente y lecciones aprendidas:
  * **Retroalimentación del cliente:** El cliente está satisfecho con las funcionalidades implementadas y sugiere agregar la opción de enviar notificaciones a los clientes sobre el estado de sus envíos.
  * **Lecciones aprendidas:** Mejorar la comunicación con el equipo de desarrollo para tener una mejor comprensión de los requerimientos del cliente. Implementar pruebas más exhaustivas antes de la entrega.

#### 5. Prompt 5: Retrospectiva del Sprint
* **Entrada:** Retroalimentación del cliente y lecciones aprendidas.
* **Salida:** Plan de mejora para el siguiente Sprint:
  * Mejorar la coordinación entre los miembros del equipo de desarrollo.
  * Implementar un proceso más eficiente para la estimación y asignación de tareas.
  * Incorporar la funcionalidad de envío de notificaciones a los clientes sobre el estado de sus envíos en el próximo Sprint.

## Resolución
### Bot 1: Cliente y Requerimientos Iniciales

#### Definición del Agente / Prompt Estructurado

**Objetivo:** 
Simular el rol del Cliente/Stakeholder para proveer las necesidades de negocio iniciales y transformarlas en funcionalidades expresadas en formato de Historias de Usuario (User Stories).

**Roles Actuantes:** 
* Cliente (Emisor principal)
* Product Owner (PO) / Analista (Receptores que guían el descubrimiento)

**Entrada (Input):** 
Requerimientos brutos del negocio logístico proporcionados por el cliente:
* Registro y autenticación de usuarios.
* Creación y seguimiento de envíos.
* Generación de reportes de estado de envíos.
* Integración con sistemas de terceros para rastreo de envíos.

**Funcionalidad / Instrucciones de Procesamiento:**
1. Actúa como el Cliente de una empresa de logística que necesita una aplicación web para mejorar su operación.
2. Toma las necesidades de negocio de la *Entrada* y estructura el alcance inicial dividiéndolo en funcionalidades claras.
3. Utiliza como herramienta principal las **Historias de Usuario** siguiendo la estructura estándar: *"Como [rol], quiero [acción] para [beneficio/valor]"*.
4. Asegúrate de redactar al menos las historias prioritarias que cubran el núcleo del sistema logístico para que puedan ser consumidas por el siguiente bot de la cadena.

**Salida (Output):** 
Listado inicial de Historias de Usuario prioritarias y redactadas formalmente con su valor de negocio.

---

#### Simulación de Ejecución del Bot 1 (Output Generado)

**[Salida del Bot 1]**

Como Cliente del proyecto logístico, tras la reunión de alineación con el Product Owner y el Analista, defino que el alcance inicial de la aplicación se centrará en las siguientes Historias de Usuario prioritarias:

* **HU-01: Autenticación Segura**
  * **Como** usuario del sistema (cliente o administrador logístico),
  * **quiero** registrarme e iniciar sesión de manera segura en la aplicación,
  * **para** acceder a mi panel personalizado y proteger la información de mis operaciones.

* **HU-02: Gestión de Despachos**
  * **Como** cliente de la empresa de logística,
  * **quiero** crear un nuevo envío introduciendo los datos de origen, destino y paquete, y visualizar su estado en tiempo real,
  * **para** gestionar mis envíos de manera autónoma y eficiente.

* **HU-03: Reportería de Estados**
  * **Como** administrador logístico,
  * **quiero** generar reportes consolidados del estado de todos los envíos realizados en un período de tiempo,
  * **para** analizar el cumplimiento de los tiempos de entrega y tomar decisiones operativas.

* **HU-04: Rastreo Integrado (Sistemas Externos)**
  * **Como** usuario final del envío,
  * **quiero** que el sistema consulte plataformas de terceros (proveedores de transporte externos) para conocer la ubicación exacta,
  * **para** tener una trazabilidad completa de punta a punta (end-to-end) sin salir de la aplicación.
 
### Bot 2: Definición y Refinamiento del Product Backlog

#### Definición del Agente / Prompt Estructurado

**Objetivo:** 
Recibir las historias de usuario crudas del cliente, analizarlas, estructurarlas de manera formal y consolidar el Product Backlog priorizado del proyecto logístico.

**Roles Actuantes:** 
* Product Owner (PO) (Responsable de maximizar el valor y priorizar)
* Analista Funcional (Responsable de detallar y refinar las condiciones de las historias)
* Cliente (Valida que la prioridad responda a su urgencia de negocio)

**Entrada (Input):** 
La salida directa del **Bot 1** (Historias de Usuario: HU-01, HU-02, HU-03, HU-04 con sus descripciones básicas).

**Funcionalidad / Instrucciones de Procesamiento:**
1. Actúa de manera conjunta como el Product Owner y el Analista Funcional del equipo Scrum.
2. Toma las 4 historias de usuario recibidas en la *Entrada*.
3. Realiza la ceremonia de **Refinamiento del Backlog**: ordena las historias aplicando un criterio de prioridad de negocio (de mayor a menor valor para el cliente, asegurando que los cimientos del sistema como el login y la carga de envíos vayan primero).
4. Agrega valor a la salida incluyendo una breve descripción del impacto de cada historia y dejándolas formalmente numeradas para que el equipo de desarrollo pueda tomarlas en la siguiente etapa.

**Salida (Output):** 
El **Product Backlog Inicial Priorizado** y ordenado de forma lógica y secuencial.

---

#### Simulación de Ejecución del Bot 2 (Output Generado)

**[Salida del Bot 2]**

Como Product Owner y Analista del proyecto, tras revisar las propuestas de funcionalidades junto al Cliente, hemos consolidado y ordenado el **Product Backlog oficial** de acuerdo con la prioridad estratégica de lanzamiento de la aplicación web de logística:

#### Product Backlog Priorizado

* **Prioridad 1: HU-01 - Registro y Autenticación Segura (Módulo de Usuarios)**
  * **Descripción:** Como usuario del sistema, quiero registrarme e iniciar sesión de manera segura en la aplicación, para acceder a mi panel personalizado y proteger la información de mis operaciones.
  * **Impacto:** Bloqueante y Crítico. Es la base de seguridad necesaria para resguardar los datos de los clientes antes de operar cualquier envío.

* **Prioridad 2: HU-02 - Creación y Seguimiento de Envíos (Core de Despachos)**
  * **Descripción:** Como cliente de la empresa de logística, quiero crear un nuevo envío introduciendo los datos de origen, destino y paquete, y visualizar su estado en tiempo real, para gestionar mis envíos de manera autónoma y eficiente.
  * **Impacto:** Crítico de Negocio. Representa el corazón de la aplicación; sin esta funcionalidad el sistema no tiene razón de ser.

* **Prioridad 3: HU-03 - Reportería de Estados (Módulo de Administración)**
  * **Descripción:** Como administrador logístico, quiero generar reportes consolidados del estado de todos los envíos realizados en un período de tiempo, para analizar el cumplimiento de los tiempos de entrega y tomar decisiones operativas.
  * **Impacto:** Medio-Alto. Permite la gestión y control del negocio a nivel interno, analizando cuellos de botella operativos en las entregas.

* **Prioridad 4: HU-04 - Rastreo Integrado con Sistemas de Terceros (Módulo de Integración)**
  * **Descripción:** Como usuario final del envío, quiero que el sistema consulte plataformas de terceros para conocer la ubicación exacta, para tener una trazabilidad completa de punta a punta sin salir de la aplicación.
  * **Impacto:** Medio. Aporta valor agregado y automatización, pero depende de APIs externas de otros proveedores de transporte.

### Bot 3: Planificación del Sprint (Sprint Planning)

#### Definición del Agente / Prompt Estructurado

**Objetivo:** 
Seleccionar las historias de usuario prioritarias del Product Backlog, estimar su complejidad (velocidad/puntos), definir el Objetivo del Sprint (Sprint Goal) y descomponerlas en tareas técnicas específicas asignando responsables.

**Roles Actuantes:** 
* Product Owner (PO) (Presenta las prioridades y valida el objetivo del Sprint)
* Equipo de Desarrollo (Dev) (Estima la complejidad, divide en tareas y asume la responsabilidad)
* Scrum Master (SM) (Facilita la ceremonia y asegura que el equipo no se sobrecargue)
* Analista Funcional (Apoya aclarando dudas sobre las reglas de negocio de las historias)

**Entrada (Input):** 
La salida directa del **Bot 2** (Product Backlog Priorizado con HU-01, HU-02, HU-03 y HU-04).

**Funcionalidad / Instrucciones de Procesamiento:**
1. Actúa como el Equipo Scrum (PO, SM y Devs) durante la ceremonia de **Sprint Planning**.
2. Define un **Objetivo del Sprint** claro y alcanzable para este primer ciclo.
3. Evalúa la capacidad del equipo y selecciona las historias que ingresarán al Sprint Backlog. 
4. Realiza la **Puntuación de Complejidad** (simulando Story Points o velocidad del equipo) para cada historia seleccionada.
5. Descompone cada historia de usuario en **tareas técnicas específicas** de desarrollo y asigna un responsable técnico (Desarrollador A, B, C, D) para asegurar el balance de carga.

**Salida (Output):** 
El **Sprint Backlog definitivo** que incluye el Objetivo del Sprint, los puntos de historia estimados y el desglose detallado de tareas con sus encargados.

---

#### Simulación de Ejecución del Bot 3 (Output Generado)

**[Salida del Bot 3]**

Tras realizar la sesión de Sprint Planning con el PO, SM y el equipo de desarrolladores, se definen los siguientes acuerdos para el **Sprint 1** (Duración: 2 semanas):

#### Objetivo del Sprint (Sprint Goal)
"Implementar el núcleo operativo y de seguridad de la plataforma web, permitiendo a los usuarios registrarse e iniciar sesión de forma segura, y habilitar la creación y el seguimiento básico de sus envíos logísticos."

#### Sprint Backlog Seleccionado y Estimación (Velocidad Total: 13 Puntos)

#### 1. HU-01: Registro y Autenticación Segura
* **Estimación de Complejidad:** 5 Puntos de Historia (Complejidad Media)
* **Desglose de Tareas Técnicas:**
  * **Tarea 1.1:** Diseñar e implementar el modelo de datos en la base de datos para usuarios y roles. -> **Asignado a:** Desarrollador A (Senior)
  * **Tarea 1.2:** Desarrollar las vistas de interfaz de usuario (Front-end) para Login y Registro. -> **Asignado a:** Desarrollador B (Junior)
  * **Tarea 1.3:** Programar la lógica de autenticación (Back-end) y encriptación de contraseñas. -> **Asignado a:** Desarrollador A (Senior)

#### 2. HU-02: Creación y Seguimiento de Envíos
* **Estimación de Complejidad:** 8 Puntos de Historia (Complejidad Alta - Core del Negocio)
* **Desglose de Tareas Técnicas:**
  * **Tarea 2.1:** Diseñar el formulario web para el ingreso de datos de envío (Origen, Destino, Peso). -> **Asignado a:** Desarrollador B (Junior)
  * **Tarea 2.2:** Desarrollar la API e integrarla con la base de datos para guardar y actualizar el estado del envío. -> **Asignado a:** Desarrollador C (Ssr)
  * **Tarea 2.3:** Crear el panel visual de tracking en tiempo real (barra de estado: Recibido -> En Viaje -> Entregado). -> **Asignado a:** Desarrollador D (Ssr)

*(Nota del SM: Las HU-03 y HU-04 quedan en el Product Backlog para el siguiente Sprint debido a la capacidad de velocidad actual del equipo Dev).*


### Bot 4: Ejecución del Sprint

#### Definición del Agente / Prompt Estructurado

**Objetivo:** 
Simular el transcurso del desarrollo técnico del Sprint, exponiendo el estado diario de las tareas, la coordinación del equipo frente a los impedimentos detectados y la entrega del incremento de software funcional.

**Roles Actuantes:** 
* Equipo de Desarrollo (Dev) (Ejecuta las tareas técnicas e informa su estatus)
* Scrum Master (SM) (Facilita la remoción de bloqueos y asegura el flujo de trabajo)

**Entrada (Input):** 
La salida directa del **Bot 3** (Sprint Backlog con las tareas técnicas asignadas a los Desarrolladores A, B, C y D).

**Funcionalidad / Instrucciones de Procesamiento:**
1. Actúa como el Equipo de Desarrollo y el Scrum Master durante el transcurso del Sprint.
2. Recrea una simulación de la ceremonia **Daily de 15 minutos**, donde los desarrolladores respondan las preguntas clave: qué hicieron, qué van a hacer y qué **bloqueos** tienen.
3. Muestra cómo el Scrum Master interviene para resolver un bloqueo y cómo los integrantes se ayudan mutuamente para cumplir el objetivo del Sprint.
4. Concluye con el estado final de las tareas al cerrarse el ciclo de desarrollo.

**Salida (Output):** 
El **Incremento de Software Funcional** listo y desplegado en el entorno de pruebas, acompañado del reporte de la dinámica diaria del equipo.

---

#### Simulación de Ejecución del Bot 4 (Output Generado)

**[Salida del Bot 4]**

#### Simulación de Ceremonia: Reunión Diaria (Daily) - Día 6 del Sprint

* **Desarrollador A (Senior):** "Ayer terminé el modelo de datos de usuarios (Tarea 1.1). Hoy voy a avanzar con la lógica de encriptación en el Back-end (Tarea 1.3). No tengo ningún bloqueo."
* **Desarrollador B (Junior):** "Terminé el diseño de las pantallas de Login y Registro (Tarea 1.2). Hoy empecé con el formulario web de ingreso de envíos (Tarea 2.1). **Tengo un bloqueo:** no me queda claro cómo validar los campos de peso y dimensiones según las reglas del negocio de logística."
* **Desarrollador C (Ssr):** "Avancé con la API para guardar los envíos (Tarea 2.2). Al escuchar el bloqueo de la Tarea 2.1 de B, me ofrezco a coordinar una sesión de 10 minutos después de la Daily para mostrarle cómo armé la API, así sabe exactamente qué formatos de datos y validaciones espera el sistema."
* **Scrum Master (SM):** "Excelente la ayuda de C. Me encargo de registrar el bloqueo de B y verificar con el Analista Funcional si hay alguna restricción extra de peso máximo para actualizar la documentación. Continuemos."

---

#### Incremento de Software Funcional Entregado (Fin del Sprint)
Al concluir las dos semanas de ejecución, el equipo ha completado satisfactoriamente el 100% del Sprint Backlog comprometido, desplegando en el entorno de testing un **incremento de software real y funcional** que incluye:

1. **Módulo de Usuarios Operativo:** Pantallas de registro e inicio de sesión integradas con una base de datos segura y contraseñas encriptadas.
2. **Módulo Core de Logística Inicial:** Formulario de carga de nuevos envíos (origen, destino, paquete) conectado a la API de almacenamiento, con un panel visual básico que refleja el estado inicial de la carga.


### Bot 5: Revisión del Sprint (Sprint Review)

#### Definición del Agente / Prompt Estructurado

**Objetivo:** 
Presentar el incremento de software funcional desarrollado durante el Sprint al Product Owner y al Cliente para evaluar el grado de avance del proyecto y recopilar comentarios y adaptaciones del negocio.

**Roles Actuantes:** 
* Equipo de Desarrollo (Dev) (Presenta la demostración técnica del software)
* Product Owner (PO) (Valida el cumplimiento de los criterios de aceptación junto al equipo antes de la demo)
* Cliente / Stakeholder (Prueba la funcionalidad, evalúa el avance y aporta feedback)
* Scrum Master (SM) (Modera la sesión y asegura el enfoque ágil de la presentación)

**Entrada (Input):** 
La salida directa del **Bot 4** (Incremento de Software Funcional con los módulos de Autenticación Segura y Creación/Seguimiento de Envíos en el entorno de pruebas).

**Funcionalidad / Instrucciones de Procesamiento:**
1. Actúa como el Equipo Scrum y el Cliente durante la ceremonia de **Sprint Review**.
2. Simula una revisión interna previa donde el equipo Dev le muestra al PO las funcionalidades listas para verificar que cumplen con el objetivo acordado.
3. Recrea la demo en vivo frente al Cliente, permitiéndole interactuar directamente con las pantallas de login y el formulario de envíos.
4. Registra formalmente las devoluciones y observaciones del Cliente (tanto lo que le gustó como las nuevas solicitudes o cambios sugeridos para el producto).

**Salida (Output):** 
Documento de **Retroalimentación del Cliente** con el grado de avance aprobado y los nuevos requerimientos identificados para el Backlog.

---

#### Simulación de Ejecución del Bot 5 (Output Generado)

**[Salida del Bot 5]**

#### Demostración y Grado de Avance
El Equipo de Desarrollo realiza la inspección del incremento funcional en el entorno de staging. El Product Owner valida el cumplimiento de los criterios de aceptación y se da inicio a la demostración con el Cliente:

1. **Demostración de HU-01 (Autenticación):** Se registra un nuevo usuario de logística ficticio y se inicia sesión correctamente. El cliente destaca la fluidez visual de la interfaz diseñada por el Desarrollador B.
2. **Demostración de HU-02 (Creación de Envíos):** El cliente ingresa datos de prueba en el formulario. Se confirma que el sistema guarda el paquete con éxito y cambia el estado de tracking a "Recibido".

---

#### Retroalimentación Oficial del Cliente (Feedback)

* **Aspectos Aprobados:** El cliente manifiesta una **alta satisfacción** con el núcleo del sistema. Declara que el proceso de inicio de sesión y la carga de datos de origen/destino responden exactamente a lo conversado inicialmente con el analista.
* **Nuevas Necesidades de Negocio Detectadas:** Al probar el flujo de seguimiento en vivo, el cliente observa una limitación operativa:
  > *"El sistema web funciona excelente, pero en la realidad logística nuestros usuarios no están mirando la pantalla todo el día. Necesitamos obligatoriamente que, cuando el estado de un envío cambie de 'En Viaje' a 'Entregado', se le dispare una **notificación por correo o alerta** automática al destinatario."*

#### Estado del Avance para el Product Backlog
El PO consolida esta solicitud: la nueva funcionalidad de **"Envío de notificaciones automáticas por cambio de estado"** se tipifica formalmente para ser procesada en el flujo de trabajo Scrum.


### Bot 6: Retrospectiva del Sprint (Sprint Retrospective)

#### Definición del Agente / Prompt Estructurado

**Objetivo:** 
Analizar el desempeño de la metodología Scrum durante el Sprint, evaluar el estado anímico y operativo del equipo, identificar aciertos y fallas, y aplicar la mejora continua transformando los problemas en nuevos requerimientos para el backlog.

**Roles Actuantes:** 
* Scrum Master (SM) (Facilita la sesión, promueve un ambiente seguro y estructura el plan de acción)
* Equipo de Desarrollo (Dev) (Aporta su perspectiva técnica y comparte cómo se sintió)
* Product Owner (PO) (Analiza el proceso desde la gestión y la claridad de los requisitos)

**Entrada (Input):** 
La salida directa del **Bot 5** (Retroalimentación del Cliente y lecciones aprendidas durante la Review).

**Funcionalidad / Instrucciones de Procesamiento:**
1. Actúa como el Scrum Master liderando la sesión de **Retrospectiva** al finalizar el Sprint 1.
2. Evalúa cómo fue la cuestión metodológica, la comunicación interna y el sentimiento del equipo.
3. Estructura los resultados en una **Tabla de Diagnóstico Metodológico** dividida estrictamente en:
   * **Cosas que están BIEN:** Prácticas exitosas que aportaron valor y se deben mantener.
   * **Cosas que están MAL:** Problemas, fricciones o ineficiencias ocurridas en el proceso.
4. Aplica la regla de mejora continua del equipo: todo lo que se clasifique como "Cosas que están MAL" debe ser analizado para **transformarse en un nuevo requerimiento concreto** (de proceso o técnico) que se inyecte directamente de regreso a la Etapa 1 y 2 (Requerimientos y Backlog) para el próximo Sprint.

**Salida (Output):** 
Tabla de Retrospectiva (Bien / Mal) y el **Plan de Acción de Mejora Continua** con los nuevos requerimientos derivados hacia las etapas iniciales del flujo.

---

#### Simulación de Ejecución del Bot 6 (Output Generado)

**[Salida del Bot 6]**

Como Scrum Master del proyecto, presento las conclusiones consolidadas de la reunión de Retrospectiva del Sprint 1, donde el equipo debatió abiertamente sobre sus dinámicas de trabajo y sentimientos individuales:

#### Tabla de Diagnóstico Metodológico (Sprint 1)

| Cosas que están BIEN (Hay que seguir haciéndolo) | Cosas que están MAL (Fricciones y problemas) |
| :--- | :--- |
| **Colaboración interna inmediata:** La Daily de 15 minutos sirvió para que el Dev C ayudara al Dev B (Junior) a destrabar su código en el formulario. | **Sobrecarga y estrés por falta de pruebas:** No se planificaron pruebas automatizadas, lo que hizo que los Devs testearan todo manualmente a última hora bajo mucha presión antes de la Review. |
| **Diseño Front-end limpio:** La interfaz gráfica entregada superó las expectativas visuales del cliente. | **Falta de claridad en reglas complejas:** El Dev Junior (B) perdió tiempo valioso porque las reglas de validación de peso del paquete de logística no estaban del todo claras en la historia original. |
| **Cumplimiento del Sprint Goal:** El equipo se mantuvo enfocado y logró desplegar el incremento funcional prometido. | **Desconexión con el comportamiento real del usuario:** El cliente nos hizo ver en la Review que los operarios no pueden estar mirando la web de tracking constantemente. |

---

#### Plan de Acción: Transformación en Nuevos Requerimientos (Vuelta a Etapas 1 y 2)

Para solucionar lo que está mal, el equipo Scrum decide reconvertir estos problemas en acciones y requerimientos que regresan inmediatamente a la mesa de diseño (Etapa 1: Requerimientos) y a la lista priorizada (Etapa 2: Backlog) para el inicio del Sprint 2:

1. **Requerimiento Técnico de Proceso (Solución a la falta de pruebas):**
   * *Acción:* Crear la tarea obligatoria *"Configurar ambiente de pruebas automatizadas básicas de regresión"* en el Backlog. Ninguna historia de usuario podrá darse por terminada si no pasa estas pruebas.
2. **Requerimiento de Análisis (Solución a la falta de claridad en reglas):**
   * *Acción:* El Analista Funcional y el PO abrirán un espacio de refinamiento obligatorio de criterios de aceptación antes de asignar tareas complejas a desarrolladores Junior.
3. **Nuevo Requerimiento de Software (Derivado del Feedback del Cliente en la Review):**
   * *Acción:* Dar de alta formalmente en la Etapa 1 la Historia de Usuario: *"HU-05: Como destinatario del envío, quiero recibir una notificación automática por correo cuando mi paquete cambie de estado, para estar informado sin necesidad de consultar la aplicación web constantemente"*. Esta historia ingresará directamente al Product Backlog refinado.
