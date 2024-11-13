# Trabajo Práctico Especial - Calidad del Vino
## Introducción
Este es el Trabajo Práctico Especial para la materia **Fundamentos de la Ciencia de Datos**. El objetivo de este proyecto es realizar un análisis exhaustivo de un dataset de calidad de vino, aplicando técnicas de limpieza de datos, análisis exploratorio, y modelado predictivo, además de proponer y validar hipótesis en base a los datos, suposiciones y resultados encontrados.

## Requisitos previos
A continuación, se indican las herramientas necesarias para ejecutar este proyecto:
- Python 3.7+: [Descarga e instalación](https://www.python.org/downloads/)
- Git: [Descarga e instalación](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Jupyter Lab: [Guía de instalación](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)
- Visual Studio Code: [Descarga e instalación](https://code.visualstudio.com/docs/)
> **Nota: Se recomienda instalar todas las herramientas anteriores antes de proceder con los siguientes pasos.**

## Guía de instalación
### 1. Descarga de los archivos necesarios
Para obtener los archivos necesarios para el proyecto, puedes optar por uno de los dos métodos siguientes:

#### A) Clonar el repositorio usando Git
Si tienes Git instalado, puedes clonar el repositorio directamente en tu máquina local. Abre una terminal, navega hasta el directorio donde deseas guardar el proyecto y ejecuta el siguiente comando:
   ```bash
       git clone https://github.com/uuulises/TPE-Hermida_Russo_Velis
   ```
#### B) Descarga directa desde GitHub
Si prefieres, puedes descargar el repositorio como un archivo ZIP:
1. Visita el [repositorio en GitHub](https://github.com/uuulises/TPE-Hermida_Russo_Velis).
2. Haz clic en el botón verde Code y selecciona Download ZIP.
3. Descomprime el archivo ZIP en la ubicación deseada en tu computadora.

### 2. Creación de un ambiente virtual
Para evitar conflictos de versiones de librerías y mantener el entorno de trabajo ordenado, se recomienda crear un ambiente virtual específico para este proyecto.
1. Abre una terminal y navega hasta la carpeta del proyecto.
2. Ejecuta el siguiente comando para crear un ambiente virtual llamado `env`:
  ```bash
       python -m venv env
   ```
3. Activa el ambiente virtual:
- En Linux o Mac:
  ```bash
       source env/bin/activate
  ```
  
- En Windows:
  ```bash
       .\env\Scripts\activate
  ```

### 3. Instalación de dependencias
Con el ambiente virtual activado, instala todas las dependencias necesarias para ejecutar el proyecto. Estas dependencias están enumeradas en el archivo `requirements.txt`. Desde la terminal, ejecuta:
  ```bash
       pip install -r requirements.txt
  ```

## 🚀 Ejecución
Una vez instaladas todas las dependencias, puedes proceder a abrir y ejecutar el análisis en `Jupyter Notebook`. Hay dos métodos recomendados: usando Jupyter Lab o Visual Studio Code.
### Método 1: Usar Jupyter Lab 
1. Con el **ambiente virtual activado**, inicia Jupyter Lab en la terminal ejecutando el siguiente comando:
  ```bash
       jupyter lab
  ```
Esto abrirá una nueva pestaña en tu navegador con el entorno de Jupyter Lab.

2. En el navegador, navega a la carpeta del proyecto y selecciona el archivo TPE.ipynb para abrirlo.
3. Para ejecutar todas las celdas de la notebook, usa la opción Run All o ejecuta cada celda individualmente para revisar el análisis paso a paso.
> **Nota: Asegurate de tener el ambiente virtual activado antes de ejecutar el comando, para que Jupyter Lab reconozca el kernel adecuado.**

### Método 2: Usar Visual Studio Code
1. Abre Visual Studio Code y navega hasta la carpeta del proyecto.
2. Asegurate de instalar las extensiones Python y Jupyter. Esto puedes hacerlo desde el icono de extensiones en la barra lateral izquierda.
3. Una vez instaladas las extensiones, abre el archivo TPE.ipynb.
4. En la parte superior de la notebook, selecciona `Run All Cells` para ejecutar el análisis completo.

## Consideraciones importantes
- Ambiente: Recuerda que siempre es importante activar el ambiente virtual antes de trabajar con la notebook para evitar problemas de compatibilidad.
- Actualización de librerías: En caso de problemas de versiones o dependencias, considera actualizar el archivo requirements.txt o reinstalar librerías específicas.
