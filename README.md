# knn_iris_classifier
Implementar um classificador KNN utilizando o dataset Iris e analisar métricas de desempenho utilizando diferentes valores de k.

🤖 KNN (K-Nearest Neighbors)

O KNN é um algoritmo de classificação baseado em proximidade.

Funcionamento:
1. Calcula a distância entre a nova amostra e todas as amostras do treinamento.
2. Seleciona os K vizinhos mais próximos.
3. A classe mais frequente entre esses vizinhos é escolhida como resultado.

Exemplo:
- K = 3
- O algoritmo analisa os 3 vizinhos mais próximos.
- A classe mais frequente será a classificação final.
  
## Acurácia

A acurácia mede a porcentagem total de acertos do modelo.

\[
Acurácia = \frac{Acertos}{Total}
\]

## Precisão (Precision)

A precisão mede quantas previsões positivas estavam corretas.

\[
Precisão = \frac{VP}{VP + FP}
\]

Onde:
- VP = Verdadeiros Positivos
- FP = Falsos Positivos

## Recall

O recall mede quantos casos positivos reais foram encontrados pelo modelo.

\[
Recall = \frac{VP}{VP + FN}
\]

Onde:
- FN = Falsos Negativos

## F1-Score

O F1-score combina precisão e recall em uma única métrica.

\[
F1 = 2 \cdot \frac{Precisão \cdot Recall}{Precisão + Recall}
\]

Quanto mais próximo de 1, melhor o desempenho do modelo.


Acurácia= Acertos/Total

Quanto maior a acurácia, melhor o desempenho geral.



