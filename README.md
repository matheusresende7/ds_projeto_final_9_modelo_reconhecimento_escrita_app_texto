# Ciência de Dados - Projeto Final 9

![Wallpaper](images/wallpaper.png)

## Projeto
**Modelo de deep learning** com visão computacional para reconhecimento de escrita em um aplicativo de transcrição de texto.


## Descrição
Nesse projeto de Ciência de Dados, foi realizada uma análise exploratória a fim de entender a fundo as imagens de dígitos manuscritos e como é na prática a função de cada pixel em escala de cinza para a formação de uma imagem. Após isso, foram criados alguns modelos de Deep Learning usando o TensorFlow e o Keras, para que pudesse classificar corretamente os dígitos a que eram expostos. Na criação desses modelos foram utilizadas técnicas de pré processamento, data augmentation, Redes Neurais Convolucionais (CNN), otimização de hiperparâmetros com Keras Tuner e ajustes para evitar overfitting, usando métricas como loss e accuracy. Por fim, o modelo foi exposto à uma avaliação com dados reais, onde classificou dígitos escritos por pessoas reais e teve uma taxa de acertividade de 90%. Dessa forma, esse modelo permite sua aplicação em um aplicativo de transcrição de texto ou anotações, para reconhecer a escrita dos usuários caso venham a escrever manualmente em um tablet, por exemplo.


## Overview do dataset
![output_dataset](images/output_dataset.png)

## Detalhamento dos pixels da figura em escala de cinza
![output_pixels_grayscale](images/output_pixels_grayscale.png)

## Verificações de overfitting no modelo
![output_overfitting_loss](images/output_overfitting_loss.png)

![output_overfitting_accuracy](images/output_overfitting_accuracy.png)

## Previsões do dataset realizadas pelo modelo
![output_predictions_dataset](images/output_predictions_dataset.png)

## Previsões de número escritos à mão realizadas pelo modelo
![output_predictions_real](images/output_predictions_real.png)