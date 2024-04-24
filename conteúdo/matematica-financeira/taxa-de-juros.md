# Taxa de Juros

<br>

## DEFINIÇÃO
* A taxa de juros é uma operação em que um capital (valor monetário conhecido hoje) é projetado para uma data posterior. O objetivo é descobrir qual o valor que esse capital irá se transformar.
* A taxa de juros é expressa como uma porcentagem acompanhada por uma unidade de tempo. Essa expressão pode se apresentar em diferentes formas, sendo fundamental adequar a expressão da taxa a condição apresentada para a realização da operação.

## TAXA NOMINAL OU APARENTE
* Taxa nominal, é a taxa em que o período da capitalização e o de tempo da capitalização estão definidas em unidades diferentes.
* Essa taxa não pode ser utilizada pois, o seu valor real é diferente de como ela está apresentada, sendo necessário a sua transformação em taxa efetiva.

Ex: 13% a.a, capitalizado mensalmente. (a taxa é anual, equanto a capitalização ocorre a cada mês)

## TAXA EFETIVA
* É a taxa de juros expressa na mesma unidade de tempo em que é capitalizada. É a real taxa aplicada a uma operação. 
* Taxas nominais devem ser transformadas em taxa efetiva para poder ser aplicada a operação.

Ex: 2% a.m com capitalização mensal.

#### Conversão da taxa nominal em taxa efetiva
* Deve-se identificar o tipo de capitalização, pois é o que determina em que unidade de período a taxa de juros deve ser expressa.

Ex: 36% a.a com capitalização mensal

Dados:
período = mensal
taxa = 36% ao ano

1. ano em meses => 1 ano = 12 meses
2. divisão => 36/12 = 3
3. logo a taxa efetiva é de 3% ao mês

## TAXAS PROPORCIONAIS
* Taxas proporcionais, são diferentes taxas que produzem os mesmos juros, em um mesmo prazo a juros simples. As taxas proporcionais são taxas equivalentes em aplicações de regime simples.
* A conversão entre taxas aplicadas a juros simples é feita a partir da relação do seu período de capitalização com o período da aplicação.


Ex: 12% a.m = 144% a.a = 24% a.b

## TAXAS EQUIVALENTES
* São diferentes taxas que aplicadas, no regime composto, a um mesmo prazo produzem o mesmo montante.
* A conversão em taxas equivalentes no regime composto se dá a partir da conversão de uma taxa de menor período para uma taxa de maior período, ou o contrário.
* O período de capitalização determina o período de cálculo da taxa equivalente em outra unidade de tempo. Por exemplo se a capitalização for mensal, para uma taxa equivalente anual o período será de 12 meses.
* Fórmula da taxa de menor período:
  - i = <sup>t</sup>√(i<sub>k</sub> + 1) - 1
  - i = taxa de período menor
  - t = período ou tempo
  - i<sub>k</sub> = taxa de período maior
* Fórmula da taxa de maior período:
  - i<sub>k</sub> = (i + 1)<sup>t</sup> - 1
  - i<sub>k</sub> = taxa de período maior
  - i = taxa de período menor
  - t = período ou tempo

Ex: Taxa composta anual equivalente a 10% em semestre é?

Dados:  
o que quer? da menor taxa para a maior  
i<sub>k</sub> = ?  
i = 10% a.s  
t = 2 (1 ano = 2 semestres)  

1. montar fórmula => i<sub>k</sub> = (0,1 + 1)<sup>2</sup> - 1
2. soma => (0,1 + 1) = 1,1
3. potência => (1,1)<sup>2</sup> = 1,1 . 1,1 = 1,21
4. subtração => 1,21 - 1 = 0,21
5. logo a taxa equivalente de 10% a.s é 21% a.a

***DICA:*** Ao converter uma taxa menor para uma maior, no regime simples a taxa equivalente  será menor do que no regime composto, já ao converter uma taxa maior para uma taxa menor, no regime simples a taxa equivalente será maior do que no regime composto. Isso pode ajudar a descobrir a resposta do valor da taxa, fazendo sua comparação com a taxa no outro regime, em questões que cobrem o valor da taxa equivalente em determinado regime.

|                  | JUROS SIMPLES    | JUROS COMPOSTOS     | RELAÇÃO                        |
| ---------------- |----------------- | ------------------- | ------------------------------ |
| MENOR PARA MAIOR | 1% a.m = 12% a.a | 1% a.m = 12,68% a.a | juros simples < juros compostos|
| MAIOR PARA MENOR | 12% a.a = 1% a.m | 12% a.a = 0,96% a.m | juros simples > juros compostos|
