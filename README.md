# Credit Scoring: como os dados apoiam a avaliação de risco de crédito

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte do bootcamp Bradesco - GenAI e Dados da DIO e tem como objetivo explorar o conceito de **Credit Scoring** e compreender como diferentes tipos de dados podem apoiar a avaliação do risco de crédito.

O estudo utiliza o **NotebookLM** como ferramenta de aprendizagem ativa, combinando curadoria de fontes, elaboração e refinamento de prompts, análise das respostas e organização do conhecimento em um miniguia de estudo.

---

## 🎯 Contexto e Objetivos

### Contexto

A avaliação de risco de crédito é uma atividade importante para instituições financeiras, pois busca estimar a probabilidade de um cliente cumprir suas obrigações financeiras.

Com a evolução da disponibilidade de dados e das técnicas de análise, os modelos de Credit Scoring passaram a incorporar diferentes informações e métodos estatísticos e de Machine Learning.

### Objetivos

- Compreender o conceito de Credit Scoring e sua finalidade;
- Identificar os principais tipos de dados utilizados na avaliação de risco de crédito;
- Entender a diferença entre modelos tradicionais de Credit Scoring e modelos de Machine Learning;
- Conhecer os principais desafios relacionados ao uso de dados na tomada de decisões de crédito;
- Utilizar o NotebookLM como ferramenta de pesquisa, questionamento e organização do conhecimento;
- Consolidar os aprendizados em um miniguia de estudo.

---

## 📚 Curadoria de Fontes

Foram selecionadas cinco fontes para compor o caderno temático no NotebookLM, buscando combinar fontes institucionais e estudos acadêmicos sobre crédito, Credit Scoring, dados e Machine Learning.

1. Banco Central do Brasil — Análise dos efeitos do Cadastro Positivo
2. Aplicação de modelos Credit Scoring na análise da inadimplência de uma instituição de microcrédito
3. Machine Learning for Enhanced Credit Risk Assessment: An Empirical Approach
4. Machine Learning for Credit Risk Prediction: A Systematic Literature Review
5. Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data

---

## 🤖 Engenharia de Prompts e "Cicatrizes"

O processo de pesquisa foi realizado de forma iterativa no NotebookLM. As perguntas foram sendo refinadas de acordo com as respostas obtidas, buscando tornar as consultas mais específicas e úteis para o estudo.

### Prompt 1 — Exploração inicial

> O que é Credit Scoring, qual é sua finalidade e qual é o papel dos dados na avaliação do risco de crédito?

**Observação:**

A resposta apresentou uma visão ampla do tema, abordando conceitos como Credit Scoring, dados utilizados, Cadastro Positivo, Machine Learning, Open Banking e desafios relacionados aos modelos.

**Aprendizado:**

A pergunta ampla foi útil para obter uma visão geral do assunto, mas resultou em uma resposta extensa e com diversos conceitos diferentes.

---

### Prompt 2 — Aprofundamento sobre os dados

> Quais são os principais tipos de dados utilizados na avaliação de risco de crédito e qual é a contribuição de cada um para o Credit Scoring? Apresente de forma objetiva, destacando apenas os aspectos mais relevantes.

**Observação:**

A resposta passou a concentrar-se especificamente nos tipos de dados utilizados e na contribuição de cada categoria para a avaliação do risco.

**Aprendizado:**

A delimitação do tema tornou a resposta mais direcionada e facilitou a identificação das principais categorias de dados.

---

### Prompt 3 — Comparação entre modelos

> Como os modelos tradicionais de Credit Scoring se diferenciam dos modelos que utilizam Machine Learning? Explique de forma objetiva as principais diferenças, vantagens e limitações de cada abordagem.

**Observação:**

A resposta permitiu comparar técnicas estatísticas tradicionais com abordagens de Machine Learning, considerando aspectos como interpretabilidade, capacidade preditiva, complexidade e tipos de dados.

**Aprendizado:**

Perguntas comparativas ajudaram a organizar conceitos diferentes dentro de uma mesma estrutura de análise.

---

### Prompt 4 — Análise crítica

> Quais são os principais desafios de utilizar dados e modelos de Machine Learning para tomar decisões de crédito?

**Observação:**

A resposta destacou desafios relacionados à qualidade dos dados, desbalanceamento, explicabilidade, privacidade e complexidade dos modelos.

**Aprendizado:**

A inclusão de perguntas críticas permitiu ir além das vantagens dos modelos e considerar também suas limitações e riscos.

---

## 📖 Miniguia de Estudo

### 1. O que é Credit Scoring?

Credit Scoring é uma metodologia utilizada para estimar o risco de crédito de um indivíduo ou empresa a partir de informações disponíveis sobre seu perfil e comportamento financeiro. O resultado pode ser representado por uma pontuação ou probabilidade associada ao risco de inadimplência.

---

### 2. O papel dos dados

Os dados são utilizados como base para a construção e aplicação dos modelos de avaliação de risco.

| Tipo de dado | Exemplos | Contribuição |
|---|---|---|
| Histórico de crédito | Pagamentos, atrasos e inadimplência | Auxilia na avaliação do comportamento de pagamento |
| Dados financeiros | Renda e compromissos financeiros | Apoia a avaliação da capacidade de pagamento |
| Dados da operação | Valor, prazo e modalidade do crédito | Permite avaliar as características da operação |
| Dados transacionais | Movimentações e saldos | Pode complementar a análise do comportamento financeiro |
| Cadastro Positivo | Histórico de pagamentos | Amplia as informações disponíveis sobre o comportamento de pagamento |

---

### 3. Modelos tradicionais x Machine Learning

| Característica | Modelos tradicionais | Machine Learning |
|---|---|---|
| Abordagem | Técnicas estatísticas | Algoritmos de aprendizado |
| Principal característica | Maior facilidade de interpretação | Capacidade de identificar padrões complexos |
| Dados | Geralmente estruturados | Pode trabalhar com diferentes tipos de dados |
| Vantagem | Simplicidade e interpretabilidade | Potencial de maior capacidade preditiva |
| Limitação | Pode ter dificuldade com relações complexas | Maior complexidade e menor interpretabilidade |

---

### 4. Principais desafios

- Qualidade e consistência dos dados;
- Dados ausentes e desbalanceamento das classes;
- Explicabilidade dos modelos;
- Privacidade e uso adequado das informações;
- Complexidade operacional e computacional.

---

## 📖 Glossário

**Credit Scoring**  
Metodologia utilizada para avaliar e estimar o risco de crédito.

**Risco de crédito**  
Possibilidade de que uma obrigação financeira não seja cumprida conforme o acordado.

**Inadimplência (default)**  
Não cumprimento de uma obrigação de pagamento.

**Cadastro Positivo**  
Conjunto de informações relacionadas ao histórico de pagamentos e adimplemento de consumidores.

**Machine Learning**  
Conjunto de técnicas que permite que modelos identifiquem padrões em dados para realizar previsões ou classificações.

**XAI (Explainable Artificial Intelligence)**  
Abordagens destinadas a tornar as decisões de modelos de Inteligência Artificial mais compreensíveis.

**SHAP**  
Método utilizado para interpretar a contribuição das variáveis para as previsões de determinados modelos de Machine Learning.

---

## 🔄 Prompts Reutilizáveis

- Explique o conceito de Credit Scoring e sua finalidade utilizando exemplos práticos.
- Quais tipos de dados podem contribuir para a avaliação do risco de crédito?
- Compare modelos tradicionais de Credit Scoring com modelos de Machine Learning.
- Quais são os principais riscos e limitações do uso de Machine Learning em decisões de crédito?
- Explique um conceito de risco de crédito utilizando uma situação prática do cotidiano.

---

## 💡 Principais aprendizados

O desenvolvimento deste projeto permitiu compreender como dados, técnicas estatísticas e Machine Learning podem ser utilizados na avaliação de risco de crédito.

Além do conteúdo financeiro, o projeto também demonstrou como o uso iterativo de prompts pode transformar uma ferramenta de Inteligência Artificial em um recurso de aprendizagem ativa, permitindo explorar um tema, identificar lacunas e refinar as perguntas para obter respostas mais direcionadas.
