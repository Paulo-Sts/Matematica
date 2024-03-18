# Relações Numéricas

<br>

## MÚLTIPLOS DE UM NÚMERO
* Os múltiplos de um número, é o conjunto formado pelos resultados da multiplicação desse número, por cada um dos elementos que formam o conjunto dos números inteiros.
* O conjunto dos múltiplos de um número, é um conjunto infinito, que se inicia sempre pelo número zero.
* Para verificar se um número **a** é múltiplo de **b** basta, dividir **a** por **b**, se o resultado for um número exato, então **a** é múltiplo de **b**.
* Representação dos múltiplos:
  - M(a) = {0, ...}

Ex: M(2)= {0, 2, 4, 6, 8, 10, ...}  

2 . 0 = 0    
2 . 1 = 2    
2 . 2 = 4    
2 . 3 = 6    
2 . 4 = 8    
2 . 5 = 10    

## DIVISORES DE UM NÚMERO
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

***DICA:*** Para verificar se o conjunto dos divisores de um número está correto, basta multiplicar os elementos extremos entre si. Todos os produtos devem ser igual ao número que se quer saber seus divisores.

Ex: D(16)= {1, 2, 4, 8, 16}
1. multiplica-se os dois primeiros extremos => 1 . 16 = 16
2. multiplica-se os segundos extremos => 2 . 8 = 16
3. para conjuntos com elementos impares, multiplica-se o elemento do meio por si mesmo => 4 . 4 = 16

#### Conjunto dos divisores de um número
1. Decompoe-se o número em fatores primos.
2. Os números da decomposição são utilizados para encontrar os divisores.
3. Começa-se multiplicando o primeiro número por 1.
4. O resultado de cada multiplicação é adicionado ao conjunto que conterá os divisores do número, começando pelo 1.
5. Depois multiplica-se os demais números por cada elemento do conjunto até o último, adicionando os resultados das multiplicações no conjunto ao final.
6. Realiza-se as multiplicações em cascata até o último número primo usado na fatoração.
7. O conjunto do resultado das multiplicações será o conjunto dos divisores do número.

Ex: D(12)= {1, 2, 3, 4, 6, 12}
1. fatora-se o 12 => 12 : 2 = 6 => : 2 = 3 : 3 => 1 (2, 2, 3)
2. multiplica-se 2 por 1 => 2 . 1 = 2 => {1}.
3. adiciona-se o resultado no conjunto => {1, 2}.
4. multiplica-se o segundo 2 pelos elementos do conjunto => 2 . 1 = 2 | 2 . 2 = 4 
5. adiciona-se os resultados da multiplicação no conjunto => {1, 2, 2, 4}
6. multiplica-se o 3 pelos elementos do conjunto => 3 . 1 = 3 | 3 . 2 = 6 | 3 . 2 = 6 | 3 . 4 = 12
7. adiciona-se os resultados da multiplicação no conjunto => {1, 2, 2, 4, 3, 6, 6, 12}
8. ordena-se o conjunto, retirando valores repetidos formando o conjunto dos divisores do 12 => {1, 2, 3, 4, 6, 12}

#### Quantidade de divisores de um número
1. Decompoe-se o número em fatores primos.
2. Organiza-se em potência os números primos utilizados na fatoração.
3. Soma-se 1 ao expoente de cada número primo.
4. O produto da desses expoentes terá como resultado a quantidade de divisores do número. 

Ex: D(12)= {1, 2, 3, 4, 6, 12}
1. fatora-se o 12 => 12 : 2 = 6 => : 2 = 3 : 3 => 1 (2, 2, 3)
2. organiza-se na forma de produto dos números primos => 2<sup>2</sup> . 3<sup>1</sup>
3. pega-se o expoente de cada potência e soma um => 2 + 1 = 3 | 1 + 1 = 2
4. multiplica-se os novos valores dos expoentes => 3 . 2 = 6
5. o 12 possui 6 divisores

#### Soma dos divisores de um número
1. Decompoe-se o número em fatores primos.
2. Organiza-se em potência os números primos utilizados na fatoração.
3. Desenvolve-se a partir de cada número primo as combinações possíveis de seus expoentes começando do zero até o maior número.
4. Soma-se essas combinações.
5. Realiza-se o produto dos resultados da soma das combinações dos expoentes possíveis de cada número primo.

Ex: D(12)= {1, 2, 3, 4, 6, 12}
1. fatora-se o 12 => 12 : 2 = 6 => : 2 = 3 : 3 => 1 (2, 2, 3)
2. organiza-se na forma de produto dos números primos => 2<sup>2</sup> . 3<sup>1</sup>
3. soma das combinações de cada número primo => (2<sup>0</sup> + 2<sup>1</sup> + 2<sup>2</sup>) | (3<sup>0</sup> + 3<sup>1</sup>)
4. produto das somas das combinações de cada número primo será o resultado => (1 + 2 + 4) . (1 + 3) => 7 . 4 = 28

## DIVISIBILIDADE
* Os critérios de divisibilidade, determinam regras que possibilitam verificar sem precisar realizar um cálculo, se um número é divisível por outro (divisão exata).

> ### Divisibilidade por dois
* Um número é divisível por dois, quando o número for par, ou seja, quando o número termina em: zero, dois, quatro, seis ou oito.

Ex: 22 (é divisível)  
Ex: 31 (não é divisível)  

> ### Divisibilidade por três
* Um número é divisível por três, quando a soma dos algarismos que o formam, for um número divisível por três.

Ex: 234 (é divisível)  
Ex: 34 (não é divisível)  

> ### Divisibilidade por quatro
* Um número é divisível por quatro, quando os dois últimos algarismos forem um zero, ou quando os dois últimos algarismos formarem um número divisível por quatro.

Ex: 1500 (é divisível)  
Ex: 1031 (não é divisível)  

> ### Divisibilidade por cinco
* Um número é divisível por cinco, quando terminar em zero ou cinco.

Ex: 50 (é divisível)  
Ex: 11 (não é divisível)  

> ### Divisibilidade por seis
* Um número é divisível por seis, quando ele for divisível por dois e por três ao mesmo tempo.

Ex: 132 (é divisível)  
Ex: 44 (não é divisível)  

> ### Divisibilidade por oito
* Um número é divisível por oito, quando seus três últimos algarismos forem zero, ou ainda quanto a soma dos três últimos algarismos formarem um número divisível por oito.

Ex: 28000 (é divisível)  
Ex: 244 (não é divisível)  

> ### Divisibilidade por nove
* Um número é divisível por nove, quando a soma dos algarismos que o formam, for um número divisível por nove.

Ex: 819 (é divisível)  
Ex: 37 (não é divisível)  

> ### Divisibilidade por dez
* Um número é divisível por dez, quando ele terminar em zero.

Ex: 1260 (é divisível)  
Ex: 505 (não é divisível)  

> ### Divisibilidade por onze
* Um número é divisível por onze, quando a diferença entre a soma dos algarismos que o formam de posição ímpar e a soma dos algarismos que o formam de posição par, resultarem em zero, ou em um número divisível por onze.

Ex: 209 (é divisível)  
1. soma-se os algarismos ímpares => 9 + 2 = 11
2. soma-se os algarismos pares => 0 = 0
3. realiza-se a subtração entre os dois resultados => 11 - 0 = 11
4. o resultado da diferença é divisível por onze => 11 : 11 = 1

Ex: 411 (não é divisível)  

> ### Divisibilidade por quize
* Um número é divisível por quinze, quanto ele for divisível por tês e por cinco ao mesmo tempo.

Ex: 900 (é divisível)  
Ex: 155 (não é divisível)  

> ### Divisibilidade de números compostos
* A divisibilidade de números compostos é determinada pelos critérios de divisibilidade da composição da multiplicação dos números que o formam, pois eles não possuem critérios próprios de divisibilidade.
* Pode-se verificar a divisibilidade de qualquer número composto identificando quais números multiplicados resultam no número, quais os critérios de divisibilidade desses números e aplicar ao número que se deseja dividir esses critérios.

Ex: 12000 : 24 (é divisível)
1. verificar os números que formam o vinte e quatro e seus critérios de divisibilidade => 24 = 8 . 3
2. é possível por vinte e quatro, quando atender aos critérios de divisibilidade de oito e três.
3. (divisibilidade por três) soma dos algarismos ser divisível por três => 1 + 2 + 0 + 0 + 0 = 3 (é divisível)
4. (divisibilidade por oito) três últimos algarismos iguais a zero ou a sua soma ser divisível por oito => 12'000 = 000 (é divisível)
5. logo é possível dividir => 12000 : 24 = 500

## NÚMEROS PRIMOS
* Número primo, é todo número divisível apenas por um e por ele mesmo.
* O conjunto dos números primos é um conjunto infinito.
* O número um não é considerado um número primo.
* O número dois, é o único número primo par.
* O teorema fundamental da aritmética define que, todo número natural maior que 1 ou é primo ou pode ser representado como o produto de números primos.
* Os números primos são fundamentais no entendimento da aritmética.O processo de transformar qualquer número em produto de fatores primos é chamado de decomposição em fatores primos.
* A conjectura de Goldbach determina que, todo número par maior que 2 pode ser representado como a soma de dois números primos.
* Representação do conjunto de números primos:
  - P = {2, 3, 5, 7, 11, ...}

Ex: 4 = 2 + 2  
Ex: 18 = 11 + 7 

***DICA:*** Para descobrir se um número é primo, basta dividi-lo pelos números primos antecedentes ao número primo que possui raíz quadrada maior que o número que se quer descobrir se é primo ou composto, se a divisão for exata ele não é primo.

## NÚMEROS COMPOSTOS
* Número composto, é todo número que possua mais de dois divisores, ou seja, além de ser divisível por um e por si mesmo, esse número também é divisível por outros números.
* Todo número não primo é um número composto, assim como todo número composto pode ser representado a partir do produto dos números primos que o forma.

## DECOMPOSIÇÃO EM NÚMEROS PRIMOS OU FATORAÇÃO NUMÉRICA
* É o processo de representar um número composto qualquer, em forma de multiplicação, em que os elementos da multiplicação são todos números primos.
* O processo de decomposição, também chamado de fatoração é a divisão sucessiva de um número por números primos, até sua redução ao número um.
* Representação da decomposição:
  - n : p = A tal que reste 1, onde p = {2, 3, 5, 7, 11, ...} e A = produto entre os elementos de p.

Ex: Decomposição de 30 = 2 . 3 . 5
1. dividir por 2 => 30 : 2 = 15
2. como não é possível dividir por 2, dividi-se pelo próximo número primo o 3 => 15 : 3 = 5
3. divide-se agora por 5 => 5 : 5 = 1
4. o produto dos quocientes é o resultado = 2 . 3 . 5 

## MMC
* Mínimo múltiplo comum, é o menor número que é múltiplo de dois ou mais números ao mesmo tempo. 
* O MMC de dois números **a** e **b**, também representa o menor valor que pode ser dividido por **a** e **b** ao mesmo tempo.
* O MMC é determinado a partir da decomposição dos valores em fatores primos.

#### Cálculo
1. Organiza-se os números a esquerda lado a lado.
2. Começa-se a divisão dos números, a partir do menor número primo que divide ao menos um dos números, colocando o quociente a direita.
3. Coloca-se o resultado das divisões abaixo de cada número, e no caso de não ser possível dividir repete-se o número.
4. O quociente da divisão (número primo) também é ordenado um abaixo do outro para cada divisão.
5. Quando não for possível dividir mais pelo número primo, passa-se para o próximo número primo em que é possível realizar a divisão.
6. Quando todos os números forem reduzidos a um, termina-se a decomposição.
7. Multiplica-se os quocientes da decomposição (números primos).
8. O resultado da multiplicação é o MMC.

Ex: MMC de 30 e 14 = 210
1. dividir por 2 => 30 : ***2*** = 15, 14 : ***2*** = 7
2. como não é possível dividir por 2, dividi-se pelo próximo número primo o 3 => 15 : ***3*** = 5, 7 : ***3*** não divide, repete-se o 7
3. divide-se agora por 5 => 5 : ***5*** = 1, 7 : ***5*** não divide, repete-se o 7
4. divide-se agora por 7 => 1 : ***7*** = repete-se o 1, 7 : ***7*** = 1
5. o produto dos quocientes é o resultado => 2 . 3 . 5 . 7 = 210

> ### Propriedades do MMC

#### MMC entre números primos
* O MMC de dois ou mais números primos, será o produto entre esses números.

Ex: MMC(2, 11) = 22  
Ex: MMC(2, 5) = 10  

#### MMC entre múltiplos
* O MMC entre dois números, em que o maior é múltiplo do menor, será o número maior.

Ex: MMC(10, 2) = 10    
Ex: MMC(6, 3) = 6    

***DICA:*** Para identificar a utilização do MMC na resolução de um problema, basta verificar se na questão existem eventos simultâneos, ou seja, se a questão pede para que se calcule em quanto tempo dois ou mais eventos que já ocorreram ao mesmo tempo irão ocorrer novamente ao mesmo tempo.

## MDC
* Máximo divisor comum, é o produto dos divisores comuns de dois ou mais números.
* O MDC de dois números **a** e **b**, é o maior valor que divide **a** e **b** ao mesmo tempo.
* O MDC é determinado a partir da decomposição dos valores em fatores primos.

#### Cálculo
1. Organiza-se os números a esquerda lado a lado.
2. Começa-se a divisão dos números, a partir do menor número primo que divide ao menos um dos números.
3. Coloca-se o resultado das divisões abaixo de cada número, e no caso de não ser possível dividir repete-se o número.
4. O quociente da divisão (número primo) também é ordenado um abaixo do outro para cada divisão.
5. Quando não for possível dividir mais pelo número primo, passa-se para o próximo número primo em que é possível realizar a divisão.
6. Quando todos os números forem reduzidos a um, termina-se a decomposição.
7. Multiplica-se os quocientes da decomposição (números primos) em que foi possível dividir todos os números ao mesmo tempo.
8. O resultado da multiplicação é o MDC.

Ex: MDC de 30 e 12 = 6
1. dividir por 2 => 30 : **2** = 15, 12 : **2** = 6 (divisor comum)
2. dividir por 2 => 15 : **2** não divide, repete-se o 15, 6 : **2** = 3
3. como não é possível dividir por 2, dividi-se pelo próximo número primo o 3 => 15 : **3** = 5, 3 : **3** = 1 (divisor comum)
4. divide-se agora por 5 => 5 : **5** = 1, 1 : **5** repete-se o 1
5. o produto dos divisores comuns é o resultado => 2 . 3 = 6

> ### Propriedades do MDC

#### MDC entre números consecutivos
* Entre dois números consecutivos o MDC entre eles sempre será 1, pois eles são primos entre si.

Ex: MDC(11, 10) = 1  

#### MDC entre divisores
* O MDC entre dois ou mais números em que um deles é divisor dos demais, o MDC será esse número.

Ex: MDC(5, 10, 20) = 5  

#### Relação MDC e MMC
* O produto entre o MDC e o MMC de dois números é igual ao produto desses dois números. 
* Representação da relação:
  - MDC(a, b) x MMC(a, b) = a x b

Ex: MDC(10, 2) = 10 e MMC(10, 2) = 2 => 10 x 2 = 10 x 2  

***DICA:*** Para identificar a utilização do MDC na resolução de um problema, basta verificar se a questão pede que seja feita a separação de diferentes elementos em quantidades iguais ao mesmo tempo, sendo cada parte o maior tamanho possível.

***DICA:*** Ao se fatorar números para encontrar o MDC, pode-se optar por usar como divisor apenas números que dividam todos os valores ao mesmo tempo (fator comum), quando não for possível mais dividir, o produto dos divisores será o MDC, e o resto da divisão de cada valor, indicará o número de vezes que o MDC corresponde ao valor. Na lógica da divisão em partes iguais o MDC será o tamanho (comprimento) de cada pedaço e o resto da divisão de cada valor será a quantidade de pedaços iguais do tamanho do MDC em que cada valor será dividido.
