# Sistemas distribuídos e computação paralela
created:: 2024-03-06 19:01
tags:: #CIÊNCIA_DA_COMPUTAÇÃO #flashcards 

## Fundamentos de Sistemas Distribuídos
**Propósito**
	Introduzir os conceitos fundamentais de sistemas distribuídos, bem como conhecer as técnicas que possibilitaram que esse tipo de arquitetura se desenvolvesse. Saber diferenciar os diversos conceitos dentro do tema e ter conhecimento de algumas arquiteturas de sistemas distribuídos, identificando vantagens e desvantagens.

***Tenha à mão um aplicativo de planilha eletrônica e uma calculadora ou use a calculadora de seu smartphone/computador.***
### OBJETIVOS
- Descrever os conceitos básicos de sistemas distribuídos
- Diferenciar memória compartilhada e memória distribuída
- Diferenciar paralelismo de dados e paralelismo de tarefas
- Identificar as arquiteturas de sistemas paralelos e distribuídos

### CONCEITOS DE SISTEMAS DISTRIBUÍDOS

#### definição formal 
```ad-quote
Um sistema distribuído é aquele no qual os componentes localizados em computadores interligados em rede se comunicam e coordenam suas ações apenas passando mensagens.
*(COULOURIS _et al._, 2013, p. 1)*
```

Os computadores conectados por uma rede podem estar em continentes diferentes, em um mesmo prédio ou sala, ou ainda a milhares de quilômetros de distância. A definição de Coulouris tem as seguintes consequências significativas:

#### Concorrência
 Em uma rede de computadores, a execução simultânea de programas é a regra geral.
#### Ausência de um relógio global
 existem limites para a precisão com a qual os computadores em uma rede podem sincronizar seus relógios
#### Falhas independentes
 Cada componente do sistema pode falhar independentemente, deixando os outros ainda em execução.

**==A principal motivação para construir e usar sistemas distribuídos é o compartilhamento de recursos==**

```ad-info
***cluster*** é um conjunto de servidores interconectados, que atuam como se fossem um único sistema e trabalham juntos para realizar tarefas de forma mais eficiente e escalável.
```
## TAXONOMIA DE FLYNN
A taxonomia de Flynn é uma categorização de formas de arquiteturas de computador paralelas.

- É uma metodologia para classificar formas gerais de operação paralela disponíveis em um processador.
- Propõe uma abordagem para esclarecer os tipos de paralelismo suportados no hardware por um sistema de processamento ou disponíveis em uma aplicação.
- Sua classificação é baseada na visão da máquina ou do aplicativo pelo programador de linguagem de máquina.

## [[Esquema de flynn]]

|            | **um**                                             | **vários**                                              |
| ---------- | -------------------------------------------------- | ------------------------------------------------------- |
| **um**     | SISD Arquitetura tradicional de von neumann        | MISD Compútadores em pipeline                           |
| **vários** | SIMD Processadores vetoriais de granularidade fina | MIMD Multicomputadores<br>           Multiprocessadores |
*Outra tabela com a mesma ideia*

|                          | Single data | Multiple data |
| ------------------------ | ----------- | ------------- |
| **Single  instruction**  | SISD        | SIMD          |
| **Multiple Instruction** | MISD        | MIND          |

## LEI DE AMDAHL E SPEEDUP
Existe um limite teórico para a velocidade de execução de tarefas em paralelo, que é determinado pela de Amdhl. 

```ad-attention
A lei de Amdahl afirma que podemos paralelizar e/ou distribuir nossos cálculos tanto quanto quisermos, ganhando em desempenho à medida que adicionamos recursos de computação. No entanto, nosso código não pode ser mais rápido do que a velocidade de suas partes sequenciais combinadas (ou seja, não paralelizáveis) em um único processador.
```
 ![[Parte Serial e Parte paralela.png]]
---
# Referencias
- **LIVROS**:
	1. 
- **VIDEOS**
	1. 
- **OUTRAS REFERÊNCIAS**
	1. 
---
## Mapa de estudo
