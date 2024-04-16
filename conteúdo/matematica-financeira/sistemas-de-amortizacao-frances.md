# Sistemas de Amortização Francês

<br>

## DEFINIÇÃO
* Em uma operação de parcelamento, ao saldarmos um compromisso através de pagamentos iguais ou variáveis, estamos na realidade fazendo dois pagamentos. O primeiro pagamento refere-se a devolução ao credor do capital recebido, processo chamado de amortização, pago de acordo com condições combinadas previamente. O segundo pagamento ao credor diz respeito à remuneração dos recursos de propriedade do detentor do capital. Esses valores referem-se aos juros. Após o pagamento de cada prestação, a amortização é abatida do saldo devedor.
* Representação:
  - Prestação = amortização + juros
* O sistema de amortização francês ou tabela price é o mais aplicado pelas instituições financeiras nos financiamentos imobiliários e pelo comércio em geral. 
* O cálculo da amortização de uma dívida é feito utilizando uma tabela que relaciona as prestações, a amortização, o saldo devedor e os juros.

#### Características
* As prestações são iguais ao longo do tempo.
* O valor da amortização é variável ao longo do tempo.
* Os juros incidem sobre o saldo devedor que por decrescerem ao longo do tempo, geram juros cada vez menores, ou seja, os juros são decrescentes.
* Como as prestações são fixas e os juros decrescentes, a amortização é crescente.

> ### Fórmula da prestação
* Fórmula para calcular o valor da prestação para o sistema de amortização da tabela price.
* Representação:
  - P = m . [(1 + i)<sup>n</sup> . i]/(1 + i)<sup>n</sup> - 1
  - P = prestação
  - m = montante
  - i = taxa de juros
  - n = quantidade de parcelas

> ### Fórmula dos juros calculados
* É o cálculo dos juros após o pagamento de cada prestação.
* Representação:
  - J = sd . i
  - J = juros
  - sd = saldo devedor
  - i = taxa de juros

> ### Fórmula dos saldo devedor atual
* É o cálculo do saldo devedor após o pagamento de cada prestação.
* Representação:
  - SDA = sd - a
  - SDA = saldo devedor atual
  - sd = saldo devedor anterior
  - a = amortização

> ### Fórmula da amortização futura
* Essa fórmula determina o valor da amortização de uma prestação futura.
* Representação:
  - A = m . [(1 + i)<sup>t - 1</sup> . i]/(1 + i)<sup>n</sup> - 1
  - A = amortização futura
  - m = montante
  - i = taxa de juros
  - t = número da prestação futura
  - n = quantidade de prestações

> ### Fórmula da saldo devedor futuro
* Essa fórmula determina o valor do saldo devedor de uma prestação futura.
* Representação:
  - SD = m . [(1 + i)<sup>n</sup> - (1 + i)<sup>t</sup>]/(1 + i)<sup>n</sup> - 1
  - SD = saldo devedor futuro
  - m = montante
  - i = taxa de juros
  - t = número da prestação futura
  - n = quantidade de prestações

**DICA:** Sempre iniciar com a realização da dívida, ou seja, pelo início da operação que é realizada no tempo 0.

Ex: Dívida no valor de R$ 6.000,00 que é amortizada pela tabela price em 5 prestações mensais, com juros de 2% ao mês. Monte a tabela.

DADOS:   
saldo devedor = R$ 6.000,00    
número de prestações = 5  
juros = 2% a.m  

| Nº PRESTAÇÃO | VALOR PRESTAÇÃO(R$) | AMORTIZAÇÃO(R$) | JUROS(R$) | SALDO DEVEDOR(R$) |
| ------------ | ------------------- | --------------- | --------- | ----------------- |
| 0            | -                   | -               | -         | 6000              |
| 1            | 1.272,95            | 1.152,95        | 120,00    | 4.847,05          |
| 2            | 1.272,95            | 1.176,01        | 96,94     | 3.671,04          |
| 3            | 1.272,95            | 1.199,53        | 73,42     | 2.471,51          |
| 4            | 1.272,95            | 1.223,52        | 49,43     | 1.247,99          |
| 5            | 1.272,95            | 1.247,99        | 24,96     | 0                 | 

CÁLCULO VALOR DA PRESTAÇÃO:
1. montar fórmula => P = 6000 . [(1 + 0,02)<sup>5</sup> . 0,02]/(1 + 0,02)<sup>5</sup> - 1
2. resolver parênteses => P = 6000 . [(1 + 0,02)<sup>5</sup> . 0,02]/(1 + 0,02)<sup>5</sup> - 1 => P = 6000 . [(1,02)<sup>5</sup> . 0,02]/(1,02)<sup>5</sup> - 1
3. resolver potências e divisão => P = 6000 . [(1,02)<sup>5</sup> . 0,02]/(1,02)<sup>5</sup> - 1 => 0,022081616064/1,1040808032 - 1 => 0,022081616064/0,1040808032 = 0,2121583941043222
4. multiplicar => P = 6000 . 0,2121583941043222 => P = 1.272,95
5. prestação = R$ 1.272,95

CÁLCULO DA 1º PARCELA:
1. cálculo do juros da primeira parcela => J = sd . i => J = 6000 . 2/100 = 120 
2. cálculo da amortização => P = a + j => a = p - j => a = 1.272,95 - 120 => a = 1.152,95 
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 6000 - 1.152,95 => SDA = 4.847,05

CÁLCULO DA 2º PARCELA:
1. cálculo do juros da segunda parcela => J = sd . i => J = 4.847,05 . 2/100 = 96,94 
2. cálculo da amortização => P = a + j => a = p - j => a = 1.272,95 - 96,94 => a = 1.176,01
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 4.847,05 - 1.176,01 => SDA = 3.671,04

CÁLCULO DA 3º PARCELA:
1. cálculo do juros da terceira parcela => J = sd . i => J = 3.671,04 . 2/100 = 73,42 
2. cálculo da amortização => P = a + j => a = p - j => a = 1.272,95 - 73,42 => a = 1.199,52
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 3.671,04 - 1.199,52 => SDA = 2.471,51

CÁLCULO DA 4º PARCELA:
1. cálculo do juros da quarta parcela => J = sd . i => J = 2.471,51 . 2/100 = 49,43 
2. cálculo da amortização => P = a + j => a = p - j => a = 1.272,95 - 49,43 => a = 1.223,52
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 2.471,51 - 1.223,52 => SDA = 1.247,99

CÁLCULO DA 5º PARCELA:
1. cálculo do juros da quinta parcela => J = sd . i => J = 1.247,99 . 2/100 = 24,96 
2. cálculo da amortização => P = a + j => a = p - j => a = 1.272,95 - 24,96  => a = 1.247,99
3. cálculo do saldo devedor atual => SDA = sd - a => SDA = 1.247,99 - 1.247,99 => SDA = 0