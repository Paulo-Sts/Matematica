# Combinação com Repetição

## Definição
- É o cálculo do número de combinações possíveis dos **n** elementos de um conjunto **A**, em que o tamanho do agrupamento é maior que a quantidade de elementos do conjunto, ou seja, existe a repetição de elementos e a ordem dos elementos não importa.
- Fórmula: 
  - CR<sub>n,p</sub>= C<sub>n + p - 1, p</sub>
  - n = total de elementos do conjunto
  - p = tamanho do agrupamento

Ex: Um posto de combustível comprou 6 bombas (idênticas) de abastecimento, que serão pintadas, antes de sua instalação, com uma única cor, de acordo com o combustível a ser vendido em cada uma. O posto poderá vender etanol (cor verde), gasolina (cor amarela) e diesel (cor preta). De quantas maneiras as bombas podem ser pintadas, considerando a não obrigatoriedade de venda de qualquer tipo de combustível?


1. Total de elementos => verde, amarela e preta (3 elementos) 
2. Grupo => 6 bombas (agrupamento com 6 elementos)
3. Fórmula => CR<sub>3,6</sub> = C<sub>3 + 6 - 1, 6</sub>
4. Somar e subtrair => C<sub>3 + 6 - 1, 6</sub> => C<sub>8, 6</sub>
5. Encontrar o complementar da combinação => C<sub>8, 6</sub> = C<sub>8, 2</sub>
6. Fatorar => C<sub>8, 2</sub> =>  8 . 7/2 . 1
7. Multiplicar e dividir => C<sub>8, 2</sub> =>  8 . 7/2 . 1 = 56/2 = 28
8. Resposta: 28 combinações