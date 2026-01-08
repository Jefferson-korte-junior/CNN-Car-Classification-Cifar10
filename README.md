# Identificação de Carros com Redes Neurais Convolucionais (CNN)

## Objetivo
Aplicar uma Rede Neural Convolucional (CNN) para classificar imagens do dataset CIFAR-10, com foco na identificação de imagens que representam carros.

## Contexto
Este projeto foi desenvolvido como prática do **Card 15** do **Bootcamp de Ciência de Dados e Visão Computacional** do **LAMIA – UTFPR**.  
O objetivo principal foi consolidar conceitos fundamentais de visão computacional e deep learning por meio de um problema real de classificação de imagens.

## Tecnologias Utilizadas
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Dataset CIFAR-10

## Pipeline do Projeto
1. Carregamento do dataset CIFAR-10
2. Pré-processamento e normalização das imagens
3. Estruturação da arquitetura da CNN:
   - Camadas convolucionais
   - Camadas de pooling
   - Flatten
   - Camadas densas
4. Treinamento do modelo
5. Avaliação do desempenho

## Arquitetura do Modelo
A CNN utilizada é composta por:
- Camadas convolucionais com função de ativação ReLU
- Camadas de MaxPooling
- Camada Flatten
- Camadas densas para classificação

## Resultados
O modelo treinado foi capaz de identificar corretamente imagens da classe “carro” no dataset CIFAR-10, demonstrando a eficácia das redes neurais convolucionais em tarefas de visão computacional.

## Conclusões
O projeto demonstra uma aplicação prática de CNNs para classificação de imagens, reforçando conhecimentos sobre arquitetura de redes neurais, pré-processamento de imagens e avaliação de modelos.

## Possíveis Melhorias
- Testar arquiteturas mais profundas
- Aplicar técnicas de data augmentation
- Avaliar métricas adicionais
- Expandir a classificação para outras classes do dataset

## Como Executar
1. Clone o repositório  
2. Instale as dependências  
3. Execute o script ou notebook de treinamento
