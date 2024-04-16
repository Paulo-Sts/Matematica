# Sistemas de Amortização Misto

<br>

## DEFINIÇÃO
* Em uma operação de parcelamento, ao saldarmos um compromisso através de pagamentos iguais ou variáveis, estamos na realidade fazendo dois pagamentos. O primeiro pagamento refere-se a devolução ao credor do capital recebido, processo chamado de amortização, pago de acordo com condições combinadas previamente. O segundo pagamento ao credor diz respeito à remuneração dos recursos de propriedade do detentor do capital. Esses valores referem-se aos juros. Após o pagamento de cada prestação, a amortização é abatida do saldo devedor.
* Representação:
  - Prestação = amortização + juros
* O Sistema de Amortização Misto (SAM) é um sistema intermediário entre o Sistema Price e o Sistema de Amortização constante. O valor da prestação no Sistema de Amortização Misto (SAM) é a média entre a prestação no sistema Price e o SAC.
* Fórmula:
  - P<sub>sam</sub> = (P<sub>saf</sub> + P<sub>sac</sub>)/2
  - P<sub>sam</sub> = Prestação no sistema de amortização mista
  - P<sub>saf</sub> = Prestação no sistema de amortização francês
  - P<sub>sac</sub> = Prestação no sistema de amortização constante

Ex: Empréstimo de 100 mil a ser pago pelo sistema SAM, em 100 prestações mensais com jutos de 1% ao mês. Qual o valor da 1ª prestação?

DADOS:  
P = ?  
m = 100.000,00  
i = 1% a.m  
n = 100  

1ª PRESTAÇÃO SISTEMA PRICE:
1. montar fórmula => P = 100000 . [(1 + 0,01)<sup>100</sup> . 0,01]/(1 + 0,01)<sup>100</sup> - 1
2. resultado => P = 1.586,57
3. Prestação pelo SAF é R$ 1.586,57

1ª PRESTAÇÃO SISTEMA SAC:
1. calcular amortização => A = sd/n => A = 100000/100 => A = 1000
2. calcular juros => J = sd . i => J = 100000 . 1/100 = 1000
3. calcular prestação => P = a + j => P = 1000 + 1000 => P = 2000
4. Prestação pelo SAC é R$ 2.000,00

1ª PRESTAÇÃO SISTEMA SAM:
1. montar fórmula => P<sub>sam</sub> = (P<sub>saf</sub> + P<sub>sac</sub>)/2 = P<sub>sam</sub> = ( 1.586,57 + 2.000,00)/2
2. somar => P<sub>sam</sub> = ( 1.586,57 + 2.000,00)/2 => P<sub>sam</sub> = 3.586,57/2
3. dividir => P<sub>sam</sub> = 3.586,57/2 => P<sub>sam</sub> = 1.793,29
4. Prestação pelo SAC é R$ 1.793,29

#### Vantegens e desvantagens do SAM
* O montante pago pelo sistema SAM é menor do que o montante pago pelo sistema Price.
* As primeiras parcelas no sistema SAM não são tão altas como no sistema SAC.
* O montante pago pelo sistema SAM é maior do que o montante pago pelo sistema SAC.

Ex: Empréstimo de 100 mil a ser pago pelo sistema SAM, em 100 prestações mensais com jutos de 1% ao mês.

| SISTEMA DE AMORTIZAÇÃO | VALOR TOTAL PAGO | VALOR AMORTIZADO | JUROS PAGOS  | 
| ---------------------- | ---------------- | ---------------- | ------------ | 
| SAC                    | R$ 150.500,00    | R$ 100.000,00    | R$ 50.500,00 | 
| SAM                    | R$ 154.578,50    | R$ 100.000,00    | R$ 54.578,50 | 
| PRICE                  | R$ 158.657,00    | R$ 100.000,00    | R$ 58.657,00 | 
 
