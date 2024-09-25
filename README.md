# 📊 Análisis de Tarifas de Megaline

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de Megaline, una compañía de telecomunicaciones que ofrece dos tarifas de prepago: **Surf** y **Ultimate**. El departamento comercial de Megaline busca determinar qué tarifa genera más ingresos para optimizar su presupuesto publicitario. 

Trabajaremos con un conjunto de datos que incluye información sobre 500 clientes, sus tarifas, y el uso que hicieron de llamadas, mensajes de texto y datos en el año 2018. Este análisis preliminar nos permitirá identificar cuál de los planes aporta más ingresos y cómo varía el uso de servicios entre las dos tarifas.

Además, se realizarán pruebas estadísticas para comprobar si el ingreso promedio entre las tarifas y las regiones difiere significativamente.

## Objetivos

- Analizar el comportamiento de los clientes y su uso de llamadas, SMS y datos.
- Calcular los ingresos generados por cada cliente.
- Determinar, mediante análisis estadístico, cuál de las dos tarifas genera mayores ingresos en promedio.
- Evaluar si los ingresos varían según la región geográfica.

## Estructura del proyecto

1. Preparación de los Datos
2. Cálculos por Usuario
3. Análisis del Comportamiento del Cliente
4. Pruebas de Hipótesis
5. Conclusión

## Datasets

Trabajaremos con cinco tablas:

1. **users**: Información sobre los clientes (ID, nombre, ciudad, plan, etc.).
2. **calls**: Datos sobre las llamadas (ID, fecha, duración, usuario).
3. **messages**: Datos sobre los SMS (ID, fecha, usuario).
4. **internet**: Uso de datos (ID, volumen de datos, fecha, usuario).
5. **plans**: Detalles sobre las tarifas de prepago (nombre del plan, precios, límites, costos adicionales).

## Librerías necesarias

- pandas, numpy, matplotlib, seaborn, scipy (para pruebas estadísticas)

## Instrucciones para Ejecutar el Proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tuusuario/megaline-tariff-analysis.git



