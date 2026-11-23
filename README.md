# Traducción Operativa: Pre-Ingeniería y Adopción en Consultoría de TI

Marco metodológico para cerrar la brecha entre los síntomas operativos del negocio y los requerimientos técnicos ejecutables antes de diseñar o programar una solución tecnológica.

---

## Tesis Central

En consultoría tecnológica, el fallo más costoso ocurre antes de escribir la primera línea de código: **traducir literalmente lo que el cliente pide en lugar de auditar lo que su operación realmente necesita.**

* **Barrera de lenguaje y ego institucional:** El cliente expresa síntomas desde su dominio operativo, mientras que las propuestas técnicas mal enfocadas suelen priorizar complejidad aparente sobre resolución de cuellos de botella.
* **Principio rector (Facultar, no generar dependencia):** El rigor metodológico se aplica con el mismo nivel de exigencia en una operación pequeña que en una organización de gran capital humano. Facultar al cliente para que crezca es la métrica tangible que valida la calidad del diseño.

---

## Fase 1: Auditoría «El Filtro del Filtro»

Antes de proponer herramientas o automatizaciones, se audita el origen del requerimiento y el entorno real de ejecución:

1. **Inventario y fricción de interfaz:** Identificación de las herramientas actuales, su nivel de usabilidad y el porcentaje real de dominio por parte del equipo (distinguiendo uso por intuición o falta de manuales/capacitación frente a dominio operativo).
2. **Fragmentación y trazabilidad de reportes:** Evaluación de qué sistemas generan reportes, cómo se consolidan y si es viable construir una capa intermedia de unificación antes de reemplazar software.
3. **Mapa de usuarios y roles:** Separación entre quienes consultan indicadores o toman decisiones y quienes capturan o procesan datos en la operación diaria.
4. **Prueba de estrés financiera y volumétrica:** Contraste entre el volumen de operaciones y el comportamiento financiero reciente. Un flujo estable a baja escala puede colapsar al incrementarse el volumen; esto define si el cuello de botella corresponde al diseño del proceso o a la capacidad del sistema.

---

## Fase 2: Delimitación de Arquitectura Ejecutable

Todo requerimiento pasa por cuatro variables base antes de pasar a implementación:

* **Qué:** Acción o flujo concreto que debe ejecutarse.
* **Cuándo / En qué tiempo:** Ventana operativa, frecuencia o plazo de respuesta requerido.
* **Para qué:** Propósito de negocio o cuello de botella que se busca resolver.
* **Para cuántos:** Alcance de usuarios, áreas o volumen transaccional esperado.

A partir de estas variables se define la **jerarquía de supervisión y control**: qué puntos requieren criterio o validación humana y qué tareas se delegan a reglas automatizadas o flujos asistidos para dar visibilidad continua del avance.

---

## Fase 3: Variantes de Adopción según Escala Organizacional

La estructura de implementación se adapta al tamaño y dinámica operativa sin reducir el rigor del diagnóstico:

| Dimensión | Variante A: Empresa Pequeña / PyME | Variante B: Gran Capital Humano |
| :--- | :--- | :--- |
| **Dinámica habitual** | Dirección y operación suelen concentrarse en pocas personas; mayor peso de procesos informales. | Mayor división de áreas, capas de mando y dependencias interdepartamentales. |
| **Riesgo principal** | Sobrecarga operativa y dependencia de tareas manuales repetitivas. | Silos de información, fricción entre áreas y desconexión entre captura y control. |
| **Enfoque de diseño** | Estandarización, aprovechamiento de herramientas existentes y automatizaciones ligeras. | Interoperabilidad entre capas, trazabilidad de punta a punta y gobernanza de flujos. |
| **Resultado esperado** | Liberar capacidad operativa y ordenar procesos para escalar con estabilidad. | Alinear ejecución y visibilidad de extremo a extremo sin frenar la operación. |

---

## Gobernanza y Validación de Resultados

Una implementación se considera válida cuando:

* El requerimiento técnico queda trazado a un problema operativo verificable.
* Los cuellos de botella identificados muestran reducción medible en fricción o tiempos de ejecución.
* La operación cuenta con información clara sobre su estado de avance y continuidad autónoma.
