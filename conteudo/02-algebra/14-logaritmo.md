# Logaritmo

## 1. Definição
- Logaritmo de um número **b** na base **a** é igual ao expoente **x** ao qual se deve elevar a base, de modo que a potência **a^x** seja igual a **b**, sendo **a** e **b** números reais e positivos e **a ≠ 1**.
- Sendo assim, o logaritmo é a uma operação na qual queremos descobrir o expoente que uma dada base deve ter para resultar em uma certa potência.
- Representação:
  - Log<sub>a</sub> b = x ↔ a^x = b
  - Lê-se logaritmo de **b** na base **a**, sendo **a > 0** e **a ≠ 1** e **b > 0** (condição de existência).
  - a = base do logaritmo
  - b = logaritmando ou antilogaritmo
  - x = logaritmo

Exemplo: Log<sub>2</sub> 4 = x  

1. Regra do Ei (Eleva a base ao logaritmo e iguala ao logaritmando): 2^x = 4
2. Iguala as bases: 2^x = 2^2
3. Corta as bases: x = 2
4. Logaritmo = 2

> ### Propriedades da Definição de Logaritmo
- Sendo **b > 0**, **a > 0** e **a ≠ 1** em um número real qualquer, tem se a seguir algumas propriedades da definição de logaritmo.

#### Logaritmando igual a 1
- Quando o logaritmando for 1, o resultado sempre será 0.
- Representação:
  - Log<sub>a</sub> 1 = 0

Exemplo: Log<sub>7</sub> 1 = x

1. 7^x = 1
2. 7^x = 7^0
3. x = 0

Exemplo: Log<sub>e</sub> 1 = 0

1. Log<sub>e</sub> 1 = x
2. e^x = 1
3. e^x = e^0
4. x = 0

#### Base e o Logaritmando Iguais
- Quando a base e o logaritmando forem iguais, o valor do logaritmo será igual a 1.
- Representação:
  - Log<sub>a</sub> a = 1

Exemplo: Log<sub>8</sub> 8 = x

1. 8^x = 8
2. 8^x = 8^1
3. x = 1

#### Base e o Logaritmando Iguais com Logaritmando com Expoente
- Quando o logaritmando tiver um expoente **m** e a base e o logaritmando forem iguais, o valor do logaritmo será o valor do expoente do logaritmando.
- Representação
  - Log<sub>a</sub> a<sup>m</sup> = m

Exemplo: Log<sub>2</sub> 2<sup>3</sup> = x

1. É possível retirar o expoente do logaritmando multiplicando o log pelo mesmo valor do expoente do logaritmando: Log<sub>2</sub> 2<sup>3</sup> ⟶ 3. Log<sub>2</sub> 2
2. Como a base e o logaritmando possuem o mesmo valor, então o resultado é 1: 3. Log<sub>2</sub> 2 ⟶ 3 . 1 = 3
3. Resultado: 3 

#### Igualdade entre Logaritmos
- Se houver uma igualdade entre logaritmos e as bases forem iguais conclui-se que os logaritimandos também serão iguais.
- Representação:
  - Log<sub>a</sub> b = log<sub>a</sub> c ↔ b = c

Exemplo: Log<sub>7</sub> x = log<sub>7</sub> 4

1. x = 4

#### Número elevado a Logaritmo com Base de Mesmo Valor
- Um número elevado a um logaritmo, tendo esse base igual ao valor do número que ele eleva, tem como logaritmo o valor do logaritmando.
- Representação:
  - a<sup>log<sub>a</sub>b</sup> = b

Exemplo:

1. 2<sup>log<sub>2</sub>5</sup> = 5

Exemplo: 3<sup>2log<sub>3</sub>4</sup> = x

1. Retirar o 2. o tornando expoente do logaritmando: 3<sup>2log<sub>3</sub>4</sup> ⟶ 3<sup>log<sub>3</sub>4<sup>2<sub></sup>
2. Resolver potência: 3<sup>log<sub>3</sub>4<sup>2<sub></sup> ⟶ 3<sup>log<sub>3</sub>16</sup>
3. Resultado: 3<sup>log<sub>3</sub>16</sup> = 16 

#### Inverso do Expoente da Base
- O expoente na base pode ser manipulado e jogado para trás do logaritmo, na sua forma inversa. 
- Representação:
  - log<sub>a<sup>m</sup></sub> b = 1/m * log<sub>a</sub>b

Exemplo: log<sub>2<sup>3</sup></sub> 5

1. Inverte-se o expoente 3 e o move para trás do logaritmo: 1/3 * log<sub>2</sub>5

#### Multiplicação de Logaritmos em que a Base e o Logaritmando são iguais mais em posição oposta o resultado vale 1
- Ao se multiplicar dois logaritmos, quando a base de um for o logaritmando do outro e o logaritmando de um for a base do outro, o resultado é igual a 1.
- Representação:
  - log<sub>a</sub> b * log<sub>b</sub> a = 1

Exemplo: log<sub>3</sub> 7 * log<sub>7</sub> 3 = 1

## 2. Logaritmo Decimal
- Quando um logaritmo possui a base igual a 10, esse é chamado logaritmo decimal.
- Ao registrar-se um logaritmo decimal, não é necessário escrever a base 10. 
- Representação:
  - Log<sub>10</sub> b = log b

Exemplo: Log 4

1. Log 4 = Log<sub>10</sub> 4

## 3. Logaritmo Natural
- O logaritmo natural de um número **b**, sendo **b > 0**, é o logaritmo desse número **b**, na base **e** (**e** é o número de Euler cujo valor vale aproximadamente 2,71).
- Representação:
  - Ln b= log<sub>e</sub> b

Exemplo: Log<sub>e</sub> 5 

1. Log<sub>e</sub> 5 = Ln 5

## 4. Cologaritmo
- O cologaritmo é o simétrico de um logaritmo.
- Representação:
  - Colog<sub>a</sub> b = – log<sub>a</sub> b

Exemplo: Colog<sub>2</sub> 4

1. Colog<sub>2</sub> 4 = -1 log<sub>2</sub> 4

## 5. Propriedades das Operações entre Logaritmos

#### Logaritmo do Produto
- O logaritmo de um produto é igual à soma de seus logaritmos.
- Representação:
  - log<sub>a</sub> (x * y) = log<sub>a</sub> x + log<sub>a</sub> y

Exemplo: Log<sub>2</sub> (4 * 3) 

1. Log<sub>2</sub> (4 * 3) = log<sub>2</sub> 4 + log<sub>2</sub> 3

Exemplo: Log<sub>3</sub> 7 + log<sub>3</sub> 2

1. Log<sub>3</sub> 7 + log<sub>3</sub> 2 = log<sub>3</sub> (7 * 2) = log<sub>3</sub> 14.

#### Logaritmo do Quociente
- O logaritmo de um quociente é igual à diferença dos logaritmos.
- Representação:
  - log<sub>a</sub> (x/y) = log<sub>a</sub> x - log<sub>a</sub> y

Exemplo: Log<sub>2</sub> (5/3) 

1. Log<sub>2</sub> (5/3) = log<sub>2</sub> 5 - log<sub>2</sub> 3

Exemplo: Log<sub>2</sub> 8 - log<sub>2</sub> 4

1. Log<sub>2</sub> 8 - log<sub>2</sub> 4 = log<sub>2</sub> (8/4) = log<sub>2</sub> 2 = 1

#### Logaritmo da Potência
- O logaritmo de uma potência é igual ao produto dessa potência pelo logaritmo. Tem-se um expoente no logaritmando como se ele pudesse, sendo conveniente ou não, jogar ele para trás e ele voltar multiplicando. É uma manipulação que é utilizada nessa propriedade.
- Representação:
  - log<sub>a</sub> x<sup>m</sup> = m * log<sub>a</sub> x

Exemplo: Log<sub>2</sub> 4<sup>2</sup>

1. Log<sub>2</sub> 4<sup>2</sup> = 2 * Log<sub>2</sub> 4

#### Mudança de Base do Logaritmo
- A mudança de base tem como consequência que o que era logaritmando continua sendo logaritmando, porém agora do numerador da razão, e o que era a base que foi modificada passa a ser o logaritmando do denominador (parte de baixo da fração), essa é a consequência de mudar-se a base. 
- Importante lembrar que a base deve ser um valor positivo e não pode sumir o valor 1.
- Representação:
  - log<sub>a</sub> x = log<sub>b</sub> x/log<sub>b</sub> a

Exemplo: Log<sub>2</sub> 5

1. Log<sub>2</sub> 5 = log<sub>3</sub> 5/log<sub>3</sub> 2


Exemplo: Log<sub>4</sub> 7

1. Log<sub>4</sub> 7 = log<sub>5</sub> 7/log<sub>5</sub> 4
