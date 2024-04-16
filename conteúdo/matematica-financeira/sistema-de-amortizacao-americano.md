# Sistemas de Amortização Americano

<br>

## DEFINIÇÃO
* Em uma operação de parcelamento, ao saldarmos um compromisso através de pagamentos iguais ou variáveis, estamos na realidade fazendo dois pagamentos. O primeiro pagamento refere-se a devolução ao credor do capital recebido, processo chamado de amortização, pago de acordo com condições combinadas previamente. O segundo pagamento ao credor diz respeito à remuneração dos recursos de propriedade do detentor do capital. Esses valores referem-se aos juros. Após o pagamento de cada prestação, a amortização é abatida do saldo devedor.
* Representação:
  - Prestação = amortização + juros
* No Sistema de Amortização Americado, se diferencia dos demais pela forma como são pagos os valores do capital obtido. Nesse sistema o principal é restituído por meio de uma parcela única ao fim da operação. Os juros podem ser pagos periodicamente (mais comum) ou capitalizados e pagos juntamente com o principal no fim do prazo.
* O devedor pode constituir um fundo de amortização do empréstimo (Sinking Fund), no qual deposita periodicamente as quotas de amortização. Essas quotas, por sua vez, devem render juros, de tal modo que, na data de pagamento do principal, o saldo desse fundo de amortização seja igual ao capital a pagar, liquidando, dessa maneira, totalmente o empréstimo.
* De modo geral, o sistema americano tem duas opções: pagar somente os juros e, na última prestação, pagar o valor todo, ou diluir o pagamento em prestações até somar todo o montante, enquanto pagam-se os juros.
* Se a taxa de aplicação do Sinking Fund for menor que a taxa a que o financiamento foi contratado (taxa de juros), o custo financeiro do Sistema de Amortização Americano será maior que o custo financeiro do Sistema Price.

> ### Fórmula da prestação
* Fórmula para calcular o valor de cada prestação.
* Representação:
  - P = m . i/(1 + i)<sup>t</sup> - 1
  - P = prestação
  - m = montante
  - i = taxa de juros
  - t = prazo

> ### Fórmula dos juros calculados
* É o cálculo dos juros após o pagamento de cada prestação.
* Representação:
  - J = sd . i
  - J = juros
  - sd = saldo devedor
  - i = taxa de juros

> ### Fórmula do saldo devedor
* É o cálculo do saldo devedor no pagamento da primeira prestação.
* Representação:
  - M = p . (1 + i)<sup>t</sup> - 1/i
  - M = montante
  - P = prestação
  - i = taxa de juros
  - t = prazo

> ### Fórmula do saldo devedor após a 1ª prestação
* Fórmula para calcular o saldo devedor após o pagamento da primeira prestação.
* Representação:
  - SD<sub>t</sub> = m - p . [(1 + i)<sup>t</sup> - 1/i]
  - SD<sub>t</sub> = saldo devedor
  - P = prestação
  - m = montante
  - i = taxa de juros
  - t = prazo

**Observação:** Para montar a tabela das prestações sem formação de fundo de amortização, usa-se apenas a fórmula dos juros, pois as prestações e os juros serão o mesmo valor, enquanto que o valor principal será pago de uma vez no último período, junto com o juros.

Ex: Empréstimo de 1 mil a ser pago pelo SAA, com taxa de 18% a.m em 4 meses. Calcule o valor sem formação de fundo de amortização e com formação de fundo.

SEM FUNDO DE AMORTIZAÇÃO:

DADOS:   
saldo devedor = R$ 1.000,00    
número de prestações = 4  
juros = 18% a.m  

| Nº PRESTAÇÃO | VALOR PRESTAÇÃO(R$) | AMORTIZAÇÃO(R$) | JUROS(R$) | SALDO DEVEDOR(R$) |
| ------------ | ------------------- | --------------- | --------- | ----------------- |
| 0            | -                   | -               | -         | 1000,00           |
| 1            | 180,00              | -               | 180,00    | 1.000,00          |
| 2            | 180,00              | -               | 180,00    | 1.000,00          |
| 3            | 180,00              | -               | 180,00    | 1.000,00          |
| 4            | 1.180,00            | 1.000,00        | 180,00    | 0                 | 

CÁLCULO DOS JUROS:
1. montar fórmula => J = sd .1 => J = 1000 . 18/100 = 180
2. multiplicar e dividir => J = 1000 . 18/100 => J = 18000/100 => J = 180
3. Logo serão pagos juros de R$ 180,00

COM FUNDO DE AMORTIZAÇÃO:

DADOS:   
saldo devedor = R$ 1.000,00    
número de prestações = 4  
juros = 18% a.m    
juros do fundo de amortização = 15% a.m 

| Nº PRESTAÇÃO | VALOR PRESTAÇÃO(R$) | AMORTIZAÇÃO(R$) | JUROS(R$) | SALDO DEVEDOR(R$) |
| ------------ | ------------------- | --------------- | --------- | ----------------- |
| 0            | -                   | -               | -         | 1000,00           |
| 1            | 380,26              | 200,26          | 180,00    | 799,74            |
| 2            | 380,26              | 200,26          | 180,00    | 569,44            |
| 3            | 380,26              | 200,26          | 180,00    | 304,59            |
| 4            | 380,26              | 200,26          | 180,00    | -                 | 

CÁLCULO DA PRESTAÇÃO:
1. calcular prestação => P = m . i/(1 + i)<sup>t</sup> - 1 => P = 1000 . 0,15/(1 + 0,15)<sup>4</sup> - 1
2. somar => P = 1000 . 0,15/(1 + 0,15)<sup>4</sup> - 1 => P = 1000 . 0,15/(1,15)<sup>4</sup> - 1
3. resolver potência => P = 1000 . 0,15/(1 + 0,15)<sup>4</sup> - 1 => P = 1000 . 0,15/1,74900625 - 1
4. subtrair denominador => P = 1000 . 0,15/1,74900625 - 1 => P = 1000 . 0,15/0,74900625
5. multiplicar => P = 1000 . 0,15/0,74900625 => P = 150/0,74900625
6. dividir => P = 150/0,74900625 => P = 200,26
7. prestação para o fundo de amortização => R$ 200,26

CÁLCULO DO SALDO DEVEDOR 1ª PRESTAÇÃO:
1. montar fórmula => M = p . (1 + i)<sup>t</sup> - 1/i => M = 200,26 . (1 + 0,15)<sup>1</sup> - 1/0,15
2. somar => M = 200,26 . (1 + 0,15)<sup>1</sup> - 1/0,15 => M = 200,26 . (1,15)<sup>1</sup> - 1/0,15
3. resolver potência => M = 200,26 . (1,15)<sup>1</sup> - 1/0,15 => M = 200,26 . (1,15 - 1)/0,15
4. subtrair => M = 200,26 . (1,15 - 1)/0,15 => M = 200,26 . 0,15/0,15
5. multiplicar e dividir => M = 200,26 . 0,15/0,15 => M = 30,039/0,15 => 200,26
6. a cada parcela deverá ser adicionado ao fundo R$ 200,26

CÁLCULO DO SALDO DEVEDOR 2ª PRESTAÇÃO:
1. montar fórmula => SD<sub>t</sub> = m - p . [(1 + i)<sup>t</sup> - 1/i] => SDA = 1000 - 200,26 . [(1 + 0,15)<sup>2</sup> - 1/0,15]
2. resultado = 569,44

**Observação:** A taxa do cálculo do saldo devedor deve ser a da taxa de aplicação do fundo de amortização, enquanto o período será o mesmo da prestação.

CÁLCULO DO SALDO DEVEDOR 3ª PRESTAÇÃO:
1. montar fórmula => SD<sub>t</sub> = m - p . [(1 + i)<sup>t</sup> - 1/i] => SDA = 1000 - 200,26 . [(1 + 0,15)<sup>3</sup> - 1/0,15]
2. resultado = 304,59

CÁLCULO DO SALDO DEVEDOR 4ª PRESTAÇÃO:
1. montar fórmula => SD<sub>t</sub> = m - p . [(1 + i)<sup>t</sup> - 1/i] => SDA = 1000 - 200,26 . [(1 + 0,15)<sup>4</sup> - 1/0,15]
2. resultado = 0