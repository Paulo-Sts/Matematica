# Probabilidade Binominal

## Definição
- A probabilidade binominal calcula a chance de um evento **S** acontecer dado um número **n** de repetições dos eventos possíveis, em que pode acontecer ou o evento **S** ou o evento **F**.
- Um evento binominal é formado por um experimento binominal que só admite dois resultados possíveis e mutualmente excludentes.
- Em um evento binominal os resultados favoráveis são chamados de **sucesso** enquanto o seu complementar é chamado de **fracasso**.
- Representação:
  - P(n, s) = C<sub>n, s</sub> . [p(s)]<sup>s</sup> . [p(f)]<sup>f</sup>
  - P(n, s) = probabilidade do evento **S** acontecer
  - C<sub>n, s</sub> = números de combinações possíveis do evento **S** dada **n** repetições
  - [p(s)]<sup>s</sup> = probabilidade do evento **S** elevado a **s** resultados favoráveis
  - [p(f)]<sup>f</sup> = probabilidade do evento **f** elevado ao complementar de **s** resultados favoráveis

Ex: Uma moeda é lançada 8 vezes, qual a chance de sair exatamente 5 caras?

1. Resultados possíveis => Ω = {cara, coroa} => n(Ω) = 2 (eventos possíveis)
2. Resultados favoráveis (sucesso) => S = {cara} => n(S) = 1 = 1/2
3. Resultados não favoráveis (fracasso) => F = {coroa} => n(F) = 1 = 1/2
4. Repetições => 8 com 5 caras => C<sub>8, 5</sub>
5. Cálculo das repetições => C<sub>8, 5</sub> = 8!/5!(8 - 5)! => C<sub>8, 5</sub> = 8!/5! . 3! => C<sub>8, 5</sub> = 8 . 7. 6 . 5!/5! . 3 . 2 . 1 = 8 . 7. 6/6 = 56
6. Fórmula => P(8 repetições, 5 cara) = 56 . 1/2<sup>5</sup> . 1/2<sup>3</sup>
7. Potência => P(8 repetições, 5 cara) = 56 . 1/32 . 1/8
8. Multiplicação => P(8 repetições, 5 cara) = 56 . 1/32 . 1/8 = 56/256
9. Divisão => P(8 repetições, 5 cara) = 56/256 : 8 = 7/32
10. Resposta: 7/32
