# Sistemas Digitais
created:: 2024-03-06 18:59
tags:: #CIÊNCIA_DA_COMPUTAÇÃO #eletronica 
people:

```ad-info
title: Conceito de uma grandeza analógica e grandeza digital
Uma grandeza **==analógica==** é aquela que apresenta valores contínuos. Uma grandeza **==digital==** é aquela que apresenta valores discretos. A maioria daquilo que se pode medir quantitativamente na natureza se encontra na forma analógica.
```

## FUNÇÕES LÓGICAS E PORTAS LÓGICAS
1. O Inversor
3. A Porta AND 
4. A Porta OR 
5. A Porta NAND 
6. A Porta NOR 
7. As Portas OR Exclusivo e NOR Exclusivo
### O inversor (Gate NOT | Porta NOT)
O trabalho da porta NOT é inverter o sinal de entrada.
Expressão lógica : A' 
```ad-summary
title: Porta NOT tabela Verdade e Representação

| Entrada | Saida |
| :-----: | :---: |
|    0    |   1   |
|    1    |   0   |

![[porta NOT.png]]
```

### A porta AND
Uma porta AND produz uma saída de nível ALTO apenas quando todas as entradas forem nível ALTO.
```ad-summary
title:Porta AND tabela Verdade e Representação

| A   | B   | Saida |
| --- | --- | ----- |
| 0   | 0   | 0     |
| 0   | 1   | 0     |
| 1   | 0   | 0     |
| 1   | 1   | 1     |

![[porta AND.png]]
```
### A porta OR
Uma porta OR produz um nível ALTO na saída quando qualquer das entradas for nível ALTO.
```ad-summary
title:Porta OR tabela Verdade e Representação

| A   | B   | Saida |
| --- | --- | ----- |
| 0   | 0   | 0     |
| 0   | 1   | 1     |
| 1   | 0   | 1     |
| 1   | 1   | 1     |

![[porta OR.png]]
```
### A porta NAND
Uma porta NAND produz uma saída de nível BAIXO apenas quando todas as entradas estive- rem em nível ALTO
```ad-summary
title:Porta NAND tabela Verdade e Representação

| A   | B   | Saida |
| --- | --- | ----- |
| 0   | 0   | 1     |
| 0   | 1   | 1     |
| 1   | 0   | 1     |
| 1   | 1   | 0     |

![[porta NAND.png]]
```
### A porta NOR
Uma porta NOR produz uma saída de nível BAIXO quando qualquer uma de suas entradas for nível ALTO. 
```ad-summary
title:Porta NOR tabela Verdade e Representação

| A   | B   | Saida |
| --- | --- | ----- |
| 0   | 0   | 1     |
| 0   | 1   | 0     |
| 1   | 0   | 0     |
| 1   | 1   | 0     |

![[porta NOR.png]]
```

### As Portas OR Exclusivo e NOR Exclusivo
A saída de uma porta OR exclusivo (EX-OR) é nível ALTO apenas quando as duas entradas estão em níveis lógicos opostos.
```ad-summary
title:tabela Verdade e Representação

| A   | B   | Saida |
| --- | --- | ----- |
| 0   | 0   | 0     |
| 0   | 1   | 1     |
| 1   | 0   | 1     |
| 1   | 1   | 0     |

![[porta EX-OR.png]]
```

```ad-summary
title:tabela Verdade e Representação

| A   | B   | Saida |
| --- | --- | ----- |
| 0   | 0   | 1     |
| 0   | 1   | 0     |
| 1   | 0   | 0     |
| 1   | 1   | 1     |

![[porta XNOR.png]]
```

## Referencias
- **LIVROS**:
	- **Bibliografia básica**
		1. [FLOYD, THomas L. Sistemas Digitais: Fundamentos e Aplicações. 9 ed. Porto Alegre: Bookman, 2007.](obsidian://open?vault=mySecondBrain&file=Arquivos%2FFLOYD%2C%20Thomas%20-%20Sistemas%20Digitais_%20Fundamentos%20e%20Aplica%C3%A7%C3%B5es-Bookman%20(2007).pdf)
		2. VAHID, Frank. Sistemas Digitais: Projeto, Otimização e HDLs. Porto Alegre: Bookman, 2008.
		3. WIDMER, Neal S. Sistemas digitais: princípios e aplicações. 12 ed.. São Paulo: Pearson, 2018.
	- **Bibliografia complementar**
		1. BIGNELL, James. Eletrônica Digital. 5 ed.. Rio de Janeiro: Elsevier, 2009.
		2. CAPUANO, Francisco G. Sistemas Digitais ­ Circuitos Combinacionais e Sequenciais. 1 ed.. São Paulo: Érica, 2014.
		3. COSTA, Cesar. Projeto de Circuitos Digitais com FPGA. 3 ed.. São Paulo: Érica, 2014. 
		4. DACHI, Édison P. Eletrônica Digital. São Paulo: Blucher, 2018. 
		5. SOUZA, Diego B. C.; et al. Sistemas Digitais. 1 ed. São Paulo: SENAI, 2018. 
- **VIDEOS**
	1. 
- **OUTRAS REFERÊNCIAS**

## Mapa de estudo
1.   **FUNÇÕES LÓGICAS E PORTAS LÓGICAS **
	- PORTAS LÓGICAS BÁSICAS AND, OR, NOT, NAND, NOR ­ TABELAS ­VERDADE 
	- FUNÇÕES XOR E XNOR 
	- CONVERSÃO ENTRE EXPRESSÕES BOOLEANAS E CIRCUITOS LÓGICOS 
	- CONVERSÃO ENTRE TABELAS ­VERDADE E CIRCUITOS LÓGICOS
2.   **ÁLGEBRA BOOLEANA **
	- TEOREMAS DA ÁLGEBRA BOOLEANA 
	- MAPAS DE KARNAUGH 
	- SIMPLIFICAÇÃO DE CIRCUITOS ATRAVÉS DA ÁLGEBRA BOOLEANA 
	- SIMPLIFICAÇÃO DE CIRCUITOS ATRAVÉS DE MAPAS DE KARNAUGH
3.   **CIRCUITOS COMBINACIONAIS** 
	- PROJETOS DE CIRCUITOS COMBINACIONAIS COM 2, 3 E 4 VARIÁVEIS
	- CIRCUITOS COMBINACIONAIS DEDICADOS (ATIVIDADE PRÁTICA SUPERVISIONADA) 
	- CIRCUITOS MULTIPLEXADOR E DEMULTIPLEXADOR 3.4 CIRCUITOS ARITMÉTICOS ­ SOMADOR E SUBTRATOR (ATIVIDADE PRÁTICA SUPERVISIONADA) 
4.   **CIRCUITOS SEQUENCIAIS **
	- LATCHES E FLIP FLOPS 
	- PROJETO DE CIRCUITOS SEQUENCIAIS E REGISTRADORES DE DESLOCAMENTO (ATIVIDADE PRÁTICA SUPERVISIONADA) 
	- MEMÓRIAS 
	- MÁQUINAS DE ESTADOS FINITOS