# Permutação

<br>

## DEFINIÇÃO
* Permutação é o cálculo do número de agrupamentos possíveis de um conjunto **A** de **n** elementos, em que cada agrupamento é formado por todos os elementos do conjunto **A** em uma determinada ordem.
* A permutação significa trocar ou embaralhar, sendo um tipo de arranjo.
* Fórmula: 
  - P<sub>n</sub> = n!
  - n = total de elementos

Ex: De quantas maneiras possíveis 5 pessoas podem ser ordenadas em uma fila?

1. P<sub>5</sub> = 5!
2. P<sub>5</sub> = 5 . 4 . 3 . 2 . 1 = 120 
3. Resposta: 120 possibilidades

> ### Tipos de permutação

#### Permutação simples
* É o total de agrupamentos possíveis em que a ordem importa e não há repetição dos elementos.

Ex: Número de anagramas da palavra pato?  

1. Total de elementos => p, a, t, o (4 elementos e sem repetição)
2. P<sub>4</sub> = 4!
3. P<sub>5</sub> = 4 . 3 . 2 . 1 = 24
4. Resposta: 24 possibilidades

***DICA:*** Questões em que se pede os agrupamentos possíveis onde duas ou mais letras devem estar juntas, considera-se as duas ou mais letras como uma só.

Ex: Agrupamentos com a palavra **alberto** em que a as letras **abl** aparecem juntas?

1. Número de elementos => e, r, t, o = 4 + abl = 1 => 5 elementos
2. P<sub>5</sub> = 5 . 4 . 3 . 2 . 1 = 120 
3. Resposta: 120 possibilidades



#### Permutação com repetição
* É o total de agrupamentos possíveis em que a ordem importa e não há repetição dos elementos.

Ex: Número de anagramas da palavra pato?  

1. Total de elementos => p, a, t, o (4 elementos e sem repetição)
2. P<sub>4</sub> = 4!
3. P<sub>5</sub> = 4 . 3 . 2 . 1 = 24
4. Resposta: 24 possibilidades

##### PERMUTAÇÃO CIRCULAR
* Ordenação dos elementos em que alguns elementos podem se repetir em etapas diferentes.
* Fórmula: 
  - PC<sub>n</sub>= (n - 1)!
  - n = Total de opções