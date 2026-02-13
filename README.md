# HeartbeatVision: ECG Arrhythmia Classification 🫀

HeartbeatVision es un proyecto de Deep Learning diseñado para la detección automática de anomalías en señales de electrocardiograma (ECG). El modelo clasifica los latidos del corazón en dos categorías principales: pacientes sanos y pacientes con arritmias u otras patologías cardíacas.

## 🚀 Descripción del Proyecto
La interpretación manual de un ECG requiere personal experto y tiempo. Este proyecto busca automatizar el triaje inicial mediante el uso de Redes Neuronales, permitiendo una identificación rápida de señales patológicas que podrían indicar condiciones críticas.

### Características principales:
* **Procesamiento de Señal:** Limpieza y normalización de datos de ECG para su análisis.
* **Arquitectura Deep Learning:** Implementado en **PyTorch**, utilizando capas densas y funciones de activación optimizadas para la clasificación binaria.
* **Evaluación de Precisión:** El modelo incluye métricas de rendimiento como Accuracy y Loss tracking para asegurar la fiabilidad del diagnóstico.



## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Framework de IA:** PyTorch
* **Análisis de Datos:** NumPy, Pandas
* **Visualización:** Matplotlib
* **Entorno:** Jupyter Notebook / Google Colab

## 📈 Metodología
El modelo se entrena utilizando un dataset de señales de latidos pre-segmentados. El flujo de trabajo incluye:
1.  **Carga de datos:** Conexión con Google Drive para procesar datasets extensos.
2.  **Arquitectura del Modelo:** Una red neuronal diseñada para extraer patrones temporales en la señal eléctrica del corazón.
3.  **Optimización:** Uso de optimizadores como `Adam` o `SGD` y funciones de pérdida como `BCELoss` (Binary Cross Entropy).



## 💻 Configuración y Uso
El proyecto está estructurado en notebooks de Jupyter para facilitar su ejecución paso a paso:

1.  **Requisitos:** Asegúrate de tener instaladas las dependencias:
    ```bash
    pip install torch pandas numpy matplotlib tqdm
    ```
2.  **Ejecución:** * Abre `heartbeatvision.ipynb` en Google Colab o Jupyter.
    * Monta tu unidad de Drive si los datos están almacenados allí.
    * Ejecuta las celdas de entrenamiento para generar el modelo.
    * Utiliza el archivo `heartbeatvision variaciones.ipynb` para probar diferentes configuraciones de hiperparámetros.

## 👥 Autores
Desarrollado como parte de un trabajo de investigación (TR) sobre la aplicación de la inteligencia artificial en el sector sanitario.

---
*Descargo de responsabilidad: Este modelo es un proyecto académico y no debe utilizarse como sustituto de un diagnóstico médico profesional.*
