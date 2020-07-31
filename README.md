# Object-Detector
Neste trabalho foi desenvolvido um detector de objetos utilizando os modelos ResNet50 e MobileNetV2, a ideia era detectar 5 objetos presentes em um conjunto de imagens.
A técnica de amostragem utilizada foi o holdout, com 80% do conjunto de dados pertencendo ao treinamento e 20% ao teste. 
O otimizador utilizado foi o gradiente descendente estocástico com uma taxa de aprendizado de 0.01, um momento de 0.9 e um peso de decaimento de 0.0005.
A métrica de acurácia utilizada foi o Pascal Voc Evaluation.


