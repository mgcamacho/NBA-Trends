# Análisis de datos de la NBA

Este proyecto tiene el propósito de analizar algunos datos sobre los partidos de la NBA (National Basketball Association) en las temporadas 2010 y 2014, usando las bibliotecas pandas, numpy, scipy, matplotlib y seaborn. Se exploran aspectos como los puntos anotados por los equipos, la diferencia de medias entre ellos, la relación entre el resultado del partido y la ubicación del mismo, y la correlación entre la diferencia de puntos y el pronóstico de victoria.

## Requisitos previos

Para ejecutar este proyecto se necesita:

- Python 3.8 o superior
- Las bibliotecas pandas, numpy, scipy, matplotlib y seaborn
- El archivo nba_games.csv que contiene los datos de los partidos

## Instalación y ejecución

Para instalar las bibliotecas se puede usar el siguiente comando:

```bash
pip install pandas numpy scipy matplotlib seaborn
python nba_analysis.py
```

## Resultados

Algunos de los resultados obtenidos con el análisis son:

- La diferencia de medias entre los puntos anotados por los equipos Knicks y Nets en la temporada 2010 fue de 9.73 puntos a favor de los Knicks.
- La distribución de los puntos anotados por ambos equipos en la temporada 2010 se muestra en el siguiente histograma:

![Histograma 2010]

- La diferencia de medias entre los puntos anotados por los equipos Knicks y Nets en la temporada 2014 fue de 0.45 puntos a favor de los Knicks.
- La distribución de los puntos anotados por ambos equipos en la temporada 2014 se muestra en el siguiente histograma:

![Histograma 2014]

- El diagrama de caja que compara los puntos anotados por todos los equipos en la temporada 2010 se muestra a continuación:

![Diagrama de caja]

- La tabla de contingencia que muestra la frecuencia del resultado del partido (ganar o perder) según la ubicación del mismo (local o visitante) es la siguiente:

| game_result | A      | H      |
| ----------- | ------ | ------ |
| L           | 133    | 105    |
| W           | 92     | 120    |


- La prueba chi-cuadrado indica que hay una asociación significativa entre el resultado del partido y la ubicación del mismo (chi2 = 6.50, p < 0.001).
- La correlación entre la diferencia de puntos y el pronóstico de victoria es 0.08, lo que indica una relación lineal positiva muy débil entre ambas variables.
- La diferencia de puntos y el pronóstico de victoria tienen una correlación positiva moderada (r = 0.44), que es estadísticamente significativa (p < 0.001). Esto significa que cuando el pronóstico de victoria es alto, la diferencia de puntos suele ser alta también, y viceversa.
- El diagrama de dispersión que muestra la relación entre la diferencia de puntos y el pronóstico de victoria se muestra a continuación:

## Contribución

Si te interesa este proyecto y quieres contribuir con tu código, ideas o comentarios, puedes hacerlo de las siguientes formas:

- Crear un issue en el repositorio para reportar un error, hacer una pregunta o proponer una mejora.
- Hacer un fork del repositorio y crear una pull request con tus cambios o aportes.
- Contactarme por email o por redes sociales para darme tu feedback o compartir tu experiencia.

## Reconocimientos

Quiero agradecer a:

- La página 538 por proporcionar los datos de los partidos de la NBA "The Complete History of the NBA".
