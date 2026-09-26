# Credit Scoring: como os dados apoiam a avaliação de risco de crédito

## Sobre o projeto

Este projeto foi desenvolvido como parte do desafio do bootcamp Bradesco - GenAI & Dados da DIO, utilizando o NotebookLM como ferramenta de apoio à pesquisa, organização e consolidação do conhecimento.

O tema escolhido foi Credit Scoring, com foco em compreender como os dados são utilizados na avaliação do risco de crédito, quais abordagens podem ser utilizadas na construção de modelos e quais desafios estão relacionados ao uso de dados e Machine Learning nesse contexto.

## Contexto e objetivos

A análise de risco de crédito utiliza diferentes informações para apoiar decisões relacionadas à concessão de crédito.

O objetivo deste estudo é compreender:

- o que é Credit Scoring e qual sua finalidade;
- qual é o papel dos dados na avaliação do risco de crédito;
- quais tipos de dados podem ser utilizados;
- como modelos tradicionais se diferenciam de abordagens de Machine Learning;
- quais são os principais desafios relacionados à utilização de dados e modelos preditivos;
- como a explicabilidade pode contribuir para a interpretação dos modelos.

O resultado esperado é a construção de um miniguia introdutório sobre Credit Scoring, utilizando fontes abertas e o NotebookLM como apoio ao processo de pesquisa e estudo.

## Curadoria das fontes

Foram selecionadas cinco fontes abertas para compor o caderno temático no NotebookLM.

A seleção buscou reunir materiais institucionais e acadêmicos relacionados a Credit Scoring, risco de crédito, Machine Learning e explicabilidade.

| Fonte | Tema principal |
|---|---|
| Banco Central do Brasil — Análise dos efeitos do Cadastro Positivo | Dados de crédito e Cadastro Positivo |
| Aplicação de modelos credit scoring na análise da inadimplência de uma instituição de microcrédito | Modelos de Credit Scoring |
| Machine Learning for Enhanced Credit Risk Assessment: An Empirical Approach | Machine Learning e risco de crédito |
| Machine Learning for Credit Risk Prediction: A Systematic Literature Review | Machine Learning aplicado ao risco de crédito |
| Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data | Explicabilidade e SHAP |

### Fontes consultadas

- Banco Central do Brasil — [Análise dos efeitos do Cadastro Positivo](https://www.bcb.gov.br/content/publicacoes/Documents/outras_pub_alfa/analise_dos_efeitos_do_cadastro_positivo.pdf)
- Revista Ciências Administrativas — [Aplicação de modelos credit scoring na análise da inadimplência](https://ojs.unifor.br/rca/article/view/264)
- MDPI — [Machine Learning for Enhanced Credit Risk Assessment](https://www.mdpi.com/1911-8074/16/12/496)
- MDPI — [Machine Learning for Credit Risk Prediction: A Systematic Literature Review](https://www.mdpi.com/2306-5729/8/11/169)
- MDPI — [Explaining Deep Learning Models for Credit Scoring with SHAP](https://www.mdpi.com/1911-8074/16/4/221)

## Utilização do NotebookLM

O NotebookLM foi utilizado ao longo do projeto para explorar as fontes selecionadas, formular perguntas sobre o tema, comparar abordagens e organizar os principais conceitos identificados durante a pesquisa.

O processo também envolveu a revisão dos prompts a partir das respostas obtidas, buscando tornar as perguntas mais específicas e direcionadas.

## Engenharia de prompts e cicatrizes

### 1. Exploração inicial

**Prompt**

> O que é Credit Scoring, qual é sua finalidade e qual é o papel dos dados na avaliação do risco de crédito?

**Objetivo:** obter uma visão geral do tema e identificar os principais conceitos que precisariam ser aprofundados.

**Cicatriz:** a pergunta inicial era ampla e gerou uma resposta extensa. A partir disso, os próximos prompts foram formulados de maneira mais específica.

### 2. Aprofundamento sobre os dados

**Prompt**

> Quais são os principais tipos de dados utilizados na avaliação de risco de crédito e qual é a contribuição de cada um para o Credit Scoring? Apresente de forma objetiva, destacando apenas os aspectos mais relevantes.

**Objetivo:** entender quais informações podem ser utilizadas nos modelos e qual é a contribuição de cada categoria.

**Cicatriz:** a delimitação do escopo e a solicitação de objetividade ajudaram a obter uma resposta mais direcionada.

### 3. Comparação entre abordagens

**Prompt**

> Como os modelos tradicionais de Credit Scoring se diferenciam dos modelos que utilizam Machine Learning? Explique de forma objetiva as principais diferenças, vantagens e limitações de cada abordagem.

**Objetivo:** comparar as principais características das abordagens tradicionais e dos modelos baseados em Machine Learning.

**Cicatriz:** a comparação permitiu organizar o estudo a partir de aspectos como interpretabilidade, complexidade e capacidade de identificar padrões.

### 4. Análise dos desafios

**Prompt**

> Quais são os principais desafios de utilizar dados e modelos de Machine Learning para tomar decisões de crédito?

**Objetivo:** identificar os principais pontos de atenção relacionados à utilização de dados e modelos preditivos no contexto de crédito.

**Cicatriz:** essa etapa ampliou a análise para além da capacidade preditiva dos modelos, considerando também aspectos relacionados à qualidade dos dados, explicabilidade e utilização das informações.

## Miniguia de estudo

O conteúdo consolidado durante a pesquisa foi organizado em um miniguia com os principais conceitos estudados.

[ Acessar o Miniguia de Credit Scoring ](miniguia_credit_scoring.md)

O material apresenta:

- conceitos fundamentais de Credit Scoring;
- papel dos dados na avaliação de crédito;
- principais categorias de dados;
- modelos tradicionais e Machine Learning;
- principais desafios;
- conceitos relacionados à explicabilidade;
- glossário;
- prompts para aprofundamento do tema.

## Ferramentas utilizadas

- NotebookLM
- GitHub
- Markdown

## Estrutura do projeto

```text
├── assets/
│   ├── mapa-mental.png
│   └── arquitetura-credit-scoring.pdf
│
├── miniguia_credit_scoring.md
│
└── README.md
