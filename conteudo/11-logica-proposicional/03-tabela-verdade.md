# Tabela Verdade

## Definição
- Trata-se de uma tabela formada por linhas e colunas, mediante a qual são analisados os valores lógicos de proposições compostas. 
- O número de linhas da tabela depende do número de proposições que a sentença apresenta. 
- Representação:
  - 2<sup>n</sup>
  - n = número de proposições
- A ordem das possibilidades inicia com 4 verdadeiro e 4 falso na proposição **p**, 2 verdadeiro e 2 falso na proposição **q** e assim por diante sendo a proxima proposição sempre a alternância entre verdadeiro e falso a metade da proposição anterior, até alternar 1 verdadeiro e 1 falso.

#### Possíveis Resultados da Tabela Verdade
- Tautologia: É uma proposição cujo valor lógico é sempre verdadeiro.
- Contradição: É uma proposição cujo valor lógico é sempre falso.
- Contingência: Quando uma proposição não é tautológica nem contra-válida, a chamamos de contingência ou proposição indeterminada.

#### Formação da Tabela Verdade
1. Descobrir o número de proposições simples.
2. Calcular o número de linhas da tabela-verdade pela fórmula.
3. Desenhar a tabela-verdade.
4. Preencher a tabela-verdade com valores lógicos de verdadeiro ou falso.

#### Regras para o preenchimento da tabela Verdade
1. Começar sempre pelas proposições simples e suas negações, se houver.
2. Resolver os ( ), [ ] e { }, respectivamente, se houver.
3. Fazer primeiro as conjunções e disjunções, depois condicional e por último o Bicondicional.
4. A última coluna da tabela deverá ser sempre a da proposição toda.

Exemplo: Renata é professora. Essa proposição pode ser verdadeira ou falsa.   

1. 2<sup>1</sup> = 2  

| p |
|---|
| v |
| f |

Exemplo 2: ~p ∧ q  
1. 2<sup>n</sup> = 2<sup>2</sup> = 2x2 = 4 linhas

| p | q | ~p | ~p ∧ q |
|:-:|:-:|:--:|:------:|
| V | V | F  | F      |
| V | F | F  | F      |
| F | V | V  | V      |
| F | F | V  | F      |

**OBSERVAÇÃO:** A última coluna sempre será a estrutura completa.

> ### Tabelas Verdade da Proposição Composta

#### Tabela Verdade da Conjunção
- Formada pelo conectivo **e**.
- Será verdadeira somente quando todas as proposições forem verdadeiras.
- Operação:
  - p ∧ q

| p | q | p ∧ q |
|:-:|:-:|:-----:|
| V | V | V     |
| V | F | F     |
| F | V | F     |
| F | F | F     |

**OBSERVAÇÃO:** Proposições compostas que possuirem uma vírgula, se expressarem a ideia de "mas" e puderem ser substituidas por "e", são conjunções. Exemplo: Não basta à mulher de César ser honesta, ela precisa parecer honesta. Não basta à mulher de César ser honesta, mas ela precisa parecer honesta.

**OBSERVAÇÃO:** Proposições compostas que possuirem um "nem", podem ser substituídas por "e não" e são conjunções. Exemplo: Não estudo nem trabalho. Não estudo e não trabalho.

#### Tabela Verdade da Disjunção 
- Formada pelo conectivo **ou**.
- Será falsa somente quando todas proposições forem falsas.
- Operação:
  - p ∨ q

| p | q | p ∨ q |
|:-:|:-:|:-----:|
| V | V | V     |
| V | F | V     |
| F | V | V     |
| F | F | F     |

#### Tabela Verdade da Condicional 
- Formada pelo conectivo **Se...então..**.
- Será falsa somente quando a primeira proposição (antecedente) for verdadeira e a segunda proposição (consequente) for falsa.
- Operação:
  - p ⟶ q

| p | q | p ⟶ q |
|:-:|:-:|:------:|
| V | V | V      |
| V | F | F      |
| F | V | V      |
| F | F | V      |

**OBSERVAÇÃO:** Proposições compostas que possuirem as expressões "implica", "consequentemente" ou "logo" são condicionais. Exemplo: Penso, logo, existo.

**DICA:** 
- Consiste em definir a cada proposição simples que forme a condicional um adjetivo que a qualifica a partir da sua posição. Isso permite identificar a proposição invertida, mas mantendo o mesmo valor lógico que a utilizada com a expressão "se... então..".
- Usar o termo "Sem Noção", sendo que S é para Suficiente (na posição de p) e N para Necessário (na posição de q). 
- Sendo assim, o que vai definir se é Suficiente ou Necessário será a sua posição, pois se q estiver em p, ainda assim será considerado Suficiente, e vice-versa.
- Exemplo: "SE estudo com Waguinho ENTÃO aprendo Matemática". Em outras palavras, a mesma proposição pode apresentar formas de dizer diferentes:
  - "Estudar com Waguinho é condição SUFICIENTE para aprender Matemática" (p → q)
  - "Aprender Matemática é condição NECESSÁRIA para estudar com Waguinho" (q → p)
  - "Estudo com Waguinho SOMENTE SE aprendo Matemática" (→)

#### Tabela Verdade da Bicondicional
- Formada pelo conectivo **Se, e somente se...**.
- Será verdadeira quando ambas as proposições tiverem o mesmo valor lógico.
- Operação:
  - p ⟷ q

| p | q | p ⟷ q |
|:-:|:-:|:------:|
| V | V | V      |
| V | F | F      |
| F | V | F      |
| F | F | V      |

**OBSERVAÇÃO:** Proposições que apresentem as expressões "condição necessária e suficiente" são bicondicionais. Exemplo: Você lavar o carro é condição necessária e suficiente para eu o emprestar a você. ou: Você lava o carro se somente se eu o emprestar a você.

#### Tabela Verdade da Disjunção Exclusiva
- Formada pelo conectivo **ou...ou...**.
- Será verdadeira somente quando ambas as proposições tiverem valor lógico diferente.
- Operação:
  - p $\underline{\lor}$ q
  - p XOR q
  - p $\oplus$ q

| p | q | p XOR q |
|:-:|:-:|:-------:|
| V | V | F       |
| V | F | V       |
| F | V | V       |
| F | F | F       |

