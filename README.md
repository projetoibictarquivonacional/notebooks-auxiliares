# notebooks-auxiliares
Notebooks auxiliares utilizados na etapa de criação da revisão de literatura no projeto de pesquisa **Inteligência Artificial para Transcrição Paleográfica de Manuscritos** entre o Ibict e o Arquivo Nacional.

## Objetivos:

O objetivo principal é implementar a classificação _few-shot_ treinando nosso aprendiz com múltiplos ciclos de poucos exemplos provenientes de conjuntos de dados utilizando apenas o título concatenado com o _abstract_ dos artigos, de modo a poupar tempo dos pesquisadores ao auxiliá-los no processo de classificação dos artigos em uma revisão sistemática de literatura ([Few-shot Approach for Systematic Literature Review Classifications](https://www.scitepress.org/Link.aspx?doi=10.5220/0011526400003318)).

+ Uso da base do [Semantic Scholar](https://www.semanticscholar.org/) para busca e requisição dos dados e metadados com o _wrapper_ [S2Query](https://github.com/BecomeAllan/S2Query), desenvolvido no LAMFO;
+ Uso do Modelo-Agnóstico de Meta-Aprendizagem de Primeira Ordem (MAML) com SciBERT para auxílio na classificação de artigos em uma Revisão Sistemática de Literatura. Modelo desenvolvido no âmbito de um projeto de pesquisa recente executado pelo LAMFO .

## Dependências:

* python (3.7.13)
* pytorch (1.11.0)
* transformers (4.16.2)
* torchmetrics (0.8.0)
* matplotlib (3.5.1)

## Referência:

Kely de Melo, M.; Faria, A.; Weigang, L.; Nery, A.; R. de Oliveira, F.; Barreiro, I. and Celestino, V. (2022). Few-shot Approach for Systematic Literature Review Classifications. In Proceedings of the 18th International Conference on Web Information Systems and Technologies - WEBIST; ISBN 978-989-758-613-2; ISSN 2184-3252, SciTePress, pages 33-44. DOI: 10.5220/0011526400003318.