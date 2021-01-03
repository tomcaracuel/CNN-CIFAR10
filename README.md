# CNN-CIFAR10

## Red neuronal convolucional para clasificar imágenes

A diferencia de otro tipo de red neuronal (como una DNN - deep neural network-), las redes neuronales convolucionales (CNN) utilizan neuronas que no son sensibles a todo el conjunto de píxeles de la imagen. Esto permite captar mejor características de los datos y a la vez bajar el numero de parámetros involucrados.

### Composicion basica de una CNN
 Generalmente las CNNs tienen como ingredientes basicos los siguientes pasos:<br/>

-Combinacion de capas convolucionales + capas de Pooling<br/>
-Una DNN conectada al paso anterior a traves Flatten().<br/>
-Una funcion de perdida sobre el conjunto.<br/>


Muestra del conjunto de entrenamiento: <br/>
![muestra conjunto de entrenamiento](https://user-images.githubusercontent.com/66931754/103487520-e41e3800-4de4-11eb-80f5-91056135a95f.png)
<br/>


Nuestro modelo CNN: <br/>
![modelo cnn](https://user-images.githubusercontent.com/66931754/103487518-df598400-4de4-11eb-95f5-32d41e60b3ee.png)
<br/>


Resultados del modelo:<br/>
![resultado prediccion](https://user-images.githubusercontent.com/66931754/103487524-e84a5580-4de4-11eb-813c-8d96662e67a3.png)
