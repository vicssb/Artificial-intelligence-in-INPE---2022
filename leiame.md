# Artificial-intelligence
Artificial intelligence in INPE - 2022

![Logo of the project](ia.jpg) <img src="inpe.jpg" alt="Logo INPE" width="300"/> <img src="amazonia.jpg" alt="amazonia" width="180"/>
 
## Análise de dados estatísticos dos satelites Sentinel 1 e 2 para classificação de cobertura e uso do solo na regiao Amazônica
 
As informações de uso e cobertura da Terra são de
elevada importância para uma sociedade bem estrutura, uma 
vez que auxiliam órgãos de gestão ambiental e desenvolvimento 
agropecuário a identificar regiões de desmatamento e avanço de 
urbanização, bem como áreas naturais que devem ser protegidas. 
O projeto MapBiomas, utiliza-se de imagens de satélite e da 
tecnologia da informação para processar e classificar a cobertura 
da Terra, informando e disponibilizando as transformações no 
território brasileiro anualmente. A versão mais recente disponibilizada pelo projeto, denominada coleção 6, utiliza-se de dados estatísticos em diversas frequências de ondas, captadas pelos instrumentos do satelite LANDSAT, e produz uma classificação com acurácia aproximada de 97% para a região de estudo. 
Este trabalho visa a análise exploratória de atributos estatísticos
dos satélites Sentinel-1 e Sentinel-2 a fim de analisar a possibilidade de classificação do uso e cobertura da Terra, em uma região especifica, através de uma Rede Neural Artificial (RNA), utilizando dados da coleção 6 do MapBiomas como parâmetro de referencia o que possibilitaria o monitoramento das mudanças em um período de tempo mais curto
 
 
## Technology 
 
Here are the technologies used in this project.
 
* Python com as seguintes bibliotecas:
    - import os                                                # PARA COMANDOS DO SISTEMA
    - import pandas as pd                                      # PARA MANIPUTACAO DE DADOS CSV
    - import numpy as np                                       # PARA OPERACOES MATEMATICAS (sqrt, abs,...)
    - import matplotlib.pyplot as plt                          # PARA PLOT DE GRAFICOS
    - import seaborn as sns                                    # PARA PLOT DE GRAFICOS
    - from pickle import dump                                  # Para salvar arquivos
    - import cv2                                               # Para trabalhar com imagens
    - from google.colab import files                           # Para baixar os arquivos
    - import zipfile                                           # Para zipar arquivos
    - import itertools
    - import random

    - from sklearn.utils import shuffle                        # PARA EMBARALHAR OS DADOS
    - from sklearn.model_selection import train_test_split     # PARA SEPARAR OS DADOS (TREINO,TESTE)
    - from sklearn import preprocessing                        # Para preprocessar os dados
    - from sklearn.decomposition import PCA                    # Para preprocessar os dados
    - from sklearn.metrics import multilabel_confusion_matrix  # Para plotar a matriz de confusão
    - from sklearn.metrics import confusion_matrix             # Para plotar a matriz de confusão
    - from sklearn.utils import class_weight                   # Para aplicar pesos a cada classe

    - import tensorflow as tf                                # PARA REDES NEURAIS
    - from tensorflow import keras                           # PARA REDES NEURAIS
    - from keras.utils.vis_utils import plot_model           # PARA REDES NEURAIS
    - from keras import layers                               # PARA REDES NEURAIS
    - from keras.callbacks import ModelCheckpoint            # PARA SALVAR OS PESOS DA REDE NEURAL
    - from google.colab import data_table                    # PARA FORMATAÇÃO DAS TABELAS DO COLAB

 
 
## Services Used
 
* Google Colab Notebook
 
 
## Getting started
 
* To install gems:
>    $ bundle install
* To create the bank and do as migrations:
>    $ rake db:create db:migrate db:seed
* To run the project:
>    $ rails s
 
## How to use
 
Here will be the images and descriptions. Principal content.
 
 
## Features
 
  - Here will be the features.
 
 
## Links
 
  - Link of deployed application: (if has been deployed)
  - Repository: https://link_of_repository
    - In case of sensitive bugs like security vulnerabilities, please contact
      YOUR EMAIL directly instead of using issue tracker. We value your effort
      to improve the security and privacy of this project!
 
 
## Versioning
 
1.0.0.0
 
 
## Authors
 
* **Luís Nascimento, Rogerio Batista e Victor Barros**: 

- @vicssb (https://github.com/vicssb)
- {luis.esnascimento, rogbatista, vicssb}@gmail.com
 
Please follow github and join us!
Thanks to visiting me and good coding!
