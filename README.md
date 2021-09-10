# experiencias_com_dataset_covid19

Este é um treinamento de modelo de detecção de covid-19 através de raio-x seguindo tutoriais do canal " youtube.com/c/canalsandeco " usando o seguinte dataset : kaggle.com/tawsifurrahman/covid19-radiography-database

Utulizei o acelerador de hardware do google colab do tipo GPU. Também tentei lidar com a maior resolução possível para as imagens sem que a memória da máquina virtual estourasse e obtive o fator de redução de escala 0.5; 

No tutorial do Canal Sandeco, ele obtem uma acurácia de 96,15%. Obtive utilizando os 3616 primeiros dados do dataset a acurária de 96,85%.

## 1. Redução das amostras e diminuição na redução de escala
Utilizando somente 1250 amostras para cada caso, foi possível utilizar uma redução de escala de 0.85. Esta mudança acabou gerando uma acurácia de 97.76%, sensitividade de 98.4% e
especificidade de 97.12%.

## Acurácia
![alt text](https://raw.githubusercontent.com/joaofranciscoxd/experiencias_com_dataset_covid19/main/acuracia%20do%20modelo.png)
## Perda
![alt text](https://raw.githubusercontent.com/joaofranciscoxd/experiencias_com_dataset_covid19/main/perda%20do%20modelo.png)
## Matriz confusão
![alt text](https://raw.githubusercontent.com/joaofranciscoxd/experiencias_com_dataset_covid19/main/matriz%20confus%C3%A3o.png  )
