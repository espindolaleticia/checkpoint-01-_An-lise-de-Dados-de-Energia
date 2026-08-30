# Análise de Dados — Soluções em Energias Renováveis e Sustentáveis

Felipe Mitsuo Takahashi Stephano RM570692

Laura Godoy Callegari RM569181

Letícia Araújo Espindola RM569308

Mariana Dreset Carbollan RM569207

Milena de Aguiar Lopes Cardoso RM570599

## Sobre o projeto

Este projeto apresenta uma atividade prática de **análise e preparação de dados do setor de energia**, utilizando **Orange Data Mining, Python e Pandas**.

Objetivo:
Aplicar os procedimentos trabalhados em aula para preparar, inspecionar e analisar diferentes conjuntos de dados do setor de energia, relacionando cada operação realizada ao contexto do dataset.

A atividade foi desenvolvida a partir de seis datasets, divididos entre os integrantes do grupo.


## Datasets analisados

| # | Dataset                                         | Fonte  | Tema                                                      |
| - | ----------------------------------------------- | ------ | --------------------------------------------------------- |
| 1 | Appliances Energy Prediction                    | UCI    | Consumo de eletrodomésticos e condições ambientais        |
| 2 | Steel Industry Energy Consumption               | UCI    | Consumo energético industrial                             |
| 3 | Power Consumption of Tetouan City               | UCI    | Consumo elétrico de três zonas e variáveis meteorológicas |
| 4 | Solar Power Generation Data                     | Kaggle | Geração de energia solar e dados de inversores            |
| 5 | Wind & Solar Energy Production Dataset          | Kaggle | Comparação entre geração eólica e solar                   |
| 6 | Individual Household Electric Power Consumption | UCI    | Consumo elétrico residencial                              |

A relação dos seis datasets e fontes é apresentada no enunciado da atividade.

## Ferramentas utilizadas

* **Orange Data Mining** — preparação, seleção e amostragem dos dados;
* **Python** — desenvolvimento das análises;
* **Pandas** — manipulação dos DataFrames;
* **Jupyter Notebook / Google Colab** — execução e documentação dos códigos.

# Modo de fazer

O trabalho foi dividido em duas etapas principais:

**1. Orange Data Mining**

Os datasets foram carregados, inspecionados e preparados. Foram selecionados os atributos necessários, verificadas possíveis inconsistências e valores ausentes e quando solicitado realizadas amostragens dos dados para posterior análise.

**2. Python / Pandas**

As amostras preparadas foram carregadas no Python. Foram realizadas operações de organização dos atributos, análise estatística, identificação de valores máximos e médios, aplicação de filtros, criação de novos DataFrames, contagem de registros e cálculo de percentuais.

Por fim, os resultados foram interpretados considerando o contexto de cada dataset. Essa organização segue a estrutura proposta na atividade.


## Fontes dos dados

Os dados utilizados foram obtidos a partir das seguintes plataformas:

* **UCI Machine Learning Repository** — datasets 1, 2, 3 e 6;
* **Kaggle** — datasets 4 e 5.

As fontes estão indicadas no material da atividade e correspondem aos conjuntos de dados utilizados nas análises.

## Desafio final

Situação-problema
Uma equipe de planejamento energético precisa analisar o comportamento da carga elétrica de uma região atendida pelo Sistema Interligado Nacional (SIN).

Os dados serão obtidos diretamente de uma API pública do Operador Nacional do Sistema Elétrico (ONS). A conexão com a API e a preparação inicial do JSON já estão fornecidas. A partir daí, sua equipe deverá construir o DataFrame, organizar os dados, criar recortes, calcular indicadores, produzir gráficos e elaborar um relatório técnico.

## Estrutura do Projeto

```text
analise-dados-energia/
│
├── 📄 README.md
│
├── 📓 notebooks/
│   ├── cp_01_sers.ipynb
│   └── Desafio_Final_Energia_ONS_API_Final_(1)_(1).ipynb
│
└── 📊 datasets/
    ├── dataset1.csv
    ├── dataset2.csv
    ├── dataset3.csv
    ├── dataset4.csv
    ├── dataset5.csv
    └── dataset6.csv
```


