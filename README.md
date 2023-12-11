
# Boston Housing Regression Trees

## Descrição
Este repositório contém um script em Python para treinar árvores de decisão na base de dados imobiliários de Boston. O objetivo é prever o valor mediano das casas ocupadas pelo proprietário.

## Passos

### 1. Formato dos Dados
Certifique-se de que a base de dados está no formato adequado para o scikit-learn.

### 2. Matriz de Correlação
Visualize a matriz de correlação para identificar variáveis com potencial preditivo.

### 3. Separação dos Dados
Separe os dados em conjuntos de treinamento e teste.

### 4. Treinamento de Árvores de Decisão
Treine duas árvores, uma com profundidade máxima = 8 e outra com profundidade máxima = 2.

### 5. Avaliação do Modelo
Calcule o MSE para cada árvore nos conjuntos de treinamento e teste.

### 6. Escolha da Árvore Adequada
Com base nos resultados, escolha a árvore mais adequada.

### 7. Visualização da Árvore de Decisão
Visualize graficamente a árvore de decisão treinada.

## Resultados

### Árvore com Profundidade 8:
- MSE Treinamento: 1.95
- MSE Teste: 8.98

### Árvore com Profundidade 2:
- MSE Treinamento: 25.65
- MSE Teste: 25.99

Com base nos resultados, a árvore com profundidade 8 é mais adequada devido ao menor MSE nos dados de teste.

## Visualização Gráfica da Árvore
Uma representação gráfica da árvore de decisão é disponibilizada para facilitar a análise.

## Como Executar
Certifique-se de ter todas as bibliotecas necessárias instaladas e execute o script Python.

## Autor
Leandro Amadeu Lima Dias

## Licença
Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.
