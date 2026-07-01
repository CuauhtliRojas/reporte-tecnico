# DeepShield - Informe técnico

Proyecto de titulación: Detección y localización de manipulaciones faciales deepfakes mediante segmentación semántica basada en redes neuronales convolucionales.

## Estructura

- `main.tex`: archivo maestro. No escribir contenido largo aquí.
- `capitulos/`: secciones editables del informe.
- `imagenes/`: figuras, diagramas, gráficas y logos.
- `referencias.bib`: bibliografía.
- `docs/`: documentación auxiliar del proyecto.

## Flujo recomendado

1. Editar únicamente el archivo del capítulo correspondiente.
2. Compilar `main.tex`.
3. Revisar el PDF generado.
4. Hacer commit con un mensaje claro.

## Compilación

Con latexmk:

```powershell
latexmk -pdf -interaction=nonstopmode main.tex
Sin latexmk:

pdflatex -interaction=nonstopmode main.tex
bibtex main
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
Regla de trabajo

No modificar el formato global desde los capítulos. El formato vive en main.tex.