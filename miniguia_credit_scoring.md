# Miniguia de Credit Scoring

## 1. Introdução

O Credit Scoring é uma abordagem utilizada para apoiar a avaliação do risco de crédito a partir da análise de diferentes informações sobre um indivíduo ou empresa.

Por meio de modelos estatísticos e, mais recentemente, técnicas de Machine Learning, os dados podem ser utilizados para identificar padrões associados ao comportamento de crédito e auxiliar na tomada de decisões.

Este miniguia apresenta os principais conceitos estudados durante a pesquisa, desde o papel dos dados até as diferenças entre modelos tradicionais e abordagens de Machine Learning.

---

## 2. O que é Credit Scoring?

Credit Scoring é uma metodologia utilizada para estimar o risco associado à concessão de crédito.

A partir de informações disponíveis sobre o cliente e seu histórico, um modelo pode produzir uma pontuação ou estimativa relacionada à probabilidade de determinado comportamento de crédito.

De forma simplificada:

**Dados → Modelo → Score/Estimativa de risco → Apoio à decisão**

O objetivo não é substituir completamente a análise de crédito, mas fornecer uma forma estruturada e quantitativa de apoiar esse processo.

---

## 3. Qual é o papel dos dados?

Os dados são a base para a construção e utilização de modelos de Credit Scoring.

A qualidade, a disponibilidade e a relevância das informações utilizadas influenciam diretamente a capacidade do modelo de identificar padrões relacionados ao risco de crédito.

Entre os dados que podem ser utilizados estão:

| Categoria | Exemplos |
|---|---|
| Histórico de crédito | pagamentos, atrasos, operações de crédito |
| Dados cadastrais | informações demográficas e socioeconômicas |
| Dados da operação | valor, prazo e características do crédito solicitado |
| Dados de relacionamento | histórico de relacionamento com instituições financeiras |
| Dados transacionais | movimentações e comportamento financeiro |
| Dados alternativos | informações digitais e outras fontes disponíveis |

A utilização de diferentes fontes de dados pode ampliar a quantidade de informações disponíveis para a análise, mas também exige atenção à qualidade, privacidade e adequação das informações utilizadas.

---

## 4. Cadastro Positivo

O Cadastro Positivo representa uma importante fonte de informações para a análise de crédito.

Enquanto uma análise baseada apenas em registros negativos pode concentrar-se em eventos de inadimplência, o histórico positivo permite considerar também informações relacionadas ao comportamento de pagamento.

Dessa forma, o histórico de crédito pode contribuir para uma avaliação mais baseada no comportamento observado do consumidor.

**Ponto principal:** dados de histórico de pagamento podem fornecer informações relevantes para a avaliação do risco de crédito.

**Fonte principal:** Banco Central do Brasil — *Análise dos efeitos do Cadastro Positivo*.

---

## 5. Modelos tradicionais de Credit Scoring

Os modelos tradicionais de Credit Scoring utilizam métodos estatísticos para relacionar características dos clientes e das operações com determinado resultado de crédito.

Um exemplo conhecido é a **regressão logística**, utilizada em problemas de classificação.

De forma simplificada, o modelo busca identificar como determinadas variáveis estão relacionadas à probabilidade de ocorrência de um evento, como inadimplência.

### Características

- metodologia estatística consolidada;
- maior facilidade de interpretação;
- estrutura relativamente mais simples;
- possibilidade de identificar a contribuição das variáveis para o resultado.

Essas características fazem com que modelos tradicionais continuem relevantes em aplicações de risco de crédito.

---

## 6. Credit Scoring com Machine Learning

Técnicas de Machine Learning podem ser utilizadas para desenvolver modelos capazes de identificar relações mais complexas entre as variáveis.

Entre os algoritmos encontrados na literatura estão:

- Random Forest;
- Gradient Boosting;
- XGBoost;
- redes neurais;
- outros métodos de classificação.

Uma diferença importante está na capacidade de alguns modelos de Machine Learning de capturar relações não lineares e interações mais complexas entre as variáveis.

Por outro lado, modelos mais complexos podem apresentar maior dificuldade de interpretação.

---

## 7. Modelos tradicionais x Machine Learning

| Aspecto | Modelos tradicionais | Machine Learning |
|---|---|---|
| Interpretabilidade | Geralmente maior | Pode ser menor em modelos complexos |
| Complexidade | Menor | Pode ser maior |
| Relações entre variáveis | Mais estruturadas | Pode capturar relações complexas |
| Transparência | Geralmente mais simples de explicar | Pode exigir técnicas adicionais |
| Exemplos | Regressão logística | Random Forest, XGBoost, redes neurais |

Não existe uma única abordagem que seja adequada para todos os contextos. A escolha depende das características dos dados, do objetivo do modelo e dos requisitos da aplicação.

---

## 8. Principais desafios

A utilização de dados e Machine Learning em decisões de crédito envolve desafios que vão além da escolha do algoritmo.

### Qualidade dos dados

Dados incompletos, inconsistentes ou incorretos podem prejudicar o desempenho do modelo.

### Desbalanceamento

Em problemas de crédito, determinados eventos podem ocorrer com menor frequência que outros. Isso pode gerar conjuntos de dados desbalanceados e exigir técnicas específicas de tratamento.

### Explicabilidade

Quanto mais complexo o modelo, maior pode ser a dificuldade para compreender por que determinada previsão foi produzida.

### Privacidade

Informações utilizadas na análise de crédito podem envolver dados pessoais e financeiros, exigindo cuidados relacionados à utilização e proteção dessas informações.

### Generalização

Um modelo precisa apresentar comportamento adequado não apenas nos dados utilizados durante seu desenvolvimento, mas também quando aplicado a novos casos.

---

## 9. Explicabilidade e SHAP

A explicabilidade busca tornar mais compreensível a relação entre as variáveis utilizadas pelo modelo e seus resultados.

Uma das técnicas estudadas nas fontes selecionadas é o **SHAP (SHapley Additive exPlanations)**.

O SHAP pode ser utilizado para analisar a contribuição das variáveis para uma determinada previsão.

Em um contexto de Credit Scoring, isso pode ajudar a responder perguntas como:

> Quais características contribuíram para determinado resultado do modelo?

Isso é especialmente relevante quando são utilizados modelos mais complexos, nos quais a relação entre entrada e resultado não é facilmente observável.

**Fonte relacionada:** *Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data*.

---

## 10. Fluxo simplificado de um modelo de Credit Scoring

```text
Coleta dos dados
       ↓
Tratamento e preparação
       ↓
Seleção/engenharia das variáveis
       ↓
Treinamento do modelo
       ↓
Avaliação do modelo
       ↓
Predição / Score
       ↓
Apoio à decisão de crédito
       ↓
Monitoramento
