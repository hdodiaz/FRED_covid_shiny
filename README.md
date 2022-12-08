# FRED_covid_shiny
Shiny App interface for FRED-covid-co

## Interfaz gráfica para ejecución del modelo **FRED-COVID-CO**

Este repositorio contiene una **Shiny App** para implementar la interfaz para el uso del modelo desarrollado para la epidemia COVID-19 en Colombia.
El modelo **FRED-COVID-CO** está basado en **FRED**, un modelo basado en agentes, originalmente diseñado para modelar epidemias de influenza, pero que ha sido adaptado, sucesivamente, para modelar la dinámica epidemiológica de varias enfermedades.

Esta interfaz fue desarrollada en el marco del proyecto **Modelo basado en agentes para evaluar estrategias de control de la epidemia COVID-19 en Colombia**, con financiación de la Vicerrectoría de Investigación de la Universidad Nacional de Colombia. En este proyecto, se desarrollaron las herramientas para poder simular la dinámica de infecciones COVID en diversas localidades de Colombia, así como las diferentes medidas farmacológicas y no farmacológicas disponibles para el control de la epidemia.

### Colaboradores

En la elaboración de esta interfaz participaron las siguientes personas:

- Hernando Díaz Morales, Universidad Nacional de Colombia

- Guido España, Notre Dame University 

- Diego Velandia, Universidad Nacional de Colombia

- Nelson Castañeda, Escuela tecnológica Instituto Técnico Central

## Shiny App Interfaz FRED-COVID

Para ejecutar FRED desde un ambiente interactivo, más amigable que la interfaz normal, basada en archivos de datos,  se creó una interfaz gráfica, basada en una **Shiny-App** ejecutable desde RStudio. De esta manera, se facilita simular diferentes alternativas  y variantes, para un modelo determinado. 

Una **Shiny App** es una aplicación interactiva, construida en `R`, utilizando el concepto básico de **programación reactiva**. Ver <https://mastering-shiny.org/index.html>.

La interfaz ha sido programada en la forma de una Shiny-App. Esta es una aplicación interactiva, basada en el paquete **shiny** de ` R.` A la interfaz la hemos denominado **FRED_covid_shiny.** 


**Atención:** toda la interfaz está programada en `R`, como una aplicación `Shiny`. Por lo tanto, se requiere tener instalado el lenguaje **R**. También se requiere tener instalados los paquetes **shiny**, **tidyverse**, **lubridate**, **plotly** y **NLP**. En caso de que alguno de estos paquetes  no esté instalado, por ejemplo el **plotly**,  basta ejecutar el comando

```
install.packages("plotly").
```

Como siempre que se trabaja en **R**, puede ser muy conveniente tener instalado **RStudio**. Sin embargo, esto no es indispensable.


### Advertencia
La aplicación puede utilizarse, de manera independiente para visualizar y estudiar resultados de experimentos  e intervenciones ya simuladas pero no puede correr nuevos experimentos, a menos que FRED esté ya instalado. 
