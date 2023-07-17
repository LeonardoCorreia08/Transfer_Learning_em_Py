# Digital Innovation One

Código criado para utilização junto a plataforma da Digital Innovation One

<p align="center"><img src="./logo.png" width="500"></p>

## Desafio do Projeto de Transfer Learning em Python 

# Projeto de Transfer Learning

Este é um projeto de transfer learning usando a biblioteca PyTorch. O objetivo deste projeto é treinar um modelo de classificação de imagens usando uma abordagem de transfer learning.

## Pré-requisitos

Certifique-se de ter o Python instalado em seu sistema. Este projeto utiliza a biblioteca PyTorch, portanto, é necessário ter o PyTorch instalado. Você pode instalar o PyTorch usando o comando:

pip install torch torchvision


## Conjunto de dados

O conjunto de dados utilizado neste projeto é composto por 12.499 imagens de gatos e 12.499 imagens de cachorros. As imagens estão organizadas em subpastas separadas para cada classe dentro dos diretórios de treinamento e teste.

Certifique-se de ter os diretórios de treinamento e teste configurados corretamente. Você pode definir os caminhos para os diretórios nas variáveis `train_path` e `test_path` no arquivo `main.py`.

## Treinamento do modelo

Para treinar o modelo, execute o arquivo `prpjeto 1.py`. O script carregará o conjunto de dados, aplicará transformações nas imagens, construirá um modelo de transfer learning usando a arquitetura ResNet-50 pré-treinada e realizará o treinamento.

Você pode ajustar os hiperparâmetros, como número de épocas, taxa de aprendizado, etc., no arquivo `prpjeto 1.py` conforme necessário.

Após o treinamento, o modelo será avaliado no conjunto de teste e exibirá a acurácia alcançada.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request com melhorias, correções de bugs ou novos recursos.



