# Machine Learning
created:: 2024-03-14 16:47
tags::
people::

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
**tipo:** 
- *Supervisionado*
- *Classificação*
- *Regressão*
**teoria**:
- Uma Árvore de Decisão é composta por nós que representam perguntas ou condições sobre os dados, e ramos que representam as possíveis respostas ou resultados.
**características**:
- 


---
## Referencias
- **LIVROS**:
	1. 
- **VIDEOS**
	1. 
- **OUTRAS REFERÊNCIAS**
	1.
---
## Mapa de estudo 