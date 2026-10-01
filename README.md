# 🧠 Fundamentos de Redes Neurais e Deep Learning com PyTorch

Este repositório contém meus estudos práticos sobre Inteligência Artificial, cobrindo a evolução desde um único neurônio até redes multicamadas (MLP), Processamento de Linguagem Natural (NLP) e Visão Computacional utilizando a biblioteca **PyTorch**.

---

## 🚀 Conteúdo do Repositório

### 1. Fundamentos e Redes Multicamadas (MLP)
- **Estrutura de um Neurônio Simples:** Soma Ponderada ($Z = \sum X \cdot W + b$) e Ativação Sigmoide.
- **Treinamento e Aprendizado:** Medição de erro com **BCELoss**, ajuste de pesos via **Backpropagation** e otimizador **SGD**.
- **Rede Neural Multicamadas (MLP):** Camadas ocultas com função de ativação não-linear **ReLU** e otimizador **Adam**.

### 2. Processamento de Linguagem Natural (NLP)
- **Tokenização e Vocabulário Dinâmico:** Limpeza de texto em português e tratamento de palavras desconhecidas com token `<UNK>`.
- **Embeddings:** Representação vetorial com `nn.Embedding`.
- **Classificação de Sentimentos:** Previsão de avaliações em frases inéditas (*Positiva* vs. *Negativa*).

### 3. Visão Computacional (Reconhecimento de Imagens)
- **Dataset MNIST:** Processamento e normalização de 60.000 imagens de dígitos manuscritos (0 a 9).
- **DataLoader e Lotes (Batches):** Carregamento otimizado de dados em PyTorch.
- **Acurácia do Modelo:** Classificação de imagens atinge mais de **97% de acurácia** no conjunto de testes.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **PyTorch** & **Torchvision**
- **Google Colab**
- **Git & GitHub**

---

## 📌 Como Executar

Você pode abrir e rodar os notebooks diretamente no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
