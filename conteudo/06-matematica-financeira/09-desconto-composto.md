# Desconto Composto

## Definição
- Desconto composto é uma dedução do valor nominal de um título quando este é pago/recebido de forma antecipada. Possue mesma lógica do desconto simples.
- Representação desconto:
  - D = n - a
  - D = desconto
  - n = valor nominal
  - a = valor atual
- Tipos de desconto composto:
  - Desconto comercial (bancário ou por fora);
  - Desconto racional (ou por dentro).

> ### Desconto comercial
- É o tipo de desconto utilizado pelos bancos e comércio em geral. A base do cálculo do desconto é o valor nominal.

#### Fórmula do valor atual
- Fórmula:
  - A = n . (1 - i)<sup>t</sup>
  - A = valor atual
  - n = valor nominal
  - i = taxa de juros
  - t = tempo

> ### Desconto racional
- É o tipo de desconto tendo como base o valor atual. Também é chamado de desconto verdadeiro.

#### Fórmula valor atual
- Fórmula:
  - A = n/(1 + i)<sup>t</sup>
  - A = valor atual
  - n = valor nominal
  - i = taxa de juros
  - t = tempo

**OBSERVAÇÃO:** O desconto racional é sempre menor do que o desconto comercial.

Ex: Título de 10 mil descontado 60 dias antes do vencimento com desconto simples de 10% ao mês. Qual o valor com o desconto comercial e o desconto racional?

Dados:  
n = 10000  
t = 60 dias = 2 meses  
i = 10% a.m  
D = ?  

Desconto comercial:
1. Montar a fórmula do valor atual => A = 10000 . (1 - 0,1)<sup>2</sup>
2. Calcular parêntese => (1 - 0,1)<sup>2</sup> = (0,9)<sup>2</sup> = 0,81
3. Multiplicar => 10000 . 0,81 = 8100
4. Resposta: O valor atual é = 8100 (desconto de 1900)

Desconto racional:
1. Montar a fórmula do valor atual => A = 1000/(1 + 0,10)<sup>2</sup>
2. Calcular parêntese => (1 + 0,1)<sup>2</sup> = (1,1)<sup>2</sup> = 1,21
3. Dividir => 10000/1,1
4. Resposta: O valor atual é = 8264,46 (desconto de 1735,53)

> ### Equivalência entre taxas de desconto comercial e desconto racional
- Duas taxas de desconto (comercial e racional) são equivalentes se produzirem o mesmo desconto em um mesmo prazo de antecipação de um título.
- Fórmula:
  - (1 - ic) . (1 + ir) = 1
  - ic = taxa de desconto comercial
  - ir = taxa de desconto racional

Ex: Qual a taxa de desconto racional equivalente a taxa de desconto comercial de 20% a.m ?

1. Montar a fórmula => (1 - 0,2) . (1 + ir) = 1
2. Resolver parêntese => (1 - 0,2) = (0,8)
3. Separar as partes => (0,8) . (1 + ir) = 1 = (1 + ir) = 1/0,8
4. Dividir => 1/0,8 = 1/8/10 = 1/1 . 10/8 = 10/8
5. Isolar icógnita => 1 + ir = 10/8 => 1 + ir = 1,25 => ir = 1,25 - 1 = 0,25
6. Resposta: A taxa de desconto racional equivalente é = 0,25 ou 25% a.m