# Progressão Aritmética

<br>

## DEFINIÇÃO
* Progressão aritmética é uma sequência de números em que cada termo a partir do segundo, se da pela soma do termo anterior com uma constante **r**. Essa constante é chamada de razão da P.A.
* As progressões aritméticas podem ser formadas por uma determinada quantidade de termos (P.A finita), ou por termos infinitos (P.A infinita).
* Cada termo da sequência possui uma posição definida, sendo a sua posição em relação aos outros termos determinante para estabelecimento dos próximos termos da P.A.
* Representação da P.A finita:
  - (a<sub>1</sub>, a<sub>2</sub>, a<sub>3</sub>, a<sub>4</sub>, a<sub>5</sub>, a<sub>n-1</sub>, a<sub>n</sub>)
  - a<sub>1</sub> = primeiro termo
  - a<sub>n</sub> = enésimo termo
* Representação da P.A infinita:
  - (a<sub>1</sub>, a<sub>2</sub>, a<sub>3</sub>, a<sub>4</sub>, a<sub>5</sub>, ...)
  - a<sub>1</sub> = primeiro termo

Ex: (2, 5, 8, 11)  
Ex: (20, 10, 0, -10, ...)

> ### Cálculo da razão da P.A
* A razão de uma P.A é determinada a partir da subtração de um termo pelo seu antecessor, se para todos os termos da sequência essa operação tiver uma mesmo resultado, trata-se de uma P.A e o resultado é a razão da P.A.
* Para determinar o próximo termo da P.A, basta somar o termo anterior com o valor da razão.
* Fórmula da razão de uma P.A:
  - r = a<sub>n</sub> - a<sub>n-1</sub>
  - r = razão da P.A
  - a<sub>n</sub> = enésimo termo
  - a<sub>n-1</sub> = termo anterior

#### Cálculo
1. Subtraí-se o 2º termo da P.A pelo primeiro termo.
2. Verifica-se se a subtração entre os demais termos e pelo seu antecessor tem o mesmo resultado.
3. Se sim, trata-se de uma P.A e esse valor é a razão que a determina.

Ex: (2, 5, 8, 11) => r = 3
1. 2º termo = 5 e 1º termo = 2 => 5 - 2 = 3
2. 3º termo = 8 e 2º termo = 5 => 8 - 5 = 3
3. 4º termo = 11 e 3º termo = 8 => 11 - 8 = 3
4. Resposta: O r = 3

> ### Classificação das P.A
* As progressões aritméticas são definidas, a partir do valor das razões que a definem.

#### Constante
* Progressão aritmérica em que o valor da razão é igual a zero. Sendo assim todos os termos da P.A possuem o mesmo valor.

Ex: (2, 2, 2, 2, 2) => r = 0  

#### Crescente
* Progressão aritmética em que o valor da razão é maior que zero. Os termos da P.A sempre aumentarão de valor.

Ex: (2, 8, 14, 20, 28, ...) => r = 6  

#### Decrescente
* Progressão aritmética em que o valor da razão é menor que zero. Os termos da P.A sempre diminuirão de valor.

Ex: (30, 25, 20, 15, 10, 5, 0, -5, -10, ...) => r = -5  

> ### Propriedades das progressões aritméticas

#### Igualdade da soma de termos equidistantes e a soma dos termos extremos
* Em uma P.A finita, a soma dos termos equidistantes dos extremos é igual a soma dos termos extremos.

Ex: (2, 6, 10, 14, 18, 22, 26)  
1. Soma dos extremos => 2 + 26 = 28
2. Soma do 2º e 6º termo => 6 + 22 = 28
3. Soma do 3º e 5° termo => 10 + 18 = 28

***DICA:*** Essa propriedade é útil em questões que se pede para encontrar o valor de um determinado termo, a partir dos termos dados, por exemplo tem se os 1º, 2º e 6º termos e se pede o valor do 5º termo. 

#### Relação entre três termos consecutivos
* Considerando três termos consecutivos de uma P.A, o termo do meio será igual a média aritmética dos termos dos extremos.

Ex: (2, 6, 10, 14, 18, 22, 26)  
1. Selecionando três termos consecutivos => 10, 14, 18
2. Média dos termos extremos => 10 + 18 = 28/2 = 14
3. Igualdade com o termo do meio => 14 = 14

#### Igualdade entre o valor central e a média dos termos equidistantes de uma P.A de tamanho ímpar
* Em uma P.A finita com número ímpar de termos, o termo central é igual à média aritmética dos termos equidistantes do termo central da P.A.

Ex: (2, 6, 10, 14, 18, 22, 26)  
1. Termo central => 14
2. Média dos termos equidistantes => 10 + 18 = 28/2 = 14 | 6 + 22 = 28/2 = 14 | 2 + 26 = 28/2 = 14
3. Igualdade com o termo central => 14 = 14

#### Igualdade entre três termos consecutivos somados e o triplo do termo central
* Em uma P.A, selecionando três termos consecutivos, a soma destes termos, será igual ao triplo do termo do central deste subconjunto.

Ex: (2, 6, 10, 14, 18, 22, 26)  
1. Selecionando três termos consecutivos => 10, 14, 18
2. Soma dos três termos => 10 + 14 + 18 = 42
3. Triplo do termo do meio => 14 . 3 = 42
4. Igualdade com o termo do meio => 42 = 42

## FÓRMULA DO TERMO GERAL DE UMA P.A
* Essa fórmula é utilizada para encontrar o valor de termos desconhecidos em uma progressão aritmética.
* Fórmula:
  - a<sub>n</sub> = a<sub>1</sub> + (n - 1).r
  - a<sub>n</sub> = termo desconhecido
  - a<sub>1</sub> = primeiro termo
  - n = total de termos da P.A
  - r = razão da P.A

Ex: (3, 5, 7, 9, _, _, _, _, ...) qual o 5º termo?

1. Montagem fórmula => a<sub>5</sub> = 3 + (5 - 1).2
2. Subtração => 3 + (5- 1).2 => 3 + (4).2
3. Multiplicado e soma => 3 + (4).2 => 3 + 8 = 11
4. Resposta: O a<sub>5</sub> = 11

## SOMA DOS TERMOS DE UMA P.A
* É a fórmula usada para calcular a soma dos termos de uma Progressão aritmética.
* Fórmula:
  - S<sub>n</sub> = (a<sub>1</sub> + a<sub>n</sub>).n/2
  - S<sub>n</sub> = soma
  - a<sub>1</sub> = primeiro termo
  - a<sub>n</sub> = último termo
  - n = total de termos da P.A

Ex: (3, 5, 7, 9, 11, 13, 15, 17)

1. Montagem fórmula => S<sub>8</sub> = (3 + 17).8/2 
2. Soma do 1º e 8º termo => 3 + 17 = 20
3. Multiplicado pelo número de termos => 20 . 8 = 160
4. Dividido por 2 => 160/2 = 80
5. Resposta: O S<sub>8</sub> = 80