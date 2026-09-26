# Miniguia de Credit Scoring

## Introdução

A concessão de crédito envolve a necessidade de avaliar o risco associado a cada cliente e operação. Para apoiar esse processo, instituições financeiras utilizam diferentes informações sobre o cliente, seu histórico de crédito e as características da operação.

Nesse contexto, o Credit Scoring utiliza dados e modelos de análise para estimar o risco de crédito e apoiar decisões relacionadas à concessão de crédito.

Este miniguia reúne os principais conceitos estudados durante a pesquisa realizada com apoio do NotebookLM, abordando o papel dos dados, o histórico de crédito, os modelos de Credit Scoring, os principais desafios e, de forma complementar, a utilização de Machine Learning e técnicas de explicabilidade.

## Acesso ao NotebookLM

O conteúdo deste miniguia foi desenvolvido a partir da exploração das fontes selecionadas no NotebookLM.

**Notebook temático:** [Acessar o notebook no NotebookLM](https://notebook.google.com/notebook/f8219e5e-2a4e-4049-a6af-d41e960b1fd2)

---

## 1. O que é Credit Scoring?

Credit Scoring é uma metodologia utilizada para apoiar a avaliação do risco de crédito por meio da análise de diferentes informações sobre um cliente ou uma operação.

A partir das características observadas nos dados, um modelo pode estimar a probabilidade de determinado comportamento de crédito e gerar uma pontuação ou classificação de risco.

De forma simplificada:

**Dados → Tratamento e análise → Modelo de Credit Scoring → Score ou estimativa de risco → Apoio à decisão de crédito**

O Credit Scoring permite estruturar a análise de crédito de maneira quantitativa, utilizando padrões identificados nos dados para apoiar o processo de decisão.

É importante destacar que o score é uma ferramenta de apoio. A decisão de crédito pode envolver outros critérios, políticas e informações além do resultado de um modelo.

---

## 2. Qual é o papel dos dados?

Os dados são a base para a construção e utilização de modelos de Credit Scoring.

Informações relacionadas ao histórico de crédito, características do cliente e características da operação podem fornecer evidências utilizadas na avaliação do risco.

Algumas categorias de dados que podem ser consideradas são:

| Categoria | Exemplos |
|---|---|
| Histórico de crédito | pagamentos, atrasos e operações anteriores |
| Dados cadastrais | informações demográficas e socioeconômicas |
| Dados da operação | valor, prazo e características do crédito solicitado |
| Relacionamento financeiro | histórico de relacionamento com instituições financeiras |
| Dados transacionais | movimentações e comportamento financeiro |
| Dados alternativos | outras informações disponíveis para análise de crédito |

A utilização dessas informações depende do contexto da instituição, da disponibilidade dos dados e das regras aplicáveis ao seu uso.

Além da quantidade de informações disponíveis, a qualidade dos dados é fundamental. Informações incompletas, inconsistentes ou incorretas podem comprometer as análises realizadas.

### Um ponto importante

Um modelo não é melhor simplesmente por utilizar uma quantidade maior de variáveis.

É necessário avaliar se as informações utilizadas são relevantes para o problema, possuem qualidade adequada e podem ser utilizadas de forma apropriada.

---

## 3. Histórico de crédito e Cadastro Positivo

O histórico de crédito é uma importante fonte de informação para a avaliação do risco.

Registros relacionados ao comportamento de pagamento podem ajudar a identificar padrões associados ao cumprimento das obrigações financeiras.

Nesse contexto, o Cadastro Positivo permite considerar informações relacionadas ao histórico de pagamentos e não apenas registros de inadimplência.

Isso amplia o conjunto de informações que pode ser utilizado na avaliação do comportamento de crédito.

### Exemplo

Considere dois clientes que estão solicitando uma operação de crédito.

Além das informações cadastrais e da operação solicitada, pode ser relevante observar informações relacionadas ao histórico de pagamentos de cada um.

O comportamento observado ao longo do tempo pode fornecer informações adicionais para a avaliação do risco.

### Ponto principal

O histórico de pagamentos pode fornecer informações relevantes para diferenciar diferentes perfis de comportamento de crédito.

**Fonte relacionada:** Banco Central do Brasil — *Análise dos efeitos do Cadastro Positivo*.

---

## 4. Como funciona uma avaliação de risco de crédito?

De forma simplificada, uma análise de risco de crédito pode envolver diferentes etapas:

**Coleta das informações → Tratamento e organização dos dados → Análise das características relevantes → Aplicação do modelo → Estimativa do risco → Apoio à decisão → Acompanhamento dos resultados**

### 4.1 Coleta

São reunidas as informações disponíveis e relevantes para o problema analisado.

### 4.2 Tratamento

Os dados podem precisar de ajustes antes de serem utilizados, como tratamento de valores ausentes, inconsistências e formatos diferentes.

### 4.3 Seleção das informações

Nem toda informação disponível necessariamente deve ser utilizada. É necessário avaliar quais variáveis são relevantes para o objetivo do modelo.

### 4.4 Modelagem

Os dados são utilizados para desenvolver um modelo capaz de estimar determinado resultado de crédito.

### 4.5 Avaliação

O modelo precisa ser avaliado para verificar seu desempenho e suas limitações.

### 4.6 Aplicação

Depois de desenvolvido e validado, o modelo pode ser utilizado para apoiar processos de decisão.

### 4.7 Monitoramento

O acompanhamento dos resultados é importante porque os dados e os comportamentos observados podem mudar ao longo do tempo.

---

## 5. Modelos de Credit Scoring

Diferentes métodos podem ser utilizados para construir modelos de Credit Scoring.

Entre as abordagens tradicionais, a regressão logística é um exemplo de método estatístico utilizado em problemas de classificação.

Esses modelos relacionam características observadas nos dados com um resultado de interesse, como a ocorrência ou não de inadimplência.

A escolha do método depende das características do problema, dos dados disponíveis e dos objetivos da análise.

### Características de modelos tradicionais

- utilização de métodos estatísticos consolidados;
- estrutura relativamente simples;
- maior facilidade de interpretação em determinadas abordagens;
- possibilidade de analisar a relação entre variáveis e resultados.

A regressão logística, por exemplo, pode ser utilizada para estimar a probabilidade de ocorrência de determinado evento a partir de um conjunto de variáveis.

## 6. Machine Learning aplicado ao Credit Scoring

Além dos métodos estatísticos tradicionais, técnicas de Machine Learning também podem ser utilizadas na construção de modelos de risco de crédito.

Essas técnicas podem identificar padrões e relações mais complexas presentes nos dados.

Alguns exemplos de algoritmos utilizados em problemas de classificação são:

- Random Forest;
- Gradient Boosting;
- XGBoost;
- redes neurais.

Uma diferença importante é que determinados modelos de Machine Learning conseguem representar relações não lineares e interações mais complexas entre variáveis.

Por outro lado, modelos mais complexos podem aumentar a dificuldade de interpretar os resultados.

Por isso, a avaliação de um modelo de crédito não deve considerar apenas seu desempenho preditivo. Aspectos como interpretação, qualidade dos dados e contexto de aplicação também são relevantes.

---

## 7. Modelos tradicionais e Machine Learning

As diferentes abordagens possuem características próprias.

| Aspecto | Modelos tradicionais | Machine Learning |
|---|---|---|
| Estrutura | Geralmente mais simples | Pode apresentar maior complexidade |
| Interpretabilidade | Geralmente mais fácil de interpretar | Pode exigir técnicas adicionais |
| Relações entre variáveis | Mais estruturadas | Pode capturar relações mais complexas |
| Exemplos | Regressão logística | Random Forest, XGBoost e redes neurais |
| Complexidade computacional | Geralmente menor | Pode ser maior dependendo do modelo |
| Aplicação | Pode atender diferentes problemas de crédito | Pode ser útil quando relações complexas precisam ser modeladas |

A comparação não significa que uma abordagem seja sempre superior à outra.

A escolha depende do problema, dos dados disponíveis, dos requisitos de interpretação e de outros critérios envolvidos na aplicação.

---

## 8. Principais desafios

A utilização de dados para avaliação de risco de crédito envolve desafios que precisam ser considerados durante o desenvolvimento e a aplicação dos modelos.

### 8.1 Qualidade dos dados

Dados ausentes, inconsistentes, duplicados ou incorretos podem afetar a análise e o desempenho dos modelos.

A preparação dos dados é, portanto, uma etapa importante do processo.

### 8.2 Representatividade

Os dados utilizados no desenvolvimento precisam representar adequadamente o contexto em que o modelo será aplicado.

Mudanças no perfil dos clientes ou nas condições do mercado podem afetar o comportamento observado pelo modelo.

### 8.3 Desbalanceamento

Em alguns problemas de crédito, determinados eventos podem ocorrer com frequência muito menor que outros.

Esse desbalanceamento precisa ser considerado durante a construção e a avaliação do modelo.

### 8.4 Privacidade e utilização dos dados

Informações utilizadas em análises de crédito podem envolver dados pessoais e financeiros.

Por isso, sua utilização exige cuidados relacionados à proteção, segurança e tratamento adequado das informações.

### 8.5 Interpretabilidade

A compreensão dos fatores que influenciam uma previsão pode ser importante para analisar e explicar os resultados de um modelo.

Esse desafio pode ser maior quando são utilizados modelos mais complexos.

### 8.6 Acompanhamento

O comportamento dos dados pode mudar ao longo do tempo.

Por isso, modelos utilizados em produção precisam ser acompanhados para verificar se continuam apresentando resultados adequados ao contexto em que estão sendo utilizados.

---

## 9. Explicabilidade dos modelos

A explicabilidade está relacionada à capacidade de compreender como as informações utilizadas por um modelo contribuem para seus resultados.

Esse aspecto ganha importância quando são utilizados modelos mais complexos, nos quais a relação entre as variáveis de entrada e a previsão não é facilmente observada.

Uma das técnicas estudadas nas fontes selecionadas é o SHAP, sigla para *SHapley Additive exPlanations*.

O SHAP pode ser utilizado para analisar a contribuição das variáveis para determinada previsão.

Em um contexto de Credit Scoring, isso pode ajudar a responder perguntas como:

> Quais características contribuíram para determinado resultado do modelo?

A explicabilidade não elimina a necessidade de avaliar o modelo de forma completa, mas pode contribuir para uma análise mais transparente de seus resultados.

**Fonte relacionada:** *Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data*.

## 10. O que diferencia uma boa análise de crédito?

A utilização de um modelo de Credit Scoring não depende apenas do algoritmo escolhido.

Uma análise estruturada envolve diferentes aspectos:

**Qualidade dos dados + Relevância das variáveis + Modelo adequado ao problema + Avaliação dos resultados + Interpretação + Monitoramento**

Isso significa que um modelo deve ser analisado dentro do contexto em que será utilizado.

Um bom processo de análise precisa considerar tanto os resultados produzidos quanto a qualidade das informações que sustentam esses resultados.

---

## 11. Glossário

| Conceito | Definição |
|---|---|
| **Credit Scoring** | Metodologia utilizada para apoiar a avaliação do risco de crédito a partir de informações sobre clientes e operações. |
| **Score de crédito** | Pontuação ou medida utilizada para representar uma estimativa de risco de crédito. |
| **Risco de crédito** | Possibilidade de uma obrigação financeira não ser cumprida conforme as condições estabelecidas. |
| **Inadimplência** | Não cumprimento de uma obrigação financeira no prazo ou nas condições acordadas. |
| **Cadastro Positivo** | Base de informações que considera o histórico de crédito e pagamentos dos consumidores. |
| **Histórico de crédito** | Conjunto de informações relacionadas ao comportamento de crédito e pagamento de um cliente. |
| **Variável** | Informação utilizada na análise ou como entrada de um modelo. |
| **Modelo preditivo** | Modelo utilizado para estimar um resultado a partir de determinadas informações. |
| **Regressão logística** | Método estatístico utilizado em problemas de classificação e que pode ser aplicado à modelagem de risco de crédito. |
| **Machine Learning** | Abordagem computacional que permite desenvolver modelos capazes de identificar padrões a partir de dados. |
| **Feature** | Variável ou característica utilizada como entrada de um modelo de Machine Learning. |
| **SHAP** | Técnica de explicabilidade utilizada para analisar a contribuição das variáveis nas previsões de um modelo. |
| **Open Banking** | Modelo que permite o compartilhamento de dados e serviços financeiros mediante autorização do cliente. |
| **Desbalanceamento** | Situação em que as classes de um conjunto de dados possuem quantidades muito diferentes de observações. |
| **Explicabilidade** | Capacidade de compreender e interpretar como um modelo chegou a determinado resultado. |

---

## 12. Prompts reutilizáveis

Os prompts abaixo podem ser utilizados para continuar estudando o tema no NotebookLM ou em outras ferramentas que permitam trabalhar com fontes fornecidas pelo usuário.

### Conceitos fundamentais

> Explique o que é Credit Scoring, qual é sua finalidade e como ele é utilizado na avaliação de risco de crédito.

### Dados

> Quais são os principais tipos de dados utilizados na avaliação de risco de crédito? Organize por categoria e explique a contribuição de cada um.

### Histórico de crédito

> Explique como o histórico de pagamentos e o Cadastro Positivo podem contribuir para a avaliação de risco de crédito.

### Processo de avaliação

> Quais são as principais etapas envolvidas na construção e utilização de um modelo de Credit Scoring? Explique cada etapa de forma objetiva.

### Modelos

> Quais são as principais abordagens utilizadas na construção de modelos de Credit Scoring? Explique de forma objetiva as características de cada uma.

### Comparação

> Compare modelos tradicionais de Credit Scoring com modelos baseados em Machine Learning, destacando as principais diferenças, características e limitações de cada abordagem.

### Análise crítica

> Quais são os principais desafios relacionados à utilização de dados na avaliação de risco de crédito? Organize os desafios por categoria.

### Qualidade dos dados

> Quais problemas de qualidade dos dados podem prejudicar um modelo de Credit Scoring? Apresente exemplos e possíveis formas de tratamento.

### Explicabilidade

> Por que a explicabilidade é importante em modelos utilizados para avaliação de crédito? Apresente exemplos de técnicas que podem ser utilizadas.

### Aprofundamento

> Com base nas fontes disponíveis, quais pontos ainda precisam ser estudados para compreender melhor a utilização de dados na avaliação de risco de crédito?

---

## 13. Principais aprendizados

A pesquisa permitiu compreender que o Credit Scoring está diretamente relacionado à utilização de dados para apoiar a avaliação do risco de crédito.

Entre os principais aprendizados estão:

- os dados são a base para a construção das análises de risco;
- o histórico de crédito pode fornecer informações relevantes sobre o comportamento de pagamento;
- diferentes categorias de dados podem contribuir para a avaliação de uma operação;
- a qualidade dos dados é tão importante quanto a escolha do modelo;
- existem diferentes abordagens para construção de modelos de Credit Scoring;
- modelos tradicionais e técnicas de Machine Learning possuem características e desafios diferentes;
- modelos mais complexos podem exigir técnicas adicionais de explicabilidade;
- o acompanhamento dos modelos é importante porque os dados e comportamentos podem mudar ao longo do tempo.

---

## 14. Conclusão

O estudo mostrou que Credit Scoring é uma abordagem baseada em dados utilizada para apoiar a avaliação do risco de crédito.

A construção de uma análise de crédito envolve mais do que escolher um modelo. É necessário compreender os dados disponíveis, avaliar sua qualidade, selecionar informações relevantes, analisar os resultados e acompanhar o comportamento do modelo ao longo do tempo.

Modelos estatísticos tradicionais e técnicas de Machine Learning podem fazer parte desse processo, dependendo das características do problema e dos objetivos da aplicação.

Outro ponto importante é a capacidade de interpretar os resultados. Em modelos mais complexos, técnicas de explicabilidade podem contribuir para compreender a influência das variáveis nas previsões.

Dessa forma, o estudo de Credit Scoring envolve uma combinação entre dados, métodos de análise, conhecimento do contexto de crédito e avaliação crítica dos resultados.

---

## 15. Fontes utilizadas

1. Banco Central do Brasil. *Análise dos efeitos do Cadastro Positivo*.

   https://www.bcb.gov.br/content/publicacoes/Documents/outras_pub_alfa/analise_dos_efeitos_do_cadastro_positivo.pdf

2. Revista Ciências Administrativas. *Aplicação de modelos credit scoring na análise da inadimplência de uma instituição de microcrédito*.

   https://ojs.unifor.br/rca/article/view/264

3. *Machine Learning for Enhanced Credit Risk Assessment: An Empirical Approach*.

   https://www.mdpi.com/1911-8074/16/12/496

4. *Machine Learning for Credit Risk Prediction: A Systematic Literature Review*.

   https://www.mdpi.com/2306-5729/8/11/169

5. *Explaining Deep Learning Models for Credit Scoring with SHAP: A Case Study Using Open Banking Data*.

   https://www.mdpi.com/1911-8074/16/4/221
