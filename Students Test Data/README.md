# Modelagem Preditiva do Desempenho Acadêmico"

Este repositório contém uma análise detalhada do desempenho acadêmico dos alunos da fictícia "University of Exampleville", bem como modelos preditivos desenvolvidos para prever o desempenho futuro com base em atributos fornecidos.

## Índice

1. [Introdução](#introdução)
2. [Estrutura do Repositório](#estrutura-do-repositório)
3. [Como Usar](#como-usar)
4. [Resultados Principais](#resultados-principais)
5. [Referências](#referências)

## Introdução

O projeto foca na análise e previsão do desempenho acadêmico dos alunos da fictícia "University of Exampleville". O conjunto de dados, originário do Kaggle, oferece uma visão abrangente dos resultados dos exames dos alunos em diversas especializações, semestres e domínios de avaliação. Através de uma análise exploratória profunda, identificamos padrões, tendências e correlações significativas que lançam luz sobre fatores que influenciam o desempenho acadêmico. Posteriormente, utilizando técnicas avançadas de aprendizado de máquina, desenvolvemos modelos preditivos para prever o desempenho acadêmico futuro dos alunos. Estes modelos, após otimização, demonstraram uma alta capacidade de prever o desempenho com precisão, sendo de potencial valor para instituições educacionais que buscam entender e melhorar o desempenho dos alunos.

## Estrutura do Repositório

- `analise_exploratoria.ipynb`: Notebook Jupyter contendo a análise exploratória dos dados.
- `modelos_preditivos.ipynb`: Notebook Jupyter detalhando a construção e avaliação dos modelos preditivos.
- `Private_data.csv`: Conjunto de dados utilizado para a análise e modelagem.
- `documentação.pdf`: Relatório detalhado contendo a documentação completa do projeto.

## Como Usar

1. Clone este repositório para sua máquina local.
2. Instale as dependências necessárias listadas nos notebooks.
3. Abra e execute os notebooks `analise_exploratoria.ipynb` e `modelos_preditivos.ipynb` em sua ordem.
4. Consulte o relatório `documentação.pdf` para uma descrição detalhada e contextualizada do projeto e seus resultados.

## Resultados Principais

* **Análise Exploratória:** A análise revelou que a maioria dos alunos possui desempenho na faixa intermediária, com poucos alcançando extremos de alto ou baixo desempenho. Além disso, observou-se que a especialização escolhida pelos alunos desempenha um papel significativo em suas pontuações no domínio específico do exame. Também identificamos uma forte correlação entre as pontuações de gestão geral e domínio específico, indicando uma consistência no desempenho dos alunos entre diferentes áreas de avaliação.

* **Modelagem Preditiva:** Diversos modelos de aprendizado de máquina foram testados e otimizados. O modelo de Floresta Aleatória destacou-se como o mais eficaz, alcançando um coeficiente de determinação (R²) de 0.998, o que indica uma alta capacidade do modelo em prever o desempenho acadêmico com base nos atributos fornecidos. Outros modelos, como Gradient Boosting e XGBoost, também apresentaram resultados promissores, mas foram ligeiramente superados pela Floresta Aleatória no contexto deste projeto.



## Referências
[Dataset Kaggle]([https://](https://www.kaggle.com/datasets/atharvbharaskar/students-test-data))
<https://www.kaggle.com/datasets/atharvbharaskar/students-test-data>



