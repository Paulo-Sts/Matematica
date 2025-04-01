# MMC

## Definição
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
1. Dividir por 2 => 30 : **2** = 15, 14 : **2** = 7
2. Como não é possível dividir por 2, dividi-se pelo próximo número primo o 3 => 15 : **3** = 5, 7 : **3** não divide, repete-se o 7
3. Divide-se agora por 5 => 5 : **5** = 1, 7 : **5** não divide, repete-se o 7
4. Divide-se agora por 7 => 1 : **7** = repete-se o 1, 7 : **7** = 1
5. O produto dos quocientes é o resultado => 2 . 3 . 5 . 7 = 210
6. Resposta: 210

> ### Propriedades do MMC

#### MMC entre números primos
* O MMC de dois ou mais números primos, será o produto entre esses números.

Ex: MMC(2, 11) = 22  
Ex: MMC(2, 5) = 10  

#### MMC entre múltiplos
* O MMC entre dois números, em que o maior é múltiplo do menor, será o número maior.

Ex: MMC(10, 2) = 10    
Ex: MMC(6, 3) = 6    

**DICA:** Para identificar a utilização do MMC na resolução de um problema, basta verificar se na questão existem eventos simultâneos, ou seja, se a questão pede para que se calcule em quanto tempo dois ou mais eventos que já ocorreram ao mesmo tempo irão ocorrer novamente ao mesmo tempo.

#### Relação MDC e MMC
* O produto entre o MDC e o MMC de dois números é igual ao produto desses dois números. 
* Representação da relação:
  - MDC(a, b) x MMC(a, b) = a x b

Ex: MDC(10, 2) = 10 e MMC(10, 2) = 2 => 10 x 2 = 10 x 2  