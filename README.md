# Análisis de Clientes y Telecomunicaciones: ConnectaTel 📡

## Objetivo del Proyecto
El objetivo principal de este análisis es evaluar el comportamiento de los usuarios de la empresa de telecomunicaciones ConnectaTel (Latinoamérica). Buscamos identificar patrones de consumo, analizar la pureza de los registros, descubrir segmentos de clientes hiper-rentables (power users) y formular recomendaciones estratégicas para optimizar la oferta entre los planes 'Básico' y 'Premium'.

## Datasets Utilizados
Los datos comprenden el registro histórico de la empresa hasta el año 2024:
* `plans.csv`: Datos de las tarifas, franquicias de llamadas y límites de gigas de cada plan.
* `users_latam.csv`: Información demográfica de los clientes (edad, ciudad, plan suscrito, fechas de registro y deserción).
* `usage.csv`: Registro de consumo detallado evento por evento (número de mensajes, volumen de llamadas y duración fraccionada).

## Etapas del Análisis
1. **Carga y Exploración preliminar**: Entendimiento de la estructura técnica y dimensionalidad de los datos.
2. **Limpieza y Preparación**: Manejo de nulos estructurales (MAR) y valores sentinela; imputación de edades nulas vía mediana estadística y limpieza de fechas futuras erróneas.
3. **Análisis Estadístico Mensualizado**: Creación de perfiles unificados por cliente calculando volumen total de uso de red.
4. **Visualización de Distribuciones**: Uso avanzado de histogramas y diagramas de caja (Boxplots) para contrastar el comportamiento de las distribuciones entre planes e identificar asimetrías.
5. **Segmentación Estratégica**: División categórica por volumen de uso (Bajo, Medio, Alto) y rango de edad (Joven, Adulto, Mayor).
6. **Informe Ejecutivo Final**: Conclusiones orientadas a stakeholders, recomendando la retención de outliers comerciales y la migración predictiva de cuentas del plan Básico.

## Cómo reproducir el análisis
Si deseas interactuar con los datos o reproducir el código del cuaderno:
1. Asegúrate de tener descargada la carpeta original de `datasets/`.
2. Clona este repositorio o descarga el archivo [.ipynb](cci:7://file:///C:/Users/rarog/Documents/Triple%2010/Sprint_7/1.ipynb:0:0-0:0).
3. Abre el archivo utilizando Jupyter Notebook o trunéalo directamente en la nube utilizando [Google Colab](https://colab.research.google.com/).
4. Ejecuta todas las celdas en el orden en el que se presentan.
