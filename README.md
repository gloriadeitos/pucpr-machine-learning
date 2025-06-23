#### Glória Maria Deitos Gomes da Silva <br> 22.Junho.2025

# pucpr-machine-learning

<p align="center">
  <img src="https://github.com/gloriadeitos/gloriadeitos/blob/main/img/pucpr.png" alt="ufpr" height="100">
  <img src="https://github.com/gloriadeitos/gloriadeitos/blob/main/img/octacore.png" alt="octacore" height="100">
  <img src="https://github.com/gloriadeitos/gloriadeitos/blob/main/img/gloriadeitos-logo.png" alt="gloriadeitos-logo" height="100">
</p>

**Disciplina:** Técnicas de Machine Learning <br>
**Curso:** Análise e Desenvolvimento de Sistemas <br>
**Instituição:** Pontifícia Universidade Católica do Paraná (PUCPR) - Brasil  

<br>

## Notebook de Machine Learning - Atividade Somativa 1

### Descrição da Atividade
Este trabalho consiste na análise preditiva do dataset **NASA Airfoil Self-Noise** utilizando técnicas de Machine Learning. O objetivo é desenvolver um modelo de regressão para prever níveis de pressão sonora em aerofólios, seguindo o fluxo completo de uma solução de ML:

1. **Pré-processamento**:
   - Normalização com `StandardScaler`
   - Redução de dimensionalidade com `PCA`

2. **Modelagem**:
   - Implementação de `RandomForestRegressor`
   - Divisão 75%/25% (treino/teste)

3. **Avaliação**:
   - Métricas: `R²` e `MSE`
   - Análise de importância de features

### Estrutura do Projeto
O projeto é organizado em um notebook Jupyter (`analise.ipynb`) contendo:

1. **Análise Exploratória**:
   - Estatísticas descritivas
   - Matriz de correlação
   - Distribuição das variáveis

2. **Pipeline de ML**:
   ```python
   from sklearn.ensemble import RandomForestRegressor
   model = RandomForestRegressor()
   model.fit(X_train, y_train)
