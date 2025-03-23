# Permutação com Repetição

## Definição
- É o cálculo do número de agrupamentos possíveis de um conjunto **A** de **n** elementos, em que cada agrupamento é formado por todos os elementos do conjunto **A** em uma determinada ordem e há repetição de elementos.
- A permutação significa trocar ou embaralhar, sendo um tipo de arranjo.
- Fórmula: 
  - P<sub>n</sub><sup>a, b, c</sup> = n!/a! . b! . c! ...
  - n = total de elementos
  - a, b, c = total de elementos repetidos de um mesmo tipo

Ex: Anagramas da palavra banana?

1. Total de elementos => 6 elementos
2. Elementos repetidos => a = 3, n = 2
3. Fórmula => P<sub>6</sub><sup>3, 2</sup> = 6!/3! . 2!
4. Fatorar => P<sub>6</sub><sup>3, 2</sup> = 6!/3! . 2! => P<sub>6</sub><sup>3, 2</sup> = 6 . 5 . 4 . 3!/3! . 2 . 1
5. Eliminar 3! => P<sub>6</sub><sup>3, 2</sup> = 6 . 5 . 4 . 3!/3! . 2 . 1 => P<sub>6</sub><sup>3, 2</sup> = 6 . 5 . 4/2 . 1
6. Multiplicar e dividir => P<sub>6</sub><sup>3, 2</sup> = 6 . 5 . 4/2 . 1 => P<sub>6</sub><sup>3, 2</sup> = 120/2 = 60
7. Resposta: 60 possibilidades


