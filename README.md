# GAN
Uma Generative Adversarial Network (GAN), treinada utilizando a base de dados MNIST, implementada com a função de perda Wasserstein e o acréscimo de Gradient Penalty para maior estabilidade no treinamento. O modelo é capaz de gerar imagens de dígitos escritos à mão com alta qualidade, explorando técnicas avançadas de aprendizado profundo.

Este repositório inclui:

- Pré-processamento dos dados MNIST: Normalização e formatação das imagens para treinar o modelo.
- Arquitetura do Gerador e Discriminador: Redes neurais projetadas para produzir e avaliar imagens.
- Função de Perda Wasserstein com Gradient Penalty: Garantindo suavidade na interpolação e um treinamento mais estável.
- Treinamento customizado: Ajustes detalhados para otimizar o desempenho do gerador e discriminador.
- Salvamento de modelos e exemplos gerados: Checkpoints para continuidade do treinamento e imagens geradas salvas para análise.
