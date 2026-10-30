# Redes Neurais Convolucionais com TensorFlow

![Jupyter Notebooks](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Modelos%20de%20vis%C3%A3o-FF6F00?logo=tensorflow&logoColor=white)
![Licença MIT](https://img.shields.io/badge/Licen%C3%A7a-MIT-green.svg)

> Exercícios e laboratórios de classificação de imagens com redes neurais convolucionais, organizados em quatro semanas de estudo.

Este repositório reúne notebooks práticos sobre preparação de imagens, treinamento de CNNs, aumento de dados e transferência de aprendizado com TensorFlow/Keras.

## Trilha de estudos

| Semana | Conteúdo | Notebooks |
| --- | --- | --- |
| **1 · Fundamentos** | Classificação de gatos e cães; construção de CNNs e fluxo de imagens | [Lab: Cat vs Dog](week1/w1_lab1.ipynb) · [Lab: melhor modelo](week1/w1_lab2.ipynb) · [Exercício: gatos e cães](week1/w1_assignment.ipynb) |
| **2 · Generalização** | Aumento de dados e treinamento de classificadores de imagens | [Lab: Horse vs Human](week2/w2_lab1.ipynb) · [Lab: aumento de dados](week2/w2_lab2.ipynb) · [Exercício: gatos e cães](week2/w2_assignment.ipynb) |
| **3 · Transfer learning** | Reutilização da InceptionV3 para classificação de imagens | [Lab: transferência de aprendizado](week3/w3_lab1.ipynb) · [Lab: Horse vs Human](week3/w3_lab2.ipynb) · [Exercício: InceptionV3](week3/w3_assignment.ipynb) |
| **4 · Múltiplas classes** | Classificação de pedra, papel e tesoura e reconhecimento de sinais | [Lab: pedra, papel e tesoura](week4/w4_lab1.ipynb) · [Lab: sinais](week4/w4_lab2.ipynb) · [Exercício: sinais](week4/w4_assignment.ipynb) |

## Como explorar

1. Escolha uma semana na trilha acima e abra o notebook pelo GitHub.
2. Para executar as células, use Jupyter Notebook ou [Google Colab](https://colab.research.google.com/).
3. Baixe ou envie os datasets solicitados pelo notebook antes de iniciar o treinamento.

Os datasets não estão armazenados neste repositório. Alguns exercícios foram preparados para o ambiente original do curso e usam caminhos locais específicos; ao executar em outro ambiente, ajuste os caminhos dos arquivos de dados conforme necessário. Os notebooks podem depender de TensorFlow/Keras, NumPy e Matplotlib.

## Estrutura

```text
.
├── week1/   # Fundamentos de CNN e classificação binária
├── week2/   # Aumento de dados e treinamento
├── week3/   # Transfer learning com InceptionV3
├── week4/   # Classificação multiclasse
├── LICENSE
└── README.md
```

## Sobre o material

O conteúdo acompanha o curso [Convolutional Neural Networks in TensorFlow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow), parte da especialização [DeepLearning.AI TensorFlow Developer](https://www.coursera.org/professional-certificates/tensorflow-in-practice) na Coursera. Este repositório serve como registro de estudos e prática.

## Licença

Consulte o arquivo [LICENSE](LICENSE).
