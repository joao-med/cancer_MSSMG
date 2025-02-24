# Fatores Socioeconômicos e Mortalidade por Câncer: Modelagem Espacial Bayesiana na Macrorregião Sudeste de Saúde de Minas Gerais

## Visão Geral

Este projeto investiga a relação entre fatores socioeconômicos e mortalidade por câncer na Macrorregião Sudeste de Saúde de Minas Gerais (MSSMG), Brasil, utilizando técnicas de modelagem espacial bayesiana. O estudo abrange o período de 2010 a 2019 e analisa dados de 94 municípios da região.

O objetivo principal é explorar como as desigualdades socioeconômicas, medidas pelo Índice de Gini, influenciam as taxas de mortalidade por câncer. O projeto utiliza o método Integrated Nested Laplace Approximation (INLA) para realizar a análise espacial e gerar insights mais precisos sobre os padrões regionais de mortalidade por câncer.

## Dados

O conjunto de dados inclui informações sobre mortalidade por câncer (C00 a C97 e D46, CID-10) e variáveis socioeconômicas, como o Índice de Gini, PIB per capita e outros indicadores dos determinantes sociais da saúde. Os dados foram extraídos de bancos de dados públicos de saúde e abrangem 94 municípios da MSSMG.

OBS: OS DADOS UTULIZADOS ULTRAPASSAM O TAMANHO PERMITIDO PELO GITHUB E ESTÃO DISPONÍVEIS SOBRE DEMANDA, BASTA SOLICITAR VIA EMAIL: jpmedeirosg@gmail.com

## Metodologia

- **Pré-processamento dos Dados**: Limpeza de dados e seleção de variáveis relevantes com base em abordagens hierárquicas, teóricas e estatísticas.
- **Modelagem Espacial Bayesiana**: Aplicação de inferência bayesiana via INLA, incorporando efeitos aleatórios estruturados e não estruturados para contabilizar dependências espaciais e heterogeneidade.
- **Avaliação do Modelo**: Comparação de diferentes modelos utilizando o Deviance Information Criterion (DIC) para selecionar o modelo de melhor ajuste.

## Principais Resultados

- O Índice de Gini foi identificado como um preditor significativo da mortalidade por câncer na região.
- Padrões espaciais de mortalidade por câncer foram observados, com taxas mais altas na região sudeste e mais baixas na região centro-norte.
- O estudo destaca a importância de abordar as desigualdades socioeconômicas para reduzir a mortalidade por câncer.

## Como Utilizar

Para replicar ou dar continuidade a esta análise, clone o repositório e siga as instruções nos scripts fornecidos. Os dados e o código R estão disponíveis para rodar os modelos e gerar os resultados.

