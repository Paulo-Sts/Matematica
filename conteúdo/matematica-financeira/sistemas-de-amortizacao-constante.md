# Sistemas de Amortização Constante

<br>

## DEFINIÇÃO
* Em uma operação de parcelamento, ao saldarmos um compromisso através de pagamentos iguais ou variáveis, estamos na realidade fazendo dois pagamentos. O primeiro pagamento refere-se a devolução ao credor do capital recebido, processo chamado de amortização, pago de acordo com condições combinadas previamente. O segundo pagamento ao credor diz respeito à remuneração dos recursos de propriedade do detentor do capital. Esses valores referem-se aos juros. Após o pagamento de cada prestação, a amortização é abatida do saldo devedor.
* Representação:
  - Prestação = amortização + juros
* O Sistema de Amortização Constante (SAC) é um sistema de amortização utilizado em geral para financiamentos imobiliários. 
* O cálculo da amortização de uma dívida é feito utilizando uma tabela que relaciona as prestações, a amortização, o saldo devedor e os juros.

#### Características
* As amortizações são iguais ao longo do tempo.
* O valor da prestação é variável ao longo do tempo.
* Os juros incidem sobre o saldo devedor que por decrescerem ao longo do tempo, geram juros cada vez menores, ou seja, os juros são decrescentes.
* Como as amortizações são fixas e os juros decrescentes, a prestação é decrescente.

> ### Fórmula da amortização
* Fórmula para calcular o valor da amortização para o sistema de amortização constante.
* Representação:
  - A = sd/n
  - A = amortização
  - sd = saldo devedor
  - n = quantidade de parcelas

> ### Fórmula dos juros calculados
* É o cálculo dos juros após o pagamento de cada prestação.
* Representação:
  - J = sd . i
  - J = juros
  - sd = saldo devedor
  - i = taxa de juros

> ### Fórmula do saldo devedor atual
* É o cálculo do saldo devedor após o pagamento de cada prestação.
* Representação:
  - SDA = sd - a
  - SDA = saldo devedor atual
  - sd = saldo devedor anterior
  - a = amortização

> ### Fórmula dos juros de prestação futura
* Essa fórmula determina o valor dos juros de uma prestação futura.
* Representação:
  - J = i . m . {1 - [(t - 1)/n]}
  - J = juros da prestação futura
  - i = taxa de juros
  - m = montante
  - t = número da prestação futura
  - n = quantidade de prestações

> ### Fórmula da saldo devedor futuro
* Essa fórmula determina o valor do saldo devedor de uma prestação futura.
* Representação:
  - SD = m . (1 - t/n)
  - SD = saldo devedor futuro
  - m = montante
  - t = número da prestação futura
  - n = quantidade de prestações

**DICA:** Sempre iniciar com a realização da dívida, ou seja, pelo início da operação que é realizada no tempo 0.

Ex: Dívida no valor de R$ 3.000,00 que é amortizada pelo SAC em 5 prestações mensais, com juros de 1% ao mês. Monte a tabela.

DADOS:   
saldo devedor = R$ 3.000,00    
número de prestações = 5 (5 meses) 
juros = 1% a.m  

| Nº PRESTAÇÃO | VALOR PRESTAÇÃO(R$) | AMORTIZAÇÃO(R$) | JUROS(R$) | SALDO DEVEDOR(R$) |
| ------------ | ------------------- | --------------- | --------- | ----------------- |
| 0            | -                   | -               | -         | 3.000,00          |
| 1            | 630,00              | 600,00          | 30,00     | 2.400,00          |
| 2            | 624,00              | 600,00          | 24,00     | 1.800,00          |
| 3            | 618,00              | 600,00          | 73,42     | 1.200,00          |
| 4            | 612,00              | 600,00          | 49,43     | 600,00            |
| 5            | 606,00              | 600,00          | 24,96     | 0                 | 

CÁLCULO VALOR DA AMORTIZAÇÃO:
1. montar fórmula =>  A = sd/n = 3000/5 = 600
2. amortização = R$ 600,00

CÁLCULO DA 1º PRESTAÇÃO:
1. cálculo do juros da primeira prestação => J = sd . i => J = 3000 . 1/100 = 30 
2. cálculo da prestação => P = a + j => P = 600 + 30 => P = 630 
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 3000 - 600 => SDA = 2400

CÁLCULO DA 2º PRESTAÇÃO:
1. cálculo do juros da segunda prestação => J = sd . i => J = 2400 . 1/100 = 24 
2. cálculo da prestação => P = a + j => P = 600 + 24 => P = 624 
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 2400 - 600 => SDA = 1800

CÁLCULO DA 3º PRESTAÇÃO:
1. cálculo do juros da terceira prestação => J = sd . i => J = 1800 . 1/100 = 18 
2. cálculo da prestação => P = a + j => P = 600 + 18 => P = 618 
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 1800 - 600 => SDA = 1200
  
CÁLCULO DA 4º PRESTAÇÃO:
1. cálculo do juros da quarta prestação => J = sd . i => J = 1200 . 1/100 = 12 
2. cálculo da prestação => P = a + j => P = 600 + 12 => P = 612 
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 1200 - 600 => SDA = 600

CÁLCULO DA 5º PRESTAÇÃO:
1. cálculo do juros da quinta prestação => J = sd . i => J = 600 . 1/100 = 6 
2. cálculo da prestação => P = a + j => P = 600 + 6 => P = 606 
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 600 - 600 => SDA = 0