# Masterpiece | Trabajo Práctico Integrador y Progresivo

**Universidad Tecnológica Nacional (UTN)**  
**Carrera:** Tecnicatura Universitaria en Programación a Distancia  
**Asignatura:** Organización Empresarial  
**Año:** 2026  
**Autor de la Entrega 4:** Franco Agustín Gómez

> Proyecto académico de gestión y documentación de un módulo de facturación electrónica para Masterpiece. El software se encuentra en etapa de propuesta y modelado; no se presenta como una implementación funcional.

## Descripción del proyecto

**Masterpiece** es una empresa argentina de comercio electrónico dedicada a la importación y venta de artículos de decoración y organización para el hogar. Comercializa sus productos mediante canales digitales como Mercado Libre, Instagram y TikTok.

El proyecto propone un **módulo de facturación electrónica integrado** para automatizar la emisión de comprobantes fiscales mediante ARCA, centralizar los datos de ventas y mantener actualizado el inventario.

## Problema identificado

Actualmente, el proceso de facturación se realiza de forma manual y sin integración automática con el resto de las operaciones. Esto puede generar:

- Demoras en la emisión de comprobantes.
- Errores de carga y diferencias entre ventas y facturas.
- Falta de sincronización con el inventario.
- Dificultades para controlar y analizar las operaciones comerciales.

## Solución propuesta

El módulo propuesto permitirá:

1. Centralizar ventas confirmadas provenientes de diferentes canales.
2. Validar los datos y las condiciones necesarias para facturar.
3. Solicitar la autorización de comprobantes electrónicos a ARCA.
4. Registrar las facturas autorizadas, incluidos sus códigos CAE.
5. Actualizar el inventario según las operaciones facturadas.
6. Registrar rechazos e incidencias para su revisión administrativa.

## Objetivos del proyecto

Los siguientes valores son **metas de planificación**, no resultados medidos:

| Indicador | Meta |
| --- | --- |
| Automatización | Facturar automáticamente al menos el **95 %** de las ventas aptas. |
| Rendimiento | Procesar el **95 %** de las solicitudes en **5 segundos o menos**, en condiciones normales. |
| Capacidad | Gestionar al menos **10.000 registros** de ventas y facturas. |
| Plazo | Completar una primera versión funcional en un máximo de **12 semanas**. |

## Modelado de procesos (BPMN)

Se modeló el proceso de facturación electrónica desde la recepción de una venta confirmada hasta su autorización fiscal y la actualización del inventario.

El diagrama contempla:

- Participantes externos: plataformas comerciales y ARCA.
- Responsabilidades internas: sistema automatizado y Administración y Finanzas.
- Decisiones: venta apta para facturación y autorización del comprobante.
- Excepciones: datos inválidos, rechazos e incidencias que requieren revisión.

**Modelo editable:** [Masterpiece_Facturacion.bpmn](bpmn/Masterpiece_Facturacion.bpmn)

## Historias de usuario y gestión ágil

Las historias de usuario se registran como **GitHub Issues** y se gestionan en un tablero Kanban:

| Historia | Funcionalidad | Estado inicial |
| --- | --- | --- |
| [HU-01](../../issues/1) | Centralizar ventas de los canales comerciales. | Todo |
| [HU-02](../../issues/2) | Automatizar la emisión de facturas electrónicas. | Todo |
| [HU-03](../../issues/3) | Actualizar automáticamente el stock. | Todo |

**[Ver tablero de GitHub Projects](https://github.com/users/Agustingomez98/projects/1/views/1?layout_template=board)**

Los estados de seguimiento son **Todo**, **In Progress** y **Done**, equivalentes a Por Hacer, En Progreso y Listo. El tablero refleja la planificación académica; las funcionalidades todavía no se consideran implementadas.

## Documentación del TPI

| Entrega | Contenido |
| --- | --- |
| **1** | La organización y su enfoque sistémico. |
| **2** | Diagnóstico y planificación del proyecto tecnológico: FODA, objetivos y Gantt. |
| **3** | Estructura formal y diseño de datos: organigrama y diccionario de datos. |
| **4** | Modelado BPMN, gestión colaborativa y mecanismos de control. |

El PDF consolidado de las cuatro entregas se incorporará en `docs/Masterpiece_TPI_Entrega_Final.pdf` cuando esté finalizado.

## Control de versiones

La documentación se organiza con **Git y GitHub** mediante ramas de trabajo, commits descriptivos y Pull Requests para registrar y revisar los cambios.

- Rama principal: `main`.
- Rama de documentación: `docs/entrega-4`.
- Gestión de tareas: GitHub Issues y GitHub Projects.

La Entrega 4 se desarrolla individualmente. La consigna académica solicita revisión de pares de al menos un Pull Request; este requisito requiere una revisión externa real o una aclaración de la cátedra para la modalidad individual.

## Declaración de uso de inteligencia artificial

En las distintas entregas se utilizaron asistentes de IA, incluidos **ChatGPT (OpenAI)** y **Claude (Anthropic)**, como apoyo para organizar ideas, revisar la redacción y elaborar propuestas de representación gráfica.

Las propuestas de IA deben contrastarse con los documentos previos, las reglas de BPMN y los requisitos de la materia. Las correcciones humanas realizadas efectivamente se documentarán antes de la presentación final; no se atribuyen a los asistentes decisiones que corresponden al autor.

La responsabilidad por la veracidad, la coherencia conceptual y la presentación del trabajo corresponde al autor.

## Autoría

- **Entrega 4:** Franco Agustín Gómez (trabajo individual).
- **Entregas anteriores:** conservan los créditos de autoría indicados en cada documento original.

---

**Proyecto académico — UTN, 2026.**
