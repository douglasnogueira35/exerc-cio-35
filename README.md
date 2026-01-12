Previsão de Renda
Este projeto tem como objetivo desenvolver e avaliar modelos estatísticos e de machine learning para prever a variável renda de indivíduos com base em características socioeconômicas.
Estrutura do Projeto
- Dados: Base previsao_de_renda2.csv contendo variáveis demográficas e financeiras.
- Pré-processamento:
- Substituição de valores ausentes pela média.
- Transformação logarítmica da variável renda.
- Exclusão das variáveis data_ref e index.
- Modelagem:
- Regressão linear (OLS).
- Avaliação de suposições do modelo (normalidade, independência, homocedasticidade).
- Diagnóstico de outliers e pontos influentes.
- Verificação de multicolinearidade (Spearman e VIF).
- Métricas: RMSE em treino e teste para comparação entre modelos originais e ajustados.
Objetivo
Validar a capacidade preditiva do modelo e identificar ajustes necessários para melhorar a performance e robustez da previsão de renda.

