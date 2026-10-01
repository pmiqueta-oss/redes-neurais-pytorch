# 🧠 Fundamentos de Redes Neurais e Deep Learning com PyTorch

Este repositório reúne meus projetos e estudos práticos sobre Inteligência Artificial, cobrindo a evolução desde conceitos fundamentais (Perceptron, MLPs) até arquiteturas avançadas de *Processamento de Linguagem Natural (NLP)*, *Visão Computacional (CNNs)*, sistemas *Multimodais* e *Transfer Learning*.

## 🚀 Conteúdo do Repositório

### 1. Fundamentos e Redes Multicamadas (MLP)
- **Neurônio Simples:** Soma Ponderada ($Z = \sum X \cdot W + b$) e Ativação Sigmoide.
- **Treinamento:** Cálculo de erro com `BCELoss`, ajuste via *Backpropagation* e otimizador `SGD`.
- **Rede Neural Multicamadas (MLP):** Camadas ocultas, ativação `ReLU` e otimizador `Adam`.

### 2. Processamento de Linguagem Natural (NLP)
- **Tokenização e Vocabulário Dinâmico:** Limpeza de texto e tratamento do token `<UNK>` para palavras fora do vocabulário.
- **Embeddings:** Vetores de representação semântica com `nn.Embedding`.
- **Análise de Sentimentos:** Classificação de avaliações com alta precisão.

### 3. Visão Computacional (Reconhecimento de Imagens)
- **Dataset MNIST:** Processamento de 60.000 imagens de dígitos manuscritos (0 a 9).
- **Classificador Linear:** Acurácia superior a *97%* no conjunto de testes.

### 4. Visão Computacional Avançada & NLP Multimodal 🌟
- **Redes Neurais Convolucionais (CNNs):** Extração de características visuais com camadas `nn.Conv2d` e `nn.MaxPool2d`.
- **Acurácia da CNN:** *99.02% de precisão* no reconhecimento do MNIST.
- **Módulo Multimodal:** Integração de análise de descrição em texto (NLP) com *99.98% de confiança* na validação das imagens.

### 5. Transfer Learning com ResNet18 🚀
- **Arquitetura Pré-treinada:** Utilização do cérebro da ResNet18 (treinado em milhões de imagens) com congelamento de camadas (*layer freezing*).
- **Fine-Tuning:** Substituição da última camada linear (`fc`) para classificação de 10 classes.
- **Acurácia Obtida:** **95.73%** em apenas 2 épocas de treinamento na GPU T4.

---

## 🛠️ Tecnologias Utilizadas
- *Python 3*
- *PyTorch* & *Torchvision*
- *Google Colab* (Aceleração GPU T4)
- *Git & GitHub*

---

## 📌 Projetos no Repositório
- `01_fundamentos_mlp.ipynb` — Introdução e Redes Multicamadas
- `02_nlp_e_visao_computacional.ipynb` — NLP Básico e Classificador MNIST
- `03_cnn_e_nlp_multimodal.ipynb` — CNN Avançada e Sistema Multimodal
- `04_transfer_learning_resnet.ipynb` — Transfer Learning e Fine-Tuning da ResNet18
