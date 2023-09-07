# Métodos Numéricos II 2023

Este curso es continuación de los temas estudiados en Métodos Numéricos 1. En esta materia, se estudian o revisan temas no introductorios de algoritmos para cálculo científico y aplicado y su implementación computacional. Se estudian tres grandes temas: 

(1) Álgebra lineal computacional, 
(2) Optimización numérica continua, 
(3) Optimización discreta. 

La primera parte el curso se enfoca en temas sobre cálculo de autovalores y autovectores, y la solución eficiente de sistemas lineales. En el segundo bloque, el bloque principal del curso, introduce los temas de optimización numérica, principalmente los métodos de gradiente y punto interior, así como métodos de la familia de gradiente conjugado y métodos quasi-Newton. El tema culmina haciendo un estudio de la teoría de optimización restricta, particularmente programación lineal y programación cuadrática. Finalmente, en el tercer bloque, hacemos una introducción a algunos métodos de optimización combinatoria y discreta. 

**Importante!!** El curso cuenta con una parte práctica extensiva, en la que el estudiante implementará en código computacional cada uno de los algoritmos estudiados. Parte fundamental del curso consiste en utilizar las herramientas aprendidas en varios proyectos aplicados donde se trabajará con datos reales y comunicar los resultados mediante reportes técnicos y seminarios.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los temas:
* Cálculo vectorial
* Álgebra lineal (teoría)
* Algunos elementos de análisis (convergencia de secuencias y series, análisis en Rn)
* Métodos numéricos para una variable (*root finding*, *fitting*, *numerical differentiation and integration*)
* Un curso de Programación.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-opt2023.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes de 19:50 a 21:25 CIT-501, y Jueves de 19:50 a 21:25 CIT-414.

### Office Hours
<div id='id-office'/>

* Viernes de 18:00 a 19:00.

# Material del curso
<div id='id-material'/>

 **No.**  | **Fecha**    | **Tópicos**                                                               | **Recursos**
 -------- | ------------ | ------------------------------------------------------------------------- |  ---------------------------------
  01      | 04.07.2023   | Introducción al curso. Normas matriciales. [Aula 01](aulas/Aula01.pdf){:target="_blank"} | Trefethen-Bau, Lecture 3. 
  02      | 06.07.2023   | Ejemplo de norma 2. Conceptos: kernel, nulidad, rango. [Aula 02](aulas/Aula02.pdf){:target="_blank"} | Trefethen-Bau, Lecture 3. <br/> [norms.ipynb](code/norms.ipynb){:target="_blank"} 
  03      | 11.07.2023   | Descomposición espectral. <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Trefethen-Bau, Lecture 4. <br/> [spectral.ipynb](code/spectral.ipynb){:target="_blank"}
  04      | 13.07.2023   | Descomposición en valores singulares (SVD). <br/> [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Trefethen-Bau, Lecture 5. <br/> [svd.ipynb](code/svd.ipynb){:target="_blank"}
  05      | 18.07.2023   | Aplicaciones de la SVD: PCA. <br/> [Aula 05a](aulas/Aula05a.pdf){:target="_blank"} [Aula 05b](aulas/Aula05b.pdf){:target="_blank"} | 
  06      | 20.07.2023   | Aplicaciones de SVD: Aproximaciones de bajo rango, compresión de imágenes. | [compression.ipynb](code/compression.ipynb){:target="_blank"} <br/> [SVD Compression Demo]([code/svd.ipynb](http://timbaumann.info/svd-image-compression-demo/)){:target="_blank"}
  L1      | 18.07.2023   |   | [Lista 01](listas/lista01.pdf){:target="_blank"} <br/> **Fecha de entrega: martes 01 de agosto.** 
  07      | 25.07.2023   | Estabilidad y condicionamiento. Número de condición. [Aula 06a](aulas/Aula06a.pdf){:target="_blank"} [Aula 06b](aulas/Aula06b.pdf){:target="_blank"} | Trefethen-Bau, Lectures 13-15.
  08      | 27.07.2023   | Eliminación gaussiana. Factoración $LU$ y $PA = LU$. Aplicaciones. [Aula 07](aulas/Aula07.pdf){:target="_blank"} | Trefethen-Bau, Lecture 6.
  09      | 01.08.2023   | Técnicas de Pivoteo. <br/> [Aula 08](aulas/Aula08.pdf){:target="_blank"} | Trefethen-Bau, Lecture 6. <br/> Burden-Faires, Cap. 6. 
  10      | 01.08.2023   | Tipos especiales de matrices. Factoración LL^T y LDL^T. <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Trefethen-Bau, Lecture 23. <br/> Burden-Faires, Cap. 6. 
  11      | 03.08.2023   | Matrices positivas definidas. Matrix positiva más cercana. Aplicación de la descomposición de Cholesky. | [cholesky.ipynb](code/cholesky.ipynb){:target="_blank"} <br/> [generate_gaussian.ipynb](code/generate_gaussian.ipynb){:target="_blank"} 
  12      | 08.08.2023   | Métodos iterativos para sistemas lineales. [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Quarteroni *et al.*, Cap. 4. 
  L2      | 08.08.2023   |   | [Lista 02](listas/lista02.pdf){:target="_blank"} <br/> **Fecha de entrega: viernes 25 de agosto.** 
  13      | 17.08.2023   | Proyectores. Factoración QR. <br/> [Aula 11](aulas/Aula11.pdf){:target="_blank"} | Trefethen-Bau, Lectures 6-8 y 10. 
  14      | 22.08.2023   | Cálculo de autovalores. El método de las Potencias. <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"} | Trefethen-Bau, Lecture 27. 
  15      | 24.08.2023   | Cálculo de autovalores. El método QR. <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"} | Trefethen-Bau, Lectures 26, 28. 
  16      | 24.08.2023   | Matrices ralas. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} | 
  L3      | 29.08.2023   |   | [Lista 03](listas/lista03.pdf){:target="_blank"} <br/> **Fecha de entrega: lunes 12 de septiembre.** 
  17      | 31.08.2023   | Fundamentos de optimización. <br/>  | 
  18      | 05.09.2023   | Derivadas vectoriales y matriciales.  |  
  19      | 07.09.2023   |   |  
  
# Proyectos
<div id='id-proyectos'/>

En el curso se desarrollarán dos proyectos, los cuales se indicarán más adelante.


**No.**  | **Fecha**    | **Tópicos**                                   | **Recursos**
-------- | ------------ | --------------------------------------------- |  -------------------------------------
 1       | 29.08.2023   | Proyecto 1 - *Spectral Clustering*.           | [Proyecto 1](proyectos/proyecto1.pdf){:target="_blank"} <br/> **Fecha de Entrega: jueves 28 de septiembre.** <br/> [plane_half.png](proyectos/plane_half.png){:target="_blank"}
 


# Referencias
<div id='id-ref'/>

### Textos:

* [L. Trefethen, L. Bau III (1997). *Numerical Linear Algebra*.](http://library.lol/main/079EA6C3FD8CDF23B0C2ACD901CA9A26){:target="_blank"}

* [J. Nocedal, S. Wright (2006). *Numerical Optimization*.](http://library.lol/main/7016B74CFE6DC64C75864322EE4AA081){:target="_blank"}

* [D. Luenberger, Y. Ye (2016). *Linear and Nonlinear Programming*.](http://library.lol/main/EB915E0FDCC8D3BA222B37C9A3DD6B4F){:target="_blank"}

### Referencias adicionales:

* [R. Burden, A. Burden, D. J. Faires (2017). *Análisis numérico.*](http://library.lol/main/87525D7D988D11F87963D6832EAA9493){:target="_blank"}

* [G. Golub, C. Van Loan (2012). *Matrix Computations*.](http://library.lol/main/72562A3A733C2E842BE163CA97D0FA7A){:target="_blank"}

* [A. Quarteroni, R. Sacco, F. Saleri (2000). *Numerical Mathematics*.](http://library.lol/main/7D136BC80ECBF0BA65798EC129FCCAF4){:target="_blank"}

* [J. Stoer, R. Bulirsch (2002). *Introduction to Numerical Analysis*.](http://library.lol/main/04B36CA585EB49F5FDED7479823F2B50){:target="_blank"}

* [A. Izmailov, M. Solodov (2014). *Newton-type for Optimization and Variational Problems*.](http://library.lol/main/C8C3ED2461D9C8C2608595B223ABDD91){:target="_blank"}

* [S. Boyd, L. Vandenberghe (2009). *Convex Optimization*.](http://library.lol/main/A9A5D9C3CA105DB0F41AF39A6C89706C){:target="_blank"}

* [C. Meyer (2001). *Matrix Analysis and Applied Linear Algebra*.](http://library.lol/main/7EF368F2EA42EB4E48F09EA438C1822E){:target="_blank"}

---
