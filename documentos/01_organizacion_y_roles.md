# 📘 Sección 1: Organización del Equipo y Definición de Roles

## 1.1 Introducción y Justificación
Uno de los principales problemas en los trabajos universitarios colaborativos es la falta de claridad sobre quién hace qué y en qué plazos. La experiencia en la gestión de proyectos demuestra que la simple repartición aleatoria de partes sin una coordinación estructurada suele derivar en documentos incoherentes, entregas fuera de tiempo o sobrecarga de trabajo en un solo integrante.

Para evitar esto, este manual adopta los principios de autogestión y distribución formal de responsabilidades recomendados para el trabajo colaborativo de alto rendimiento ([Schwaber y Sutherland, 2020](../referencias/referencias_bibliograficas.md#ref-scrum-2020)).

---

## 1.2 Matriz de Responsabilidades (Modelo RACI)
En lugar de que todos hagan de todo al mismo tiempo, el equipo debe asignar roles principales según la matriz **RACI** (*Responsable, Aprobador, Consultado e Informado*):

| Rol del Estudiante | Función Principal | Responsable (*Responsible*) | Aprobador (*Accountable*) |
| :--- | :--- | :--- | :--- |
| **Líder de Proyecto** | Coordinar el cronograma y resolver bloqueos entre integrantes. | Asignación de tareas y seguimiento del tablero Kanban. | Velar por el cumplimiento de las fechas límite. |
| **Redactor Técnico** | Sintetizar la información y redactar en formato Markdown. | Escribir los contenidos asignados en su propia rama. | Unificar el tono y estilo del texto según ([Normas APA, 2024](../referencias/referencias_bibliograficas.md#ref-apa-2024)). |
| **Investigador / Documentalista** | Buscar fuentes académicas válidas y gestionar las referencias. | Recopilar bibliografía con enlaces funcionales. | Validar la veracidad de la información recopilada. |
| **Revisor de Calidad & Git** | Auditar ortografía, formato y controlar el repositorio. | Comprobar enlaces, carpetas y sintaxis de Markdown. | Aprobar los *Pull Requests* y realizar las fusiones a `main`. |

> 📌 **Nota sobre los roles:** En equipos de dos personas (como el de este proyecto), cada integrante asume responsabilidades compartidas. Sin embargo, la regla inquebrantable de control de versiones es que **nadie aprueba su propio Pull Request**; la revisión de calidad siempre la realiza el compañero.

---

## 1.3 Protocolo de Comunicación Síncrona vs. Asíncrona
Para no saturar los grupos de mensajería ni depender de reuniones presenciales constantes, adoptamos el flujo de trabajo asíncrono recomendado por la documentación de GitHub ([GitHub, 2024](../referencias/referencias_bibliograficas.md#ref-github-2024)):

1. **Comunicación Asíncrona (Principal):**
   * **Medio:** Issues de GitHub, comentarios en los Pull Requests y notas en el tablero Kanban.
   * **Uso:** Asignación de tareas, revisión de avances y observaciones sobre correcciones específicas.
   * **Ventaja:** Deja un registro histórico transparente de todo lo que se ha trabajado y acordado.

2. **Comunicación Síncrona (Excepcional):**
   * **Medio:** Google Meet, Discord o llamadas breves.
   * **Uso:** Sesiones cortas de alineación (máximo 15-20 minutos) al inicio de cada fase o ante dudas complejas.
   * **Regla de Oro:** Todo acuerdo tomado verbalmente debe anotarse como comentario en la *Issue* correspondiente.

---

## 1.4 Flujo Visual de Comunicación
El siguiente diagrama resume cómo el equipo debe tomar decisiones según la urgencia del caso:

![Flujo de Toma de Decisiones y Comunicación](../imagenes/flujo_comunicacion.md)