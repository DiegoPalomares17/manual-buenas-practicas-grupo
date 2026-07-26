# 📘 Sección 3: Ecosistema de Herramientas Colaborativas

## 3.1 Entorno de Trabajo Integrado (VS Code + Git + GitHub)


![VSCode, Git y GiHub](../imagenes/vsc-git-github.jpg)

Para garantizar la consistencia técnica del proyecto, el equipo adopta un stack de herramientas estandarizado que permite el desarrollo, control de versiones y edición simultánea de documentación.

| Herramienta | Rol en el Proyecto | Justificación Técnica |
| :--- | :--- | :--- |
| **Visual Studio Code** | Editor de código y documentación | Soporta extensiones de previsualización en tiempo real de Markdown, resaltado de sintaxis y terminal integrada. |
| **Git** | Control de versiones local | Registra el historial de cambios mediante *commits* e independiza el trabajo individual mediante ramas (*branches*). |
| **GitHub** | Repositorio remoto y gestión | Centraliza el código fuente, hospeda el tablero Kanban, gestiona revisiones con *Pull Requests* y almacena la documentación ([GitHub, 2024](../referencias/referencias_bibliograficas.md#ref-github-2024)). |

---

## 3.2 Estándar de Redacción Técnica en Markdown
Todo el manual se redacta utilizando la sintaxis de marcado ligero Markdown ([Gruber, 2004](../referencias/referencias_bibliograficas.md#ref-gruber-2004)). Este formato asegura que el texto sea perfectamente legible como código fuente plano y fácil de exportar a PDF o HTML.

### Reglas Clave de Estilo Markdown:
1. **Estructura Jerárquica de Títulos:** 
   * Se utiliza un solo `#` (Título 1) para el nombre principal de la sección.
   * Se utilizan `##` (Título 2) para subsecciones y `###` (Título 3) para apartados específicos.
2. **Resaltado y Listas:** Uso moderado de negritas (`**texto**`) para términos clave y listas no ordenadas (`*`) para descomponer conceptos densos.
3. **Tablas y Bloques:** Tablas estructuradas para matrices comparativas y bloques de cita (`>`) para reglas inquebrantables o advertencias.

---

## 3.3 Convención de Mensajes de Commit (Conventional Commits)
Para mantener un historial de cambios profesional y rastreable, los integrantes del equipo deben redactar sus mensajes de *commit* siguiendo el estándar de prefijos:

* `Docs(sección):` Para adiciones o mejoras en los archivos de documentación (Ej: `Docs(Sec-3): Redactar ecosistema de herramientas`).
* `Fix(módulo):` Para corrección de enlaces rotos, sintaxis de Markdown o errores de formato.
* `Refactor(estructura):` Para reorganización de carpetas o renombrado de archivos sin alterar el contenido teórico.
* `Changelog:` Para actualizaciones en el historial de versiones del proyecto.

> 📌 **Vinculación obligatoria con Issues:** Todo commit que cierre una tarea programada debe incluir la etiqueta correspondiente al final de su mensaje (Ej: `Closes #3`).