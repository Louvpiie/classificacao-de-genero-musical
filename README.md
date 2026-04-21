# Classificação de Gênero Musical

Este projeto tem como objetivo analisar e classificar gêneros musicais utilizando técnicas de Data Science e Machine Learning. A principal característica deste repositório é a implementação paralela em **Python** e **R**, permitindo comparar abordagens, bibliotecas e resultados em ambas as linguagens.

-----

## Tecnologias e Ferramentas

O projeto está dividido em dois ecossistemas principais:

### **Python**

  * **Pandas & NumPy**: Manipulação e tratamento de dados.
  * **Scikit-Learn**: Implementação de algoritmos de classificação.
  * **Matplotlib / Seaborn**: Visualização de dados e matrizes de confusão.

### **R**

  * **Tidyverse**: Limpeza e manipulação de dados.
  * **Caret / Tidymodels**: Treinamento de modelos de aprendizado de máquina.
  * **ggplot2**: Gráficos estatísticos de alta qualidade.

-----

## Funcionalidades

  * **Análise Exploratória (EDA):** Identificação de padrões em características como *tempo*, *acousticness*, *danceability*, entre outras.
  * **Pré-processamento:** Tratamento de valores ausentes e normalização de escalas.
  * **Modelagem:** Treinamento de modelos para identificar automaticamente o gênero da música.

-----

## Equipe de Desenvolvimento

Projeto desenvolvido de forma colaborativa pelos integrantes:

  * **GABRYELLA SANTOS PINHO**
  * **LOUIE NERY SILVA**
  * **MARIA EDUARDA RITA MARQUES NOLETO**
  * **NATHANAEL VICTOR PAIVA MAGNO**
  * **RAMON MIGUEL ROSA PEREIRA ATAIDES**

-----

## Estrutura do Projeto

A organização dos diretórios segue a separação por linguagem de programação:

```bash
classificacao-de-genero-musical/
├── python/
│   ├── data/                # Datasets utilizados
│   ├── notebooks/           # Jupyter Notebooks com as análises
│   └── scripts/             # Scripts .py estruturados
├── r/
│   ├── scripts/             # Scripts .R
│   └── reports/             # Relatórios gerados em RMarkdown
├── README.md                # Documentação do projeto
└── .gitignore               # Arquivos ignorados pelo Git
```

-----

## Como Executar

### Para Python:

1.  Navegue até a pasta `python/`.
2.  Instale as dependências: `pip install -r requirements.txt`.
3.  Execute o notebook ou script principal.

### Para R:

1.  Abra o projeto no **RStudio**.
2.  Navegue até a pasta `r/`.
3.  Instale os pacotes necessários: `install.packages("tidyverse")`.
4.  Execute o script `.R`.
