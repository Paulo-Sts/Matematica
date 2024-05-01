# Progressão Geométrica

<br>

## DEFINIÇÃO
* Progressão geométrica é uma sequência de números em que cada termo a partir do segundo, se da pela multiplicação do termo anterior com uma constante **q**. Essa constante é chamada de razão da P.G.
* Cada termo da sequência possui uma posição definida, sendo a sua posição em relação aos outros termos determinante para estabelecimento dos próximos termos da P.G.

Ex: (3, 6, 12, 24)    
Ex: (64, 16, 4, 1, ...)  

> ### Razão da P.G
* A razão de uma P.G é determinada a partir da divisão de um termo pelo seu antecessor, se para todos os termos da sequência essa operação tiver uma mesmo resultado, trata-se de uma P.G e o resultado é a razão da P.G.
* Para determinar o próximo termo da P.G, basta multiplicar o termo anterior com o valor da razão.
* Fórmula da razão de uma P.G:
  - q = a<sub>n</sub>/a<sub>n-1</sub>
  - q = razão da P.G
  - a<sub>n</sub> = enésimo termo
  - a<sub>n-1</sub> = termo anterior

#### Cálculo
1. Divide-se o 2º termo da P.G pelo primeiro termo.
2. Verifica-se se a divisão entre os demais termos pelo seu antecessor tem o mesmo resultado.
3. Se sim, trata-se de uma P.G e esse valor é a razão que a determina.

Ex: (2, 4, 8, 16) => q = 2
1. 2º termo = 4 e 1º termo = 2 => 4/2 = 2
2. 3º termo = 8 e 2º termo = 4 => 8/4 = 2
3. 4º termo = 16 e 3º termo = 8 => 16/8 = 2
4. Resposta: O q = 2

> ### Classificação das P.Gs
* As progressões aritméticas são definidas, a partir do valor das razões que a definem.

#### Constante
* Progressão geométrica em que o valor da razão é igual a 1, sendo assim todos os termos da P.G possuem o mesmo valor.

Ex: (2, 2, 2, 2, 2) => q = 1  

#### Crescente
* Progressão geométrica em que o valor da razão é maior que zero. Os termos da P.G sempre aumentarão de valor.

Ex: (9, 27, 81, 243, 729...) => q = 3  

#### Decrescente
* Progressão geométrica em que o valor da razão é menor que zero. Os termos da P.G sempre diminuirão de valor.

Ex: (-6, -36,- 216, -1296, ...) => q = 6  

#### Oscilante ou alternante
* Progressão geométrica em que o valor da razão é menor que zero e a continuidade varia entre termos positivos e negativos.

Ex: (2, -4, 8, -16, 32, 64, …) => q = -2  

#### Quase nula
* Progressão geométrica em que apenas o primeiro elemento é diferente de zero.

Ex: (5, 0, 0, 0) => q = 0  

> ### Propriedades das progressões geométricas

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

## FÓRMULA DO TERMO GERAL DE UMA P.G
* Essa fórmula é utilizada para encontrar o valor de termos desconhecidos em uma progressão geométrica.
* Fórmula:
  - a<sub>n</sub> = a<sub>1</sub> . q<sup>n-1</sup>
  - a<sub>n</sub> = termo desconhecido
  - a<sub>1</sub> = primeiro termo
  - n = total de termos da P.G
  - q = razão da P.G

Ex: (1, 2, 4, 8, _, _, _, _, ...) qual o 15º termo?

1. Encontrar razão => 2/1 = 2
2. Montagem fórmula => a<sub>15</sub> = 1 . 2<sup>15-1</sup>
3. Subtração => a<sub>15</sub> = 1 . 2<sup>15-1</sup> => a<sub>15</sub> = 1 . 2<sup>14</sup>
4. Multiplicado => a<sub>15</sub> = 1 . 2<sup>14</sup> => a<sub>15</sub> = 2<sup>14</sup>
5. Potência => a<sub>15</sub> = 2<sup>14</sup> => a<sub>15</sub> = 16.384
6. Resposta: O a<sub>15</sub> = 16.384

## SOMA DOS TERMOS DE UMA P.A
* É a fórmula usada para calcular a soma dos termos de uma Progressão aritmética.
* Fórmula:
  - S<sub>n</sub> = [a<sub>1</sub> . (q<sup>n</sup> - 1)]/q - 1
  - S<sub>n</sub> = soma
  - a<sub>1</sub> = primeiro termo
  - n = total de termos da P.G
  - q = razão

Ex: (1, 3, 9, ...) Soma dos 5 primeiros termos

1. Montagem fórmula => S<sub>5</sub> = [1 . (3<sup>5</sup> - 1)]/3 - 1
2. Potência => S<sub>5</sub> = [1 . (3<sup>5</sup> - 1)]/3 - 1 => S<sub>5</sub> = [1 . (243 - 1)]/3 - 1
3. Subtração e Multiplicação => S<sub>5</sub> = [1 . (243 - 1)]/3 - 1 => S<sub>5</sub> = [1 . 242]/2 => S<sub>5</sub> = 242/2
4. Divisão => S<sub>5</sub> = 242/2 => S<sub>5</sub> = 121
5. Resposta: O S<sub>5</sub> = 121