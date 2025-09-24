Análise de Desempenho no ENEM 2020: Escolas Públicas E Privadas
📋 Sobre o Projeto
Este projeto de análise de dados explora o desempenho de estudantes no Exame Nacional do Ensino Médio (ENEM) de 2020, com o objetivo de investigar a relação entre o tipo de escola (pública ou privada) e as notas obtidas nas provas. A análise foi realizada com base nos microdados oficiais do exame, aplicando técnicas estatísticas e de visualização de dados para testar uma hipótese central.

🎯 Hipótese
A hipótese principal é que alunos de escolas privadas obtiveram notas médias mais altas no ENEM 2020 do que alunos de escolas públicas.

⚙️ Metodologia
A análise seguiu as seguintes etapas:

Coleta e Filtragem de Dados: Os dados foram carregados a partir do arquivo MICRODADOS_ENEM_2020.csv. O dataset foi filtrado para incluir apenas participantes que cursaram o ensino médio em escolas públicas ou privadas.

Análise Descritiva: Foram calculadas a média, o desvio padrão e o número de participantes para cada uma das cinco provas do ENEM (Redação, Ciências da Natureza, Ciências Humanas, Linguagens e Matemática).

Teste de Normalidade: Foi utilizado o teste de Shapiro-Wilk para verificar se as distribuições das notas seguiam uma curva normal. Os resultados indicaram a não-normalidade dos dados, justificando a escolha de um teste não paramétrico.

Teste de Hipótese: O Teste de Mann-Whitney U foi aplicado para determinar se a diferença nas notas médias entre os grupos era estatisticamente significativa.

Visualização: Foram criados boxplots para ilustrar a distribuição das notas e a presença de outliers em cada grupo.

📈 Resultados e Conclusão
A análise estatística confirmou a hipótese inicial. O Teste de Mann-Whitney U mostrou que a diferença nas notas médias entre alunos de escolas públicas e privadas é estatisticamente significativa em todas as áreas do conhecimento.

Notas Médias: Alunos de escolas privadas obtiveram, em média, notas consistentemente mais altas em todas as provas, como demonstrado nos cálculos de média.

Significância: O valor de p em todos os testes foi muito menor que 0.05, indicando que a diferença não é aleatória.

Esta análise destaca a disparidade educacional no Brasil, sugerindo que fatores socioeconômicos e a diferença nos recursos escolares podem ter um impacto direto no desempenho dos estudantes no ENEM.

🛠️ Tecnologias Utilizadas
Python

Pandas: Para manipulação e análise dos dados.

Matplotlib e Seaborn: Para a criação de gráficos e visualizações.

SciPy: Para a realização dos testes estatísticos (Shapiro-Wilk e Mann-Whitney U).

Numpy: Para operações numéricas.