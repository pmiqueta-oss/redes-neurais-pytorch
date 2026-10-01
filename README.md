# 🧠 Fundamentos de Redes Neurais e Deep Learning com PyTorch

Este repositório contém meus estudos práticos sobre Inteligência Artificial, cobrindo a evolução desde um único neurônio até redes multicamadas (MLP) e Processamento de Linguagem Natural (NLP) utilizando a biblioteca **PyTorch**.

---

## 🚀 Conteúdo do Notebook

No notebook [`01_fundamentos_redes_neurais.ipynb`](./01_fundamentos_redes_neurais.ipynb), foram abordados os seguintes tópicos:

1. **Estrutura de um Neurônio Simples:**
   - Soma Ponderada ($Z = \sum X \cdot W + b$)
   - Função de Ativação Sigmoide para probabilidade ($0$ a $1$)
   - Forward Pass explícito

2. **Treinamento e Aprendizado (Classificador de Crédito):**
   - Medição de erro com a função de perda **BCELoss** (Binary Cross Entropy)
   - Ajuste de pesos via **Backpropagation** e **SGD** (Gradiente Descendente)
   - Generalização do modelo testado com novos dados de clientes

3. **Rede Neural Multicamadas (MLP - Multi-Layer Perceptron):**
   - Criação de uma **Camada Oculta (Hidden Layer)**
   - Uso da função de ativação não-linear **ReLU**
   - Otimização avançada com o algoritmo **Adam**

4. **Introdução ao NLP (Processamento de Linguagem Natural):**
   - Mapeamento de texto para números (**Tokenização**)
   - Representação vetorial com **nn.Embedding**
   - Classificação de sentimento de frases (*Positiva* vs. *Negativa*)

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **PyTorch**
- **Google Colab**
- **Git & GitHub**

---

## 📌 Como Executar

Você pode abrir e rodar o projeto diretamente no Google Colab clicando no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pmiqueta-oss/redes-neurais-pytorch/blob/main/01_fundamentos_redes_neurais.ipynb)
