# Modelagem de sistemas em UML
created:: 2024-03-06 19:02
tags:: #CIÊNCIA_DA_COMPUTAÇÃO
people::

## Conceitos Básicos de Modelagem de Sistemas

UML - *Unified Modeling Language* - Linguagem de Modelagem Unificada
é uma língua padrão para a elaboração da estrutura de projetos de software

OBJETIVOS
	- Reconhecer a importância dos modelos na exposição de requisitos e soluções sistêmicas
	- Distinguir os conceitos e pilares de análise e projeto orientados a objetos
	- Descrever as visões, a síntese geral e os diagramas da UML


==o foco dessas anotações é no desenvolvimento de sistemas orientado a objetos.==

### O que são modelos e para que eles servem
- uma simplificação da realidade
- **Modelo:** *representação abstrata e simplificada da realidade.*
- **Finalidade principal:** *antecipar a existência de uma realidade de forma a avaliar sua estrutura e comportamento.*
- **exemplos:** Maquetes, planta baixa de uma casa e etc.
### Modelos se aplicam ao contexto de desenvolvimento de sistemas?
- funciona também como instrumento de gerenciamento de complexidade.
- ajuda no processo de abstração
###### pontos positivos 
- comunicação entre as pessoas envolvidas
- redução nos custos do desenvolvimento
- facilidade para alterações do sistema
- documentação dos sistema
- delimitar o escopo do sistema											
## MODELAGEM DE SISTEMAS
Diferentes modelos podem ser usados em um mesmo sistema, cada um de um ponto de vista diferente
Outra forma de abordar os sistemas computacionais por meio de visões que seriam:

| Externa                                                                                                                        | Comportamental                                                                           | Estrutural                                                                 | Interação                                                                               |
| ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| modela-se o ambiente em que o sistema está inserido, mostrando sua relação com os usuários e demais sistemas com que interage. | modela-se o comportamento dinâmico do sistema e como ele reage aos eventos que o afetam. | modela-se sua estrutura organizacional ou os dados que o sistema processa. | modela-se as interações de seus componentes ou ainda do sistema e seu ambiente externo. |
- Os modelos são abstratos, deixando de lado os detalhes e concentrando-se nos aspectos de interesse que são relevantes. A esse processo chamamos de **abstração**.
- Cada modelo apresenta o sistema sob uma diferente visão ou perspectiva da realidade.
- Os modelos são descritos em notações gráficas, que denominamos diagramas.
## O PROCESSO DE DESENVOLVIMENTO DE SISTEMAS EM FASES
Inicio do processo, quando o nível de abstração é alto e pouco se conhece da realidade. 
![[Realidade Nebulosa.png]]

*O principal recurso no desenvolvimento de um sistema são pessoas, profissionais capacitados.*

Para representar adequadamente a realidade e entender o que se passa no contexto do sistema a ser construído, precisamos traduzir a realidade em modelos.
## FASES COMUNS E MAIS RELEVANTES DO PROCESSO DE DESENVOLVIMENTO

Os modelos são, portanto, uma representação simplificada da realidade, representando os elementos de interesse naquele momento, permitindo abstrair o que não interessa e concentrar naquilo que de fato é relevante para o desenvolvimento do sistema.

As metodologias de processos podem ser divididos em fases.
###### Identificação dos requisitos
necessidades que os usuários têm e que devem estar contidos nas funcionalidades e propriedades do sistema a ser construído.
###### Análise
Compreende-se o que o sistema deve fazer 
###### Projeto
Como eles serão implementados, usando a tecnologia adequada para tal, definindo sua arquitetura e seus componentes.
redes de computadores, banco de dados, linguagem de programação, dentre outros elementos.
###### Implementação
diz respeito à identificação dos programas necessários e sua **codificação na linguagem de programação** selecionada na fase de projeto, bem como o banco de dados que será usado.

## MODELOS COMO ELEMENTOS DE COMUNICAÇÃO
Os modelos atuam em mão dupla enquanto elementos de comunicação no processo de desenvolvimento de sistemas, ajudando:
**a) no entendimento e na validação dos modelos junto aos usuários; e  
b) no entendimento do sistema por membros da equipe de desenvolvimento.**

existem três momentos do entendimento e validação dos modelos junto aos usuários
**Equipe levantando dados  junto ao usuário:** Equipe se reúne com os usuários usando técnicas de levantamento de dados
**Equipe Construindo modelos:** A equipe de desenvolvimento constrói os modelos que julga pertinentes para compreender e destacar aspectos relevantes da realidade
**Equipe Validando dados junto aos usuários:** validação com os usuário para garantir que o(s) modelo(s) representam de fato a realidade

---
## PARADIGMA ORIENTADO A OBJETOS
**Pilares da Programação Orientada a Objetos:**
- abstração
- encapsulamento
- herança
- polimorfismo
**Princípios centrais da Orientação a objetos:**
- Qualquer coisa do mundo real é um objeto
- Objetos realizam tarefas requisitando serviços a outros objetos
- Os objetos similares são agrupados em classes e cada objeto pertence a uma classe
- A classe determina o comportamento possível a um objeto
- Classes são organizadas em hierarquias
## CONCEITOS FUNDAMENTAIS DA ORIENTAÇÃO A OBJETOS
```ad-important
Quanto mais acima, mais genérico.
Quanto mais abaixo, mais específico.
```
### Objetos e classes
Um objeto pode referenciar qualquer coisa do mundo real.
Um objeto é um elemento específico de uma classe, ou ainda uma instância de uma classe.

```ad-note
**Classe**: abstração das características de um grupo de coisas do mundo real.  
**Objeto**: um elemento específico de uma classe ou uma instância de uma classe.
```

**EXEMPLO DE CLASSE**
- ![[Exemplo de classe em UML.png]]
**EXEMPLO DE OBJETO**
- ![[Exemplo de objeto em UML.png]]

### Operação, mensagem e estado
![[Partes de um Objeto.png]]

## ANÁLISE DE SISTEMAS ORIENTADA A OBJETOS
De forma simples, pode-se dizer que a atividade de análise visa identificar  ***o que***  os usuários e os demais interessados (que juntos formam os _stakeholders_) precisam que o sistema faça.
```ad-info
A preocupação da atividade de análise é identificar: O QUE o sistema deve fazer para atender às necessidades de seus usuários.**
```
##### Levantamento de requisitos
```ad-note
As necessidades e os desejos que os usuários têm são, tecnicamente, chamados de **requisitos**.
```
```ad-important
**Requisitos Funcionais:** Declaram as funcionalidades necessárias ao sistema.
**Requisitos não Funcionais:** Apresentam algumas características associadas a uma, algumas ou todas as funcionalidades, e dizem respeito a aspectos de qualidade, confiabilidade, desempenho, portabilidade, segurança e usabilidade do sistema.
```

==Um ponto a ser estudado é o **documento de Requisitos**==

```ad-tip
title:Dica
O **documento de requisitos** seguirá como base da comunicação entre os desenvolvedores e os usuários, devendo ser validado por estes, uma vez que servirá de norte para as atividades subsequentes do desenvolvimento do sistema. É, portanto, fundamental a participação ativa e efetiva dos usuários do sistema na fase de levantamento de requisitos.

No documento de requisitos estará definido, também, o escopo do sistema.

```

O principal ponto da fase de levantamento de requisitos é compreender profundamente no sistema antes de iniciar a sua construção.

### Análise de requisitos
- um requisito funcional pode demandar mais de uma funcionalidade e uma funcionalidade pode agregar mais de um requisito funcional.
- A análise de requisitos tem, minimamente, duas perspectivas ou visões:
	- **[[ANÁLISE DO DOMÍNIO (OU DO NEGÓCIO)]]** - Visa a identificar ou modelar os objetos que serão usados na aplicação.
	- **[[ANÁLISE DA APLICAÇÃO]]** - 

---
## Referencias
- **LIVROS**:
	1. 
- **VIDEOS**
	1. 
- **OUTRAS REFERÊNCIAS**
	1. 