# Padrões de Problemas

## 1. Encontrar Termos Futuros
- Questões que envolvem sequencias e o objetivo é saber o valor de um termo futuro.
- Lógica:
  - Pegar primeiro elemento da sequencia e somar ele ao valor da posição que se quer menos 1 e multiplicar pela lei de formação que forma a sequência.

Ex: Os cinco primeiros termos de uma sequência são 3, 7, 11, 15,19. Qual é o seu 112º termo?  

1. Lei de formação = soma 4
2. 3 + 111 . 4 = 447

## 2. Soma de Termos
- Questões que envolvem sequencias e o objetivo é saber o valor da soma de todos os termos do primeiro a um termo futuro.
- Lógica:
  - Somar os valores das extremidades vai dar sempre o mesmo valor, ai basta multiplicar esse valor por metade do total de números do intervalo da sequencia que se quer o valor.

Ex: Considere uma sequencia 1, 3, 6, 10, 15 ... qual o valor da soma dos termos até o 100º?

1. Lei de formação = soma o valor + a numeração crescente
2. 1 + 100 = 101 (padrão)
3. 101 . 50 = 5050

## 3. Ciclos 
- Questões que envolvem sequencias formada por um conjunto de simbolos que se repete e o objetivo é saber o qual dos elementos do conjunto é o termo em uma posição futura.
- Lógica:
  - Pegar o tamanho do conjunto e dividir pela posição que se quer, o resto vai dizer qual a posição do elemento do conjunto correspondente a posição que se deseja.

Ex: I M B E L J F I M B E L J F I M B E L J F... Mantendo esse padrão, a 500ª letra dessa faixa será?

1. Lei de formação = cada ciclo tem 7 letras
2. 500 / 7 = 71 e sobra 3
3. Posição 3 é a letra B

## 4. Pior Caso ou Alternativa Incontroversa
- Questões que envolvem uma situação em que se quer o valor mínimo de algo para que um evento aconteça.
- Lógica:
  - Pensar na pior situação, que é que todas as outras aconteçam para que a situação aconteça com certeza.

Ex: Em um saco, há 10 fichas iguais na forma e no tamanho, porém de 4 cores diferentes: 4 são brancas, 3 são pretas, 2 são azuis e 1 é vermelha, Quantas fichas são necessárias tirar para garantir que uma será branca?

1. Pior situação = Tirar todas as pretas, azuis e vermelhas = tirar 6 fichas.
2. A ficha 7 com certeza será branca, então são necessárias 7 fichas.

## 5. Torneiras e Afins
- Questões que envolvem uma situação em que se quer o valor quando duas ou mais coisas agem ao mesmo tempo, fazendo determinada ação que sozinhas elas realizariam em um periodo diferente.
- Lógica:
  - Montar uma equação com frações em que cada coisa é uma fração que somada dará o resultado. Se envolver ralo ao invés de somar deve-se subtrair.
  - 1/T1 + 1/T2 + ... = 1/T

Ex: Existem duas torneiras para encher um tanque vazio. Se apenas a primeira torneira for aberta, ao máximo, o tanque encherá em 24 horas. Se apenas a segunda torneira for aberta, ao máximo, o tanque encherá em 48 horas. Se as duas torneiras forem abertas ao mesmo tempo, ao máximo, em quanto tempo o tanque encherá?

1. Tirar MMC => 1/24 + 1/48 = 1/T = 2 + 1/48 = 1/T
2. Meio pelos extremos => 3/48 = 1/T => 3T = 48 => T= 48/3 => T= 16
3. 16 horas 

## 6. Calendários
- Questões que envolvem saber que dia era em uma determinada data partindo de uma data anterior ou posterior.
- Lógica:
  - Identificar a duração de cada mês, pode ser usando os ossos da mão.
  - Contar quantos dias tem entre as 2 datas, excluindo da conta a data de origem.
  - Dividir o total de dias por 7, se tiver resto conta-se do dia de refeencia a quantidade de dias do resto para chegar na data exata.

Ex: Certo ano, o dia 1º de agosto caiu em uma segunda-feira. Nesse ano, o dia das crianças, 12 de outubro, foi?

1. Total de dias = 31 - 1 + 30 + 12 = 72
2. 72/7 = 10 e sobra 2
3. Conta a partir da segunda que foi o ultimo dia das 10 semanas mais 2 dias = quarta feira

## 7. Quantas vezes aparece um Algarismo
- Questões que envolvem saber quantas vezes um algarismo aparece em um intervalo de números.
- Lógica:
  - Parte do princípio que de 0 a 99 todos os algarismos aparecem 20 vezes, exceto o zero. A partir disso basta apenas dividir o intervalo em períodos de 100 e ir somando os valores.

Ex: Se um livro tem 400 páginas numeradas de 1 a 400, quantas vezes o algarismo 2
aparece na numeração das páginas desse livro?

1. De 0 a 99 o 2 aparece -> 20 vezes
2. De 101 a 199 o 2 aparece -> 20 vezes
3. De 201 a 299 o 2 aparece -> 100 + 20 vezes
4. De 301 a 399 o 2 aparece -> 20 vezes
5. Total = 180 vezes