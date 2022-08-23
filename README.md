# Introducción a Python y análisis exploratorio de datos

La estadística trata sobre la recolección, organización, análisis e interpretación de datos, es por ello que la estadística es esencial para el correcto análisis de datos. 

Existen dos grandes conjuntos de herramientas para analizar datos:

**Análisis Exploratorio de Datos (EDA)**: Consiste en resúmenes numéricos como la media, moda, desviación estándar, rangos intercuartiles, etc (esto se conoce también como estadística descriptiva). Además hace énfasis en el uso de métodos visuales para inspeccionar los datos, como por ejemplo histogramas y gráficos de dispersión.

**Estadística Inferencial**: Consiste en usar datos para generar enunciados que exceden los propios datos. A veces esto implica realizar predicciones, a veces entender los detalles de algún fenómeno en particular o elegir entre varias explicaciones plausibles.

> El foco de este curso está en aprender a usar Python en el contexto del análisis exploratorio de datos.

## A quienes está dirijido?

Este es un curso introductorio para personas sin conocimiento previo de programación o estadística. En el curso veremos una introducción a Python y a las librerías Numpy, Scipy, Matplotlib, Seaborn y Pandas.

## Cómo usar este material

* Versión estática: Al hacer click en los archivos que se muestran arriba (los que terminan en ipynb) podrás leer una versión estática del material. Es decir podrás ver el texto y las figuras pero no podrás modificarlos, ni interactuar con el material.

* Versión interactiva online [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Grupo-de-modelado-probabilista/python_eda/HEAD).

* Versión interactiva local. También es posible descargar el material y ejecutarlo en tu propia computadora. Para ello has click [acá](https://github.com/Grupo-de-modelado-probabilista/python_eda/archive/refs/heads/main.zip) y sigue las instrucciones de la próxima sección (Instalación).


## Instalación
Para usar este material es necesario tener instalado Python. Se recomienda la versión 3.9 o superior. Además es necesario instalar los siguientes paquetes:

* NumPy 1.22.4
* SciPy 1.9
* Matplotlib 3.5.1
* Seaborn 0.11.1
* Pandas 1.4.2
* Ipython 8.3
* Jupyter 1.0.0

Se recomienda instalar primero [Anaconda](https://www.anaconda.com/products/distribution). Luego instalar el resto de los paquetes con el comando:

```bash
conda env create -f environment.yml
```

Este creará un ambiente que nos permite aislar los paquetes y sus versiones que vamos a utilizar durante el curso.
De esta forma, no se altera la versión de los paquetes que se usa para otras aplicaciones.

Para activar el ambiente debemos hacer:

```bash
conda activate python_eda
```

Ahora, podemos ejecutar todas las notebooks del curso y trabajar de forma local.
Cuando queramos desactivar el ambiente, utilizamos:

```bash
conda deactivate
```

## Contribuciones
Todo el contenido de este repositorio es abierto, esto quiere decir que cualquier persona interesada puede contribuir al mismo. Todas las contribuciones serán bien recibidas incluyendo:

* Correcciones ortográficas
* Nuevas figuras
* Correcciones en el código Python, incluidas mejoras de estilo
* Mejores ejemplos
* Mejores explicaciones 
* Correcciones de errores conceptuales

La forma de contribuir es vía Github, es decir los cambios deberán ser hechos en forma de _pull requests_ y los problemas/bugs deberán reportarse como _Issues_.

