# Análisis de Tarifas de Megaline

## Descripción del Proyecto
Este proyecto fue desarrollado como parte de un Bootcamp de análisis de datos. El objetivo es realizar un análisis preliminar del comportamiento de los clientes de Megaline, un operador de telecomunicaciones, para determinar cuál de sus dos tarifas de prepago (Surf o Ultimate) genera más ingresos. Utilizando una muestra de 500 clientes y datos de sus actividades en 2018, analizamos la cantidad de llamadas, mensajes y uso de datos para identificar patrones de uso y llevar a cabo pruebas estadísticas.

## Dataset
El análisis se basa en cinco tablas diferentes que contienen información sobre los usuarios, sus llamadas, mensajes de texto, uso de internet y las tarifas disponibles:

- **users**: Información general de los clientes (ID, nombre, ciudad, plan, etc.).
- **calls**: Detalles sobre las llamadas realizadas (duración, fecha, ID de usuario).
- **messages**: Registros de los SMS enviados (fecha, ID de usuario).
- **internet**: Datos sobre el uso de internet (volumen de datos, fecha, ID de usuario).
- **plans**: Detalles sobre las tarifas de prepago (nombre de la tarifa, precios, límites de minutos, SMS y datos).

## Objetivo
El departamento comercial de Megaline desea saber qué tarifa genera más ingresos para ajustar su presupuesto de publicidad. Para ello, analizamos el comportamiento de los clientes y determinamos, mediante pruebas estadísticas, qué plan aporta más ingresos en promedio.

## Herramientas Utilizadas
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy (para pruebas estadísticas)

## Instrucciones de Uso

1. Clona este repositorio:
   ```bash
   git clone https://github.com/SammEst48/tarifas-megaline.git

2. Navega al directorio del proyecto:
   ```bash
   cd analisis-tarifas-megaline
 
3. Ejecuta el notebook en Jupyter:
   ```bash
   jupyter notebook analisis_megaline.ipynb


## Conclusiones
Este análisis preliminar revela que el plan Ultimate genera más ingresos en promedio que el plan Surf y se encontró evidencia de que los ingresos promedio de los usuarios en el área de Nueva York-Nueva Jersey eran diferentes a los de otras regiones. Estos resultados proporcionan insights clave que ayudarán a Megaline a optimizar su estrategia de marketing y asignación de presupuesto.

