Taller No. 3 Topicos Avanzados en Inteligencia Artificial.
Integrantes: Daniel Chavarro - Alexander Luna Ruiz
El taller consta de las siguientes características:

Preparación del dataset: En este caso, se puede tener un archivo de Jupyter Notebook o un archivo Python separado para la limpieza y transformación del dataset. Este archivo se puede llamar "preparacion_dataset.ipynb" o "preparacion_dataset.py".

Experimentación del modelo: Para la experimentación del modelo, se pueden utilizar varios archivos para probar diferentes algoritmos de aprendizaje automático. Cada archivo debe contener un modelo diferente y se puede nombrar de acuerdo al modelo que está siendo probado, por ejemplo, "modelo_1.py", "modelo_2.py", "modelo_3.py", etc.

Selección del mejor modelo: Después de haber experimentado con diferentes modelos, se puede seleccionar el mejor modelo y publicarlo en MLflow. Para este paso, se puede tener un archivo llamado "seleccion_mejor_modelo.py" que contenga la lógica para seleccionar el modelo con el mejor desempeño.

Despliegue del modelo: Para el despliegue del modelo, se pueden tener dos archivos diferentes, uno para la creación del servicio API RESTful y otro para la interfaz gráfica. Estos archivos se pueden llamar "creacion_servicio_api.py" y "interfaz_grafica.py".

Monitoreo del modelo: Para el monitoreo del modelo, se puede tener un archivo llamado "monitoreo_modelo.py" que contenga la lógica para medir las métricas de rendimiento y detectar cualquier problema en el modelo.

INSTRUCCIONES:
1. Ejecutar el docker-compose que generará el ambiente requerido para el taller.
2. Almacenar los datos requeridos en la base de datos MySQL. Ingresar a http://10.43.102.113:8501/, Clic en process_data y ejecutar. Los datos serán almacenados en la base de datos db. Este proceso se hará una única vez.
3. Procesar los datos. Ingresar a http://10.43.102.113:8888/, contraseña 123456. Ejecutar el cuaderno, que generará el procesamiento de los datos y la ejecución de los modelos.
4. El resultado de esta ejecución estará disponible en MLFlow, para ello se deberá ingresar a http://10.43.102.113:5000/, donde residirán los modelos en experimentación.
5. Acceder a MinIO Console en http://10.43.102.113:8000/, donde se dispondrá el mejor modelo de los evaluados en MLFlow para producción con el fin de generar inferencias.
