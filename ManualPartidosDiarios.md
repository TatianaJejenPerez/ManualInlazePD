
![badge](Imagenes/inlaze_logo2.webp)

# Manual Partidos Diarios

## índice

- [Manual Programación de Partidos](#manual-reporte-gestores)
  - [índice](#índice)
  - [1. Recursos](#1-recursos)
    - [Aliados de trabajo y herramientas](#aliados-de-trabajo-y-herramientas)
    - [Fuentes de trabajo](#fuentes-de-trabajo)
  - [2. Herramienta](#2-herramienta)
    - [Filtros](#filtros)
    - [Tablas programación de partidos](#tablas-programación-de-partidos)
    - [Ejemplos de filtro ](#ejemplos-de-filtro)
  - [3. Datos a tener en cuenta para las posibles estrategias](#3-datos-a-tener-en-cuenta-para-las-posibles-estrategias)
    - [Conclusiones Competencias](#conclusiones-competencias)
  - [4.Reglas para Construcción de Indicadores](#4-reglas-para-construcción-de-indicadores)
  - [5. Contacto](#5-contacto)

## 1. Recursos

### Aliados de trabajo y herramientas

![Imagenes/aliadosyherramientas.png](Imagenes/aliadosyherramientas.png)

[índice](#índice)

### Fuentes de trabajo

- La principal fuente de este tablero es la base que nos proporciona una API específicamente de fútbol en la cual encontraremos fechas de futuros partidos. Es de tener en cuenta que el API no es en tiempo real y que tarda en actualizar un promedio de 2 a 3 días las nuevas competencias o nuevos partidos programados según los resultados de cada encuentro.
- La segunda base es el histórico con el que cuenta la compañía, con el cual podemos proyectar las intenciones de apuestas por competencia y equipo usando (Leads, FTD y CPA). 
- Tendencia deportivas, se investiga por competencia cuales son más populares para proyectar una intencion de apuesta más acertada.


[índice](#índice)


## 2. Herramienta

**(Tablero Power BI)**

![Imagenes/presentac.png](Imagenes/presentac.png)



### Filtros 

Se genera la creación de un filtro flotante por fechas para que se puede seleccionar una o varias fechas según los partidos que se quieran visualizar.adicional ayudara a una forma más rapida de navegacion.

![Imagenes/filtro.png](Imagenes/filtro.png)

[índice](#índice)

### Tablas programación de partidos

En estas tablas se podrá visualizar los partidos que se juegan hoy, mañana o están próximos a jugar junto con las proyecciones de leads, FTD y CPA que puede causar cada uno.

Es importante que tengan en cuenta que la tabla número 3 que se puede ver en la siguiente imagen está porcentuada de manera general porque están todas las fechas. Esto quiere decir que para ver el impacto puntual de los partidos se debe seleccionar en el filtro la fecha que se quiere validar y así nos dará el porcentaje real de los partidos que se jugarán.

![Imagenes/tablas.png](Imagenes/tablas.png)

### Ejemplos de filtro 

Esta seria la manera correcta de filtrar para poder visualizar el impacto exacto que puede tener un partido segun la fecha a validar

![Imagenes/ejemplodefiltro.gif](Imagenes/ejemplodefiltro.gif)


[índice](#índice)

## 3. Datos a tener en cuenta para las posibles estrategias

Tendencia de poularidad para las competencias  tanto en Colombia como en Brasil (Estos fueron unos de los porcentajes usados para dimencionar las proyecciones)

![Imagenes/tendenciaporcompetencia.png](Imagenes/tendenciaporcompetencia.png)

### Conclusiones Competencias

Basandonos en algunos articulos e investigaciones podemos concluir que :


**- Premier League (Inglaterra)**

- La liga más vista y apostada en el mundo.
- Equipos como Manchester City, Liverpool, Arsenal y Manchester United generan millones en apuestas.

**-UEFA Champions League**

- La élite del fútbol europeo, con partidos de alto nivel y apuestas masivas.
- Eliminatorias y finales tienen picos enormes de apuestas.

**- La Liga (España)**

- Equipos como Real Madrid y Barcelona atraen muchas apuestas.
- Menos partidos igualados que la Premier, pero sigue siendo muy apostada.

**- Serie A (Italia)**

- Equipos históricos como Juventus, Inter y AC Milan generan interés.
- La liga ha vuelto a ganar popularidad en apuestas en los últimos años.

**- Bundesliga (Alemania)**

- Bayern Múnich domina, pero la competitividad de equipos como Dortmund y  Leverkusen mantiene el interés.
- Liga de muchos goles, lo que favorece apuestas en mercados como "Más de 2.5 goles".

**- Libertadores (Sudamérica)**

- El torneo de clubes más importante de América.
- Apuestas altas en equipos brasileños y argentinos, además de partidos de eliminación directa.

**-Ligue 1 (Francia)**

- Dominada por el PSG, pero con equipos competitivos como Marsella y Mónaco.
- Menos atractiva para apostadores en comparación con otras ligas top.

**-Brasileirão Serie A (Brasil)**

- Liga muy seguida en Sudamérica y Europa, con partidos impredecibles.
- Apuestas populares en goles y tarjetas debido al ritmo intenso del fútbol brasileño.

**-Eredivisie (Países Bajos)**

- Competición ofensiva, ideal para apuestas en goles.
- Equipos como Ajax, PSV y Feyenoord generan mayor volumen de apuestas.

**-Championship (Inglaterra, Segunda División)**

- Torneo con partidos muy parejos, lo que lo hace atractivo para apostadores que buscan cuotas altas.

**-Primeira Liga (Portugal)**

- Equipos como Benfica, Porto y Sporting dominan.
- No es tan apostada fuera de Portugal, pero ofrece buenos mercados.

**- European Championship (Eurocopa) (solo cuando se juega)**

- En años de Eurocopa, las apuestas suben considerablemente.
- Fase de grupos y eliminatorias generan apuestas similares a la Champions.


[índice](#índice)

## 4. Reglas para Construcción de Indicadores


-  Fútbol por investigación de mercado de apuestas en Colombia y Brasil (86 y 85 % respectivamente).

- Fecha del partido = que se usa para proyectar Fecha deposito y - 3 días.
  
- Intención de Leads, FTD y CPAs debido al evento futbolístico (se toma historico de Leads, FTD y CPAs por día y se calcula segun partidos y equipos que jugaron ese mismo día ).  
  
- Comportamiento histórico por equipo, si era local o visitante y tipo de competencia, acorde a intención anterior.
  
- Castigar la probabilidad de la intención por competencia más apostada en mercado y por total de partidos por fecha (para evitar duplicar los Leads, FTD y CPA).
  
- Eso genera automáticamente un árbol de decisión por deposito, encuentro, competencia, local-visitante, equipo de fútbol.
  

[índice](#índice)

## 5. Contacto

Para sugerencias,dudas o peticiones contactar a el siguiente correo (Equipo BI):

*a.jejen@inlaze.com*



                                                    2025 © Inlaze