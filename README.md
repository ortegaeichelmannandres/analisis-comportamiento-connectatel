# Análisis de Comportamiento del Cliente: ConnectaTel

## Objetivo del Proyecto
El objetivo principal de este proyecto es realizar un análisis exhaustivo del comportamiento de los clientes de la empresa de telecomunicaciones **ConnectaTel** durante el año 2024. El análisis busca identificar patrones de consumo, segmentar a los usuarios por edad y nivel de uso, y detectar tendencias que permitan diseñar estrategias de retención de clientes y optimización de los planes actuales.

## Datasets Utilizados
Para este estudio se integraron tres fuentes de datos principales:
- `plans.csv`: Información técnica y comercial de los planes (tarifas, gigabytes incluidos, minutos y costos por excedentes).
- `users.csv`: Datos demográficos y contractuales de los clientes (edad, ciudad de residencia, fecha de registro y estatus de cancelación o *churn*).
- `usage.csv`: Registro detallado del uso real de los servicios, incluyendo el volumen de llamadas y mensajes por usuario.

## Etapas del Análisis
El proyecto se desarrolló siguiendo un flujo de trabajo profesional de ciencia de datos:

1.  **Exploración y Limpieza de Datos:** Identificación de valores nulos, corrección de tipos de datos (especialmente fechas) y manejo inicial de registros.
2.  **Análisis Estadístico Descriptivo:** Construcción de un perfil estadístico de los clientes basado en edad y distribución geográfica.
3.  **Análisis de Consumo:** Evaluación de métricas clave como minutos consumidos y mensajes enviados para entender la demanda real frente a la oferta de los planes.
4.  **Segmentación de Usuarios:** Clasificación de los clientes en grupos basados en su edad y su intensidad de uso del servicio.
5.  **Identificación de Patrones:** Aunque se detectaron valores atípicos (*outliers*), el enfoque se mantuvo en las métricas totales y los segmentos representativos para asegurar recomendaciones con mayor impacto en el negocio.

## Cómo Ejecutar el Notebook
Puedes visualizar y ejecutar el análisis de las siguientes maneras:

### Opción 1: Google Colab (Recomendado)
1.  Sube el archivo `.ipynb` a tu Google Drive.
2.  Haz clic derecho sobre el archivo y selecciona **Abrir con > Google Colaboratory**.
3.  Asegúrate de cargar los archivos `.csv` mencionados en la sección de Datasets en el entorno de Colab antes de ejecutar las celdas.

### Opción 2: Entorno Local (Jupyter Notebook / VS Code)
1.  Clona este repositorio: `git clone https://github.com/tu-usuario/nombre-del-repo.git`
2.  Instala las dependencias necesarias:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Ejecuta el comando `jupyter notebook` en tu terminal y abre el archivo correspondiente.

## Guía de Reproducción
Para obtener los mismos resultados presentados en este análisis, sigue estos pasos:
1.  Descarga los archivos `plans.csv`, `users.csv` y `usage.csv` y colócalos en la misma carpeta que el notebook.
2.  Ejecuta las celdas en orden secuencial. 
3.  **Nota sobre el alcance:** El análisis está restringido exclusivamente a los datos del año 2024.
4.  Las visualizaciones generadas (histogramas de edad, llamadas y mensajes) se guardarán automáticamente en la carpeta de ejecución si decides correr el script de exportación incluido.

---

### Visualizaciones Incluidas
El proyecto genera diversos gráficos estadísticos para apoyar las conclusiones:
- Distribución de edades de los clientes.
- Frecuencia y duración de llamadas.
- Volumen de mensajería por segmento.

---
_Este proyecto forma parte de mi portafolio del bootcamp de Data Analist por **Triple Ten**_
