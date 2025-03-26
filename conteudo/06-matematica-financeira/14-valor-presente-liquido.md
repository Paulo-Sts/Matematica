# Valor Presente Líquido

## Definição
- O valor presente líquido (VPL) é o cálculo da relação entre o valor presente inicial (valor do investimento, do empréstimo ou financiamento) e o valor presente previsto (benefícios ou pagamentos) de caixa. O VPL indica o retorno de um investimento, relacionando o valor do investimento com os seus retornos ao longo do tempo de acordo com a taxa de juros.
- O VPL também é conhecido como valor atual líquido (VAL) e método do valor atual.
- Fórmula:
  - VPL = - p + r1/(1 + i)<sup>1</sup> + r2/(1 + i)<sup>2</sup> + r3/(1 + i)<sup>3</sup> + ... + rn/(1 + i)<sup>n</sup>
  - p = valor presente inicial
  - r = valor de entrada ou saída de caixa previsto em cada período do período total
  - i = taxa real de juros
  - n = período

#### Resultado do VPL
- O resultado do VPL indica a viabilidade de realizar a operação.
- Entre dois investimentos viáveis, o mais vantajoso será o de maior VPL.

| RESULTADO | CONCLUSÃO                |
| --------- | ------------------------ |
| VPL > 0   | Investimento viável      |
| VPL = 0   | Investimento indiferente |
| VPL < 0   | Investimento inviável    |


Ex: Investimento de 100 mil, com retorno de fluxo de caixa de 50 mil por ano durante 4 anos, a uma taxa real anual de 2%. É viável?

DADOS:  
p = R$ 100.000,00  
r = R$ 50.000,00  
i = 2% a.n  
n = 4 anos    
VPL = ?  

1. Montar fórmula => VPL = - 100000 + 50000/(1 + 0,02)<sup>1</sup> + 50000/(1 + 0,02)<sup>2</sup> + 50000/(1 + 0,02)<sup>3</sup> + 50000/(1 + 0,02)<sup>4</sup>
2. Somar denominadores => VPL = - 100000 + 50000/(1,02)<sup>1</sup> + 50000/(1,02)<sup>2</sup> + 50000/(1,02)<sup>3</sup> + 50000/(1,02)<sup>4</sup>
3. Resolver potência dos denominadores => VPL = - 100000 + 50000/1,02 + 50000/1,0404 + 50000/1,061208 + 50000/1,08243216
4. Dividir frações => VPL = - 100000 + 50000/1,02 + 50000/1,0404 + 50000/1,061208 + 50000/1,08243216 = (49.019,60784313725 + 48.058,43906189927 + 47.116,11672735223 + 46.192,27130132571)
5. Somar resultado => 49.019,60784313725 + 48.058,43906189927 + 47.116,11672735223 + 46.192,27130132571 = 190.386,4349337145
6. Subtrair => VPL = - 100000 + 190.386,4349337145 = 90.386,43493371446
7. Resposta: O investimento é viável e vai render = R$ 90.387,00