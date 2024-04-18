<!-- PROJECT SHIELDS -->
[![Colaboradores][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Estrellas][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">Formatos de Tareas PUCE</h3>
  <p align="center">
    Formato de LaTeX para la elaboración de tareas de estudiantes de la PUCE.  
    <br />
    <a href="https://github.com/andres-merino/Formato-Tareas-PUCE/issues">Reportar un Problema</a>
    ·
    <a href="https://github.com/andres-merino/Formato-Tareas-PUCE/issues">Solicitar cambio</a>
    <br />
    Abrir en 
    <br />
    <a href="https://www.overleaf.com/read/vhdczzsymytd#3bf1e4">
    <img src="https://img.shields.io/badge/Overleaf-47A141?logo=overleaf&logoColor=fff&style=for-the-badge" alt="Overleaf Badge">
    </a>
  </p>
</div>



## Sobre el Proyecto

En este proyecto se proporciona un formato de LaTeX para la elaboración de tareas de estudiantes de la Pontificia Universidad Católica del Ecuador. Este formato usa la línea gráfica de la universidad y sus lineamientos en lo que respecta a bibliografía. Incluye ambientes para la creación de ejercicios, problemas, soluciones, código entre otros. 


### Construido con

[![LaTeX][LaTeX]][LaTeX-url]


## Descripción

Se proporcionan dos ejemplos, el primero es un ejemplo de una tarea tipo ensayo donde se indica como incluir imágenes, tablas y código, además de las formas de citar y la inclusión de bibliografía. El segundo ejemplo es la resolución de un problema de matemáticas, donde se incluyen el enunciado y su solución.

Para el formato del título, se utiliza los paquetes [`titling`](https://ctan.org/pkg/titling) y [`authblk`](https://ctan.org/pkg/authblk). 

Se usa el tipo de letra Montserrat mediante el paquete [`montserrat`](https://ctan.org/pkg/montserrat) (en el caso de compilación LaTeX o pdfLaTeX) y [`fontspec`](https://ctan.org/pkg/fontspec) (en el caso de compilación XeLaTeX).

De fondo de cada página se utiliza el archivo `HojaMembretada.pdf` que contiene la línea gráfica de la universidad.

Para la bibliografía, se utiliza el paquete [`biblatex`](https://ctan.org/pkg/biblatex) con el estilo `apa`, añadiendo configuraciones adecuadas para el español.

Se definen el ambientes `ejer` para escribir los enunciados de los ejercicios. Para definir más ambientes, se puede incluir el siguiente código:

```latex
\newtheorem{ejer}{Ejercicio}
    \tcolorboxenvironment{ejer}{%
        color=colordef,recuadrost,colback=colordef!7,drop fuzzy shadow
    }
```

### Pruebas

Este proyecto se ha probado con Tex Live 2023 sin problemas.

## Últimos cambios

```
- 2024-04-18
   - Se agrega el proyecto a GitHub para inicio de control de versiones.
```

## Créditos

Andrés Merino\
[Proyecto Alephsub0](https://www.alephsub0.org/about/),\
Docente Investigador\
Pontificia Universidad Católica del Ecuador\
aemerinot@gmail.com\
[![LinkedIn][linkedin-shield]][linkedin-url-aemt]

## Licencia

Distribuido bajo la licencia MIT. 

[![MIT License][license-shield]][license-url]




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[contributors-url]: https://github.com/andres-merino/Formato-Tareas-PUCE/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[forks-url]: https://github.com/andres-merino/Formato-Tareas-PUCE/forks
[stars-shield]: https://img.shields.io/github/stars/andres-merino/Formato-Tareas-PUCE?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[issues-url]: https://github.com/andres-merino/Formato-Tareas-PUCE/issues
[license-shield]: https://img.shields.io/github/license/andres-merino/Formato-Tareas-PUCE.svg?style=for-the-badge
[license-url]: https://es.wikipedia.org/wiki/Licencia_MIT
[linkedin-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-aemt]: https://www.linkedin.com/in/andrés-merino-010a9b12b/
[LaTeX]: https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=fff&style=for-the-badge
[LaTeX-url]: https://www.latex-project.org/