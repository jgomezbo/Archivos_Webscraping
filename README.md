# Archivos_Webscraping
Es un programa que genera un archivo denominano "archivo.html" donde se guarda el formato html de la página "https://ocio.uncomo.com/articulo/preguntas-de-cultura-general-con-respuestas-49522.html". Posteriormente, genera un segundo archivo denominado "preguntas_scrap.txt" donde se almacena la información de la página anterior con arreglos y en general, en limpio y lista para ser usada por el proyecto, en este caso, por "Quiz Maker".

# Integrantes
  - Luis Fernando Chitiva Arévalo
  - Johan Danilo Gómez Bocanegra
  - Daniel Ricardo Quintero Moya
  
# Requisitos

El programa necesita las siguientes librerías : io, bs4, urlopen, random. Ejecutar los siguientes comandos para instalar las librerías:
  - from bs4 import BeautifulSoup
  - import io
  - from urllib.request import urlopen
  - import random
  
Librerias externas
  - bs4: pip install bs4 == 0.0.1

Ejecutar:
  - pip install -r requirements.txt
  
Los archivos se generan en la carpeta "archivos_quizmaker". Ejecutar el que se llama "webscrapping.py"
