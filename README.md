# Primer_Desafio_TelecomX
Proyecto  TelecomX para investigar causas del churn en esta empresa


# Desafio_TelecomX
La empresa de telecomunicaciones Telecom X, tiene como objetivo entregar servicios de telefonía, Internet y streaming. En su operación se ha dado cuenta que existe una fuga de clientes y necesita en primer lugar cuantificar a cuánto asciende este churn o evasión de clientes.

Por otra parte, necesita conocer las causas de este abandono de clientes, con el objeto de tomar medidas para evitar que sus clientes se vayan a la competencia. Para ello, nuestro desafío será recopilar, procesar y analizar los datos de la empresa Telecom X, para realizar los análisis necesarios y de allí extraer información valiosa.

Objetivo.
El objetivo principal es recopilar, procesar y analizar datos de clientes. Con ello, se obtuvieron insights que ayudarán al equipo de Data Science a desarrollar modelos predictivos y estrategias efectivas para reducir la tasa de churn.

Desarrollo de  Actividades
Para realizar la tarea indicada se utilizó codigo Python y  sus bibliotecas (pandas, numpy, matplotlib, seaborn, scipy, requests, json).

a) Carga y exploración inicial del dataset: Carga del dataset desde una fuente externa (JSON) , luego se efectuó su  normalización  para facilitar el análisis. Se realiza una exploración inicial para entender la composición de los datos.

b) Limpieza y transformacion de datos: SE comenzó con el manejo de valores nulos y transformaciones necesarias, como mapeo de variables categóricas a numéricas para preparar los datos, revisar si existian filas duplicadas, etc.

c) Creacion de la columna Cuentas diarias, con el objeto de ver el gast diario qu tienen los clientes

Análisis de los datos:
En primer lugar se efectuó la descripcion mediante graficos de las diferentes columnas del dataframe.

Luego se visualizaron las variables numericas y categoricas que influyen en el churn ( abandono de clientes)
para ello, se utilizaron matriz de correlacion para variables numericas y la prube V de Crámer, para variables categoricas.

Finalmente se caracterizaron los servicios contratados por los clientes que abandonan a TelecomX

Recomendaciones para evitar el abandono de clientes (Churn)
Se efectuarob varias recomendaciones, a la luz de la interpretacion de los graficos prsentados.

Herramientas y bibliotecas utilizadas
Python
-pandas
-numpy
requests
-pprint
-matplotlib
-pyplot
-seaborn
-json
-scipy.stats  chi2_contingency

Principales hallazgos.
Los clientes que abandonan a telecom X:
** Contratan Servicio telefónico, Servicio Internet fibra óptica.
** No contratan servicios adicionales de internet ni de Streaming.
** Pagan con cheque electrónico.
** Tienen contrato mes a mes.



