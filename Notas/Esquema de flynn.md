# Esquema de flynn
created:: 2024-03-15 16:51
tags:: #CIÊNCIA_DA_COMPUTAÇÃO  #flashcards 
people::

|                          | Single data | Multiple data |
| ------------------------ | ----------- | ------------- |
| **Single  instruction**  | SISD        | SIMD          |
| **Multiple Instruction** | MISD        | MIND          |

Essa tabela é conhecida como esquema de Flynn e tenta categorizar os computadores paralelos --- existem outros esquemas como esse, mas em geral acabam sendo imprecisos (este também).

1. SISD -  *Single instruction - Single Data*
	- Ele possui apenas um fluxo de instrução e de dados, de modo que apenas uma operação é feita por vez --- puramente sequencial.
2. SIMD - *Single instruction - Multiple Data*
	- Máquinas desse tipo possuem apenas um fluxo de instrução, mas possuem múltiplas unidades de cálculo. Isso significa que a máquina é capaz de executar uma mesma instrução em um conjunto de dados de maneira simultânea.
	- placas de vídeo que são especializadas neste tipo de operação
1. MISD - *Multiple instruction - Single Data*
	- Máquinas MISD operam várias instruções diferentes em um único dado
	- É quase que um modelo completamente teórico, sem nenhum exemplo real
1. MIMD - *Multiple instruction - Multiple Data*
	- São as máquinas que possuem CPUs independentes, onde cada unidade processante atua com instruções diferentes em dados diferentes.
	- Os processadores com mais de um núcleo caem nesse modelo.

o que significam essas "instruções únicas/múltiplas";;É o número de instruções diferentes que são executadas ao mesmo tempo.
<!--SR:!2024-03-16,1,230-->


---
## Referencias
- **LIVROS**:
	1. 
- **VIDEOS**
	1. 
- **OUTRAS REFERÊNCIAS**
	1. https://pt.stackoverflow.com/questions/257086/qual-o-significado-das-siglas-sisd-simd-misd-mimd-qual-a-sua-relação-com-pro