# Projeto1_Equipe_PANDAS
## Análise de Dados e Modelagem - Titanic
Projeto de análise exploratória e preditiva utilizando o dataset clássico do Titanic.

O objetivo foi aplicar técnicas de limpeza, visualização e machine learning para entender e prever a sobrevivência dos passageiros.

### O que foi feito
- Importação e exploração inicial do dataset.
- Tratamento de dados ausentes e transformação de variáveis categóricas.
- Treinamento de modelos preditivos (para analisar a sobrevivencia dos passageiros): Regressão Logística e Árvore de Decisão.
- Avaliação de desempenho com métricas de classificação.

### Resultados dos Modelos
#### Regressão Logística
- Accuracy: 0.81
- Precision: 0.79
- Recall: 0.73
- F1-Score: 0.76
- AUC-ROC: 0.79

#### Árvore de Decisão
- Accuracy: 0.79
- Precision: 0.84
- Recall: 0.63
- F1-Score: 0.72
- AUC-ROC: 0.77

**A Regressão Logística apresentou melhor equilíbrio entre precisão e recall, enquanto a Árvore de Decisão teve maior precisão, mas menor recall.**

### Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
