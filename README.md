# Reinforcement-Learning-for-time-series-forecasting
Alojamiento del código fuente y datos del proyecto Proyección del comportamiento de enlaces en redes inalámbricas LLN mediante series de tiempo aplicando algoritmos de aprendizaje por refuerzo.

En la carpeta de análisis de datos, se encuentran los scripts creados para el análisis de dispersión de las series de tiempo y su verificación.

En la carpeta llamada Diseño de experimentos se encuentra lo siguiente:
* Datos
* Datos para DDPG y RDPG
* Algoritmos (Implementaciones WFV y sin WFV)


<h1>¿Cómo usar?</h1>
-Se descarga el repositorio, y se ejecutan los scripts teniendo muy en cuenta el direccionamiento de la serie de tiempo que se quiera evaluar.
Nota: Para DDPG y RDPG en WFV es muy importante tener en cuenta los comentarios del código, ya que hay 3 scripts, y para cada script hay que importar y exportar unas series de tiempo, decargando los .csv y editándolos según las recomendaciones (borrando la columna del índice, y solo dejar la columna de los valores sin ningún título).

Cualquier duda, inquietud o aporte, contacto vía e-mail: riveracepedabrayan@gmail.com
