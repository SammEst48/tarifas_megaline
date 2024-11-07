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

## Datasets

Trabajaremos con cinco tablas:

1. **users**: Información sobre los clientes (ID, nombre, ciudad, plan, etc.).
2. **calls**: Datos sobre las llamadas (ID, fecha, duración, usuario).
3. **messages**: Datos sobre los SMS (ID, fecha, usuario).
4. **internet**: Uso de datos (ID, volumen de datos, fecha, usuario).
5. **plans**: Detalles sobre las tarifas de prepago (nombre del plan, precios, límites, costos adicionales).

## Herramientas utilizadas 
- **Python**: pandas, numpy, math, scipy, matplotlib, seaborn.
- **Jupyter Notebooks**: para análisis interactivo.

## Pasos de análisis
- **Preparación de los datos**: se convertienten los datos a los tipos necesarios, se encuentra y corrigen errores, se calculan las métricas mensuales para cada usuario (llamadas, SMS, datos e ingresos).
- **Analizar los datos**: se describe el comportamiento de los clientes en función de las métricas mensuales, calculando la media, varianza y desviación estándar, y visualizando las distribuciones.
- **Probar las hipótesis**: se determina si hay diferencia significativa en los ingresos promedio entre los usuarios de las dos tarifas, y si el ingreso promedio de los usuarios del área de Nueva York-Nueva Jersey es diferente al de otras regiones.

## Conclusiones
Finalmente, se concluye que, aunque la media del ingreso generado por el plan Ultimate es ligeramente superior al plan Surf, no se encuentran diferencias significativas en el ingreso promedio entre los usuarios de ambos planes. Se concluye que la empresa podría optimizar sus estrategias de publicidad y marketing teniendo en cuenta el comportamiento del usuario en cada plan y el perfil de cada uno.

**Nota**: Este proyecto fue desarrollado como parte de mi formación en el bootcamp de Tripleten en el área de análisis de datos.

## Visualizaciones
![output](https://github.com/user-attachments/assets/f7540ec1-1483-44a6-b2de-3517e4ed9325)
![surf](https://github.com/user-attachments/assets/8b3a7be1-b923-477b-8eaf-ce5f78d6c301)
![ultimate](https://github.com/user-attachments/assets/5ba7ec84-ce1d-46a5-a3ab-fc0cf9131bf5)


