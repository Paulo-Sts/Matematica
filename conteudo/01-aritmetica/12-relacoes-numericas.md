# Relações Numéricas

## Múltiplos de um número
* Os múltiplos de um número, é o conjunto formado pelos resultados da multiplicação desse número, por cada um dos elementos que formam o conjunto dos números naturais.
* O conjunto dos múltiplos de um número, é um conjunto infinito, que se inicia sempre pelo número zero.
* Para verificar se um número **b** é múltiplo de **a** basta, dividir **b** por **a**, se o resultado for um número exato, então **b** é múltiplo de **a**.
* Representação dos múltiplos:
  - M(a) = {0, ...}

Ex: M(2)= {0, 2, 4, 6, 8, 10, ...}  

2 . 0 = 0    
2 . 1 = 2    
2 . 2 = 4    
2 . 3 = 6    
2 . 4 = 8    
2 . 5 = 10    

## Divisores de um número
* Os divisores de um número, são o conjunto formado pelos números por quem ele pode ser dividido e que ao dividi-lo tem um resultado exato.
* O conjunto dos divisores de um número é finito, se inicia pelo número um e termina no próprio número, ou seja, o maior divisor de um número é ele mesmo.
* O divisor que multiplicado por si mesmo é igual ao dividendo, é o elemento do meio do conjunto dos divisores desse dividendo, sendo os demais elementos divisores à sua direita, os números que multiplicados pelos elementos divisores à sua esquerda, a partir dos extremos, tem como resultado também o dividendo.
* O zero não é divisor de nenhum número.
* Representação dos divisores:
  - D(a) = {1, ..., a}

Ex: D(10)= {1, 2, 5, 10}  
   
10 : 1 = 10    
10 : 2 = 5    
10 : 3 = 3 com resto 1 (não divisível)      
10 : 4 = 2 com resto 2 (não divisível)  
10 : 5 = 2  
10 : 6 = 1 com resto 4 (não divisível)
10 : 7 = 1 com resto 3 (não divisível)
10 : 8 = 1 com resto 2 (não divisível) 
10 : 9 = 1 com resto 1 (não divisível) 
10 : 10 = 1  

**DICA:** Para verificar se o conjunto dos divisores de um número está correto, basta multiplicar os elementos extremos entre si. Todos os produtos devem ser iguais ao número que se quer saber seus divisores.

Ex: D(16)= {1, 2, 4, 8, 16}
1. Multiplica-se os dois primeiros extremos => 1 . 16 = 16
2. Multiplica-se os segundos extremos => 2 . 8 = 16
3. Para conjuntos com elementos impares, multiplica-se o elemento do meio por si mesmo => 4 . 4 = 16
4. Resposta: 16

#### Conjunto dos divisores de um número
1. Decompoe-se o número em fatores primos.
2. Os números da decomposição são utilizados para encontrar os divisores.
3. Começa-se multiplicando o primeiro número por 1.
4. O resultado de cada multiplicação é adicionado ao conjunto que conterá os divisores do número, começando pelo 1.
5. Depois multiplica-se os demais números por cada elemento do conjunto até o último, adicionando os resultados das multiplicações no conjunto ao final.
6. Realiza-se as multiplicações em cascata até o último número primo usado na fatoração.
7. O conjunto do resultado das multiplicações será o conjunto dos divisores do número.

Ex: D(12)= {1, 2, 3, 4, 6, 12}
1. Fatora-se o 12 => 12 : 2 = 6 => : 2 = 3 : 3 => 1 => (2, 2, 3)
2. Multiplica-se 2 por 1 => 2 . 1 = 2 => {1}.
3. Adiciona-se o resultado no conjunto => {1, 2}.
4. Multiplica-se o segundo 2 pelos elementos do conjunto => 2 . 1 = 2 | 2 . 2 = 4 
5. Adiciona-se os resultados da multiplicação no conjunto => {1, 2, 2, 4}
6. Multiplica-se o 3 pelos elementos do conjunto => 3 . 1 = 3 | 3 . 2 = 6 | 3 . 2 = 6 | 3 . 4 = 12
7. Adiciona-se os resultados da multiplicação no conjunto => {1, 2, 2, 4, 3, 6, 6, 12}
8. Ordena-se o conjunto, retirando valores repetidos formando o conjunto dos divisores do 12 => {1, 2, 3, 4, 6, 12}
9. Resposta: O conjunto dos divisores do 12 => {1, 2, 3, 4, 6, 12}

#### Quantidade de divisores de um número
1. Decompoe-se o número em fatores primos.
2. Organiza-se em potência os números primos utilizados na fatoração.
3. Soma-se 1 ao expoente de cada número primo.
4. O produto da desses expoentes terá como resultado a quantidade de divisores do número. 

Ex: D(12)= {1, 2, 3, 4, 6, 12}
1. Fatora-se o 12 => 12 : 2 = 6 => : 2 = 3 : 3 => 1 (2, 2, 3)
2. Organiza-se na forma de produto dos números primos => 2<sup>2</sup> . 3<sup>1</sup>
3. Pega-se o expoente de cada potência e soma um => 2 + 1 = 3 | 1 + 1 = 2
4. Multiplica-se os novos valores dos expoentes => 3 . 2 = 6
5. Resposta: O 12 possui 6 divisores

#### Soma dos divisores de um número
1. Decompoe-se o número em fatores primos.
2. Organiza-se em potência os números primos utilizados na fatoração.
3. Desenvolve-se a partir de cada número primo as combinações possíveis de seus expoentes começando do zero até o maior número.
4. Soma-se essas combinações.
5. Realiza-se o produto dos resultados da soma das combinações dos expoentes possíveis de cada número primo.

Ex: D(12)= {1, 2, 3, 4, 6, 12}
1. Fatora-se o 12 => 12 : 2 = 6 => : 2 = 3 : 3 => 1 (2, 2, 3)
2. Organiza-se na forma de produto dos números primos => 2<sup>2</sup> . 3<sup>1</sup>
3. Soma das combinações de cada número primo => (2<sup>0</sup> + 2<sup>1</sup> + 2<sup>2</sup>) | (3<sup>0</sup> + 3<sup>1</sup>)
4. Produto das somas das combinações de cada número primo será o resultado => (1 + 2 + 4) . (1 + 3) => 7 . 4 = 28
5. Resposta: 28

> ### Divisibilidades
* Os critérios de divisibilidade, determinam regras que possibilitam verificar sem precisar realizar um cálculo, se um número é divisível por outro (divisão exata).

#### Divisibilidade por dois
* Um número é divisível por dois, quando o número for par, ou seja, quando o número terminar em: zero, dois, quatro, seis ou oito.

Ex: 22 (é divisível)  
Ex: 31 (não é divisível)  

#### Divisibilidade por três
* Um número é divisível por três, quando a soma dos algarismos que o formam, for um número divisível por três.

Ex: 234 (é divisível)  
Ex: 34 (não é divisível)  

#### Divisibilidade por quatro
* Um número é divisível por quatro, quando os seus dois últimos algarismos forem zero, ou quando os dois últimos algarismos formarem um número divisível por quatro.

Ex: 1500 (é divisível)  
Ex: 1031 (não é divisível)  

#### Divisibilidade por cinco
* Um número é divisível por cinco, quando terminar em zero ou cinco.

Ex: 50 (é divisível)  
Ex: 11 (não é divisível)  

#### Divisibilidade por seis
* Um número é divisível por seis, quando ele for divisível por dois e por três ao mesmo tempo.

Ex: 132 (é divisível)  
Ex: 44 (não é divisível)  

#### Divisibilidade por oito
* Um número é divisível por oito, quando seus três últimos algarismos forem zero, ou ainda quando a soma dos três últimos algarismos formarem um número divisível por oito.

Ex: 28000 (é divisível)  
Ex: 244 (não é divisível)  

#### Divisibilidade por nove
* Um número é divisível por nove, quando a soma dos algarismos que o formam, for um número divisível por nove.

Ex: 819 (é divisível)  
Ex: 37 (não é divisível)  

#### Divisibilidade por dez
* Um número é divisível por dez, quando ele terminar em zero.

Ex: 1260 (é divisível)  
Ex: 505 (não é divisível)  

#### Divisibilidade por onze
* Um número é divisível por onze, quando a diferença entre a soma dos algarismos que o formam de posição ímpar e a soma dos algarismos que o formam de posição par, resultarem em zero, ou em um número divisível por onze.

Ex: 209 (é divisível)  
1. Soma-se os algarismos ímpares => 9 + 2 = 11
2. Soma-se os algarismos pares => 0 = 0
3. Realiza-se a subtração entre os dois resultados => 11 - 0 = 11
4. O resultado da diferença é divisível por onze => 11 : 11 = 1
5. Resposta: Sim

Ex: 411 (não é divisível)  

#### Divisibilidade por quize
* Um número é divisível por quinze, quanto ele for divisível por três e por cinco ao mesmo tempo.

Ex: 900 (é divisível)  
Ex: 155 (não é divisível)  

> ### Divisibilidade de números compostos
* A divisibilidade de números compostos é determinada pelos critérios de divisibilidade da composição da multiplicação dos números que o formam, pois eles não possuem critérios próprios de divisibilidade.
* Pode-se verificar a divisibilidade de qualquer número composto identificando quais números multiplicados resultam no número, quais os critérios de divisibilidade desses números e aplicar ao número que se deseja dividir esses critérios.

Ex: 12000 : 24 (é divisível)
1. Verificar os números que formam o 24 e seus critérios de divisibilidade => 24 = 8 . 3
2. É possível por 24, quando atender aos critérios de divisibilidade de 8 e 3.
3. (Divisibilidade por três) soma dos algarismos ser divisível por três => 1 + 2 + 0 + 0 + 0 = 3 (é divisível)
4. (Divisibilidade por oito) três últimos algarismos iguais a zero ou a sua soma ser divisível por oito => 12'000 = 000 (é divisível)
5. Dividir => 12000 : 24 = 500
6. Resposta: Sim