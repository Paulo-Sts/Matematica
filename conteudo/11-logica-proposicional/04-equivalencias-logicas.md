# Equivalências Lógicas

> ## 1. Conceito de Equivalência Lógica
- Duas proposições são logicamente equivalentes quando suas tabelas-verdade são idênticas.  
- Notação: p ⇔ q ou p = q ou p ≡ q
- Exemplo:
  - p ⟶ q é equivalente a ~p ∨ q

| p | q | p ⟶ q | ~p | ~p ∨ q |
|:-:|:-:|:------:|:--:|:------:|
| V | V | V      | F  | V      | 
| V | F | F      | F  | F      |
| F | V | V      | V  | V      |
| F | F | V      | V  | V      |

> ### 1.1 Equivalências Básicas

| EQUIVALÊNCIA     | EXEMPLO                                                          |
|:----------------:|:-----------------------------------------------------------------|
| p ∧ p = p       | "José é inocente e inocente" = "José é inocente"                  |
| p ∨ p = p       | "Maria foi ao teatro ou ao teatro" = "Maria foi ao teatro"        |
| p ∧ q = q ∧ p   | "A águia é forte e veloz" = "A águia é veloz e forte"             |
| p ∨ q = q ∨ p   | "A camiseta é azul ou vermelha" = "A camiseta é vermelha ou azul" |
| p ⟷ q = q ⟷ p | "Amo se, e somente se, vivo" = "Vivo se, e somente se, amo"       |

> ### 1.2 Equivalências da Condicional

> #### Forma Contrapositiva
- Inverte as proposições e as nega.
- Representação:
  - p ⟶ q = ~q ⟶ ~p  
- Exemplo:  
  - "Se chove, então faz frio" equivale a: "Se não faz frio, então não chove"

> #### Regra do "Neymar" (Nega a primeira OU mantém a segunda)
- Nega a primeira proposição, troca a condicional por disjunção e repete a segunda proposição.
- Representação:
  - p ⟶ q = ~p ∨ q  
- Exemplo: "Se estudo, então passo no concurso" equivale a: "Não estudo ou passo no concurso"

> ### 1.3 Equivalência da Disjunção
- Nega a primeira proposição, troca a disjunção pela condicional e repete a segunda proposição.
- Representação:
  - p ∨ q = ~p ⟶ q  
- Exemplo: "Chove ou faz frio" equivale a: "Se não chove, então faz frio"

> ### 1.4 Equivalência da Disjunção Exclusiva
- É formada por duas proposições conjuntivas, sendo ligadas por uma disjunção, em que na primeira conjunção, repete-se a primeira proposição e se nega a segunda proposição, e na segunda conjunção nega a primeira proposição e repete a segunda proposição. 
- Representação:
  - p $\underline{\lor}$ q = (p ∧ ~q) ∨ (~p ∧ q)  
- Exemplo: "Ou traga café ou traga chá" equivale a: "Tragam café e não tragam chá ou não tragam café e tragam chá"

> ## 2. Leis Associativas e Distributivas

> #### Leis Associativas
1. (p ∧ q) ∧ r = p ∧ (q ∧ r)
2. (p ∨ q) ∨ r = p ∨ (q ∨ r)

> #### Leis Distributivas
1. p ∧ (q ∨ r) = (p ∧ q) ∨ (p ∧ r)
2. p ∨ (q ∧ r) = (p ∨ q) ∧ (p ∨ r)

## 3. Leis da Dupla Negação e Simplificação

> #### Dupla Negação
- A negação de uma negação de proposição é a própria proposição.
- Representação:
  - ~(~p) = p

#### Regras de Simplificação
- p ∨ p = p
- p ∧ p = p
- p ∨ ~p = V (tautologia)
- p ∧ ~p = F (contradição)
- p ∨ V = V
- p ∨ F = p
- p ∧ V = p
- p ∧ F = F
- p ⟷ p = V
- p ⟷ ~p = F
- p ∨ (p ∧ q) = p (Lei da Absorção)
- p ∧ (p ∨ q) = p (Lei da Absorção)