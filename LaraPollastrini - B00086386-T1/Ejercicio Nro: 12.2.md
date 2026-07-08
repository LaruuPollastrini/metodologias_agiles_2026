# Ejercicio Nro: 12.2

## Enunciado
Ejercicio Integrador: Aplicación de la Metodología Lean con Odoo Project

## Resolución

[cite_start]**Empresa:** LeanDev [cite: 11]  
[cite_start]**Herramienta de Gestión:** Odoo Project [cite: 14]

---

### Parte 1: Diagnóstico Inicial del Proceso

[cite_start]A partir del análisis del flujo de trabajo propuesto para la gestión de proyectos de desarrollo de software [cite: 9, 27][cite_start], se identifican los siguientes **5 tipos de desperdicios (Muda)** clave dentro del ciclo actual[cite: 28]:

1. [cite_start]**Defectos / Retrabajo:** Funcionalidades que no se ajustan a las necesidades del cliente o contienen errores, obligando a reescribir código[cite: 28, 45].
2. [cite_start]**Espera:** Tareas totalmente paralizadas en la etapa de Testing debido a la falta de capacidad de validación[cite: 28, 52].
3. [cite_start]**Sobreproducción:** Desarrollo de características o características complejas (*features*) que el cliente final no utiliza ni necesita[cite: 28, 65].
4. [cite_start]**Talento No Utilizado:** Desarrolladores Junior ociosos mientras el equipo Senior se encuentra saturado y al borde del colapso[cite: 75].
5. [cite_start]**Procesamiento Extra:** Diseñar e implementar software sin validación temprana de requisitos, lo que genera bucles innecesarios de revisión[cite: 45, 48].

---

### Parte 2: Resolución de Casos de Uso Lean en Odoo

[cite_start]A continuación se detalla el análisis de los 5 casos prácticos, especificando el **Desperdicio Detectado** [cite: 83][cite_start], las **Prácticas Lean Aplicadas** [cite: 84] [cite_start](con sus respectivas tareas en Odoo [cite: 17]) y los **Resultados Observados**[cite: 85].

#### Caso 1: Retrabajo constante en entregas
* [cite_start]**Contexto:** El cliente recibe funcionalidades que no pidió o que no se ajustan a sus necesidades reales[cite: 45].
* [cite_start]**Desperdicio detectado:** Retrabajo / Defectos y Procesamiento Extra[cite: 28].
* **Prácticas Lean aplicadas & Tareas en Odoo:**
  * [cite_start]Crear la tarea: `"Detectar origen del retrabajo"` para analizar las fallas en la toma de requerimientos[cite: 47].
  * [cite_start]Agregar la etapa `"Revisión de Requisitos"` en el tablero Kanban de Odoo antes de pasar a desarrollo.
  * [cite_start]Configurar una política de *"Validación temprana de requisitos"* junto con un **WIP Limit estricto** en la etapa de validaciones[cite: 48, 50].
* [cite_start]**Resultados observados:** Alineación inmediata entre las expectativas del cliente y el equipo técnico, reduciendo drásticamente las iteraciones correctivas post-entrega[cite: 45, 85].

#### Caso 2: Bloqueo en testing por sobrecarga
* [cite_start]**Contexto:** Múltiples tareas acumuladas esperando validación en Testing sin suficiente capacidad para procesarlas[cite: 52].
* [cite_start]**Desperdicio detectado:** Espera / Inventario (Trabajo en curso acumulado)[cite: 28].
* **Prácticas Lean aplicadas & Tareas en Odoo:**
  * [cite_start]Ejecutar análisis para *"Detectar cuello de botella"* en el flujo de valor[cite: 54].
  * [cite_start]Establecer y redefinir un **WIP Limit restrictivo** en la columna `"Testing"` dentro de Odoo Project[cite: 18, 55].
  * [cite_start]Implementar la política Pull: *"No ingresar nuevas tareas al flujo si la columna Testing está llena"*[cite: 56].
* [cite_start]**Resultados observados:** Reducción del tiempo de ciclo total (*Lead Time*), obligando al equipo a resolver los bloqueos antes de iniciar nuevo desarrollo[cite: 57, 85].

#### Caso 3: Bugs recurrentes post-producción
* [cite_start]**Contexto:** Alta tasa de errores y fallos críticos detectados por los usuarios tras la liberación del producto[cite: 59].
* [cite_start]**Desperdicio detectado:** Defectos (Costo de no-calidad)[cite: 28].
* **Prácticas Lean aplicadas & Tareas en Odoo:**
  * [cite_start]Implementar la práctica de *Jidoka* mediante *"Revisiones entre pares (Peer Reviews)"* antes de dar por terminada una tarea[cite: 61].
  * [cite_start]Crear tareas automatizadas de tipo `"Tests automatizados básicos"` (pruebas unitarias/regresión)[cite: 62].
  * [cite_start]Clasificar y priorizar las tareas usando la etiqueta (`Tag`): `"Prevención de errores"`[cite: 19, 63].
* [cite_start]**Resultados observados:** Mayor estabilidad del software en producción y traspaso de la calidad hacia la izquierda del flujo (*Shift-Left Testing*), detectando fallos antes del despliegue[cite: 59, 85].

#### Caso 4: Features no utilizadas por el cliente
* [cite_start]**Contexto:** El cliente no utiliza varias de las funcionalidades entregadas tras el despliegue[cite: 65].
* [cite_start]**Desperdicio detectado:** Sobreproducción[cite: 28].
* **Prácticas Lean aplicadas & Tareas en Odoo:**
  * [cite_start]Crear tarea de auditoría: `"Identificar funcionalidades no usadas"` mediante analíticas de uso[cite: 67].
  * [cite_start]Reestructurar el mapa del producto para `"Planificar entregas incrementales"` enfocadas exclusivamente en el valor real[cite: 71].
  * [cite_start]Automatizar en Odoo tareas del tipo `"Demo con cliente"` mandatorias antes del cierre definitivo de cualquier *feature*[cite: 73].
* [cite_start]**Resultados observados:** Optimización del esfuerzo del equipo, asegurando que cada hora invertida en programación responda a una necesidad validada y de alto impacto[cite: 65, 85].

#### Caso 5: Saturación del equipo senior
* [cite_start]**Contexto:** Programadores Senior colapsados de trabajo, mientras los perfiles Junior carecen de asignaciones y permanecen ociosos[cite: 75].
* [cite_start]**Desperdicio detectado:** Talento No Utilizado / Desbalance (*Mura*)[cite: 28].
* **Prácticas Lean aplicadas & Tareas en Odoo:**
  * [cite_start]Modificar la gestión del flujo en Odoo para `"Balancear la asignación de tareas"` de forma equitativa[cite: 77].
  * [cite_start]Crear la tarea continua: `"Mentoría rápida"` para potenciar la autonomía del equipo Junior[cite: 78].
  * [cite_start]Agendar y `"Planificar sesiones de apoyo"` técnicas semanales entre roles[cite: 79].
* [cite_start]**Resultados observados:** Reducción del estrés laboral del equipo senior, aumento de la capacidad técnica global y eliminación del monocultivo de conocimiento en el proyecto[cite: 75, 85].

---

### Parte 3: Priorización, Visualización y Mejora Continua (Ciclo PDCA)

[cite_start]Para asegurar la sostenibilidad de estas mejoras en **LeanDev** [cite: 11][cite_start], se implementa la gestión ágil mediante el ciclo **PDCA** (*Plan-Do-Check-Act*) enfocado en el cuello de botella más crítico (Caso 2: Testing)[cite: 35, 36]:

* [cite_start]**Plan (Planificar):** Identificado el atasco en Testing [cite: 35, 52][cite_start], se planifica la reducción de tareas simultáneas fijando un tope máximo de trabajo (WIP = 2) [cite: 18, 55] y se diseñan los criterios de aceptación mínimos.
* [cite_start]**Do (Hacer):** Se configuran las restricciones y automatizaciones en el Kanban de Odoo[cite: 17, 31]. [cite_start]Se ejecutan pruebas cruzadas donde los desarrolladores ayudan a testear para descongestionar la columna[cite: 52].
* [cite_start]**Check (Verificar):** En las reuniones diarias simuladas[cite: 33], se monitorean las métricas del tablero. Se comprueba si el tiempo que le toma a una tarea pasar de "Desarrollo" a "Listo" disminuyó.
* [cite_start]**Act (Actuar):** Al constatar la efectividad de la medida, se oficializa la política estricta en la organización [cite: 56][cite_start], documentando el proceso en la retrospectiva del proyecto dentro de Odoo para estandarizar la solución[cite: 24, 36].
