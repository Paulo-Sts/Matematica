# Combinação Simples

<br>

## DEFINIÇÃO
* É o cálculo do número de combinações possíveis dos **n** elementos de um conjunto **A**, em que o tamanho do agrupamento é igual ou menor a quantidade de elementos do conjunto e a ordem dos elementos não importa, ou seja, os mesmos elementos em ordem distinta representam uma mesma combinação.
* Fórmula: 
  - C<sub>n, p</sub>= n!/p!(n - p!)
  - n = total de elementos do conjunto
  - p = tamanho do agrupamento

Ex: Quais as alternativas ao se convidar 3 amigos entre os amigos A, B, C, D e E?

1. Total de elementos => A, B, C, D e E (5 elementos e sem repetição)
2. Grupo => 3 pessoas (agrupamento com 3 elementos)
3. Fórmula => C<sub>5,3</sub>= 5!/3!(5 - 3!)
4. Subtrair => C<sub>5,3</sub>= 5!/3!(5 - 3!) => C<sub>5,3</sub>= 5!/3! . 2!
5. Fatorar => C<sub>5,3</sub>= 5!/3! . 2! => C<sub>5,3</sub>= 5 . 4. 3!/3! . 2 . 1
6. Eliminar 3! => C<sub>5,3</sub>= 5 . 4. 3!/3! . 2 . 1 => C<sub>5,3</sub>= 5 . 4/2 . 1
7. Multiplicar => C<sub>5,3</sub>= 5 . 4/2 . 1 => C<sub>5,3</sub>= 20/2
8. Dividir => C<sub>5,3</sub>= 20/2 = 10
9. Resposta: 10 possibilidades
