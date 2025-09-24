# Modelo de Deep Learning com Transfer Learning em TensorFlow

Este projeto de Deep Learning foi desenvolvido como parte de um desafio da DIO, com o objetivo de aplicar técnicas de Transfer Learning utilizando o modelo MobileNetV2 para realizar tarefas de classificação.

# Desafio

Dadas n matrizes de confusão, crie um algoritmo que determine qual delas possui a maior acurácia (accuracy). A acurácia é calculada por: accuracy = (TP + TN) / (TP + FP + FN + TN). Retorne o índice e o valor da acurácia da matriz vencedora.

Entrada

Uma string contendo:

Um inteiro n (quantidade de matrizes).
Em seguida, exatamente n linhas, cada uma com quatro inteiros no formato TP,FP,FN,TN.
Saída
Index: X — onde X é o índice da matriz com maior acurácia.
Accuracy: Y — onde Y é a acurácia da matriz vencedora, arredondada para duas casas decimais (remova zeros finais desnecessários).
Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.
EntradaSaída2
100,0,0,50
80,10,2,98Index: 0
Accuracy: 14
70,15,8,78
60,20,10,80
45,5,3,92
80,7,15,98Index: 2
Accuracy: 0.943
50,10,5,85
20,5,8,67
30,12,4,88Index: 0
Accuracy: 0.9

## Contexto

Este projeto foi desenvolvido com o objetivo de treinar um modelo de visão computacional utilizando redes neurais pré-treinadas, aplicando técnicas de Transfer Learning para resolver um problema de classificação em um contexto específico, com uso de um dataset customizado.

## Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Frameworks:** TensorFlow, Keras
- **Bibliotecas:** Matplotlib, NumPy
- **Ambiente:** Google Colab (GPU)

## Resultados

O modelo atingiu uma acurácia de validação de **96%** após 10 épocas de treinamento, demonstrando alta eficácia na tarefa de classificação.

## Como Utilizar o Projeto

    ```
1.  Abra o notebook `classificador_de_imagens.ipynb` no Google Colab ou Jupyter.
2.  Execute as células para treinar o modelo e ver os resultados.

## Próximos Passos

- [ ] Implementar *Fine-Tuning* para tentar melhorar ainda mais a acurácia.
- [ ] Fazer o deploy do modelo usando Streamlit ou Flask para criar uma aplicação web interativa.
- [ ] Aumentar o dataset com mais imagens e classes de outras comidas típicas.

## Autor

**Daniel Tavares de França**
