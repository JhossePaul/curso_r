# Data Wrangling en R

## Objetivo y Descripción del curso
Este curso se enfocará a la utilización de R, bajo la filosofía *tidy data*,
para la extracción, transformación y exportación de datos desde diferentes fuentes:

 - CSV
 - Excel
 - .txt
 - Otros

"R es un lenguaje de programación interpretado, de distribución libre, bajo Licencia GNU, 
y se mantiene en un ambiente para el cómputo estadístico y gráfico..." [https://cran.r-project.org/doc/contrib/Santana_El_arte_de_programar_en_R.pdf]

Pretendemos ayudarles a conocer una herramienta más, que les facilite el manejo 
de información (tablas dinámicas, conteos y resúmenes de datos), de una manera más 
eficiente. 
Para poder aprovechar el curso es necesario tener la disposición de aprender 
algo nuevo, un pequeño *background* de programación:

 - Haber hecho una macro.
 - Utilizar funciones de BUSCARV, BUSCARH, etc...
 - Realizar tablas dinámicas en excel.
 

## Requisitos

- R (> 3.5)
- RStudio
- data.table
- lubridate
- magrittr

## Temario

- Semana 1: R y RStudio
    - Instalación
    - Introducción a R
        - ¿Por qué usar R? 
        - Benchmark (Excel vs R)
            - Runtime
            - Reproducibilidad
        - Operaciones básicas
        - Instalación de paquetes
    - Tour por RStudio
        - Panel de Script
        - Panel de código
        - Environment
        - Paneles misc.

- Semana 2: Estructuras de datos
    - Atomic vectors
    - Vectors
    - Matrix & Arrays
    - Lists
    - data.frame, data.table

- Semana 3: 
    - Operaciones vectoriales
    - Operaciones matriciales
    - Composición de funciones

- Semana 4: Importar/Exportar datos
    - read.table
    - read.csv
    - fread
    - readxl
    - openxlsx
    - rio

- Semana 5: Tidy data
    - Tidy data
    - Wide data
    - Long data
    - dcast y melt
    - merge, rbind, cbind

- Semana 6: Introducción a data.table
    - Eficiencia de data.table, copy y punteros
    - Filter
    - Select
    - Group by
    - Update

- Semana 7: Repaso y ejercicios
    - GRID
    - FOVISSSTE histórico

- Semana 8: Manipulación avanzada
    - Manipulación de fechas
    - SDcols
    - Agregaciones complejas
    - Forma funcional de asignación
    - Variables especiales
