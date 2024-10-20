---
tags:
  - Inteligência_Artificial
  - big_data
  - machine_learning
---
# Introdução à Inteligência Artificial - TIC em Trilhas
created:: 2024-03-14 16:47

## Módulo 1 - O que é inteligência artificial (IA)
### A Historia da IA
- O estudo das IAs existe desde os Anos 50.
- Em vários momentos da Historia houve uma pausa nesses estudos por falta de inventimento. faltou din din:💸💸💸💸💸🤑🤑🤑💸💸💸💸💸
```ad-cite
title:O que é inteligencia?
A definição de inteligência mais aceita pela comunidade científica é uma combinação de habilidades cognitivas e capacidades mentais que permitem aos indivíduos aprender, resolver problemas, adaptar-se a novas situações e pensar de maneira abstrata.
```
### IA no cotidiano
Nós já interagimos com IAs há muito tempo.
```ad-example
- Sistemas de recomendação em plataformas como **streaming** e **redes sociais**
- aprovação de crédito de bancos.
- IAs generativas como ChatGPT e etc...
```

### IA e o mercado de trabalho
**Profissões**
- Analista de Dados
- Cientista de Dados
- Engenheiro de Dados

### Tendências da IA
podcast do curso falando sobre o cenário atual da Inteligência Artificial

### Sociedade Data-Driven
```ad-quote
title:Introdução da aula
A análise e interpretação de dados se tornou algo fundamental no mundo moderno, e hoje os dados são considerados um bem valioso, utilizados para orientar decisões e políticas. Nesse vídeo iremos discutir a forma como os dados e sua utilização vêm impactando a economia e a sociedade.
```
```ad-question
title:De que forma os dados e sua utilização afetam o mundo? 
```
- quem é o chefe de quem trabalha para a Uber?
- Nossas decisões, são realmente nossas decisões?
	- podemos entrar em bolhas na internet, nos privando de outras visões.
### Perigo das falhas nos algoritmos
```ad-quote
title:Introdução da aula
Apesar de os algoritmos serem benéficos para a sociedade ao reduzir despesas, perigos e fornecer soluções para problemas complexos, é importante lembrar que, se executados sem supervisão adequada, podem resultar em consequências prejudiciais e inesperadas.
```
```ad-attention
title:Os algoritmos são confiaveis?
è importante resaltar que nossos algoritmos sempre vem com um grau de responsabilidade, sendo baixo ou alto, devemos nos atentar que se eles falharem prejudicaram seus usuários.
```
### Revolução da Big Data
```ad-quote
title:Introdução da aula
Um dos pilares da evolução na Inteligência Artificial foram os sistemas de Big Data, capazes de integrar, gerenciar e analisar os grandes volumes de dados gerados diariamente.
```
Com milhares de pessoas conectadas precisamos ter um cuidado a mais com os dados que são transferidos. 
```ad-info
title:Os 4 V's
- Volume
- velocidade
- Veracidade
- Variedade
```
A partir desses dados podemos customizar diversas coisas aos usuários,  tanto de aplicativos ou supermercados.

### Coleta e análise de dados
```ad-quote
title:Introdução da aula
A coleta e análise de dados em um contexto de Big Data são tarefas fundamentais que envolvem uma variedade de técnicas e ferramentas avançadas. A coleta de dados envolve a aquisição de grandes quantidades de dados de diversas fontes, e a análise de dados ajuda a entender tendências, padrões e informações importantes.
```
**Como coletar esses dados?**
- IOT : internet das coisas
- Redes Sociais
- Datasets públicos
- Web Scraping
### Computação em nuvem
```ad-quote
title:Introdução da aula
Assim como o Big Data foi importante para a Inteligência Artificial, ele só pode existir devido à Computação em Nuvem. A Computação em Nuvem é capaz de fornecer recursos para permitir a execução das ferramentas de armazenamento e processamento de dados.
```
A nuvem é simplesmente um computador que não temos acesso físico
## Módulo 2 - Ética e Dilemas
### Desbalanceamento de dados
```ad-info
![[Dados Desbalanceados.png|400]]
Em datasets há casos de desbalancementos de desses dados.
Ou seja, temos muitos mais casos de uma classe do que outra.
```
Isso se Torna um problema na hora de **fazer nosso modelo**, o modelo será vítima do [Paradoxo da Acurácia](https://medium.com/turing-talks/paradoxo-da-acurácia-56baa75334f2#:~:text=Definição,realizar%20predições%20de%20fato%20significativas.)👻👻
```ad-important
title: Lidando com Dados Desbalanceados
- **Reestruturação dos Dados**
	- Undersampling
	- Oversampling
- **Escolher um algoritmo mais resiliente**
	- Gradient Boosting (Recomendação)
- **Coletar mais dados**
	- métodos mais eficaz
	- utilizar essa técnica apenas em situações que os dados a serem adicionados são          similares o suficiente com a sua base inicial.
- **Usar modelos Penalizados (diferentes funções de custo)**
	- Atribuir pesos diferentes as classes
- **Utilizar outras métricas para o Treino**
	- ~~parâmetros de acurácia~~
- **Utilizar as métricas corretas de avaliação**
```
### Viés em IA
```ad-info
O viés pode ser identificado quando algum preconceito ou análise tendenciosa influencia alguma decisão.
```
```ad-summary
title:tipos de viés
- mais de 180 tipos de vieses
- viés de relatório
- viés de seleção
- viés discriminatório
- viés histórico
- viés de experimento
```
```ad-seealso
title:Maneiras de combater o viés
- avaliar o contexto
- Analisar os dados
- Avaliando as soluções geradas
- uso de Ferramentas 
	- AI fairness 360
	- What-if Tool
```
### Proteção de dados (LGPD)
LGPD - Lei Geral de Proteção de Dados Pessoais
```ad-info
title:trê conceitos importantes
- Privacidade
- Segurança
- Disponibilidade
```
==O Brasil vem aprimorando as leis de proteção dos dados.==

### O que é Consciência?
```ad-missing
title:Discutir sobre conciência de IA's é **paia**
```
```ad-info
title:Simular inteligencia humana é **extremamente dificil**
```
### Teste de Turing
Em resumo esse mede o quanto uma máquina consegue simular um comportamento humano.
- O teste consistia em colocar um humano para conversar com um máquina e um humano ao mesmo tempo. No final do teste o humana precisava responder qual era a máquina.

### IA e consciência
[[Introdução à Inteligência Artificial - TIC em Trilhas#O que é Consciência?]]
O que dá significado ao que os modelos de linguagem natural como ChatGPT e entre outros.
### Confiança e culpabilidade
```ad-question
title:O que é ética

```

**pilares da ética dentro da IA**
- justiça
- explicabilidade
- Robustes
- Transparência
- Privacidade dos Dados

**Responsabilidade compartilhada**
- Quem é responsabilizado pelos modelos de IA?
	- Desenvolvedores
	- Empresários
	- ...
### Tecnologia e desemprego - com Josiany Ketzer
```ad-info
title:Podcast
**Pontos em destaque:**
- 
```
### Direitos autorais – com Aline Schurmam
```ad-info
title:Podcast
**Pontos em destaque:**
- 
```

## Módulo 3 - Métodos de IA
### IA Clássica
```ad-note
title: **Lógica e Raciocínio**
collapse: open
primeira forma de imitar um comportamento humano foi a mais de 200 anos
lógica aristotélica
- só lembrar de portas lógicas **and**, **or** e **not**
- exemplo : Todos os homens são **mortais**, Platão é um **homem**, logo Platão é         **mortal**
```
```ad-note
title:**Planejamento e rotas**
collapse: open
relembrando conceitos de grafos dando exemplos com mapas e rotas que podem seguidos
algoritmos de busca informadas
- busca não informada - apenas definição do problema sem a necessidade de dados específicos
	- algoritmo de Dijkstra
		- garantia de encontrar o menor caminho para todos os pontos do grafo
		- lento
		- exaustivo
		- consumo de alto de memoria
- busca informada - é dado dicas para melhorar a execução da busca
	- algoritmo guloso
		- simples
		- rápido
		- nem sempre nos leva a melhor solução
	- algoritmo A-estrela
		- garantia de achar o menor caminho calculando  o menor número de passos possíveis
		- não adequado a problemas complexos
		- complexidade exponencial
```
```ad-note
title:**Algoritmos genéticos**
collapse: open
- computação evolutiva
- técnica de otimização usando conceitos de seleção natural.
- aplicações
	- planejamento de rotas
	- robótica
	- indústria automobilística
```
### Algoritmos de Recomendação
```ad-note
title: **Sistemas de recomendações personalizadas**
collapse: open
- modelos de machine Learning capazes de aprender o gosto do usuário
```
### Aprendizado por Reforço

```ad-note
title: **Fundamentos do aprendizado por reforço**
collapse: open
- o aprendizado por reforço pode envolver recompensas ou punições
- envolve várias técnicas desafiadoras
```
```ad-note
title: **Aprendizado por reforço na prática**
collapse: open
- Alguns dos principais exemplos do Aprendizado por Reforço podem ser observados em ambientes interativos, que apresentam diversas decisões e táticas complexas, e os jogos proporcionam um desafio interessante para o aprendizado.
```

## Módulo 4 - Visão Computacional
### Introdução a Visão computacional
```ad-note
title: A evolução da visão computacional
collapse: open
- Como os computadores exergam?
- os computadores enxergam apenas valores numericos.
- houve estudos sobre como a visão biológica funcionar.
	- começamos primeiro reconhecendo formas e coisas mais básicas.
	- Após nos focamos mais no detalhes.
```
```ad-note
title: Preprocessamento e filtros
collapse: open
exemplos de equipamento de captura
- camera de celular
- cameras de segurança
- sensores
- etc...

hoje em dia nos nossos equipamentos possuem um preprocessamento das imagens

**convolução**
- operação matematica
- dedicada a encontrar caracteristicas em imagens.

**preprocessamento**
- detecção de objetos
- detecção de humanos
- detecção de faces
- etc..
```
### Aplicações da visão computacional
```ad-note
title:**visão computacional no dia a dia**
collapse:open
- reconhecimento facial para desbloquear o celular
- serviços em diversas áreas
	- agricultura
	- fabril
	- automobilistica
- carro altonomo
- area medica
	- qualquer exame que gere imagem
- linha de produção de fábricas
```
### IA Generativa
```ad-note
title: Panorama de IA Generativa
collapse: open
Como a IA generativa funciona
Essas IA criam novos conteúdos???
IA's são limitadas a algumas funções

**Modelos de IA famosas:**
- ChatGPT
- Dall.E
- Lhama
- Gemini
- Copilot
```

## Módulo 5 - Processamento de Linguagem Natural
### Introdução ao processamento de linguagem natural
```ad-note
title:PLN - Visão geral
**Processamento de Linguagem Natural** (em inglês **Natural Language Processing**)
- Procura entender como os seres humanos processam e aprendem sobre a liguagem natural.

Sintaxe - estrutura das sentensas
Semântica - procura o significado das palavras e das sentensas 
Contexto - estuda a mudança da sintaxe e da semântica
Fonética - 
```
```ad-note
title:Pré-processamento em PLN
- Tokenização das palavras
- Normalização
	- palavras compostas
	- palavras científicas
	- textos informais
	- abreviações
	- preposições
- Stemming
	- efetivo em mecanismos de busca
- Particionamento
- reconheciemento de entidade nomeada
- modelamento de tópico
```
### Aplicações do PLN
```ad-note
title:PLN no dia a dia
- Podemos fazer uma pesquisa onde podemos predizer opniões de pessoas e até mesmo seus sentimentos.
- classificação de spam em emails
- O chat GPT pode ser resumido de uma forma bem burra como algo parecido com o corretor automático, prevendo a próxima palavra, em diversos apps de conversa. 
```
### Agentes conversacionais
```ad-note
title:Chatbots
- como treinar chatbots?
- chatbots - são assistentes conversacionais 
```
```ad-note
title:ChatGPT
- OpenAI
- lançamento : 2018
- palavras são tokenizadas.
- o treinamento desse troço é caro pra cacete.
- [[Introdução à Inteligência Artificial - TIC em Trilhas#O que é Consciência?]]
- o treinamento é **pura força bruta**.
```
### RASA Bot
```ad-note
title:Setup do ambiente
```




---
## Referencias
- **LEITURAS**:
	1. [turing-talks](https://medium.com/turing-talks/tagged/grupo-turing)
	2. ferramentas usadas para avaliar o viés e imparcialidade de modelos
		- [Fairness Indicators](https://www.tensorflow.org/responsible_ai/fairness_indicators/guide?hl=pt-br)
		- [AI Fairness 360](https://ai-fairness-360.org)
		- [Fairlearn](https://fairlearn.org)
		- [What-if Tool](https://pair-code.github.io/what-if-tool/)
- **VIDEOS**
	1. [O Grande PROBLEMA da INTELIGÊNCIA ARTIFICIAL](https://www.youtube.com/watch?v=_xog6mO_vOA)
	2. [ANALISTA DE DADOS X CIENTISTA DE DADOS X ENGENHEIRO DE DADOS](https://www.youtube.com/watch?v=k-Vo6pU5fgI)
	3. [Cloud Computing (Computação em Nuvem) // Dicionário do Programador](https://www.youtube.com/watch?v=97l0Ahu2efE)
	4. [PARADOXO DE BRAESS: Construir Estradas PIORA o Trânsito?](https://www.youtube.com/watch?v=a0PM0D4Z9wA)
	5. "O Dilema das Redes Sociais"
	6. Estes vídeos explicam um pouco mais sobre como funcionas as regulamentações da LGPD e GDPR.
		- [O que é LGPD? - Lei Geral de Proteção de Dados](https://www.youtube.com/watch?v=6zcbVahlqSg)
		- [O QUE É GDPR](https://www.youtube.com/watch?v=RiT3X2q8eFo)
	7. [Ted Talk Consciência Humana](https://www.ted.com/talks/david_chalmers_how_do_you_explain_consciousness?subtitle=en&lng=pt-br&geo=pt-br)
	8. [INTELIGÊNCIA ARTIFICIAL E DIREITOS AUTORAIS](https://www.youtube.com/watch?v=CVcHGnvKduU)
	9. [Ted Talk algoritmos genéticos.](https://www.youtube.com/watch?v=D3zUmfDd79s)
	10. Esse [tutorial](https://www.datacamp.com/tutorial/recommender-systems-python) demonstra o passo-a-passo de como construir um recomendador de filmes usando Filtragem Colaborativa com Python.
	11. Para entender um pouco mais sobre aprendizado por reforço e os feitos conquistados pelos modelos AlphaGo, OpenAI Five e AlphaStar, estes 3 vídeos exploram como estes modelos conseguiram superar os seres humanos em seus respectivos jogos: 
		- [AlphaGo: The Movie](https://www.youtube.com/watch?v=WXuK6gekU1Y)
		- [Artificial Gamer](https://www.youtube.com/watch?v=AZQeaUyNVsw)
		- [AlphaStar](https://www.youtube.com/watch?v=3UdH3lPF7nE)
- **OUTRAS REFERÊNCIAS**
	1.
---
## Mapa de estudo