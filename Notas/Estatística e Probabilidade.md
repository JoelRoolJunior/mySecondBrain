# Estatística e Probabilidade
created:: 2024-03-06 19:00
tags:: #MATEMÁTICA
people::

## Análise de Dados Quantitativos
- **Descrição**: Análise exploratória, medidas de posição e medidas de dispersão.

- **Propósito**: Compreender as principais ferramentas de análise exploratória de dados e as medidas de posição e dispersão.

- **Preparação**:Antes de iniciar o conteúdo, tenha em mãos uma calculadora científica ou use a calculadora de seu smartphone/computador.

**OBJETIVOS**
Reconhecer as ferramentas de análise exploratória de dados.
Analisar as medidas de posição ou tendência central.
Descrever as medidas de dispersão ou variabilidade.
## Análise exploratória de dados

- Vamos analisar os conceitos das principais medidas de dispersão, tais como variância, desvio-padrão e coeficiente de variação.
### Ferramentas de análise exploratória de dados
- responsável pelo primeiro contato com a informação
- útil na detecção de  erros, de valores extremos(outliers)
- entre outras

#### Classificação das variáveis

**Quantitativas**: Quando assumem valores numéricos.
**Qualitativas**: Quando seus possíveis valores não são numéricos

![[classificação das Variáveis.png]]
#### Conceitos básicos
- **População**: Conjunto de indivíduos ou objetos com pelo menos uma característica em comum.
- **Amostra**: Uma parte da população.
- **Dados brutos**: Conjunto de dados que não tem uma ordem aparente.
- **Rol**: Conjunto de dados que tem um ordenamento, seja crescente ou decrescente.
- **Amplitude total**: Diferença entre o maior e o menor valor observado no conjunto de dados.

## Distribuições de frequência
A distribuição de frequência é uma das formas mais simples e úteis de resumir um conjunto de dados.
Nada mais é do que a apresentação dos dados em classes às suas respectivas frequências absolutas.
As classes são divisões dos valores da variável em estudo.
### Elementos da distribuição de frequência
###### Limites de classe: 
São as várias formas de expressar os limites de classe em uma distribuição de frequência. O limite à esquerda é chamado de limite inferior (Li) e o limite à direita é chamado de limite superior (Ls) da classe.
como representa-las?

| notação  escrita | notação matemática | descrição                                                     |
| ---------------- | ------------------ | ------------------------------------------------------------- |
| Li \|---\| Ls    | [Li , Ls]          | indica uma classe que é fechada à esquerda e à direita        |
| Li \|--- Ls      | [Li , Ls[          | indica uma classe que é fechada à esquerda e aberta à direita |
| Li ---\| Ls      | ]Li , Ls]          | indica uma classe que é fechada à direita e aberta à esquerda |
###### Amplitude de Classe(AC)
É a diferença entre o limite superior e o limite inferior da classe.
###### Ponto Médio da classe (Xi)
Média Aritmética entre o limite superior e o limite inferior da classe
$$
X_i = \frac{Li + Ls}{2} = 
$$
No cálculo do ponto médio da classe (Xi), os limites superior e inferior são considerados, mesmo se as classes forem fechadas ou abertas
###### frequência relativa $F_i$%
É a frequência relativa dada por: $F_i$% $=\frac{F_i}{n}$, em que $n = \sum{F_{i}}$
Observe que para obter a frequência relativa de cada classe, basta dividir a frequência absoluta de cada uma por n, que é o tamanho do conjunto de dados ou tamanho da amostra. Então,
$f_{1}$% $= \frac{F_{1}}{n}*100$
$f_{2}$% $= \frac{F_{2}}{n}*100$
$f_{3}$% $= \frac{F_{3}}{n}*100$

###### frequência Acumulada ($F_{ac}$)
É o acúmulo das frequências absolutas.
A partir da primeira frequência, somam-se as respectivas frequências absolutas.
exemplo:
[[Tabela2_Análise_de_dados_quantitativos.pdf]]
Veja que, para a primeira classe, a frequência acumulada é igual à frequência absoluta. A partir daí, começamos a somar as frequências absolutas, de forma que a acumulada da segunda classe é a frequência absoluta da primeira classe mais a frequência absoluta da segunda classe, ou seja,

## Representações gráficas
É importante  conhecer  os principais tipos de gráficos e quando aplica-los.
São ferramentas fundamentais de visualização.
###### Gráfico de barras ou colunas
É o tipo de gráfico mais utilizado em geral, pois serve para representar quaisquer dados ==quantitativos==.
*Exemplo*: Considere a distribuição de frequência referente à quantidade de famílias que receberam auxílio escolar por número de filhos.
![[gráfico de barras.png]]
###### Histograma
É o gráfico típico da distribuição de frequência. A diferença desse gráfico para o gráfico de barras ou colunas se dá pelo fato de as colunas apresentarem-se justapostas, ou seja, sem espaçamento entre elas. Em geral, a abcissa desse gráfico é representada pelas classes e a ordem é representada pela frequência absoluta ou relativa.
*Exemplo*: Considere a distribuição de frequência a seguir, que representa as notas na disciplina de estatística em uma turma de 40 alunos.
![[Histograma.png]]
###### Gráfico de Linhas
É o gráfico mais apropriado quando trabalhamos com uma série de tempo.
*Exemplo*: Número de acidentes por mês ao longo de um ano.
![[Gráfico de Linhas.png]]
###### Setor
É o gráfico mais apropriado quando trabalhamos com porcentagens.
*Exemplo*: Em uma pesquisa de satisfação sobre determinado produto, 55% dos entrevistados disseram que estavam satisfeitos, 35% disseram que estavam insatisfeitos e 10% disseram que eram indiferentes.
![[Setor.png]]
###### Caixa (BoxPlot)
É um dos gráficos mais utilizados atualmente, visto que traz várias informações sobre o conjunto de dados. Com esse gráfico é possível verificar a tendência central, a variabilidade e a simetria da distribuição dos dados, conceitos esses que serão vistos de forma mais detalhada posteriormente.
*Exemplo*: Considere os dados referentes aos preços de aluguéis de imóveis (em reais) em certo bairro do Rio de Janeiro.

1000 1500 1800 2000 2200 2500 2600 3000 3500 7000
![[boxplot.png]]
Observe que nesse gráfico temos informações como: o primeiro e o terceiro quartis, a **mediana** e a **média**. Os traços abaixo do primeiro quartil e acima do terceiro quartil representam o **menor** e o **maior** valor dentro do intervalo normal de variação dos dados.

## Medidas de posição ou tendência central
---
## Referencias
- **LIVROS**:
	1. [Carlos A. B. Dantas - Probabilidade_ um Curso Introdutório-Edusp (2008)](obsidian://open?vault=mySecondBrain&file=Arquivos%2FCarlos%20A.%20B.%20Dantas%20-%20Probabilidade_%20um%20Curso%20Introdut%C3%B3rio-Edusp%20(2008).pdf)
- **VIDEOS**
	1. 
- **OUTRAS REFERÊNCIAS**
	1. 