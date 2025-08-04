# Proyecto de Análisis de Clientes de Telecomunicaciones

Este proyecto tiene como objetivo analizar los datos de clientes de una empresa de telecomunicaciones con el fin de obtener información clave sobre su comportamiento, como patrones de cancelación, servicios contratados, duración del contrato, y otros factores relevantes. El análisis permite generar conclusiones útiles para la toma de decisiones estratégicas.

## Descripción

El proyecto se enfoca en procesar un conjunto de datos con información de clientes de una empresa de telecomunicaciones. A través de análisis estadísticos y visualizaciones gráficas, se identifican patrones en la retención o cancelación de clientes, relación entre servicios y duración del contrato, y se detectan posibles factores que inciden en la pérdida de clientes.

## Tecnologías utilizadas

- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook o Google Colab

## Uso

### Cargar los datos:

El análisis parte de un conjunto de datos cargado desde un archivo CSV (presente en el mismo directorio o montado desde Drive si se usa Google Colab). El archivo contiene variables como:

- Tipo de contrato  
- Servicios contratados (Internet, streaming, soporte técnico)  
- Duración del contrato  
- Estado del cliente (activo o cancelado)  
- Método de pago  
- Cargos mensuales y totales

### Ejecutar el análisis:

Puedes ejecutar el notebook en Jupyter Notebook o Google Colab. El análisis incluye:

- Distribución de cancelaciones por tipo de contrato  
- Análisis de servicios y su relación con la cancelación  
- Promedios de cargos mensuales por cliente  
- Visualización de correlaciones entre variables  
- Segmentación de clientes basada en características clave

### Generar las visualizaciones:

El código genera automáticamente gráficos de barras, histogramas, mapas de calor de correlaciones y gráficos de dispersión. Puedes guardar estos gráficos usando funciones de Matplotlib o Seaborn.

## Funcionalidades

- **Análisis de cancelaciones:** Permite identificar los factores asociados a la pérdida de clientes.
- **Segmentación de clientes:** Ayuda a distinguir grupos de clientes con mayor propensión a cancelar.
- **Visualizaciones claras:** Gráficos intuitivos que facilitan la interpretación de los datos.
- **Soporte para múltiples servicios:** Analiza la relación entre los servicios contratados y la duración del cliente.

## Autor

Desarrollado por [Alan Guillen](https://github.com/MickGuillen).
