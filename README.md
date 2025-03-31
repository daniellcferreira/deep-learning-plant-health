# Classificador de Doenças em Plantas com CNN

![Python](https://img.shields.io/badge/Python-Interpreted-blue?style=flat-square&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?style=flat-square&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-red?style=flat-square&logo=keras)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=flat-square&logo=opencv)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-blue?style=flat-square&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=flat-square&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?style=flat-square&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Visualization-blue?style=flat-square&logo=python)

## Descrição
Este projeto implementa uma Rede Neural Convolucional (CNN) para classificação de doenças em folhas de plantas. Utilizando um conjunto de imagens de treinamento e testes, a rede é treinada para identificar padrões característicos de diferentes doenças, auxiliando na tomada de decisão para o manejo adequado das culturas. O modelo utiliza TensorFlow e Keras, realizando pré-processamento de imagens com OpenCV e visualização dos resultados com Matplotlib.

A CNN é composta por múltiplas camadas convolucionais, seguidas de camadas de pooling e camadas densas fully connected. Além disso, técnicas de regularização como Dropout são utilizadas para evitar overfitting, garantindo uma melhor generalização do modelo. 

O projeto também inclui um sistema de previsão que permite classificar novas imagens carregadas pelo usuário, fornecendo um diagnóstico da planta e sugerindo recomendações baseadas no tipo de doença identificado.

## Funcionalidades
- Leitura e pré-processamento de imagens de folhas infectadas e saudáveis.
- Implementação de uma Rede Neural Convolucional (CNN) com camadas de convolução, pooling e fully connected.
- Normalização das imagens para otimização do treinamento do modelo.
- Treinamento da CNN com conjuntos de imagens rotuladas.
- Avaliação da acurácia do modelo utilizando um conjunto de teste.
- Geração de previsões para imagens individuais.
- Exibição de imagens de entrada e saída com as respectivas classes preditas.
- Salvamento do modelo treinado para reutilização futura.
- Uso de técnicas de regularização como Dropout para reduzir overfitting.
- Implementação de camadas de ativação Softmax para classificação multi-classe.
- Otimização do modelo utilizando Adam Optimizer.
- Uso de ImageDataGenerator para gerar e normalizar imagens para treinamento.
- Visualização gráfica do treinamento e validação do modelo.
- Interação com usuários via Jupyter Notebook para facilitar a execução do código.
- Uso de bibliotecas de visualização para melhor entendimento dos dados.

## Tecnologias Abordadas
- **Python**: Linguagem principal utilizada para desenvolvimento do modelo.
- **TensorFlow & Keras**: Frameworks para construção e treinamento da CNN.
- **OpenCV**: Biblioteca utilizada para manipulação e pré-processamento das imagens.
- **Matplotlib & Seaborn**: Utilizadas para visualização das imagens e análise dos resultados.
- **NumPy & Pandas**: Para manipulação de arrays e análise de dados.
- **ImageDataGenerator**: Usado para gerar e normalizar imagens para treinamento.
- **Sequential API**: Abordagem do Keras para criar a CNN de forma estruturada.
- **Dropout Layer**: Implementado para reduzir overfitting durante o treinamento.
- **Softmax Activation**: Utilizada na camada de saída para classificação multi-classe.
- **Adam Optimizer**: Algoritmo de otimização eficiente para aprendizado da CNN.
- **Binary Crossentropy Loss**: Função de perda utilizada para avaliar o desempenho do modelo.
- **Jupyter Notebook**: Ambiente interativo utilizado para execução dos experimentos.

