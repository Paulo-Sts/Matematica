# MDC

## Definição
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
1. Dividir por 2 => 30 : **2** = 15, 12 : **2** = 6 (divisor comum)
2. Dividir por 2 => 15 : **2** não divide, repete-se o 15, 6 : **2** = 3
3. Como não é possível dividir por 2, dividi-se pelo próximo número primo o 3 => 15 : **3** = 5, 3 : **3** = 1 (divisor comum)
4. Divide-se agora por 5 => 5 : **5** = 1, 1 : **5** repete-se o 1
5. O produto dos divisores comuns => 2 . 3 = 6
6. Resposta: 6

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

**DICA:** Para identificar a utilização do MDC na resolução de um problema, basta verificar se a questão pede que seja feita a separação de diferentes elementos em quantidades iguais ao mesmo tempo, sendo cada parte o maior tamanho possível.

**DICA:** Ao se fatorar números para encontrar o MDC, pode-se optar por usar como divisor apenas números que dividam todos os valores ao mesmo tempo (fator comum), quando não for possível mais dividir, o produto dos divisores será o MDC, e o resto da divisão de cada valor, indicará o número de vezes que o MDC corresponde ao valor. Na lógica da divisão em partes iguais o MDC será o tamanho (comprimento) de cada pedaço e o resto da divisão de cada valor será a quantidade de pedaços iguais do tamanho do MDC em que cada valor será dividido.
