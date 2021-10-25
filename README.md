
# Modelo de Clasificación Para La Prevención Del Fraude

Nuestra empresa opera en un mercado digital en donde la mayoría de los usuarios residen en Latinoamérica, región en donde el riesgo de fraude duplica el promedio europeo. Realidad que llevada a plataformas en donde la volumetría de transacciones y usuarios es significativa, dan pie a que los cibercriminales y demás actores del fraude se sientan atraídos.

Ante este contexto vemos necesario desde el equipo responsable de la prevención del fraude, habilitar soluciones que permitan dar respuesta a los retos expuestos, agregando valor a nuestras operaciones y clientes

## Comenzando 🚀

Para la ejecución del modelo se debe tener en cuenta que está dividido en 2 componentes, el primero en R y el segundo en python. _Esto se realizó intencionalmente para evidenciar el conocimiento en ambos lenguajes para efectos del challenge_, a continuación el detalle:

1. "Archivo Preprocesamiento.rmd" : contiene  los analisis premilinares sobre los datos en R y bajo extensión markdown. Este codigo consume la data virgen del archivo "Fraud Dataset  - Data .csv" hace las trasnformaciones requeridas y luego entrega como salida el archivo "Data-Limpia.csv"

2. "Archivo "Modelamiento-Inferencia.ipynb: Responsable de consumir el archivo "Data-Limpia.csv" entrega el paso anterior y ejecutar las fases de modelamiento y evaluación.

### Pre-requisitos 📋

A continuación dejo unas instrucciones te permitirán obtener una copia del proyecto en ambiente local:

a. Ubicarse en el directorio-carpeta donde se desea almacenar el repositorio.

b. Click derecho y seleccionar la opcion _"Git Bash Here"_. Esto va abrir una ventana en modo bash instanciando de una vez el directorio destino.

c. Una vez allí, escribimos la siguiente instrucción **"git clone https://github.com/sebas-arboleda/Modelo-Prevencion-del-Fraude"**.

d. Luego, ejecutado lo anterior iniciara la descarga del repositorio para que pueda ser utilizado.


## Construido con

Finalmente describo a continuación los software y librerias utilizados para el desarrollo del modelo:

***Herramientas***

* [R](https://cran.r-project.org/bin/windows/base/) - Utilizado para el análisis descriptivo y transformaciones de los datos. versión 4.1.1.
* [RStudio](https://www.rstudio.com/products/rstudio/download/) - IDE para el uso de R.
* [Python](https://www.python.org/downloads/) - Lenguaje para el modelamiento y la inferencia. Versión 3.8.5.
* [VS Code](https://code.visualstudio.com/download) - IDE para el uso de python.

***Librerias de R***

[tidyverse()](https://tidyverse.tidyverse.org),
[dplyr()](https://github.com/tidyverse/dplyr),
[corrplot()](https://github.com/taiyun/corrplot) y
[psych()](https://personality-project.org/r/psych/)

***Librerias de Python***

[Sklearn](https://scikit-learn.org/stable/),
[MinMaxScaler()](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html),
[accuracy_score()](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html) y
[fbeta_scor()](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.fbeta_score.html) 



## Autores

* **Juan Sebastián Arboleda** - [sebas-arboleda](https://github.com/sebas-arboleda) - sebastianarboled@hotmail.com

## Expresiones de Gratitud 🎁

Agradecer al equipo de prevención del fraude, por la oportunidad que me brindan. Espero podamos co-crear juntos en el futuro. 



---
[M.Sc. Juan Sebastián Arboleda](https://www.linkedin.com/in/juan-sebasti%C3%A1n-arboleda-restrepo-67512041/) - Data Scientist 😊
