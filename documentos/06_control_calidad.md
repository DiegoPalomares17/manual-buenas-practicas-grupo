# 📘 Sección 6: Control de Calidad, Revisión y Presentación

## 6.1 Auditoría de Calidad Previa a Entregas
Para asegurar que todo documento entregado por el equipo cumpla con los máximos estándares académicos y técnicos, ningún archivo se considera "listo para entrega" sin haber superado una auditoría de revisión cruzada por parte de un integrante distinto al autor principal ([Schwaber y Sutherland, 2020](../referencias/referencias_bibliograficas.md#ref-scrum-2020)).

---

## 6.2 Lista de Chequeo (Checklist) Pre-Entrega
Antes de realizar la fusión final a la rama `main` y proceder a la exportación, el equipo debe verificar el cumplimiento de los siguientes puntos:

### 1. Revisión Redaccional y Ortográfica
* [ ] **Cero errores ortográficos y gramaticales:** Lectura completa asistida por correctores del editor (VS Code CodeSpell / Languagetool).
* [ ] **Tono y estilo uniforme:** Redacción en tercera persona o voz impersonal académica a lo largo de todo el texto.
* [ ] **Claridad sintáctica:** Uso de oraciones cortas, párrafos estructurados y lenguaje técnico preciso.

### 2. Consistencia de Formato y Markdown
* [ ] **Jerarquía de títulos impecable:** Uso ordenado de `#`, `##` y `###` sin saltar niveles de encabezado.
* [ ] **Estilo APA 7 respetado:** Tablas minimalistas con encabezados claros y figuras etiquetadas correctamente.
* [ ] **Bloques de código delimitados:** Sintaxis de comandos e instrucciones formateadas dentro de bloques ` ``` `.

### 3. Integridad de Fuentes y Enlaces
* [ ] **Citas pareadas:** Toda cita en el texto `([Autor, Año])` cuenta con su ficha correspondiente en `referencias_bibliograficas.md`.
* [ ] **Hipervínculos funcionales:** Comprobación de que todas las rutas relativas (`../referencias/...#ref-id`) abran correctamente sin errores 404.
* [ ] **URLs públicas:** Los enlaces del catálogo bibliográfico apuntan a sitios estables y accesibles sin credenciales.

### 4. Presentación y Exportación a PDF
* [ ] **Compilación exitosa:** Exportación limpia desde Markdown a PDF utilizando Pandoc, Markdown PDF (Extensión VS Code) o la vista previa oficial.
* [ ] **Paginación y márgenes:** Verificación visual de márgenes (2.54 cm) y saltos de página adecuados (evitando títulos huérfanos al final de página).

---

## 6.3 Protocolo de Presentación Final
Una vez validada la lista de chequeo:
1. Se firma la revisión del Pull Request en GitHub.
2. Se genera la versión distribuible en PDF desde la rama principal `main`.
3. Se almacena el artefacto final en la carpeta de entregas acordada con su correspondiente número de versión (`v1.0`).