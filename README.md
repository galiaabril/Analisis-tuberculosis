# Análisis de Tuberculosis Mundial

Proyecto de análisis de datos desarrollado con información oficial de la Organización Mundial de la Salud (OMS), enfocado en explorar el comportamiento de la tuberculosis a nivel global, detectar patrones epidemiológicos y comparar la evolución de la enfermedad entre países y regiones a lo largo del tiempo.

## Objetivo

Transformar y analizar datos históricos de tuberculosis para generar indicadores comparables entre países, identificar tendencias relevantes y evaluar el progreso hacia los objetivos internacionales de reducción de incidencia establecidos por la ONU para 2025.

## Datos utilizados

- who.csv: registros de casos de tuberculosis reportados a la OMS por país, año, sexo, grupo de edad y tipo de diagnóstico.
  
- population.csv: población total por país y año utilizada para normalizar los datos y calcular tasas de incidencia.

## ¿Qué se hizo?

Durante el proyecto se realizó una exploración inicial de ambos datasets para revisar su estructura, tipos de variables y calidad de los datos. Posteriormente se llevó a cabo el proceso de limpieza y transformación de la información para reorganizar los registros en un formato más adecuado para análisis.

A partir de ello, los datos fueron clasificados por:

* género
* grupo de edad
* método de diagnóstico
* país y año

Con la integración de la información poblacional se calculó la tasa de incidencia por cada 100,000 habitantes, permitiendo comparar el impacto de la enfermedad entre países con diferentes tamaños de población.

Finalmente se desarrollaron visualizaciones para analizar:

* evolución de casos a través de los años
* comparación entre regiones y países
* distribución por sexo y edad
* tendencias en los distintos métodos de diagnóstico
* comportamiento de la incidencia global

## Herramientas

Google Colab • Python • Pandas • NumPy

## Autora

Galia Abril Morales — Estudiante de Finanzas
