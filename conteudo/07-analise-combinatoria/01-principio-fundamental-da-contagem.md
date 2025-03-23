# Princípio Fundamental da Contagem

## Definição
- O princípio fundamental da contagem, ou princípio multiplicativo é um método para calcular o número de possibilidades de um evento de acordo com as condições que o forma (análise combinatória).
- O cálculo das possibilidades de um evento com **n** etapas, em que para cada etapa exista uma quantidade de opções de resultados (elementos), o número total de possibilidades que formam o evento, será o produto do número das opções de cada etapa do evento.
- O PFC também é chamado de médoto do tracinho, em que o tracinho representa o número de etapas ou escolhas de um evento.
- As formas mais comuns de se cobrar análise combinatória são: de quantas maneiras, de quantos modos, quantas são as possibilidades.

Ex: Quais as possibilidades de formar uma roupa com 5 camisas, 3 calças e 2 sapatos?

DADOS:  
etapa 1 => 5 (camisa)  
etapa 2 => 3 (calça)  
etapa 3 => 2 (sapato)  

1. número de possibilidades = 5 . 3 . 2 = 30 

**DICA:** Eventos em que se deve fazer uma escolha, entre um ou outro possível, geralmente usam a palavra **ou**. Para esses eventos em que existem hipóteses, o total de possibilidades será a soma das possibilidades de cada hipótese.

**DICA:** Eventos formados por etapas, são independentes e o total de possibilidades será formado pela multiplicação das possibilidades de cada etapa do evento.

> ### Tipos de cálculo PFC

#### Questões que pedem a condição "pelo menos um"
1. Calcular o total de possibilidades.
2. Calcular o número de possibilidades que não atendam a condição.
3. Subtrair do total as possibilidades que não atendam a condição, encontrando a resposta.

Ex: Quantos números de 4 algarismos, formados pelos algarismos 1, 2, 4, 6 e 8 tem pelo menos um algarismo repetido?

1. Total de números de 4 algarismos => 5 . 5 . 5 . 5 = 625
2. Números com algarismos distintos => 5 . 4 . 3 . 2 = 120
3. Subtração => 625 - 120 = 505
4. Resposta: 505 números

#### Questões que apresentam mais de uma hipótese para um evento
1. Calcular as possibilidades para cada evento.
2. Somar as possibilidades dos dois eventos.

Ex: Existem 2 modos de se ir da cidade A à cidade B, 3 modos de se ir da cidade B à cidade C e 4 modos de se ir da cidade A à cidade C sem passar pela cidade B. Usando essas opções, o número de modos diferentes de se ir da cidade A à cidade C?

Hipótese 1: (De A para C)
1. 4 possibilidades

Hipótese 2: (De A para B de para C)
1. Multiplicar => 2 . 3 = 6 possibilidades

Total:
1. Somar possiblidades das hipóteses => 4 + 6 = 10 
2. Resposta: 10 possibilidades