# Projeto de Deep Learning para classificar imagens usando TensorFlow e Transfer Learning

# Classificador de Comidas Típicas de Pernambuco com Transfer Learning

![Status](https://img.shields.io/badge/status-concluído-green)

Este projeto de Deep Learning foi criado como parte de um desafio da DIO e tem como objetivo classificar duas joias da culinária local: Bolo de Rolo e Rocambole, usando a técnica de Transfer Learning com o modelo MobileNetV2.

![Bolo de Rolo vs Rocambole](images/exemplo_predicao.png)

## 🎯 Contexto

Muitas vezes confundidos por quem não é da região, o Bolo de Rolo (Patrimônio Cultural e Imaterial de Pernambuco) e o Rocambole possuem diferenças sutis. Este projeto nasceu da ideia de treinar um modelo de visão computacional para aprender a diferenciá-los, explorando o poder das redes neurais pré-treinadas para resolver um problema de nicho e com um dataset customizado.

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Frameworks:** TensorFlow, Keras
- **Bibliotecas:** Matplotlib, NumPy
- **Ambiente:** Google Colab (GPU)

## 📈 Resultados

O modelo alcançou uma acurácia de validação de **96%** após 10 épocas de treinamento, mostrando-se altamente eficaz na distinção das duas classes.

#### **Acurácia ao Longo das Épocas**
![Gráfico de Acurácia](images/grafico_acuracia.png)

#### **Perda (Loss) ao Longo das Épocas**
![Gráfico de Perda](images/grafico_perda.png)

## 📂 Como Utilizar o Projeto

    ```
1.  Abra o notebook `classificador_de_imagens.ipynb` no Google Colab ou Jupyter.
2.  Execute as células para treinar o modelo e ver os resultados.

## 🚀 Próximos Passos

- [ ] Implementar *Fine-Tuning* para tentar melhorar ainda mais a acurácia.
- [ ] Fazer o deploy do modelo usando Streamlit ou Flask para criar uma aplicação web interativa.
- [ ] Aumentar o dataset com mais imagens e classes de outras comidas típicas.

## 👨‍💻 Autor

**Daniel Tavares de França**
