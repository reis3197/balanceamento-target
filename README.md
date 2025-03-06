# balanceamento-target
📊 Machine Learning: A importância de balancear a variável Target em modelos de classificação 🤖

Hoje quero compartilhar um tema essencial para quem trabalha com modelos de classificação em Machine Learning: o balanceamento da variável Target.

🔎 Quando criamos um modelo de classificação, a variável alvo (ou Target) é aquela que queremos prever, geralmente representada por valores como "Sim ou Não", "True ou False" ou simplesmente 0 e 1.
Mas você sabia que, se essa variável estiver desbalanceada, seu modelo pode ficar completamente enviesado? Isso acontece porque, em casos de forte desbalanceamento (por exemplo, 95% das amostras sendo "Não" e apenas 5% sendo "Sim"), o modelo pode aprender a simplesmente prever sempre a classe majoritária — e, mesmo assim, obter uma alta acurácia. Porém, esse resultado é ilusório e prejudica a qualidade da previsão.

⚠️ Quais problemas o desbalanceamento pode causar?
Modelos enviesados que ignoram a classe minoritária.
Métricas como acurácia se tornam enganosas.
Menor capacidade de generalização do modelo.

✅ Como resolver isso? Existem várias técnicas para balancear a variável Target, como:

Oversampling: aumentar artificialmente a quantidade de registros da classe minoritária.
Undersampling: reduzir a quantidade de registros da classe majoritária.
SMOTE: técnica de oversampling que cria novos exemplos sintéticos da classe minoritária.

Se você trabalha com Data Science, Análise de Dados ou Machine Learning, vale sempre conferir como está a distribuição da sua variável alvo antes de treinar o modelo. Um pequeno ajuste nesse ponto pode fazer toda a diferença nos resultados!
