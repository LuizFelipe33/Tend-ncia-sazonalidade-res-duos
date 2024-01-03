# Projeto de Análise de Dados da População Alemã ao Longo dos Anos

## Descrição
Este projeto analisa dados da população alemã, aplicando diversas técnicas de análise de séries temporais e modelos preditivos, incluindo Box Plot, Decomposição de Séries Temporais, Holt-Winters, SARIMA, Random Forest, MLP, LSTM e CNN.

## Objetivo
Explorar padrões temporais na população alemã e construir modelos preditivos para comparar e avaliar o desempenho de diferentes abordagens.

## Metodologia

### Análise de Séries Temporais

1. **Box Plot:**
   - Visualização das estatísticas descritivas e detecção de outliers.

2. **Decomposição de Séries Temporais:**
   - Decomposição nos componentes de tendência, sazonalidade e resíduos.

### Modelos Preditivos

3. **Holt-Winters:**
   - Aplicação do método de Holt-Winters com treinamento nos anos de 1856 a 1999 e teste nos anos de 2000 a 2005.
   - Cálculo do erro de predição.

4. **SARIMA:**
   - Implementação do modelo SARIMA com treinamento nos anos de 1960 a 2000 e teste nos anos de 2001 a 2019.
   - Cálculo do erro de predição.

5. **Random Forest:**
   - Criação de um modelo Random Forest usando os dados da série temporal e atributos mais importantes.

6. **MLP (Multilayer Perceptron):**
   - Desenvolvimento de um modelo MLP utilizando técnicas de otimização de hiperparâmetros para melhorar o desempenho.

7. **LSTM (Long Short-Term Memory):**
   - Construção de um modelo LSTM utilizando os dados da série temporal e atributos mais importantes.

8. **CNN (Convolutional Neural Network):**
   - Criação de uma CNN para comparar com os modelos anteriores.

### Comparação de Modelos

9. **Avaliação e Comparação:**
   - Comparação de desempenho entre os modelos Holt-Winters, SARIMA, Random Forest, MLP, LSTM e CNN.

## Resultados
Os resultados obtidos proporcionam uma visão abrangente sobre a eficácia dos diferentes modelos na predição da população alemã, permitindo a identificação do método mais adequado para este contexto.

## Tecnologias Utilizadas
- Python
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn
- TensorFlow/Keras
- Random Forest
- LSTM
- CNN
