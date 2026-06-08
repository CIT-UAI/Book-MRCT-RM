# Guía Técnica MRCT

Repositorio del libro digital **Guía Técnica MRCT: Para la Construcción de la Matriz de Resiliencia Climática Territorial**, desarrollado por el Centro de Inteligencia Territorial.

El proyecto está construido como un libro Quarto y organiza la metodología para estimar, integrar y comunicar la Matriz de Resiliencia Climática Territorial (MRCT).

## Contenido

El libro sigue una secuencia metodológica:

1. Introducción
2. Región de estudio y unidades de análisis
3. Insumos satelitales e índices espectrales
4. Indicadores base
5. Vector de estado ecosistémico y línea base
6. Trayectoria del estado sistémico
7. Integración espacial
8. Sensibilidad del sistema
9. Síntesis de resiliencia territorial
10. Trabajo de terreno, validación e integración
11. Conclusiones

La configuración principal del libro está en `_quarto.yml`. Los capítulos fuente están en archivos `.qmd` en la raíz del repositorio.

## Estructura del repositorio

- `_quarto.yml`: configuración del libro Quarto.
- `index.qmd`: prefacio y portada del libro.
- `*.qmd`: capítulos y secciones del libro.
- `references.bib`: bibliografía.
- `style.css`: estilos personalizados para la salida HTML.
- `images/`: imágenes e insumos gráficos usados por el libro.
- `docs/`: salida HTML renderizada, configurada como `output-dir` para publicación.

## Requisitos

Para trabajar con el libro se requiere:

- Quarto
- R y/o Python, según los bloques ejecutables usados en los capítulos
- RStudio o un editor compatible con Quarto, opcional

## Uso

Previsualizar el libro localmente:

```bash
quarto preview
```

Renderizar la versión HTML completa:

```bash
quarto render
```

El resultado se escribe en `docs/`, de acuerdo con la configuración del proyecto.

## Publicación

Antes de publicar, el proyecto debe estar vinculado a un repositorio de GitHub.

Para publicar el libro, ejecutar:

```bash
quarto publish
```

Luego seleccionar la opción **GitHub Pages** cuando Quarto solicite el destino de publicación.

El libro también está preparado para renderizarse en `docs/`, de acuerdo con `output-dir: docs` en `_quarto.yml`.

## Autores

- John Treimun Ríos, Centro de Inteligencia Territorial
- Denis Berroeta González, Centro de Inteligencia Territorial
