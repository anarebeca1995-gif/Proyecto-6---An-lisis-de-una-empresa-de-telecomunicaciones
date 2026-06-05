# Proyecto-7---Análisis-de-una-empresa-de-telecomunicaciones
Análisis de Datos de Telecomunicaciones
Objetivo del Proyecto

El objetivo de este proyecto es analizar el comportamiento de los usuarios de una empresa de telecomunicaciones para comprender sus patrones de consumo y comparar el uso de los diferentes planes tarifarios. A través del análisis exploratorio de datos , se busca identificar tendencias en llamadas, mensajes y uso de servicios, así como generar información útil para la toma de decisiones.

Datasets Utilizados

El proyecto utiliza los siguientes conjuntos de datos:

users.csv: Información demográfica y plan tarifario de los usuarios.

usage.csv: Registros de actividad de los usuarios, incluyendo llamadas y mensajes.


Variables principales analizadas
user_id: Identificador único del usuario.
age: Edad del usuario.
city: Ciudad de residencia.
tariff: Plan tarifario contratado.
duration: Duración de llamadas.

Variables agregadas:
1. cant_mensajes
2. cant_llamadas
3. cant_minutos_llamada
   
Etapas del Análisis:
- Carga de datos
- Importación de librerías.
- Lectura de los archivos CSV.
- Exploración inicial
- Revisión de dimensiones y tipos de datos.
- Identificación de valores faltantes y duplicados.
- Limpieza y preparación
- Corrección de tipos de datos.
- Tratamiento de valores nulos.
- Creación de variables auxiliares.
- Agregación de métricas
- Cálculo del número de mensajes por usuario.
- Cálculo del número de llamadas por usuario.
- Cálculo del total de minutos de llamadas por usuario.
- Integración de datos
- Unión de tablas mediante user_id.
- Construcción del dataset consolidado user_profile.
- Análisis exploratorio
- Estadísticas descriptivas.
- Distribuciones de variables numéricas.
- Distribución de planes tarifarios.
- Identificación de posibles valores atípicos.
- Visualización
- Histogramas.
- Diagramas de caja (boxplots).
- Análisis comparativo entre planes.

Cómo Ejecutar el Notebook 
Jupyter Notebook
Clona el repositorio:
git clone <URL_DEL_REPOSITORIO>
Instala las dependencias necesarias:
pandas numpy matplotlib seaborn
Inicia Jupyter Notebook:
Abre el archivo .ipynb y ejecuta todas las celdas.
Guía de Reproducción

Para reproducir completamente el análisis:

Descargar o clonar este repositorio.
Colocar los datasets en la carpeta indicada.
Abrir el notebook Jupyter.
Ejecutar las celdas en el orden establecido.
Revisar los resultados generados en tablas y gráficos.
Comparar los hallazgos obtenidos con las conclusiones del proyecto.
Resultados Esperados

El análisis permite comprender el comportamiento de los usuarios, identificar diferencias entre planes tarifarios y generar métricas útiles para la toma de decisiones basada en datos.

Autor

Ana Rebeca Pavón Villamil
