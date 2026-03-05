# Negação de Proposições Compostas

> ## 1. Definição
- No caso das proposições compostas, devemos utilizar as fórmulas da negação.
- Estas fórmulas são expressões equivalentes à negação das proposições.

> ### 1.1 Negação da Conjunção (1ª Lei de Morgan)
- A regra da 1ª Lei de Morgan diz que deve-se negar a primeira proposição, trocar o conectivo **e** pelo conectivo **ou** e negar a segunda proposição.
- Fórmula: ~(p ∧ q) = ~p  ∨ ~q
- Exemplo:
  - Proposição: Luís não é habilidoso e Carla é criativa.
  - Negação: Luís é habilidoso ou Carla não é criativa.

> ### 1.2 Negação da Disjunção (2ª Lei de Morgan)
- A regra da 2ª Lei de Morgan diz que deve-se negar a primeira proposição, trocar o conectivo **ou** pelo conectivo **e** e negar a segunda proposição.
- Fórmula: ~(p ∨ q) = ~p  ∧ ~q
- Exemplo:
  - Proposição: João vai ao futebol ou Ana vai ao teatro.
  - Negação: João não vai ao futebol e Ana não vai ao teatro.

> ### 1.3 Negação da Condicional (Regra do Mané)
- Mantém a primeira proposição troca o condicional por conjunção e nega a segunda proposição. Para facilitar a memorização, esta regra é chamada de Mane (Manter a 1ª e Negar a 2ª).
- Fórmula: ~(p ⟶ q) = p ∧ ~q
- Exemplo:
  - Proposição: Se chove, então Carlos vai ao teatro.
  - Negação: Chove e Carlos não vai ao teatro.

> ### 1.4 Negação da Bicondicional

> #### Regra Principal
- A negação da bicondicional resulta em uma disjunção exclusiva.
- Fórmula: ~(p ⟷ q) = p $\underline{\lor}$ q
- Exemplo: 
  - Proposição: 4 é par se, e somente se 3 é ímpar.
  - Negação: Ou 4 é par ou 3 é ímpar.

> #### Outras formas de negar a Bicondicional
- Também pode ser representada negando apenas uma das proposições e mantendo o conectivo:
  - ~(p ⟷ q) = ~p ⟷ q
  - ~(p ⟷ q) = p ⟷ ~q

> ### 1.5 Negação da Disjunção Exclusiva

> #### Regra Principal
- A negação da disjunção exclusiva resulta em uma bicondicional.
- Fórmula: ~(p $\underline{\lor}$ q) = p ⟷ q
- Exemplo: 
  - Proposição: Ou Carlos é Paulista ou Lucas é carioca.
  - Negação: Carlos é paulista se, e somente se Lucas é carioca.

#### Outras Formas de Negar a Disjunção Exclusiva
- ~(p $\underline{\lor}$ q) = ~p $\underline{\lor}$ q
- ~(p $\underline{\lor}$ q) = p $\underline{\lor}$ ~q

> ## 2. Resumo da Negação das Proposições Compostas

| NOME                | PROPOSIÇÃO | NEGAÇÃO  |
|---------------------|------------|----------|
| Conjunção           |  ~(p ∧ q)  | ~p  ∨ ~q |
| Disjunção           | ~(p ∨ q)   | ~p  ∧ ~q |
| Condicional         | ~(p ⟶ q)  | p ∧ ~q   |
| Bicondicional       | ~(p ⟷ q)  | p XOR q  |
| Bicondicional       | ~(p ⟷ q)  | ~p ⟷ q  |
| Bicondicional       |  ~(p ⟷ q) | p ⟷ ~q  |
| Disjunção Exclusiva | ~(p XOR q) | p ⟷ q   |
| Disjunção Exclusiva | ~(p XOR q) | ~p XOR q |
| Disjunção Exclusiva | ~(p XOR q) | p XOR ~q |