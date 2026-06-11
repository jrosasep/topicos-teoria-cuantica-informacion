# Quantum Information

Apunte en desarrollo del curso **Tópicos de Teoría Cuántica de la Información**  
**Universidad de Concepción — semestre 1 de 2026**

**Profesor:** Aldo Patricio Delgado  
**Autor:** José Ignacio Rosas

---

## Descripción

Este repositorio contiene un apunte personal en desarrollo, elaborado a partir de las clases del curso **Tópicos de Teoría Cuántica de la Información** dictado durante el **semestre 1 de 2026** en la **Universidad de Concepción**.

La idea de este proyecto es reunir, reorganizar y redactar de manera progresiva los contenidos del curso en un formato más sistemático, claro y útil para estudio. El apunte está todavía **incompleto**, por lo que irá cambiando con el tiempo a medida que se agreguen nuevas secciones, correcciones, figuras y comentarios.

---

## Origen y proceso de elaboración

El documento se construyó a partir de apuntes tomados en clases y transcritos a **LaTeX**, complementados con la bibliografía citada. En su edición se utilizó **ChatGPT Plus, modelo GPT-5.5 Thinking**, como apoyo para ordenar la redacción, revisar explicaciones y ajustar figuras en TikZ. La revisión y responsabilidad final del contenido corresponden al autor.

---

## Estado del proyecto

**Versión en revisión.** La versión actual incorpora material hasta la última clase del curso (26-05-2026) incluida en el documento y contiene, además de la base introductoria, secciones avanzadas sobre mediciones generalizadas, canales cuánticos, separabilidad y operaciones locales.

Antes de considerar el apunte como una versión cerrada, quedan pendientes revisiones de:

- redacción y consistencia de notación;
- demostraciones y cálculos incorporados desde las notas de clase;
- fidelidad de las explicaciones respecto de los artículos originales;
- figuras TikZ, pies de figura y referencias internas;
- bibliografía y atribución de material complementario.

---

## Contenidos actuales

### Fundamentos de mecánica cuántica

- postulados de la mecánica cuántica;
- estados, evolución temporal y mediciones;
- sistemas compuestos;
- ensambles, operador densidad y formulación moderna de los postulados.

### Información cuántica y no-clonación

- qubits, fase relativa y esfera de Bloch;
- estados de Bell y transformaciones locales mediante operadores de Pauli;
- teorema de no-clonación;
- propuesta FLASH y comunicación superlumínica;
- clonado cuántico aproximado y restricción de no señalización.

### Protocolos ópticos

- teleportación cuántica;
- realización experimental con fotones;
- conversión paramétrica descendente tipo II;
- medición parcial en la base de Bell;
- coincidencias experimentales;
- intercambio de entrelazamiento.

### Mediciones y dinámica abierta

- mediciones generalizadas y POVM;
- operadores de Kraus y estados posteriores a la medición;
- canales cuánticos al ignorar el resultado de una medición.

### Entrelazamiento y operaciones locales

- estados separables y estados entrelazados;
- transposición parcial y criterio PPT de Peres--Horodecki;
- negatividad y norma traza;
- convexidad y mezcla clásica de estados;
- operaciones locales y comunicación clásica (LOCC);
- operaciones elementales en la realización de un canal local.

---

## Artículos discutidos

Entre las fuentes empleadas para desarrollar el apunte se encuentran:

- N. Herbert, *FLASH—A Superluminal Communicator Based Upon a New Kind of Quantum Measurement*, **Foundations of Physics** 12, 1171–1179 (1982).
- W. K. Wootters y W. H. Zurek, *A single quantum cannot be cloned*, **Nature** 299, 802–803 (1982).
- V. Bužek y M. Hillery, *Quantum copying: Beyond the no-cloning theorem*, **Physical Review A** 54, 1844–1852 (1996).
- N. Gisin, *Quantum cloning without signaling*, **Physics Letters A** 242, 1–3 (1998).
- D. Bouwmeester, J.-W. Pan, K. Mattle, M. Eibl, H. Weinfurter y A. Zeilinger, *Experimental quantum teleportation*, **Nature** 390, 575–579 (1997).

---

## Archivos principales

```text
topicos-de-la-teoria-cuantica-de-la-informacion.tex
topicos-de-la-teoria-cuantica-de-la-informacion.pdf
logo_udec_vertical.png
README.md
```

La portada fue reformulada en un estilo institucional para la presentación del apunte como material de apoyo al curso. Los antiguos recursos gráficos asociados a apéndices eliminados no son necesarios para compilar la versión actual, salvo que se reincorporen esas secciones en el futuro.

---

## Compilación

El documento puede compilarse localmente con `latexmk`:

```bash
latexmk -pdf topicos-de-la-teoria-cuantica-de-la-informacion.tex
```

Alternativamente, puede compilarse con `pdflatex`; se recomienda ejecutarlo más de una vez para actualizar correctamente el índice y las referencias internas:

```bash
pdflatex topicos-de-la-teoria-cuantica-de-la-informacion.tex
pdflatex topicos-de-la-teoria-cuantica-de-la-informacion.tex
```

También puede importarse el proyecto directamente en **Overleaf**, manteniendo el archivo `.tex` y los recursos gráficos requeridos en la misma carpeta del proyecto.

---
