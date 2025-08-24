# 🖼️ Proyecto de Preprocesamiento y Balanceo de Imágenes

Este proyecto implementa un flujo de trabajo para preparar datasets de imágenes con el fin de entrenar modelos de Deep Learning en un entorno balanceado y listo para usar.

---


## 🚀 Descripción
La aplicación permite:
- 📦 Descomprimir un archivo ZIP con imágenes clasificadas en carpetas.
- 🔍 Contar automáticamente cuántas imágenes hay por clase.
- ⚖️ Crear un dataset balanceado seleccionando la misma cantidad de imágenes en cada clase.
- 📂 Guardar el nuevo dataset listo para entrenamiento en un directorio separado.

## 🛠️ Tecnologías utilizadas
- Python 3.8+
- TensorFlow / Keras para el manejo de datasets de imágenes.
- NumPy para manipulación de datos.
- PIL (Pillow) para procesar imágenes.
- Matplotlib para visualización de imágenes.
- Google Colab como entorno de ejecución.

## 📂 Flujo de trabajo
- 📥 Subir un archivo ZIP con imágenes organizadas en carpetas por clase.
- 📦 Descomprimir el dataset en el entorno de trabajo.
- 🔍 Calcular el número de imágenes en cada clase.
- ⚖️ Seleccionar aleatoriamente la misma cantidad de imágenes por clase (equilibrar dataset).
- 📂 Guardar el dataset balanceado en una nueva carpeta (test_balanced/).

## ⚙️ Requisitos previos
- Dataset comprimido en formato ZIP con subcarpetas por clase.
- Google Colab o entorno local con TensorFlow instalado.
- Paquetes: numpy, Pillow, matplotlib.

## 📑 Ejemplo de uso
- Dataset original:
   * Clase A → 500 imágenes
   * Clase B → 300 imágenes
   * Clase C → 200 imágenes

- Dataset balanceado final:
  * Clase A → 200 imágenes
  * Clase B → 200 imágenesç
  * Clase C → 200 imágenes

## 🎯 Resultado
Obtendrás un dataset equilibrado que mejora la calidad del entrenamiento en redes neuronales al evitar sesgo hacia clases con más ejemplos.
