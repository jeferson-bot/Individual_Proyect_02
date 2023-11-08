<p align="center">
 <img src="imagenes\OIG.jpg" alt="Telecomunicaciones" width="1200" height="600">
</p>

<h1 align="center">Analisis de Datos de Telecomunicaciones</h1>

<p align="center">
En este proyecto, una empresa de telecomunicaciones me ha encargado la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. <br>
La principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el comportamiento asociado al resto de los servicios de comunicación. <br>
El objetivo es orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.<br>
Para ello, se han identificado los siguientes desafíos y oportunidades en el sector de las telecomunicaciones: <br>
<br>
- El sector de telecomunicaciones está experimentando una demanda de servicios sin precedentes, lo que requiere de una constante innovación e inversión <br>
- Las empresas de telecomunicaciones necesitan implementar la analítica avanzada para tomar decisiones más inteligentes sobre la complejidad de sus redes <br>
<br>
El análisis realizado en este proyecto buscará abordar estos desafíos y oportunidades, proporcionando a la empresa una visión clara del comportamiento del sector de las telecomunicaciones y orientándola en su estrategia de crecimiento y expansión. <br>
El análisis se realiza utilizando Python y Jupyter Notebooks. <br>
</p>

<br>

<p align="center">
 <img src="imagenes\OIG2.jpg" alt="br" width="1200" height="50">
</p>

<br>

<h2 align="center">Estructura del Proyecto</h2>

<p align="center">
El proyecto se estructura en Jupyter Notebooks, centrado en un aspecto específico del análisis. El cuaderno principal que contiene la mayor parte del análisis es:
<a href="E_D_A_(Exploratory_Data_Analysis)/e_d_a.ipynb">
<p align="center">(Análisis Exploratorio de Datos)</p>
</a>
</p>

<br>

<h2 align="center">Proceso de Análisis Exploratorio de Datos</h2>

<p align="center">
Este cuaderno contiene el análisis exploratorio de los datos de telecomunicaciones.<br>
Primero se cargan y limpian los datos, eliminando las columnas irrelevantes y manejando adecuadamente los valores faltantes.<br>
Los datos limpios se analizan para obtener información sobre varios aspectos de las telecomunicaciones, esto incluye: <br>

<p align="center"><strong>Análisis del acceso a Internet por cada 100 hogares en diferentes provincias</strong><br>

</p>

<p align="center">
<img src="imagenes\promedio_acceso_100_hogares_provincia.png" alt="Accesos" width="1200" height="600">
</p>

<p align="center">Representamos el promedio de acceso a internet por cada 100 hogares en diferentes provincias, esto con el fin de comparar la disponibilidad o uso de este servicio en diferentes provincias.<br>
Las provincias podrían estar representadas en el eje x, y el promedio de acceso en el eje y.<br>
Las diferencias en las alturas de las barras entre las provincias representan diferencias en el acceso a Internet.</p>

<p align="center">Identificación de provincias con penetración de Internet por debajo del 60%, que se consideran áreas potenciales para mejorar el servicio</p>

<p align="center"><strong>promedio de penetracion de internet inferior al 60%</strong></p>

<center>

| Provincia           | Media de accesos por cada 100 hogares |
| ------------------- | ------------------------------------- |
| Catamarca           | 36.737500                             |
| Chaco               | 33.472778                             |
| Chubut              | 53.114444                             |
| Corrientes          | 35.597778                             |
| Entre Ríos          | 51.164444                             |
| Formosa             | 26.581389                             |
| Jujuy               | 35.920000                             |
| La Rioja            | 42.564444                             |
| Mendoza             | 37.265000                             |
| Misiones            | 35.512222                             |
| Río Negro           | 53.567500                             |
| Salta               | 41.886667                             |
| San Juan            | 33.618333                             |
| San Luis            | 44.339722                             |
| Santa Cruz          | 32.937778                             |
| Santiago Del Estero | 32.591944                             |
| Tucumán             | 44.124167                             |

</center>

<br>

<p align="center"><strong> Mejorar la penetración de internet en estas provincias puede tener varias ventajas</strong></p>

<br>

<p align="center">
Por un lado, puede ayudar a reducir la brecha digital, mejorando el acceso a la información y las oportunidades para la educación y el empleo.<br>
Por otro lado, puede beneficiar a las empresas que buscan expandirse a nuevas regiones, ya que una mayor penetración de internet puede indicar una mayor demanda de servicios digitales.</p>

<br>

<p align="center">
Además, las provincias con una penetración de internet por debajo del 60% pueden presentar oportunidades para la inversión en infraestructura de internet.<br>
Por ejemplo, podrían ser candidatas para recibir fondos de inversión para mejorar la infraestructura de internet.<br>
podrían tener mayores oportunidades para recibir subvenciones o programas de apoyo para mejorar el acceso a internet.</p>

<br>

<p align="center">
Visualización de datos para rastrear cambios a lo largo del tiempo e identificar eventos específicos que podrían haber influido en el acceso a Internet.</p>

<p align="center"><strong>Este grafico representa el Crecimiento Porcentual Año a Año de las Tecnologías</strong></p>

<br>

<p align="center">
<img src="imagenes\Crecimiento_Porcentual_Año_a_Año_de_las_Tecnologías.png" alt="Accesos" width="1200" height="600">
</p>

<p align="center">
El cuaderno concluye con los datos limpios guardados como un archivo CSV para su uso posterior en Power BI.</p>

<br>

<p align="center">
 <img src="imagenes\OIG2.jpg" alt="br" width="1200" height="50">
</p>

<br>

<h2 align= "center">Datos</h2>

<br>

<p align="center">
Los datos utilizados en este proyecto son una colección de datos de telecomunicaciones, fueron extraidos de la pagina de ENACOM.<br>
Incluyen información sobre el acceso a Internet y su uso en diferentes regiones. Los datos se almacenan en varios archivos XLSX, para luego ser transformados en archivos CSV.<br>
se cargan en los cuadernos Jupyter para su análisis.</p>

<br>

<h2 align= "center">Librerías Utilizadas</h2>

<p align="center">
El proyecto utiliza varias bibliotecas de Python para el análisis de datos y la visualización</p>

<p align="center">import pandas as pd</p>
<p align="center">import numpy as np</p>
<p align="center">import matplotlib.ticker as ticker</p>
<p align="center">import matplotlib.pyplot as plt</p>
<p align="center">import matplotlib.cm as cm</p>
<p align="center">import matplotlib.colors as colors</p>
<p align="center">import random</p>
<p align="center">import seaborn as sns</p>
<p align="center">import csv </p>
<p align="center">import warnings</p>

<br>

<h2 align= "center">Conclusion</h2>

<p align="center">
Este proyecto proporciona valiosos conocimientos sobre el estado de las telecomunicaciones en diferentes regiones.<br>
Los resultados del análisis se pueden utilizar para identificar áreas para mejorar el servicio y para rastrear cambios en el acceso a Internet a lo largo del tiempo.<br>
Los datos limpios y procesados también se guardan para un análisis más profundo en Power BI.</p>

<h2 align= "center">Contato</h2>

<br>

<p align="center">"Estoy a tu disposición para cualquier consulta, sugerencia o simplemente para establecer una comunicación contigo. Puedes ponerte en contacto conmigo de las siguientes maneras:"</p>
<br>
<p align="center">Correo Electrónico: [jeffersson2210@gmail.com](mailto:jeffersson2210@gmail.com)</p>

<p align="center">LinkedIn: [Jeferson Tonetto mogollon](https://www.linkedin.com/in/jeferson-tonetto-mogollon-09ba311b0/)</p>

<br>

<p align="center">
 <img src="imagenes\OIG1.jpg" alt="Infinito" width="1200" height="550">
</p>
