# telecom-analysis

# ConnectaTel — Análisis de Datos de Clientes

## 1. Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones que opera en Latinoamérica.

Mediante técnicas de análisis de datos, se busca identificar problemas de calidad de la información, explorar patrones de consumo, segmentar a los usuarios por edad y nivel de uso, y generar hallazgos que permitan apoyar la toma de decisiones basada en datos.

## 2. Datasets utilizados

El proyecto utiliza conjuntos de datos que contienen información de los clientes y registros relacionados con el uso de los servicios.

- **Dataset de usuarios (`users`):** contiene información de los clientes, como identificador de usuario, edad, ciudad, plan contratado y fecha de cancelación del servicio.
- **Dataset de uso (`usage`):** contiene registros relacionados con el consumo de los servicios, incluyendo identificadores de usuario, duración de llamadas y otras variables de uso.
- **Dataset de planes contratados (`plans`):** contiene registro de planes contratados por los usuarios

Los tres  conjuntos de datos permiten explorar las características de los clientes y analizar sus patrones de consumo.


## 3. Etapas del análisis realizadas

El proyecto sigue las siguientes etapas:

1. **Exploración de datos:** revisión de la estructura de los datasets, tipos de variables y estadísticas descriptivas.
2. **Evaluación de la calidad de los datos:** identificación de valores faltantes, registros inválidos e inconsistencias.
3. **Limpieza y preparación:** revisión y tratamiento de los problemas de calidad identificados para preparar los datos para su análisis.
4. **Análisis exploratorio de datos (EDA):** exploración de las características de los clientes y las variables relacionadas con el uso de los servicios.
5. **Segmentación de clientes:** clasificación de usuarios por grupos de edad y niveles de consumo.
6. **Visualización de datos:** elaboración de gráficos para analizar la distribución de los segmentos identificados.
7. **Análisis ejecutivo:** interpretación de los resultados y elaboración de recomendaciones orientadas al negocio.

## 4. Cómo ejecutar el notebook

El proyecto puede ejecutarse utilizando Google Colab o Jupyter Notebook.

### Opción A: Google Colab

1. Descarga el archivo `.ipynb` desde este repositorio.
2. Accede a [Google Colab](https://colab.research.google.com/).
3. Selecciona **Archivo → Subir notebook** y carga el archivo descargado.
4. Sube los datasets requeridos al entorno de Colab.
5. Verifica las rutas de los archivos en el código y actualízalas si es necesario.
6. Selecciona **Entorno de ejecución → Ejecutar todas** para ejecutar el análisis completo.

### Opción B: Jupyter Notebook

1. Descarga o clona este repositorio.
2. Instala Python y las bibliotecas necesarias para ejecutar el proyecto.
3. Coloca el notebook y los datasets en las rutas correspondientes.
4. Abre el archivo `.ipynb` desde Jupyter Notebook o JupyterLab.
5. Ejecuta las celdas en orden, desde la carga de los datos hasta el análisis ejecutivo.

## 5. Guía de reproducción

Para reproducir el análisis y obtener los resultados:

1. Asegúrate de contar con todos los datasets requeridos.
2. Verifica que las rutas de los archivos coincidan con su ubicación en el entorno de ejecución.
3. Ejecuta las celdas del notebook en el orden original.
4. Revisa las tablas, estadísticas y visualizaciones generadas en cada etapa.
5. Consulta los resultados de la segmentación y las conclusiones documentadas para comprender los hallazgos.


