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

#### Relação entre termo médio e termos extremos
* Em uma P.G (a, b, c) em que a ≠ 0, o quadrado do termo médio da P.G será igual ao produto dos termos extremos da P.G.

Ex: (3, 6, 12)
1. Quadrado do termo do meio => 6<sup>2</sup> = 36
2. Produto dos extremos => 3 . 12 = 36
3. Igualdade => 36 = 36

#### Igualdade do produto de termos equidistantes e termos extremos
* A multiplicação de termos equidistantes de uma P.G será igual ao produto dos termos extremos da P.G.

Ex: (4, 8, 16, 32, 64)
1. Produto entre o segundo e quarto termo => 8 . 32 = 256
2. Produto dos extremos => 4 . 64 = 256
3. Igualdade => 256 = 256

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

## FÓRMULA DO PRODUTO DOS TERMOS DE UMA P.G
* Essa fórmula é utilizada para encontrar o valor do produto dos termos de em uma progressão geométrica.
* Fórmula:
  - P<sub>n</sub> = ±√(a<sub>1</sub> . a<sub>n</sub>)<sup>n</sup>
  - P<sub>n</sub> = produto dos termos de uma P.G
  - a<sub>1</sub> = primeiro termo
  - n = total de termos da P.G
  - q = razão da P.G
* Definição do sinal:
  - Positivo se todos os termos forem positivos, ou se o número de termos negativos for par.
  - Negativo se o número de termos negativos for ímpar.

Ex: (2, -4, 8, ...) Produto dos 7 primeiros termos da P.G

1. Razão => -4/2 = -2
2. Montar fórmula => P<sub>7</sub> = ±√(2 . a<sub>7</sub>)<sup>7</sup>
3. Encontrar a<sub>7</sub> => a<sub>7</sub> = 2 . -2<sup>6</sup> = 2<sup>7</sup>
4. Resolver parentese => P<sub>7</sub> = ±√(2 . 2<sup>7</sup>)<sup>7</sup> => P<sub>7</sub> = ±√(2<sup>8</sup>)<sup>7</sup>
5. Potência de Potência => P<sub>7</sub> = ±√(2<sup>8</sup>)<sup>7</sup> => P<sub>7</sub> = ±√2<sup>56</sup>
6. Inverter raíz => P<sub>7</sub> = ±√2<sup>56</sup> => P<sub>7</sub> = ±2<sup>56/2</sup>
7. Dividir => P<sub>7</sub> = ±2<sup>28</sup>
8. Definir final => P<sub>7</sub> = -2<sup>28</sup> (número de termos negativos é ímpar)
9. Resposta: Soma dos 7 primeiros termos é = -2<sup>28</sup>

## SOMA DOS TERMOS DE UMA P.G FINITA
* É a fórmula usada para calcular a soma dos termos de uma Progressão geométrica finita.
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

## SOMA DOS TERMOS DE UMA P.G INFINITA
* É a fórmula usada para calcular a soma dos termos de uma progressão geométrica infinita quando o valor da razão for menor do que 1.
* Fórmula:
  - S<sub>∞</sub> = a<sub>1</sub>/1 - q
  - S<sub>∞</sub> = soma
  - a<sub>1</sub> = primeiro termo
  - q = razão

Ex: (4, 2, 1, ...) Soma dos termos da P.G

1. Razão => 2/4 = 1/2 (q < 1)
2. Montar fórmula => S<sub>∞</sub> = 4/1 - 1/2
3. Resolver fração => S<sub>∞</sub> = 4/1 - 1/2 => S<sub>∞</sub> = 4/1/2
4. Divisão => S<sub>∞</sub> = 4/1/2 => S<sub>∞</sub> = 4 . 2/1 = 8/1
5. Resposta: S<sub>∞</sub> = 8