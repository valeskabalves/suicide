# Objetivo

El objetivo de este trabajo es desarrollar un dashboard interactivo dirigido a investigadores y profesionales de la salud que trabajan en la prevención del suicidio y el apoyo psicológico. Este dashboard tiene como objetivo proporcionar información detallada sobre las tendencias y variaciones de las tasas de suicidio a lo largo del tiempo, con el fin de ayudar en la toma de decisiones y en la implementación de políticas eficaces de prevención.

## Audiencia

**Destinatarios**: El dashboard está destinado a investigadores y profesionales de la salud pública que trabajan directamente en la prevención del suicidio y el apoyo psicológico.

**Nivel de Conocimiento**: Se supone que los destinatarios tienen conocimientos en salud pública, prevención del suicidio y una familiaridad básica con gráficos e interpretación de datos.

**Plataforma Principal y Contexto de Uso**: El dashboard se utilizará principalmente en plataformas digitales, con acceso regular y periódico para el seguimiento continuo de las tendencias y el análisis de datos relacionados con las tasas de suicidio.

## Preguntas a Resolver con la Visualización

1. **Tendencias Temporales**: ¿Cuáles son las tendencias temporales de las tasas de suicidio en diferentes países durante los últimos años?
2. **Variación por Grupos de Edad y Género**: ¿Cómo varían las tasas de suicidio entre los diferentes grupos de edad y género en cada país?
3. **Picos y Caídas**: ¿Qué países tienen los mayores picos o caídas en las tasas de suicidio y en qué años ocurrieron estos eventos?
4. **Correlaciones Significativas**: ¿Existen correlaciones significativas entre las tasas de suicidio de diferentes grupos de edad o entre géneros?
5. **Valores Atípicos**: ¿Cuáles son los valores atípicos en las tasas de suicidio y qué países y años están asociados con estos valores atípicos?
6. **Impacto de Políticas de Prevención**: ¿Las políticas de prevención del suicidio implementadas en ciertos años resultaron en cambios significativos en las tasas de suicidio?

El dashboard desarrollado tiene como objetivo proporcionar respuestas claras y visualmente accesibles a estas preguntas, utilizando datos recientes y relevantes para apoyar el análisis y la acción de los profesionales involucrados en la prevención del suicidio.

## Estructura del Proyecto

El proyecto se organiza en las siguientes carpetas principales:

Datos: Contiene los archivos de datos utilizados en el análisis.
- filtered_df.csv: Datos filtrados para visualizaciones y análisis.

Dashboard: Archivos para la creación y configuración del dashboard interactivo.
- dashboard.Rmd: Código para generar el dashboard con flexdashboard y shiny.
- app.R: Archivo principal de la aplicación Shiny.

Informe: Informe técnico detallado en formato R Markdown.
- informe.Rmd: Contiene análisis, gráficos y conclusiones, compilado en HTML y PDF.

Presentación: Archivos para la presentación del informe y hallazgos en diapositivas.
- presentacion.Rmd: Genera una presentación interactiva en PowerPoint.

### Cómo Ejecutar el Proyecto

1.	Preparar el Entorno: Instalar R, RStudio y las bibliotecas necesarias 
(tidyverse, knitr, kableExtra, flextable, officer, ggplot2, flexdashboard, shiny).

2.	Cargar los Datos: Colocar los archivos de datos en la carpeta Datos.

3.	Generar el Dashboard: Abrir dashboard.Rmd en RStudio y compilarlo.

4.	Crear el Informe: Compilar informe.Rmd para generar el informe en HTML/PDF.

5.	Preparar la Presentación: Compilar presentacion.Rmd para generar la 
presentación en PowerPoint.

6.	Desplegar la Aplicación Shiny: Usar app.R para desplegar el dashboard en un 
servidor Shiny.

Este README proporciona una visión general de la estructura del proyecto y las 
instrucciones para ejecutar y utilizar los diferentes componentes del mismo.