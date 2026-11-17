# Análisis del desempeño de operadores en telecomunicaciones

## 1. Contexto

Una empresa de telecomunicaciones busca evaluar el desempeño de sus operadores para identificar posibles ineficiencias en la atención de llamadas y mejorar la calidad del servicio.

El proyecto analiza información relacionada con llamadas entrantes y salientes, llamadas atendidas y perdidas, duración de las llamadas, tiempos de espera e identificadores de operadores.

El objetivo fue identificar operadores con indicadores de desempeño desfavorables, establecer criterios para detectar posibles ineficiencias y comprobar estadísticamente las diferencias entre grupos de operadores.

## 2. Mi contribución

Desarrollé un análisis integral de los datos que incluyó:

- Exploración, limpieza y revisión de la estructura de los conjuntos de datos.
- Análisis de llamadas entrantes y salientes, atendidas y perdidas.
- Cálculo de indicadores de desempeño, como la tasa de llamadas perdidas y el tiempo de espera.
- Identificación de operadores con indicadores desfavorables mediante valores de referencia.
- Comparación del desempeño entre grupos de operadores.
- Aplicación de pruebas estadísticas para evaluar diferencias significativas.
- Interpretación de resultados y elaboración de recomendaciones de negocio.

## 3. Metodología y decisiones técnicas

El proyecto se desarrolló en cuatro etapas:

**Análisis exploratorio de datos (EDA)**

Se examinaron los conjuntos de datos para comprender su estructura, identificar valores ausentes, revisar los tipos de variables y explorar el comportamiento de las llamadas.

Se analizaron las llamadas por dirección, estado de atención, duración y operador, con especial atención a las llamadas entrantes perdidas y sus tiempos de espera.

**Identificación de indicadores de desempeño**

Se calcularon indicadores para evaluar el desempeño de los operadores, principalmente:

- Tasa de llamadas perdidas.
- Tiempo de espera de las llamadas entrantes.

Se establecieron valores de referencia a partir de la distribución de los datos, con el propósito de identificar operadores que presentaran resultados desfavorables en ambos indicadores.

**Análisis comparativo y pruebas de hipótesis**

Se identificaron 65 operadores que superaron simultáneamente los valores de referencia establecidos.

Posteriormente, se compararon grupos de operadores con diferentes niveles de desempeño mediante pruebas estadísticas, para determinar si existían diferencias significativas en los indicadores analizados.

**Interpretación y recomendaciones**

Se interpretaron los resultados obtenidos para identificar posibles áreas de mejora en la operación y proponer acciones orientadas a optimizar la atención de llamadas.

## 4. Resultados principales

**Identificación de operadores**

Se identificaron 65 operadores que presentaron simultáneamente una tasa de llamadas perdidas superior al valor de referencia de 1.364% y un tiempo de espera superior a 327.23 segundos.

**Evaluación estadística**

Se realizaron pruebas de hipótesis para comparar los indicadores de desempeño entre los grupos de operadores.

Los resultados obtenidos fueron:

| Indicador | Valor p |
|---|---:|
| Tasa de llamadas perdidas | 0.000183 |
| Tiempo de espera | 0.000183 |

Ambos valores p fueron inferiores al nivel de significancia de 0.05, por lo que se rechazaron las hipótesis nulas y se encontraron diferencias estadísticamente significativas entre los grupos analizados.

## 5. Conclusiones e impacto potencial en el negocio

Los resultados permitieron identificar operadores con indicadores que podrían representar áreas de oportunidad en la atención de llamadas.

El análisis muestra la importancia de monitorear conjuntamente la tasa de llamadas perdidas y el tiempo de espera, ya que ambos indicadores aportan información relevante sobre el desempeño operativo.

Se recomienda:

- Revisar la carga de trabajo de los operadores con indicadores desfavorables.
- Dar seguimiento periódico a la tasa de llamadas perdidas y los tiempos de espera.
- Optimizar la distribución de llamadas para evitar posibles sobrecargas.
- Considerar acciones de capacitación y redistribución de actividades cuando sea necesario.

Este análisis puede servir como punto de partida para implementar estrategias de mejora operativa y fortalecer la calidad del servicio al cliente.

## 6. Herramientas y tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook
- Tableau Public

## 7. Evidencia del proyecto

- **Dashboard interactivo:** [Visualizar en Tableau Public](https://public.tableau.com/app/profile/lorena.torres.sojo/viz/Proyecto_Final_Telecomunicaciones/Dashboard2?publish=yes)
- **Presentación del proyecto:** https://github.com/lorenasojo/An-lisis-del-desempe-o-de-operadores-/blob/main/Presentacion%20del%20desempe%C3%B1o%20de%20operadores.pdf
- **Repositorio de GitHub:**https://github.com/lorenasojo/Analisis-de-operadores

