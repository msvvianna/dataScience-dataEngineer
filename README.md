# 02/01/2025 - DATASCIENCE E DATA ENGINEER - DAY 1

## Inteligência Artificial, Machine Learning e Deep Learning

### O que é Inteligência Artificial (IA)?
A Inteligência Artificial é uma **área da computação** que busca desenvolver **sistemas** capazes de simular **comportamentos inteligentes** como:

* **Reconhecimento de padrões:** Identificar similaridades em dados.
* **Tomada de decisões:** Escolher a melhor ação com base em informações.
* **Resolução de problemas:** Encontrar soluções para desafios complexos.
* **Entendimento de linguagem natural:** Interagir com humanos através da linguagem falada ou escrita.

**Exemplo:** Assistentes virtuais como a Alexa e o Google Assistente.

### O que é Machine Learning (ML)?
Machine Learning é um **subcampo da IA** que permite que sistemas **aprendam e melhorem automaticamente** com a experiência, **sem serem explicitamente programados** para cada tarefa. 

- Aprendizado Supervisionado
  - Classificação ou Regressão
- Aprendizado Não Supervisionado
  - Agrupamento de dados, feature selection
- Aprendizado por Reforço ou Semi-Supervisionado

**Como funciona:**

1. **Coleta de dados:** Os sistemas são alimentados com grandes quantidades de dados (imagens, textos, etc.).
2. **Aprendizado:** Algoritmos analisam os dados para identificar padrões e criar modelos.
3. **Previsão:** Os modelos gerados são utilizados para fazer previsões ou tomar decisões sobre novos dados.

**Exemplo:** Filtros de spam que aprendem a identificar e-mails indesejados.

### O que é Deep Learning (DL)?
Deep Learning é um **subcampo do Machine Learning** que utiliza **redes neurais artificiais com múltiplas camadas** para aprender representações **complexas dos dados**.
- ANN: Redes Neurais Artificiais
- RNN: Redes Neurais Recorrentes
- CNN: Redes Neurais Convolucinárias

**Características:**
* **Excelência em dados não estruturados:** Ideal para lidar com grandes volumes de dados como imagens e texto.
* **Aprendizado automático:** Capaz de aprender padrões complexos sem intervenção humana.
* **Alta demanda computacional:** Requer hardware poderoso para treinamento.

**Exemplo:** Sistemas de reconhecimento facial e tradução automática.

### Diferenças entre IA, ML e DL

| Característica | IA | ML | DL |
|---|---|---|---|
| Definição | Área ampla da computação que busca simular inteligência. | Subcampo da IA focado em aprendizado de máquina. | Subcampo do ML que utiliza redes neurais profundas. |
| Entrada | Regras ou dados. | Dados estruturados ou semi-estruturados. | Grandes volumes de dados não estruturados. |
| Complexidade do Modelo | Pode ser baseado em regras ou aprendizado. | Modelos que aprendem padrões. | Modelos altamente complexos com múltiplas camadas. |
| Exemplo | Sistemas especialistas. | Recomendação de produtos. | Reconhecimento de objetos em imagens. |

### Resumo
* **IA:** Campo abrangente que engloba todas as técnicas para criar sistemas inteligentes.
* **ML:** Subcampo da IA que permite que sistemas aprendam com dados.
* **DL:** Subcampo do ML que utiliza redes neurais profundas para resolver problemas complexos.

**Relação entre os conceitos:** Todo Deep Learning é Machine Learning e todo Machine Learning é Inteligência Artificial, mas nem toda IA é ML e nem todo ML é DL.

## Cientista de Dados vs Engenheiro de Dados

- Embora os papéis de Cientista de Dados e Engenheiro de Dados sejam complementares no domínio da análise de dados, eles possuem diferenças significativas em suas responsabilidades, habilidades e ferramentas. Este README apresenta um resumo comparativo entre essas duas funções.

### Comparativo

| **Aspecto**                | **Cientista de Dados**                                                                 | **Engenheiro de Dados**                                                      |
|-----------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Foco Principal**         | Análise e interpretação de dados para gerar insights e resolver problemas de negócio. | Design, construção e manutenção de infraestrutura e pipelines de dados.     |
| **Objetivo**               | Extrair conhecimento e valor dos dados.                                               | Garantir que os dados sejam acessíveis, limpos e bem organizados.            |
| **Responsabilidades**      | - Construir modelos estatísticos e de aprendizado de máquina.                          | - Desenvolver e manter pipelines de ETL/ELT.                                |
|                             | - Visualizar e comunicar resultados para stakeholders.                                | - Garantir a escalabilidade e confiabilidade dos sistemas de dados.         |
|                             | - Realizar análises exploratórias e experimentos.                                    | - Integrar diversas fontes de dados e gerenciar armazenamento.              |
| **Habilidades**            | - Matemática, estatística e aprendizado de máquina.                                   | - Programação avançada e engenharia de software.                            |
|                             | - Linguagens como Python, R, SQL.                                                    | - Linguagens como Python, Java, Scala, SQL.                                 |
|                             | - Visualização de dados (Tableau, Power BI, Matplotlib).                             | - Conhecimento em bancos de dados (SQL/NoSQL), ferramentas de ETL.          |
| **Ferramentas**            | - Jupyter Notebook, Pandas, Scikit-learn, TensorFlow, PyTorch.                        | - Hadoop, Spark, Kafka, Airflow, Apache Beam.                               |
|                             | - Bibliotecas de visualização de dados (Seaborn, Plotly).                            | - Sistemas de banco de dados (PostgreSQL, MongoDB, Redshift, BigQuery).     |
| **Interação com Dados**    | - Trabalha diretamente com análises de dados e modelos.                               | - Prepara e organiza os dados para serem usados por cientistas e analistas. |
| **Formação Comum**         | - Ciência de Dados, Estatística, Matemática, Ciência da Computação.                   | - Ciência da Computação, Engenharia de Software, Engenharia de Dados.       |
| **Perfil Profissional**    | - Curioso, focado em resolver problemas e comunicar resultados.                       | - Detalhista, com forte foco em arquitetura de sistemas e eficiência.        |

### Resumo

- **Cientista de Dados**: trabalha principalmente na análise, interpretação e modelagem dos dados, gerando insights que ajudam a tomar decisões estratégicas.  
- **Engenheiro de Dados**: garante que a infraestrutura e os pipelines de dados funcionem de forma eficiente, fornecendo dados de qualidade e acessíveis para análise.


## O que é Big Data

- É o um termo utilizado para definir grande e complexos conjuntos de dados, é definido em cinco V's que são:
  - **Volume:** grande quantidade de dados.
  - **Velocidade:** processamento em tempo satisfatorio
  - **Variedade:** diversos tipos de dados
  - **Veracidade:** precisão e acurácia das análises
  - **Valor:** valor de negócio

## O que é Mineração de dados

- É um processo computacional para descobrir padróes em grandes conjuntos de dados

## Classificação e Estimativa de Probabilidade

### Classificação
A classificação é uma tarefa de aprendizado de máquina onde o objetivo é categorizar dados em classes ou categorias predefinidas.

### Exemplos:
- Determinar se um e-mail é *spam* ou *não spam* (classes: spam, não spam).
- Identificar o dígito em uma imagem de um número manuscrito (classes: 0 a 9).
- Classificar clientes como propensos ou não a cancelar um serviço (classes: cancelar, não cancelar).

### Funcionamento:
1. **Modelo:** Um algoritmo (como árvore de decisão, SVM, ou redes neurais) é treinado em um conjunto de dados rotulado.
2. **Entrada:** O modelo recebe novos dados (ex.: texto de um e-mail).
3. **Saída:** O modelo atribui uma classe (ex.: *spam*).

### Principais Algoritmos:
- Regressão logística (binária ou multinomial).
- Árvores de decisão.
- Random Forest.
- SVM.
- Redes neurais.

---

## Estimativa de Probabilidade
A estimativa de probabilidade vai além da classificação binária ou categórica. Em vez de apenas indicar uma classe, o modelo fornece a **probabilidade** de cada classe.

### Por que é útil?
- Permite a tomada de decisão com base em níveis de confiança.
- Permite ajustar limites de decisão (thresholds) dependendo do problema.

### Exemplo:
- Um modelo prevê que um e-mail é *spam* com 80% de probabilidade e *não spam* com 20%.
- **Decisão:** Se o limiar de decisão for 50%, o e-mail será marcado como *spam*. Se for 90%, será classificado como *não spam*.

### Como funciona:
- Muitos modelos de classificação (ex.: regressão logística, redes neurais) calculam a probabilidade usando funções matemáticas.
- Exemplo de método:
  - A **Regressão Logística** usa a função sigmoide para calcular a probabilidade de uma classe (entre 0 e 1).

### Aplicações práticas:
- Detecção de fraudes: Classificar transações com base na probabilidade de serem fraudulentas.
- Diagnósticos médicos: Indicar a probabilidade de um paciente ter uma doença específica.
- Sistemas de recomendação: Classificar itens com base na probabilidade de o usuário gostar deles.

---

## Diferença Principal
| **Classificação**                  | **Estimativa de Probabilidade**                  |
|------------------------------------|-------------------------------------------------|
| Fornece apenas a classe final (ex.: spam/não spam). | Fornece a probabilidade de cada classe.        |
| Adequado quando o objetivo é decidir apenas entre as classes. | Útil quando a confiança nas previsões é importante. |
| Ex.: Resultado: "spam".            | Ex.: Probabilidade: 80% spam, 20% não spam.     |

---

## Regressão ou Estimativa de Valor

A **regressão** (ou **estimativa de valor**) é uma técnica de aprendizado de máquina supervisionado usada para prever um valor contínuo com base em variáveis independentes (também chamadas de recursos ou *features*). Ela busca modelar a relação entre as variáveis de entrada (X) e a variável de saída (Y).

---

### **Exemplo Prático**
- Prever o preço de uma casa com base em suas características, como tamanho, número de quartos e localização.
- Estimar a temperatura de uma cidade amanhã com base nos dados climáticos de hoje.

---

### **Como funciona?**
1. O modelo é treinado em um conjunto de dados rotulado, onde as variáveis de entrada e os valores reais estão disponíveis.
2. Ele aprende uma **função matemática** que relaciona as entradas aos valores de saída.
3. Essa função é usada para prever valores em novos dados.

---

### **Principais Tipos de Regressão**

### 1. **Regressão Linear Simples**
- Modela a relação linear entre uma variável independente (X) e uma dependente (Y).  
- **Fórmula:** \( Y = aX + b \)  
- **Exemplo:** Prever o salário com base na experiência.

### 2. **Regressão Linear Múltipla**
- Relaciona múltiplas variáveis independentes (X₁, X₂, ... Xₙ) com a variável dependente (Y).  
- **Fórmula:** \( Y = a₁X₁ + a₂X₂ + ... + aₙXₙ + b \)  
- **Exemplo:** Prever o preço de uma casa com base em vários atributos.

### 3. **Regressão Polinomial**
- Lida com relações não lineares ao incluir termos polinomiais (como \( X² \)).  
- **Exemplo:** Prever a evolução de uma pandemia ao longo do tempo.

### 4. **Regressão Logística (Estimativa de Probabilidade)**
- Embora seja frequentemente usada para classificação, ela estima probabilidades que podem ser interpretadas em um contexto contínuo.

---

### **Aplicações Comuns**
- Prever vendas futuras de um produto.
- Estimar a nota de alunos com base em horas de estudo.
- Modelagem de risco em seguros ou finanças.

---
## Combinação por Similaridade e Agrupamento

Esses dois conceitos estão relacionados a técnicas de análise de dados e aprendizado de máquina, frequentemente usados para identificar padrões em conjuntos de dados. 

---

## **1. Combinação por Similaridade**
A combinação por similaridade é um processo que mede o grau de semelhança entre diferentes objetos em um conjunto de dados. É amplamente utilizada em sistemas de recomendação e em problemas de busca e recuperação de informações.

### **Como funciona?**
1. **Definir uma métrica de similaridade:**
   - **Distância Euclidiana:** Mede a distância direta entre dois pontos em um espaço multidimensional.
   - **Coeficiente de Similaridade de Cosseno:** Mede o ângulo entre dois vetores, útil para comparar documentos ou textos.
   - **Distância de Jaccard:** Mede a similaridade entre conjuntos, baseado na interseção e na união dos elementos.

2. **Calcular a similaridade:**
   - Para cada par de objetos, calcula-se o grau de similaridade.
   - Pode-se estabelecer um limiar para decidir quais pares são considerados similares.

3. **Aplicar aos dados:**
   - Agrupar objetos similares.
   - Utilizar em recomendações, agrupamentos, ou detecção de duplicações.

### **Exemplo:**
Em um sistema de recomendação de filmes, dois usuários que deram notas similares a um conjunto de filmes podem ser considerados "similares", e as recomendações serão baseadas em itens avaliados positivamente por um deles.

---

## **2. Agrupamento (Clustering)**
O agrupamento é uma técnica de aprendizado não supervisionado que organiza dados em grupos (ou clusters) com base em características semelhantes.

### **Como funciona?**
1. **Definir critérios de agrupamento:**
   - Os objetos dentro de um cluster devem ser semelhantes entre si.
   - Os objetos de clusters diferentes devem ser distintos.

2. **Utilizar algoritmos de agrupamento:**
   - **K-Means:** Agrupa dados em \(k\) clusters, otimizando as distâncias médias entre pontos do cluster e o centróide.
   - **DBSCAN:** Baseado em densidade, identifica clusters com base na proximidade de pontos densos.
   - **Hierárquico:** Cria uma hierarquia de clusters que podem ser representados como uma árvore (dendrograma).

3. **Analisar os resultados:**
   - Identificar grupos significativos para gerar insights.

### **Exemplo:**
Em marketing, os clientes podem ser agrupados em segmentos com base em seus comportamentos de compra, permitindo campanhas mais direcionadas.

---

## **Diferença entre Combinação por Similaridade e Agrupamento**

| **Combinação por Similaridade**                          | **Agrupamento**                                      |
|----------------------------------------------------------|-----------------------------------------------------|
| Mede o grau de semelhança entre pares de objetos.        | Organiza dados em grupos distintos com base na similaridade. |
| Envolve cálculo explícito de similaridade entre pares.   | Não calcula diretamente a similaridade entre pares; usa critérios para formar clusters. |
| Exemplo: Sistemas de recomendação.                      | Exemplo: Segmentação de clientes.                  |

---

### **Aplicações Práticas**
- **Combinação por Similaridade:**
  - Sistemas de recomendação (filmes, produtos).
  - Deduplicação de dados (identificar registros duplicados).

- **Agrupamento:**
  - Análise de segmentos de clientes.
  - Detecção de anomalias (grupos distintos de comportamento incomum).


# Regras de Associação e Anomalias

## **Regras de Associação**

### O que são?
Regras de associação são técnicas de aprendizado de máquina usadas para descobrir relações ou padrões interessantes entre itens em grandes conjuntos de dados. São amplamente utilizadas em mineração de dados.

### Principais conceitos:
1. **Itemset**: Um conjunto de itens que aparecem juntos em um banco de dados.
   - Exemplo: Em um supermercado, um itemset pode ser {leite, pão}.
2. **Suporte**: Frequência com que um item ou itemset aparece no conjunto de dados.
   - **Fórmula:** \( \text{Suporte}(A) = \frac{\text{Número de transações contendo } A}{\text{Total de transações}} \)
3. **Confiança**: Mede a probabilidade de um item aparecer, dado que outro já apareceu.
   - **Fórmula:** \( \text{Confiança}(A \Rightarrow B) = \frac{\text{Transações com } A \text{ e } B}{\text{Transações com } A} \)
4. **Lift (Efeito de alavancagem)**: Mede a força da relação entre itens.
   - **Fórmula:** \( \text{Lift}(A \Rightarrow B) = \frac{\text{Confiança}(A \Rightarrow B)}{\text{Suporte}(B)} \)

### Exemplo prático:
- **Regra:** “Se um cliente compra pão, há 80% de chance de comprar leite.”
- **Aplicação:** Marketing direcionado ou organização de prateleiras.

### Algoritmos mais comuns:
- Apriori
- FP-Growth (Frequent Pattern Growth)

---

## **Anomalias**

### O que são?
Anomalias são observações ou eventos que se desviam significativamente do padrão ou comportamento esperado nos dados. Elas podem indicar problemas, como fraudes ou falhas no sistema.

### Tipos de anomalias:
1. **Pontuais**:
   - Um único dado difere do restante.
   - **Exemplo:** Uma transação com valor muito acima da média.
2. **Contextuais**:
   - Um dado é anômalo apenas em um contexto específico.
   - **Exemplo:** Temperaturas altas no inverno.
3. **Coletivas**:
   - Um conjunto de dados, considerado em conjunto, é anômalo.
   - **Exemplo:** Uma série de compras incomuns feitas em um curto período.

### Métodos para detecção:
1. **Baseados em estatísticas**:
   - Identificam valores fora de distribuições normais.
2. **Baseados em aprendizado de máquina**:
   - Modelos supervisionados ou não supervisionados, como K-Means, DBSCAN ou Autoencoders.
3. **Baseados em regras**:
   - Detectam desvios com base em regras predefinidas.

### Aplicações:
- Detecção de fraudes financeiras.
- Identificação de falhas em sistemas industriais.
- Monitoramento de segurança em redes de computadores.

---

## **Resumo Comparativo**

| **Aspecto**              | **Regras de Associação**                         | **Anomalias**                                   |
|---------------------------|-------------------------------------------------|------------------------------------------------|
| **Objetivo**              | Encontrar padrões ou relações entre itens.     | Identificar desvios ou eventos incomuns.       |
| **Dados analisados**      | Conjuntos de itens frequentes.                  | Observações individuais ou coletivas.          |
| **Aplicações principais** | Varejo, marketing, recomendação de produtos.    | Segurança, manutenção preditiva, detecção de fraudes. |
