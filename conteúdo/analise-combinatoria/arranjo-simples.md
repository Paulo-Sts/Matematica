# Arranjo Simples

<br>

## DEFINIÇÃO
* É o cálculo do número de agrupamentos possíveis dos **n** elementos de um conjunto **A**, em que o tamanho do agrupamento é igual ou menor a quantidade de elementos do conjunto e a ordem dos elementos no agrupamento importa. A característica dos elementos também importa.
* Fórmula: 
  - A<sub>n,p</sub>= n!/(n - p!)
  - n = total de elementos do conjunto
  - p = tamanho do agrupamento

Ex: Quantos números de 4 algarismos pode-se formar com os números: 1, 2, 3, 4, 5, 6, 7 sem repetição?

1. Total de elementos => 7
2. Tamanho do agrupamento => 4
3. Montar fórmula => A<sub>7,4</sub>= 7!/(7 - 4!)
4. Subtrair => A<sub>7,4</sub>= 7!/(7 - 4!) => A<sub>7,4</sub>= 7!/(3!)
5. Fatorar => A<sub>7,4</sub>= 7!/(3!) => A<sub>7,4</sub>= 7 . 6 . 5 . 4 . 3!/(3!)
6. Eliminar divisão => A<sub>7,4</sub>= 7 . 6 . 5 . 4 . 3!/(3!) => A<sub>7,4</sub>= 7 . 6 . 5 . 4
7. Multiplicar => A<sub>7,4</sub>= 7 . 6 . 5 . 4 = 840
8. Resposta: 840 possibilidades