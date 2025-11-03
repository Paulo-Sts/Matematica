# Medidas de dispersão 

## Definição
- São parâmetros estatísticos usados para determinar o grau de variabilidade dos dados de um conjunto de valores.
- A utilização desses parâmetros tornam a análise de uma amostra mais confiável, visto que as variáveis de tendência central (média, mediana, moda) muitas vezes encondem a homogeneidade ou não dos dados.
- As medidas de dispersão mais usadas são: amplitude, variância, desvio padrão e coeficiente de variação.
- Por exemplo: Vamos considerar as idades de dois grupos de crianças que irão participar de duas festas diferentes. Festa A: 1 ano, 2 anos, 2 anos, 12 anos, 12 anos e 13 anos; Festa B: 5 anos, 6 anos, 7 anos, 7 anos, 8 anos e 9 anos. Em ambos os casos, a média é igual a 7 anos de idade. Entretanto, ao observar as idades dos participantes podemos admitir que as atividades escolhidas sejam iguais?

> ### Amplitude
- Essa medida de dispersão é definida como a diferença entre a maior e a menor observação de um conjunto de dados.
- Por ser uma medida que não leva em consideração como os dados estão efetivamente distribuídos, não é muito utilizada.
- Representação:
  - A = X<sub>maior</sub> - X<sub>menor</sub>

Exemplo: O setor de controle de qualidade de uma empresa seleciona ao acaso peças de um lote. Quando a amplitude das medidas dos diâmetros das peças ultrapassa 0,8 cm o lote é rejeitado.
Considerando que em um lote foram encontrados os seguintes valores 2,1 cm; 2,0 cm; 2,2 cm; 2,9 cm; 2,4 cm, esse lote foi aprovado ou rejeitado?  

1. Para calcular a amplitude, basta identificar o menor e o maior valores, que neste caso, são 2,0 cm e 2,9 cm. 
2. Calculando a amplitude, temos: A = 2,9 - 2 = 0,9 cm
3. Nesta situação o lote foi rejeitado, pois a amplitude ultrapassou o valor limite.

> ### Variância
- A variância é determinada pela média dos quadrados das diferenças entre cada uma das observações e a média aritmética da amostra.
- Representação:
  - V = (x - M)<sup>2</sup> + (x2 - M)<sup>2</sup> + ... (xn - M)<sup>2</sup>/n

Exemplo: Considerando as idades das crianças das duas festas indicadas anteriormente, vamos calcular a variância desses conjuntos de dados.

FESTA A: 1 ano, 2 anos, 2 anos, 12 anos, 12 anos e 13 anos  

1. Média = (1 + 2 + 2 + 12 + 12 + 13)/6 = 7 anos
2. V = (1 - 7)<sup>2</sup> + (2 - 7)<sup>2</sup> + (2 - 7)<sup>2</sup> + (12 - 7)<sup>2</sup> + (12 - 7)<sup>2</sup> + (13 - 7)<sup>2</sup>/6  
3. V = 36 + 25 + 25 + 25 + 25 + 36/6 = 28.67 anos<sup>2</sup>

FESTA B: 5 ano, 6 anos, 7 anos, 7 anos, 8 anos e 9 anos  

1. Média = (5 + 6 + 7 + 7 + 8 + 9)/6 = 7 anos
2. V = (5 - 7)<sup>2</sup> + (6 - 7)<sup>2</sup> + (7 - 7)<sup>2</sup> + (7 - 7)<sup>2</sup> + (8 - 7)<sup>2</sup> + (9 - 7)<sup>2</sup>/6  
3. V = 4 + 1 + 0 + 0 + 1 + 4/6 = 1.67 anos<sup>2</sup>

> ### Desvio Padrão
- O desvio padrão é definido como a raiz quadrada da variância. Desta forma, a unidade de medida do desvio padrão será a mesma da unidade de medida dos dados, o que não acontece com a variância.
- Quando todos os valores de uma amostra são iguais, o desvio padrão é igual a 0. Sendo que, quanto mais próximo de 0, menor é a dispersão dos dados.
- Representação:
  - DP = √v

Exemplo: Considerando ainda o exemplo anterior, vamos calcular o desvio padrão para as duas situações:

1. DP = √28.67 = 5.35 anos
2. DP = √1.67 = 1.29 anos
3. Agora, sabemos que a variação das idades do primeiro grupo em relação a média é de aproximadamente 5 anos, enquanto que a do segundo grupo é de apenas 1 ano.

> ### Coeficiente de Variação
- Para encontrar o coeficiente de variação, devemos multiplicar o desvio padrão por 100 e dividir o resultado pela média. 
- Essa medida é expressa em porcentagem.
- O coeficiente de variação é utilizado quando precisamos comparar variáveis que apresentam médias diferentes.
- Como o desvio padrão representa o quanto os dados estão dispersos em relação a uma média, ao comparar amostras com médias diferentes, a sua utilização pode gerar erros de interpretação.
- Desta forma, ao confrontar dois conjuntos de dados, o mais homogêneo será aquele que apresentar menor coeficiente de variação.
- Representação:
  - CV = 100.DP/MA

Exemplo:  
Turma 1 DP = 2.6, Média = 6.2  
Turma 2 DP = 3.0, Média = 8.5  

1. CV1 = 100.2.6/6.2 = 42%
2. CV2 = 100.3/8.5 = 35%
3. Desta forma, a turma mais homogênea é a turma 2, apesar de apresentar maior desvio padrão.