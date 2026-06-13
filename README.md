# TFE_DeepLearning_Retinopatia
Este repositorio contiene el código fuente utilizado para el Trabajo Fin de Estudios (TFE) titulado: "Evaluación de modelos de Deep Learning (CNN, U-Net y Transformers) para la detección temprana de la enfermedad retiniana Retinopatía diabética".

# TFE: Evaluación de Modelos Deep Learning para Detección de Retinopatía Diabética

**Autor:** Donny Alexander Rodríguez Cáceres  
**Director:** Carlos Manuel Moreno Negrin  
**Universidad:** Internacional de La Rioja (UNIR)  
**Fecha:** 2026

## Descripción
Este repositorio contiene el código fuente del Trabajo de Fin de Máster que compara tres arquitecturas de deep learning (CNN ResNet18, U-Net y Vision Transformer) para el diagnóstico automático de retinopatía diabética a partir de imágenes de fondo de ojo. El estudio utiliza el conjunto de datos público **Messidor-2** y evalúa métricas como sensibilidad, especificidad, AUC-ROC y eficiencia computacional.

## Estructura del repositorio
- `TFE_Notebook_DeepLearning_Retinopatia.ipynb`: Cuaderno principal con todo el flujo de trabajo.
- `requirements.txt`: Dependencias necesarias.
- `TFE_Código_Python_DL_Retinopatia.py`: Código completo del proyecto en Python.

## Requisitos de instalación
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/dnysecure/TFE_DeepLearning_Retinopatia.git
   cd TFE_DeepLearning_Retinopatia
   
## Instalación y ejecución en Google Colab

Para ejecutar este cuaderno en Google Colab con aceleración GPU, sigue estos pasos:

1. Abre [Google Colab](https://colab.research.google.com/).
2. Sube el archivo `TFE_Notebook_DeepLearning_Retinopatia.ipynb` desde tu ordenador o impórtalo directamente desde este repositorio usando la pestaña **GitHub**.
3. En el menú superior, selecciona `Entorno de ejecución` → `Cambiar tipo de entorno de ejecución` y elige **GPU** como acelerador de hardware.
4. Ejecuta la primera celda del cuaderno. Esta instalará automáticamente todas las dependencias necesarias (las mismas que aparecen en `requirements.txt`). Si prefieres instalarlas manualmente, puedes ejecutar en una celda:
   ```python
   !pip install -r https://raw.githubusercontent.com/dnysecure/TFE_DeepLearning_Retinopatia/refs/heads/main/requirements.txt
