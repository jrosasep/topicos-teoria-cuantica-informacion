# Tópicos de Teoría Cuántica de la Información

Apunte personal en desarrollo del curso **Tópicos de Teoría Cuántica de la Información**, Universidad de Concepción, semestre 1 de 2026.

**Autor:** José Ignacio Rosas  
**Profesor del curso:** Aldo Patricio Delgado

Este repositorio contiene el código fuente en LaTeX y una versión compilada en PDF del apunte. El documento no corresponde a un material oficial del curso; es una reorganización personal de notas de clase, bibliografía y desarrollos complementarios.

## Estado actual

La versión actual incluye contenidos sobre:

- preliminares y notación de mecánica cuántica;
- postulados de la mecánica cuántica;
- mediciones, ensambles y operador densidad;
- teorema de no-cloning;
- estados de Bell;
- teleportación cuántica e intercambio de entrelazamiento;
- mediciones generalizadas, POVM y canales cuánticos;
- separabilidad, criterio PPT, negatividad, LOCC y construcción por techo convexo.

El apunte sigue en revisión, especialmente en redacción, consistencia de notación, figuras TikZ, referencias internas y bibliografía.

## Estructura del repositorio

```text
.
├── main.tex
├── preamble.tex
├── frontmatter.tex
├── bibliografia.tex
├── logo_udec_vertical.png
├── topicos-teoria-cuantica-informacion.pdf
├── README.md
└── chapters/
    ├── 00_introduccion.tex
    ├── 01_postulados_de_la_mecanica_cuantica.tex
    ├── 02_medicion_ensambles_y_operador_densidad.tex
    ├── 03_teorema_de_no_cloning.tex
    ├── 04_estados_de_bell.tex
    ├── 05_teleportacion_cuantica_experimental_e_intercambio_de_entrelazamiento.tex
    ├── 06_mediciones_generalizadas_povm_y_canales_cuanticos.tex
    ├── 07_separabilidad_transposicion_parcial_y_criterio_ppt.tex
    └── 08_entrelazamiento_locc_y_techo_convexo.tex
```

El archivo principal es `main.tex`. Los capítulos se encuentran separados en `chapters/`, de modo que pueden editarse de manera independiente.

## Compilación

Para compilar el documento completo:

```bash
latexmk -pdf main.tex
```

También puede compilarse con `pdflatex`, ejecutándolo más de una vez para actualizar índice y referencias:

```bash
pdflatex main.tex
pdflatex main.tex
```

El proyecto puede importarse directamente en Overleaf manteniendo la misma estructura de carpetas.

## Agradecimientos y asistencia

Agradezco al profesor **Aldo Patricio Delgado** por las clases del curso y por facilitar los artículos en los cuales se basa parte importante de este apunte.

Este material también fue desarrollado con asistencia de **ChatGPT Plus** y **Claude Pro**, usados como apoyo para la organización del documento, redacción en LaTeX, revisión local de consistencia matemática y edición de figuras en TikZ. En particular, Claude Pro fue utilizado para modificar figuras TikZ y revisar el capítulo de preliminares.

El contenido final fue revisado y editado por el autor. La responsabilidad por el texto, las omisiones y posibles errores remanentes corresponde al autor.
