# Análisis mediante R de datos públicos sobre casos COVID-19 en España desde el 1 de enero de 2020 (¡EN CURSO!!!)

Análisis de la evolución del número de casos detecados (curvas epidémicas) en España de la COVID-19 desde el 1 de enero de 2020.
Los datos se han descargado de la página web con los datos oficiales proporcionados por el Gobierno de España en datos.gob.es y otros enlaces. Los enclaces concretos se detallan en el propio análisis.
La información descargada no ha sufrido tratamiento alguno más allá del necesario para su análisis mediante R y dicha manipulación está visible en la documentación inluída.
A disposición de quien quiera para el uso que quiera.
Se agradecerán sugerencias para la mejora/optimización del código. Estoy aprendiendo R desde hace muy poco tiempo y estoy muy pez todavía además de arrastrar vicios de otros lenguajes aprendidos muchos años atrás ;-)
La versión "AnalisisCovidEspaña_SinCodigo.Rmd" no es más que el mismo documento "AnalisisCovidEspaña.Rmd" pero con la opción "echo=FALSE" (knitr::opts_chunk$set(echo=FALSE)). En caso de discrepancia entre las versiones, la versión más actualizada será siempre "AnalisisCovidEspaña.Rmd", que es el verdadero archivo de trabajo. La versión "_SinCodigo" no es más que una réplica la versión de trabajo con la opción de mostrar el código anulada que en algún momento en el pasado no ha estado actualizada con la activa principal correspondiente. Se advierte sobre la necesidad de comprobar la fecha de actualización antes de usar el archivo "AnalisisCovidEspaña_SinCodigo.Rmd". En caso de duda utilícese el archivo "AnalisisCovidEspaña.Rmd" y ajústese la opción "echo" a FALSE.
Se ha añadido una versión resumida para hacer más fácil el seguimiento de la evolución denominada: "AnalisisCovidEspaña_Monitor"
