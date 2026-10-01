# Netflix-Users-Analytics-Dashboard
Dashboard interactivo desarrollado con HTML, CSS y JavaScript para explorar y analizar información de usuarios de Netflix mediante visualizaciones dinámicas e indicadores ejecutivos.
¿Qué hace este proyecto?

La aplicación permite cargar y analizar información de usuarios a partir de diferentes fuentes:

Archivos CSV o TXT.
Datos copiados directamente desde Excel.
Tablas copiadas en formato Markdown.
Datos de prueba incluidos en la aplicación.

Una vez cargados los datos, el sistema identifica las variables disponibles y genera automáticamente los análisis correspondientes.

Principales funcionalidades
📊 Resumen ejecutivo

Presenta indicadores generales de la información cargada, entre ellos:

Total de usuarios.
Cantidad de adultos.
Cantidad de adultos mayores.
Cantidad de menores de edad.
Horas promedio de visualización.
Número de países registrados.
👥 Análisis demográfico

A partir de la variable Age, el sistema genera automáticamente una nueva variable denominada:

Grupo_Etareo

La clasificación utilizada es:

Edad	Grupo
Menor de 18 años	Menor de Edad
18 a 59 años	Adulto
60 años o más	Adulto Mayor

Esto permite transformar una variable numérica en una categoría útil para el análisis.

📺 Análisis de suscripciones

Permite analizar la distribución de usuarios según:

Subscription_Type

Por ejemplo:

Basic
Standard
Premium

La aplicación representa esta información mediante gráficos para facilitar la interpretación de la distribución de usuarios.

🎬 Análisis del comportamiento

Utiliza variables como:

Age
Watch_Time_Hours
Favorite_Genre

para explorar la relación entre edad, tiempo de visualización y preferencias de contenido.

🌎 Análisis geográfico

Utiliza la variable:

Country

para identificar la distribución de usuarios por país y generar una visión general del componente geográfico de la base de datos.

Arquitectura del proyecto

El proyecto está desarrollado como una aplicación web independiente:

HTML: estructura de la aplicación.
CSS: diseño visual e identidad gráfica.
JavaScript: procesamiento de datos, generación de variables, indicadores y visualizaciones.

No requiere una base de datos ni un backend para ejecutar los análisis básicos.

Flujo de funcionamiento
Carga de datos
       ↓
Lectura y procesamiento
       ↓
Detección de variables
       ↓
Creación de variables derivadas
       ↓
Cálculo de indicadores
       ↓
Generación de gráficos
       ↓
Visualización del análisis
Variable derivada

Uno de los elementos principales del proyecto es la creación automática de variables derivadas.

A partir de:

Age

se genera:

Grupo_Etareo

Esto demuestra cómo una variable original puede transformarse en una categoría analítica que facilita la generación de indicadores y visualizaciones.

Objetivo del proyecto

Este proyecto hace parte de un ejercicio de analítica de datos y visualización, orientado a convertir datos estructurados en información comprensible mediante una interfaz web interactiva.

Además de mostrar resultados, busca integrar conceptos de:

Datos → Transformación → Análisis → Visualización → Interpretación

Tecnologías utilizadas
HTML5
CSS3
JavaScript
Visualización de datos
Procesamiento de archivos CSV
Procesamiento de datos tabulares
Ejecución

El proyecto puede ejecutarse directamente abriendo el archivo HTML en un navegador web.

También puede publicarse mediante GitHub Pages para convertirlo en una aplicación web accesible desde Internet.

Fuente de datos

El ejercicio utiliza una estructura de datos de usuarios de Netflix con variables relacionadas con características demográficas, suscripción, comportamiento de visualización, género favorito y ubicación.

Autor

Edgar Orjuela

Ingeniero de Sistemas | Analítica de Datos | Transformación Digital | LMS | Automatización
