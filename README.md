##Calculo de Métricas de Avaliação de Aprendizado##

Descrição do Projeto
Este projeto implementa um modelo de aprendizado de máquina para classificar dígitos manuscritos utilizando a base de dados MNIST. O objetivo principal é construir e avaliar um modelo que possa reconhecer números de 0 a 9 a partir de imagens.

Etapas do Projeto
Carregamento dos Dados: O conjunto de dados MNIST é carregado diretamente da biblioteca Keras, contendo 60.000 imagens de treinamento e 10.000 imagens de teste.

Pré-processamento: As imagens são normalizadas para que os valores dos pixels variem entre 0 e 1, facilitando o treinamento do modelo.

Criação do Modelo: Um modelo de rede neural densa é construído com uma camada oculta e uma camada de saída que utiliza a função de ativação softmax.

Treinamento do Modelo: O modelo é treinado usando o algoritmo Adam, com uma função de perda de entropia cruzada.

Avaliação do Modelo: Após o treinamento, o modelo é avaliado em um conjunto de teste, e uma matriz de confusão, bem como métricas de desempenho (acurácia, sensibilidade, precisão e F1 score) são calculadas para verificar a eficácia do modelo.

Resultados
O modelo alcançou uma acurácia de 97.7%, com altas pontuações de sensibilidade, precisão e F1 score, mostrando sua capacidade de classificar corretamente os dígitos manuscritos.

Exemplo de Matriz de Confusão

[[ 971    0    1    0    3    1    2    1    1    0]
 [   0 1127    2    1    0    1    2    1    1    0]
 [   1    6 1000    4    3    0    3    6    8    1]
 [   0    0    7  984    0    1    1    7    3    7]
 [   2    0    1    0  969    0    4    1    0    5]
 [   3    0    0   11    1  867    3    2    5    0]
 [   6    3    1    1    7    2  934    1    3    0]
 [   0    8    8    2    1    0    0  996    3   10]
 [   4    1    2    7    5    2    5    3  942    3]
 [   3    4    0    3   11    1    0    5    2  980]]
Métricas de Avaliação
Acurácia: 0.977
Sensibilidade (Recall): 0.9768
Precisão: 0.9771
F1 Score: 0.9769

Tecnologias Utilizadas

Python
TensorFlow/Keras
NumPy
Scikit-learn

Instruções
Para executar o código, você pode clonar este repositório e rodar o script em um ambiente Python com as bibliotecas necessárias instaladas, ou utilizar o Google Colab.

Como Clonar o Repositório
git clone https://github.com/Cris-noscore/Calculo-de-M-tricas-de-Avaliacao-de-Aprendizado.git

Instalando Dependências
pip install tensorflow scikit-learn

Executar o Código
Após instalar as dependências, você pode executar o script no seu ambiente local ou no Google Colab.
