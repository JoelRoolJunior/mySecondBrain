---
tags:
  - machine_learning
---
# Machine Learning - TIC em Trilhas
created:: 2024-03-14 16:47

## Manipulação e visualização de dados

### Aula 1 - Introdução ao aprendizado de máquina
#### Áreas de atuação e carreiras em ML
- Engenharia de Dados
- Cientista de Dados
### Aula 2 - Introdução a dados
#### Tipos de dados
Amostra  de dados é um subgrupo de um conjunto de dados maior. A amostra serve para fazer uma estimativa.

- dados numéricos: podem ser quantificados.
	- altura, temperatura, peso, etc.
- Dados Categóricos: Não possuem ordem / hierarquia natural
	- Cor, sexo, Raça, etc.
- Dados ordinais: Possuem um ordem / hierarquia natural
	- educacional, posição em uma corrida, entre outros.
#### Dados tabulares
São Informações guardadas em tabelas com colunas e linhas,
Características:
- Tipos de dado
- Presença de valores ausentes
- Distribuição de valores

#### Tabelas
- Linhas: (Dados)
- Colunas: (Variaveis)
- Formatos: (cvs, txt, xlsx)
- SQL
##### Tabela de frequência
![[Tabela de frequência TIC em Trilhas.png|800]]
**Frequência Absoluta**: 
**Frequência relativa**: 
**Frequência absoluta acumulada**: 
**Frequência relativa acumulada**: 

#### Operações comuns
Aula sobre criar e preparar dataframes
#### Pipeline
- O ***Pipeline*** de dados é composto por etapas que vão desde a coleta até a análise de dados.
- definição do problema e do objetivo
- garantir que os dados são:
	- confiáveis
	- completos
	- diversificados
- **objetivo final**:extrair informações a partir dos dados
#### Coleta de Dados
A coleta de dados é uma etapa crucial para ML, pois é a partir dos dados que os algoritmos são treinados para fazer previsões e tomar decisões. Esses dados podem ser obtidos de diversas fontes, como: 

- Bancos de dados internos da empresa;
- Dados públicos disponíveis na internet;
- Sensores ou dispositivos IoT (Internet of Things).

É importante que os dados coletados sejam relevantes para o problema em questão e que sejam de qualidade, ou seja, que não contenham erros ou informações duplicadas.

#### Informação dos Dados
É Através de insights que encontramos tendências, padrões, e correlações

### Aula 3 - Ética e sensibilidade dos dados
#### Ética de Dados
A ética de dados envolve o tratamento justo e transparente das informações, incluindo a **coleta**, **armazenamento**, **processamento**, **análise** e **compartilhamento de dados**.
#### Sensibilidade de dados
- Consideração de implicações Sociais
- Aborda o uso adequado dos dados
- envolve garantir que os dados coletados representem de forma justa e precisa as populações e comunidades, levando em conta questões de **inclusão** e **diversidade**.

### Aula 4 - Visualização de dados

## Métodos de Aprendizado de Máquina e suas aplicações


### Aula 1 - Aplicações do aprendizado de máquina
#### Exemplos de utilização
- os computadores podem aprender com os dados
- Machine Learning (Aprendizado de Máquina) é uma área da inteligência artificial
- empresas que utilizam:
	- **Google Fotos:** reconhecer rostos, objetos e lugares nas fotos e organizar as imagens por categorias;
	- **Netflix:** recomendar filmes e séries aos usuários com base em seus gostos e preferências;
	- **Spotify:** criar playlists personalizadas para os usuários com base em suas músicas favoritas;
	- **OpenAI:** responder perguntas em linguagem natural e auxiliar na tomada de decisões através do ChatGPT;
	- **DeepMind:** jogar o jogo de tabuleiro Go, atingindo resultados melhores que jogadores profissionais usando a inteligência artificial AlphaGo.
### Aula 2 - Modelos
#### Introdução a modelos
Um dos conceitos fundamentais do Aprendizado de Máquina é o de modelo.
- modelo é uma representação matemática de um fenômeno ou processo real.
- pode ser usado para fazer previsões.

primeiro temos que lembra um pouco de ***Funções***. 
Sempre temos formulas para chegar na resposta certa.
F(x) = 2x+2
```desmos-graph
left=-1; right=5;
top=12; bottom=-1;
---
y=2x+2|x>0
```

E se a pergunta for o contrário? Tenho um **conjunto de pontos**, qual a **formula que representa eles**.
```desmos-graph
left=-1; right=5;
top=12; bottom=-1;
---
y=2x+2|x>0|dotted
```
O treinamento é isso, tentar achar a formula que representa aproximadamente nosso conjunto de dados
##### Tipos de Aprendizado
###### Por Reforço
- **Positivo**
	- segue caminhos que "dão certo"
- **Negativo**
	- Evita caminhos que "dão errado"
###### Supervisionado
o modelo vai ser treinado com dados já tabulados e categorizados
###### Não supervisionado
Procura padrões dentro dos dados.

##### Divisão de Dados
- **Treino**
	- O modelo tenta se aproximar dos dados de treino.
- **Teste**
	- Verificar se o modelo funciona para novas informações.

O que acontece quando tem poucos dados de treino?
**Underfitting**
- O modelo não se ajusta aos dados de treino

E o que acontece quando o modelo se ajusta demais aos dados?
**Overfitting**
- Uma linha mais genérica representa melhor os dados.

![[Overfitting e underfitting em Machine Learning.png]]

### Treinando Modelos
é o processo de o ***Modelo*** aprender a partir de dados.
O objetivo é que o algoritmo consiga ***generalizar*** o que aprendeu para novos dados que não foram usados no treino, chamados de ***dados de teste.***

#### Predição
se meu modelo estiver errando, eu posso querer ajustar ele. Mas como? 
##### Função de Custo
compara o resultado do modelo com o esperado
Resultado esperado é **20** ------------  10 => | **MODELO** | => 15
**Tipos:**
- Erro Absoluto : 20-15=5
- Erro quadrado: (20-15)² = 25
- Binário: certo ou errado | 1 ou 0
##### Gradiente Descendente
- ajusta o modelo para ter o menor custo possível
- Qual o melhor jeito de ajustar o modelo?
	- Qual o parâmetro minimiza o custo?
	- O que pode ser esse parâmetro?
		- pode ser o grau de inclinação de uma reta até que ela se encaixe melhor ao conjunto de dados. 
##### Mínimos Locais
![[Minimo_local_e_global.png|500]]
como achar os mínimos locais?
	definir pontos iniciais

### Aula 3 - Problemas de Aprendizado de Máquina
#### Classificação
A classificação consiste em prever a qual de duas ou mais classes (categorias) uma instância  de dados pertence.
*exemplo*:
- classificação de doenças a partir de informações como peso, altura, idade, etc.

#### Regressão Linear
A regressão linear é um método estatístico usado para modelar a relação entre uma variável dependente (Y) e uma ou mais variáveis independentes (X). 
O objetivo é encontrar uma **linha reta (no caso da regressão linear simples)** ou um **hiperplano (no caso da regressão linear múltipla)** que melhor ajuste os dados.
![[Exemplo de regressão linear.png]]
#### Máquina de vetores de suporte (support-vector machine)

- **tipo:**
	- *Supervisionado*
	- *Classificação*
	- *Regressão*
- **teoria**:
	- a SVM analisa os dados e encontra um **hiperplano** que separa as **classes-alvo** com a maior margem possível.
	- Dividir os dados com base nas suas características
	- maximizar as margens
	- suport vectors
![[support-vector machine.png|500]]
**E para divisões não lineares??**
![[divisão não linear.png|500]]
se usa o:
- Kernel trick

#### K-nearest neighbors

KNN (K-Nearest Neighbors, ou K vizinhos mais próximos).
- **tipo:** 
	- *Supervisionado*
	- *Classificação*
	- *Regressão*
- **teoria**:
	- Se baseia baseia na ideia de que objetos similares estão próximos um dos outros.
	- usa localização espacial para criar a categoria.
- **características**:
	- treino rápido
	- pode demorar na predição
		- KD tree - otimização
	- Não Funciona muito bem com dados com muitas dimensões
![[KNN exemplo.png]]
#### Árvore de decisão

- **tipo:** 
	- *Supervisionado*
	- *Classificação*
	- *Regressão*
- **teoria**:
	- **simplificado**
		- criar uma serie de perguntas.
		- como a divisão é feita? --> *Escolhe a característica que vai te trazer a melhor divisão*
	- **completo**
		- Uma Árvore de Decisão é composta por nós que representam perguntas ou condições sobre os dados, e ramos que representam as possíveis respostas ou resultados.
		- O objetivo é construir uma Árvore que consiga separar os dados em grupos homogêneos, de acordo com a variável alvo (a classe ou o valor que se quer prever).
- **características**:
	- estrutura hierárquica
	- raiz
	- folhas
	- Rápidas
	- Se encaixam muito bem em dados desbalanceados
	- Podem ter dificuldade para generalizar em alguns casos.
##### Florestas Aleatórias
- conjunto de arvores de decisão
- cada uma delas vota em uma resposta.
- A resposta mais votada se torna o resultado do modelo.
![[Arvore de decisão.png]]

#### Random Forest

- **Tipo:**
    
    - _Supervisionado_
    - _Classificação_
    - _Regressão_
- **Teoria:**
    - **Simplificado:**
        - Combina várias árvores de decisão para fazer previsões ou classificações.
        - Como a divisão é feita? --> _Cada árvore de decisão é treinada com um subconjunto aleatório dos dados e das variáveis_.
    - **Completo:**
        - Random Forest é um método de aprendizado de máquina que utiliza múltiplas árvores de decisão para melhorar a precisão e a robustez das previsões.
        - Cada árvore de decisão é treinada com um subconjunto aleatório dos dados (amostragem com reposição, conhecida como bootstrap) e um subconjunto aleatório das variáveis.
        - A combinação dessas árvores reduz o risco de overfitting, pois cada árvore tem alta variabilidade individual, mas sua combinação resulta em um modelo mais estável e preciso.
        - A previsão ou classificação final é determinada pela média (para regressão) ou pela votação da maioria (para classificação) das previsões ou classificações de todas as árvores.
- **Características:**
    - Estrutura composta por múltiplas árvores de decisão.
    - Utiliza amostragem bootstrap para gerar diferentes subconjuntos de dados.
    - Seleciona aleatoriamente um subconjunto de características em cada divisão de nó.
    - Reduz o overfitting em comparação com uma única árvore de decisão.
    - Geralmente mais preciso e robusto que árvores de decisão individuais.
    - Pode lidar bem com dados de alta dimensionalidade.
    - É eficiente em dados grandes e complexos.
    - Interpretabilidade mais difícil do que árvores de decisão individuais, mas fornece medidas de importância das variáveis.

### Naive Bayes

- **Tipo:**
    - _Supervisionado_
    - _Classificação_
- **Teoria:**
    - **Simplificado:**
        - Utiliza o teorema de Bayes para estimar a probabilidade de uma classe para uma dada observação.
        - Como as características são tratadas? --> _Supõe-se que as características de uma observação são independentes entre si_.
    - **Completo:**
        - O Naive Bayes é um algoritmo de classificação baseado no teorema de Bayes, que calcula a probabilidade posterior de uma classe com base nas probabilidades anteriores e na probabilidade condicional das características dadas as classes.
        - A "ingenuidade" do modelo vem da suposição de independência condicional entre as características, ou seja, a presença ou ausência de uma característica é considerada independente da presença ou ausência de qualquer outra característica.
        - Esta suposição simplifica significativamente os cálculos das probabilidades, tornando o modelo computacionalmente eficiente, mesmo em datasets de alta dimensionalidade.
        - Existem diferentes variações do Naive Bayes, como Gaussian Naive Bayes (para dados contínuos), Multinomial Naive Bayes (para dados discretos), e Bernoulli Naive Bayes (para dados binários).
- **Características:**
    - Baseado no teorema de Bayes.
    - Supõe independência condicional entre as características.
    - Computacionalmente eficiente e rápido.
    - Funciona bem com datasets pequenos e grandes.
    - Pode lidar com dados de alta dimensionalidade.
    - Simples de implementar e interpretar.
    - Pode ser menos preciso se a suposição de independência for fortemente violada nos dados.
    - Útil em aplicações como filtragem de spam, classificação de textos e análise de sentimentos.

![[Naive Bayes Classifier.png]]
### Agrupamento (Clustering)

- **Tipo:**
    - _Não supervisionado_
    - _Agrupamento_
- **Teoria:**
    - **Simplificado:**
        - Encontra grupos de objetos similares em um conjunto de dados.
        - Qual é o objetivo? --> _As instâncias dentro de um mesmo grupo devem ser mais parecidas entre si do que com os objetos de outros grupos_.
    - **Completo:**
        - Agrupamento (ou clustering) é uma técnica de Aprendizado de Máquina que visa identificar e formar grupos de dados ou instâncias similares dentro de um conjunto de dados.
        - O objetivo é que as instâncias dentro de um mesmo grupo (cluster) tenham maior semelhança entre si, enquanto sejam diferentes das instâncias em outros grupos.
        - Existem diversos algoritmos de agrupamento, como K-means, DBSCAN, e Agglomerative Clustering, cada um com suas particularidades e áreas de aplicação.
        - O K-means, por exemplo, particiona o espaço de dados em K clusters, onde cada instância pertence ao cluster com o centróide mais próximo.
        - DBSCAN (Density-Based Spatial Clustering of Applications with Noise) identifica clusters com base na densidade de pontos, podendo encontrar clusters de formas arbitrárias e identificar pontos de ruído.
        - Agrupamento hierárquico constrói uma hierarquia de clusters, podendo ser aglomerativo (bottom-up) ou divisivo (top-down).
- **Características:**
    - Técnica não supervisionada.
    - Encontra e forma grupos (clusters) de dados similares.
    - Algoritmos comuns incluem K-means, DBSCAN, Agglomerative Clustering.
    - Útil para segmentação de mercado, análise de comportamentos, identificação de padrões.
    - Pode lidar com dados de diferentes formatos e tamanhos.
    - Sensível à escala dos dados, podendo necessitar de normalização.
    - A eficácia pode ser influenciada pelo método de inicialização e pelos parâmetros escolhidos.
    - Resultados podem variar com diferentes algoritmos e critérios de similaridade.
![[modelo Kmeans.png]]
## Métricas e Análises
### Aula 1 - Matriz de confusão
Uma matriz de confusão é uma ferramenta que permite avaliar o desempenho de um modelo de classificação.
- **Objetivo**
	- mostrar o número de acertos e erros do modelo
### Aula 2 - Métricas
#### Métricas de classificação
##### Precisão
- TP/(TP+FP)
- $$\frac{TruePositives}{TruePositives + FalsePositives}$$

	- Mede quantas das amostras positivas de fato foram categorizadas como positivas
#### Acurácia
- (TP + TN)/(TP+TN+FP+FN)
- $$\frac{TruePositives+TrueNegatives}{TruePositives+TrueNegatives + FalsePositives+FalseNegatives}$$
- mede quantas observações foram corretamente classificadas
- Não deve ser utilizada em dados não balanceados

#### Recall/Sensitivity
- TP/(TP+FN)
- $$\frac{TruePositives}{TruePositives+FalseNegatives}$$
- prioridade para a classificação
- quando queremos ter certeza que estamos pegando todos os verdadeiros
#### Especificidade
- TN/(TN+FP)
- $$\frac{TrueNegatives}{TrueNegatives + FalsePositives}$$
- Prioridade nos casos negativos
#### F beta Score
- $$(1+\beta^2)*\left( \frac{presicion*recall}{\beta^2*presicion+recall} \right)$$
- Leva em conta a precisão:
	- Acerta o máximo possivel de positivas
- E o recall:
	- Ter certeza que os positivos estão sendo classificados certos
#### F1-Score
- $$(1+1^2)*\left( \frac{presicion*recall}{1^2*presicion+recall} \right)$$
- $$(2)*\left( \frac{presicion*recall}{presicion+recall} \right)$$
- Harmonia entre precisão e recall

#### Formulas

|      Métrica       |                                               Fórmula                                               |
| :----------------: | :-------------------------------------------------------------------------------------------------: |
|      Precisão      |                      $$\frac{TruePositives}{TruePositives + FalsePositives}$$                       |
|      Acurácia      | $$\frac{TruePositives+TrueNegatives}{TruePositives+TrueNegatives + FalsePositives+FalseNegatives}$$ |
| Recall/Sensitivity |                       $$\frac{TruePositives}{TruePositives+FalseNegatives}$$                        |
|   Especificidade   |                      $$\frac{TrueNegatives}{TrueNegatives + FalsePositives}$$                       |
|    F beta Score    |          $$(1+\beta^2)*\left( \frac{presicion*recall}{\beta^2*presicion+recall} \right)$$           |
|      F1-Score      |                  $$(2)*\left( \frac{presicion*recall}{presicion+recall} \right)$$                   |

#### Métricas numéricas
como podemos comparar e avaliar os regressores
##### *MAE - Mean Absolute Erro* (Erro Médio Absoluto)
- media dos erros
- Quando temos dados ruidosos
$$
\text{MAE}(y, \hat{y}) = \frac{\sum_{i=0}^{N - 1} |y_i - \hat{y}_i|}{N}
$$
##### MSE - *Mean Squared Error* (Erro Quadrático Médio)
- Media dos erros Quadráticos
- Não podemos  ter dados muito divergentes
$$
\text{MSE}(y, \hat{y}) = \frac{\sum_{i=0}^{N - 1} (y_i - \hat{y}_i)^2}{N}
$$
##### RMSE  
- Raiz media dos erros quadráticos
- Não podemos ter dados muito divergentes
$$
\sqrt{\frac{\sum_{i=0}^{N - 1} (y_i - \hat{y}_i)^2}{N}}
$$
##### RMSLE
- Raiz media de log dos erros quadráticos
$$
\text{MSLE}(y, \hat{y}) = \frac{1}{N} \sum_{i=0}^{N - 1} (\log_e (1 + y_i) - \log_e (1 + \hat{y}_i) )^2
$$

### Aula 3 - Métodos de aprimoramento 
#### ROC e AUC
Os métodos de aprimoramento ROC (Receiver Operating Characteristic) e AUC (Area Under the Curve) são ferramentas importantes na avaliação de modelos de classificação, especialmente em problemas de classificação binária.
![[ROC e AUC.png]]
A AUC é a área sob a curva ROC. Ela fornece uma medida agregada do desempenho do modelo em todos os limiares possíveis. A AUC varia entre 0 e 1:

- **AUC = 1**: Modelo perfeito.
- **AUC = 0.5**: Modelo aleatório (sem poder discriminativo entre classes).
- **AUC < 0.5**: Modelo pior que aleatório.
#### Validação Cruzada
#### Tunagem de hyperparâmetros


---
## Referencias
- **LEITURA**:
	- **Livros**
	- **Artigos**
		1. [Medium - Where good ideas find you.](https://medium.com)
		2. [**Dashboard Design Patterns**](https://dashboarddesignpatterns.github.io): Demonstra boas práticas na hora de apresentar dados.
- **VIDEOS**
	- **Youtube**
		1. [A saga dos computadores](https://www.youtube.com/playlist?list=PLYjrJH3e_wDOA5mxhiMxE6yslcIzU5NkX)
		2. [StatQuest with Josh Starmer](https://www.youtube.com/channel/UCtYLUTtgS3k1Fg4y5tAhLbw)
		3. [UniversoProgramado](https://www.youtube.com/@UniversoProgramado)
	- **Filmes**
		1. Jogo da imitação:
		2. Estrelas além do tempo
- **OUTRAS REFERÊNCIAS**
	1. **[Business Intelligence and Analytics Software](https://www.tableau.com):** Essa ferramenta facilita a criação de dashboards.
	2. A biblioteca [Manim Community](https://www.manim.community) é uma biblioteca python para criação de vídeos animados.
---
## Mapa de estudo 