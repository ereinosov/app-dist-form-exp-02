# GA-EXP-02 FORM

**Coevaluación de exposiciones: informe del evaluador sobre la exposición EXP-1**

![UTEQ](https://img.shields.io/badge/UTEQ-Ingenier%C3%ADa%20de%20Software-1f4e79)
![Asignatura](https://img.shields.io/badge/Asignatura-Aplicaciones%20Distribuidas-2e7d32)
![Tema](https://img.shields.io/badge/Tema-T7%20Computaci%C3%B3n%20paralela-6a1b9a)
![LaTeX](https://img.shields.io/badge/LaTeX-pdflatex-b71c1c)

---

Actividad formativa individual de Aplicaciones Distribuidas (ISR-701), 7.º nivel, paralelo A, SPA 2026–2027. Informe de coevaluación de la exposición EXP-1 (GA-SUM-02) del 26 de noviembre de 2026: una sección por equipo observado, con nivel y evidencia por dimensión (D1 a D6), nota sugerida con su cuenta y retroalimentación. Equipo evaluado en esta sesión: GGHL (T7, Computación paralela, 08:30 a 09:00).

- Autor: Eduardo David Reinoso Vélez (ereinosov), equipo propio: Grupo 2 (LMRT)
- Docente: Gleiston Cicerón Guerrero Ulloa, PhD
- Cierre: 26 de noviembre de 2026, 23:59
- Repositorio: https://github.com/ereinosov/app-dist-form-exp-02

## Estructura

```
app-dist-form-exp-02/
├── informe.tex       # Archivo principal del informe (Bloques 1 a 4, anexo y declaración de IA)
├── informe.pdf       # PDF compilado
├── hojas_campo/      # Captura de la hoja de campo digital de cada equipo (notas originales, sin corregir)
├── .gitignore
└── README.md
```

Las hojas de campo se tomaron en un archivo digital (Bloc de notas) durante la sesión, que se siguió por Google Meet. En clase el docente no exigió hacerlas a mano: propuso tener la transmisión de Meet abierta y usar un bloc de notas.

## Compilación

Requisitos: MiKTeX o TeX Live con `pdflatex`. El informe no usa bibliografía, así que no requiere `biber`. Entorno de referencia: Windows, MiKTeX 25.12, TeXstudio.

Desde la carpeta raíz del repositorio, ejecutar en este orden:

```
pdflatex informe.tex
pdflatex informe.tex
```

El resultado es `informe.pdf`. `informe.tex` carga los paquetes inputenc, fontenc, babel (spanish), geometry, amsmath, booktabs, array y xcolor; MiKTeX instala los que falten automáticamente y en TeX Live se instalan a mano con `tlmgr`.
