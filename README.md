# Projeto 1 Taxa-de-aprendizado RNA

##  Objetivo

O objetivo deste projeto é pôr em prática os aprendizados da 1° unidade da disciplina a fim de desenvolver uma RNA capaz de identificar os dígitos de 0 a 9 do dataset MNIST e analisar seu comportamento sob diferentes taxas de aprendizado.  
Como trata-se de um dataset simples, servirá como uma avaliação para desempenho do algoritmo. Espera-se obter essa avaliação através de algumas métricas, como o gráfico da evolução por época à partir das diferentes taxas de aprendizado, perda e acurácia por época, além da matriz de confusão e comportamento sob ruído Gaussiano.
torch – Biblioteca principal do PyTorch para computação com tensores.

##  Bibliotecas utilizadas 

torch.nn – Submódulo do PyTorch para criar redes neurais.
torch.optim – Submódulo do PyTorch para otimizadores (ex: SGD, Adam).
torchvision.datasets e torchvision.transforms – Para carregar e transformar datasets de imagens.
numpy (np) – Para operações numéricas.
matplotlib.pyplot (plt) – Para visualização gráfica.
seaborn (sns) – Para visualizações estatísticas mais elegantes.
sklearn.metrics.confusion_matrix – Para gerar a matriz de confusão (avaliação de modelos de classificação).

## O ruído Gaussiano foi adicionado com o seguinte script/link:

📁 ruido_gaussiano.py ou 🔗 Notebook no Colab

O ruído é adicionado às imagens para avaliar a robustez da RNA sob condições adversas.


