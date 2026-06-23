# Few-Shot-Learning

Este es un entorno de trabajo para hacer pruebas sobre modelos de clasificación de texto con pocos datos a partir de cualquier dataset disponible en la librería de HugginFace. En el código se incluyen modelos de redes neuronales, con Data Augmentation y ajuste fino a los modelos de BERT y DISTILBERT. También se incluye un entorno de pruebas para **aprendizaje de contexto** vía Langchain con modelos de OpenAI mediante API, o de Ollama instalados en local. Por último se han implementado algunos modelos populares de *few shot text clasifiacion* como las **redes de aprendizaje de métricas** SNN, MNN y PNN, y **algoritmos de aprendizaje semisupervisado**  UDA y UAST.

# Requisitos principales:

* El código está diseñado para ser ejecutado en un entorno de Python 3.10
* Instalación de las librerías incluídas en el fichero "requirements.txt"
* Para algunos de los modelos es necesario tener un entorno gráfico instaldo con drivers compatibles con tensorflow 2.10
