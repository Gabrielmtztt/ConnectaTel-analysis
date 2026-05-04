# ConnectaTel-analysis

**Objetivo del Proyecto**
El objetivo principal de este análisis es evaluar la calidad, estructura y comportamiento de los datos transaccionales de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia. Se buscó identificar patrones de consumo, segmentar clientes y detectar oportunidades estratégicas de negocio.

**Datasets Utilizados**
El análisis se basa en datos transaccionales y de perfiles de usuario:

user_profile: datos demográficos y de suscripción de los clientes.

usage_data: datos de consumo de servicios (llamadas, mensajes, etc.).

Nota: Los datos han sido tratados para corregir inconsistencias en formatos de fecha y valores nulos.

**Etapas del Análisis**
Limpieza y preparación: tratamiento de valores nulos, conversión de tipos de datos y manejo de formatos de fecha.

Ingeniería de características: creación de las columnas grupo_uso y grupo_edad para segmentar la base.

Análisis exploratorio (EDA): visualización de la distribución demográfica y de comportamiento.

Segmentación ejecutiva: identificación de patrones de valor y riesgos de deserción (churn).

Insights estratégicos: traducción de hallazgos en recomendaciones accionables.

**Cómo ejecutar este Notebook**
Este análisis fue desarrollado en Python usando las bibliotecas pandas, seaborn y matplotlib.

Opción A (Google Colab):

Haga clic en este [enlace] (puede pegar aquí su link de Colab si lo tiene compartido).

Seleccione "Ejecutar todo" para recrear los resultados.

Opción B (Local):

Clone este repositorio: git clone [URL-de-repo]

Asegúrese de tener instalados los requerimientos: pip install pandas seaborn matplotlib

Abra el archivo .ipynb en Jupyter Notebook o VS Code.

 **Guía de Reproducción**
Asegúrese de tener los archivos de datos en el mismo directorio que el notebook.

El orden de ejecución es secuencial: comienza por la limpieza de datos antes de aplicar las funciones de segmentación.

Si desea ajustar los umbrales de segmentación (por ejemplo, definir "Alto uso" de forma distinta), puede modificar los parámetros dentro de las funciones definidas en la etapa de ingeniería de características.

