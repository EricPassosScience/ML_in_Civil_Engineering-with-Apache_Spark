# Machine Learning na Engenharia Civil com Apache Spark.
Aplicaremos todo o processo de Machine Learning em um contexto de um problema de Engenharia Civil.

Entretanto, ao invés de aplicar tarefas uma a uma, criaremos módulos de automação. Ou seja, vamos desenvolver nosso próprio sistema de AutoML, sem uso de frameworks específicos e aplicando Machine Learning com o Spark MLlib no PySpark.

## Objetivo
O concreto é o material mais importante na Engenharia Civil. A resistência à compressão do concreto é uma função altamente não linear da idade e dos ingredientes usados para preparar o concreto.

Construíremos um modelo preditivo capaz de prever a força do concreto com base em uma série de características e ingredientes do concreto.

## Fonte dos Dados
Usaremos o dataset disponível publicamente neste link: https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

A variável "Concrete compressive strength" (coluna csMPa no dataset) será nossa variável alvo e as demais serão as variáveis preditoras.

## Algoritmos e Observações
Como iremos prever um valor numérico que representa a força do concreto e temos dados de entrada e saída, este será um problema de regressão. Vamos experimentar diferentes algoritmos de regressão e escolher o que representa a melhor performance. Técnicas de otimização de hiperparâmetros serão exploradas para chegar ao melhor modelo possível.

Com o modelo treinado faremos previsões usando novos dados.

## ESPAÑOL: 

# Machine Learning en Ingeniería Civil con Apache Spark.
Aplicaremos todo el proceso de Machine Learning en el contexto de un problema de Ingeniería Civil.

Sin embargo, en lugar de aplicar tareas una por una, crearemos módulos de automatización. Es decir, vamos a desarrollar nuestro propio sistema AutoML, sin utilizar frameworks específicos y aplicando Machine Learning con Spark MLlib en PySpark.

## Objetivo
El hormigón es el material más importante en la Ingeniería Civil. La resistencia a la compresión del hormigón es una función altamente no lineal de la edad y los ingredientes utilizados en su preparación.

Construiremos un modelo predictivo capaz de predecir la resistencia del hormigón en base a una serie de características e ingredientes.

## Fuente de datos
Usaremos el conjunto de datos disponible públicamente en este enlace:  https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

La variable "Concrete compressive strength" (columna csMPa en el conjunto de datos) será nuestra variable objetivo y las demás serán las variables predictoras.

## Algoritmos y Observaciones
Como vamos a predecir un valor numérico que representa la resistencia del concreto y tenemos datos de entrada y salida, esto será un problema de regresión. Probemos diferentes algoritmos de regresión y elijamos el que represente el mejor rendimiento. Se explorarán técnicas de optimización de hiperparámetros para llegar al mejor modelo posible.

Con el modelo entrenado haremos predicciones usando nuevos datos.
