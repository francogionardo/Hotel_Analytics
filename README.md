<h1 align='center'>
 <b>Proyecto  Final</b>
</h1>


***
<h1 align='center'>
<b>Hoteles 🏨🥂🏝</b>
</h1>

<p align="center">
  <img src="Image/logo.png" />
</p>

***
Nuestra empresa de Consultoría, Data Wise Solutions DWS, se especializa en la organización, clasificación y procesamiento de los datos proporcionados por nuestros clientes, generando informes completos y detallados. En esta ocasión, nuestro compromiso es brindar un enfoque analítico integral para extraer información valiosa de los datos, con el objetivo de ofrecer a nuestros clientes una visión clara y precisa del estado actual de su negocio.

### **Contexto**
***
En esta ocasión, llevamos a cabo un análisis exhaustivo de los comentarios y reseñas proporcionados por los usuarios de diversos hoteles. El objetivo principal es identificar las áreas en las que los clientes han expresado su insatisfacción o preocupación en relación con los servicios ofrecidos. Para lograrlo, empleamos técnicas de análisis de sentimientos mediante el uso de la biblioteca VADER (Valence Aware Dictionary and sEntiment Reasoner) y la librería FastText. La meta es generar tópicos o temáticas clave a partir de esta información, con el propósito de ofrecer recomendaciones valiosas a nuestro cliente.

<p align="center">
  <img src="Image/dash3.jpg" />
</p>


El panel de control muestra una parte del modelo de machine learning. Mediante el análisis de sentimientos llevado a cabo, calculamos un índice de satisfacción del cliente utilizando una fórmula DAX. Esto nos brinda la capacidad de evaluar el nivel de satisfacción de los usuarios de los hoteles en relación con los servicios ofrecidos, considerando los comentarios proporcionados por los mismos.


Además, analizamos otras métricas cruciales, como la calificación por estado o ciudad, que nos proporciona una visión de las evaluaciones dadas por los usuarios. Asimismo, examinamos la distribución del rating, permitiéndonos comprender el nivel de satisfacción de los usuarios en una escala que va del 1 al 5.





<p align="center">
  <img src="Image/dash4.jpg" />
</p>



Por otro lado, también es viable examinar tanto la calificación por hotel como el sentimiento asociado, ya sea positivo, negativo o neutro. Esto proporciona una perspectiva valiosa sobre cómo los usuarios están evaluando su cadena hotelera, y si es necesario implementar mejoras con el fin de elevar el rating o índice de satisfacción general.


### **Objetivo General**
***
* Para este proyecto se plantea conocer los principales aspectos de la industria hotelera en Estados Unidos, además de analizar las reseñas de los usuarios usando un modelo de ML.
  
### **Objetivo Específicos**
***
* Por medio del  diagrama de arquitectura explicar el flujo del dato.
* Entender cómo se cargan los datos a Google Cloud desde su origen.
* Hacer una demostración de carga incremental en el Datawarehouse.
* Presentar un  dashboard en PowerBI con KPI’s del caso de estudio.
* Dar a conocer algunos hallazgos relevantes adicionales.

  
***
### ⌛KPI's
***
Los indicadores de desempeño que se emplearon para analizar la información son los siguientes:

1. **Índice de Satisfacción del Cliente**: Evalúa la satisfacción general de los usuarios en relación con los productos/servicios mediante el análisis de los sentimientos expresados en las reseñas proporcionadas.
2. **Promedio de Rating por Ciudad o Estado**:
Calcula el promedio de los valores de 'rating' para analizar cómo califican los usuarios los hoteles en diferentes ciudades o estados.
3. **Distribución de Ratings**: Analiza la distribución de los valores de 'rating' para entender la proporción de reseñas positivas, neutrales y negativas.
4.	**Promedio de Rating por Hotel**: Calcula el promedio de los valores de 'rating para analizar cómo califican los usuarios una cadena hotelera o un hotel en particular.
5.	**Promedio de Sentimiento por Hotel**: Calcula el promedio del sentimiento en las categorías positiva (1), negativa (0) y neutra (-1), teniendo en cuenta la percepción de los usuarios.
6.	**% Crecimiento de la ocupación 2019 vs. 2023**: Indica la proporción en la que ha crecido la ocupación hotelera, en el periodo de tiempo indicado. 


***
### **👀Alcances del Proyecto**
***
* Roles de usuario para garantizar la información
* [Tablero interactivo en Power Bi](https://app.powerbi.com/view?r=eyJrIjoiYzkyMTUyMDYtMGNiNi00ZWQyLTg5MGYtNTMwY2NkNjkwYmQ2IiwidCI6IjUwNjIwMTJiLTI4NGEtNDJkNS1hOTk0LTk2ZTBiZmNlOTczNiIsImMiOjR9)
* Sistema de interpretación de reseñas de Google y Yelp
* Automatización de la Carga incremental mediante los servicios de Google Cloud Platform
* 6 Kpi´s  en el tablero de PowerBi
* Enlace público del Tablero interactivo en PowerBI

***
### **Entregables**
***
* **Código fuente del modelo de Machine Learning** usado para el Sistema de interpretación de Reseñas
* **Códigos fuente** usados para la Automatización de carga Incremental en GCP:
* **Sistema de la orquestación** de la flujo de datos en la nube
* **Documentación detallada de los procesos**: EDA, ETL, Diagrama Entidad- Relación, Diagrama de Arquitectura
* **Usuario administrador** con Tablero interactivo en PowerBI 

## **📈Stack Tecnológico**
***
Una lista de tecnologías utilizadas en el proyecto:

* 🐍[Python](https://docs.python.org/3/)
* 🐬[SQL](https://cloud.google.com/sql-server?hl=es)
* 💻[Google Cloud Platform](https://console.cloud.google.com/welcome?hl=es)
* 📊 [Power Bi](https://powerbi.microsoft.com/es-es/)
* 🐱‍💻 [Git](https://github.com/)
* 📜[Jira](https://id.atlassian.com/logout?continue=https%3A%2F%2Fplanealab.atlassian.net)


## **Colaboradores 👪**
***
En este proyecto contribuyeron las siguientes personas: 

* [Andrea Huertas](https://www.linkedin.com/in/luz-andrea-huertas-guerrero-30bb7a237/)
* [Franco Ccapa](https://www.linkedin.com/in/abelfrancoccapa/)
* [Joaquin Olea](https://www.linkedin.com/in/joaqu%C3%ADn-olea-ibarra-895aa413a/)
* [Jeison Suárez](https://www.linkedin.com/in/jeison-su%C3%A1rez-bbb753266/) 
* [Tomas Alvarenga](https://www.linkedin.com/in/tomas-agostino-alvarenga-4a7a80265/)
