<p align="left">
   <img src="https://img.shields.io/badge/STATUS-Completado-green">
</p>

<h1 align="center">Múltiples comparaciones con el método LSD de Fisher </h1>

<p>Este método, propuesto por primera vez por Fisher en 1935, cuyas siglas en inglés significan: Least Significant Difference (LSD), permite comparar la media de tres o más grupos o tratamientos. </p>

<p>La idea principal del LSD es calcular la diferencia significativa más pequeña entre dos medias como si estas medias hubieran sido las únicas medias a comparar y declarar significativa cualquier diferencia mayor que el LSD. Es básicamente una extensión de la prueba t de Student.</p>

<p>Esta técnica sólo se puede utilizar si el test anova F es significativo, es decir, si las medias de todos los grupos o tratamientos son diferentes, en otras palabras, se rechaza la hipótesis nula de igualdad entre medias.</p>

<p>La diferencia entre dos medias se declara significativa en cualquier nivel de significación deseado si supera el valor derivado de la fórmula general:</p>

<p align="center">
   <img src="img/formula1.png" width="400" height="150">
</p>

<p>Donde la Ho se rechaza si: |t| ≥ tα/2 con grados de libertad (dentro de grupos) y MSE (error medio cuadrático dentro de grupos). Por lo tanto, se puede escribir de la siguiente manera, siendo lo mismo: </p>

<p align="center">
   <img src="img/formula2.png" width="500" height="150">
</p>

<p>La finalidad de este ejercicio, es aprovechar la ventaja de cálculo comparativa del LSD de Fisher, cuando solo se dispone de los promedios, desviación y tamaño de cada grupo o tratamiento y no de la data completa. Para ello se realizó en el framework de Pyscript que permite incorporar el lenguaje de python en una página HTML y así tener mayor facilidad para realizar los cálculos.</p>

<p>La página la pueden probar en el siguente link: https://estebanlab2021.github.io/lsd_fisher/</p>

<p><b>NOTA</b>: Recargar la página cada vez que inicien un nuevo cálculo.</p>
