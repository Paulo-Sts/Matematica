# Operações com Matrizes

## Adição e Subtração de Matrizes
- A adição ou a subtração de duas matrizes, A e B, do mesmo tipo é efetuada somando-se ou subtraindo-se os seus elementos correspondentes.
- Representação:
  - C = A + B → cij = aij + bij
  - C = A - B → cij = aij - bij

Ex: A = [1 2; 2 4; 5 6], B = [4 5; 3 7; 0 -1] A + B ?  

1. 1 2 + 4 5 = 5 7
2. 2 4 + 3 7 = 5 11
3. 5 6 + 0 -1 = 5 5
4. C = [5 7; 5 11; 5 5]

Ex: A = [1 2; 2 4; 5 6], B = [4 5; 3 7; 0 -1] A - B ?  

1. 1 2 - 4 5 = -3 -3
2. 2 4 - 3 7 = -1 -3
3. 5 6 - 0 -1 = 5 7
4. C = [-3 -3; -1 -3; 5 7]

#### Propriedades

| PROPRIEDADE     | FÓRMULA                   |
|:----------------|:--------------------------|
| Comutativa      | A + B = B + A             |
| Associativa     | (A + B) + C = A + (B + C) |
| Elemento Neutro | A + 0 = A                 |
| Elemento Oposto | A + (-A) = 0              |

## Multiplicação Escalar
- Multiplicação escalar refere-se ao produto de um número real com uma matriz. Ao se trabalhar com matrizes os números reais são chamados de escalares.
- Em multiplicações escalares, cada elemento da matriz é multiplicado pelo escalar determinado.

Ex: A = [9 4; 0 -1] 2A ?

1. 9 . 2 = 18
2. 4 . 2 = 8
3. 0 . 2 = 0
4. -2 . 2 = -2
5. Resultado: A = [18 8; 0 -2]

## Multiplicação de Matrizes
- A multiplicação de matrizes corresponde ao produto entre duas matrizes. 
- Na multiplicação de duas matrizes, **A** e **B**, o número de colunas de **A** deve ser igual ao número de linhas de **B**, se não forem iguais não é possível multiplicar as matrizes. O produto **AB** terá o mesmo número de linhas de A e o mesmo número de colunas de B.
- Representação:
  - A<sub>m x n</sub> . B<sub>m x p</sub> = (A.B)<sub>m x p</sub>

| PROPRIEDADE             | FÓRMULA             |
|:------------------------|:--------------------|
| Associativa             | A. (BC) = (AB). C   |
| Distributiva à Direita  | A.(B + C) = AB + AC |
| Distributiva à Esquerda | (B + C).A = BA + CA |

- Observação:
  - A multiplicação de matrizes não é comutativa, isto é, existem matrizes A e B tais que AB ≠ BA.
  - Se ocorrer AB = BA, dizemos que as matrizes A e B comutam.
  - Na multiplicação de matrizes não vale a lei do anulamento do produto, isto é, podemos ter AB = 0, mesmo com A≠0 e B≠0.
  - Não vale também a lei do cancelamento, isto é, podemos ter AB = AC, mesmo com ≠0 e B≠0.

Exemplo: Dada as matrizes A e B a seguir, vamos calcular A. B  

| 1 | 2 |
|---|---|
| 3 | 4 |

|-1 | 3 |
|---|---|
| 4 | 2 |

1. As duas matrizes são estilo 2 (linha)x 2 (coluna).
2. É feita a multiplicação da linha vezes a coluna. 
3. A primeira linha vezes a primeira coluna é igual a 1 x -1 + 2 x 4 = 7
4. A primeira linha vezes a segunda coluna é igual a 1 x 3 + 2 x 2 = 7 
5. A segunda linha vezes a primeira coluna é igual a 3 x -1 + 4 x 4 = 13
6. A segunda linha vezes a segunda coluna é igual a 3 x 3 + 4 x 2 = 17
7. Resultado: C =  [7 7; 13 17]

Exemplo 2: Dada as matrizes A e B a seguir, vamos calcular A. B  

| 3 | 2 |
|---|---|
| 5 | -1|

| 6 | 4 | -2|
|---|---|---|
| 0 | 7 | 1 |

1. Multiplicar cada linha de A por cada coluna de B

| 3.6 + 2.0    | 3.4 + 2.7    | 3.(-2) + 2.1     |
|--------------|--------------|------------------|
| 5.6 + (-1).0 | 5.4 + (-1).7 | 5. (-2) + (-1).1 |

2. Somar o resultado

| 18 + 0 | 12 + 14 | -6 + 2 |
|--------|---------|--------|
| 30 + 0 | 20 - 7  | -10 -1 |

3. Resultado:

| 18 | 26 | -4 |
|----|----|----|
| 30 | 13 | -11|