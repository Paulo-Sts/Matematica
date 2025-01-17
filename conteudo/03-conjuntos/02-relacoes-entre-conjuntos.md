# Relações entre Conjuntos

<br>

## UNIÃO ENTRE CONJUNTOS
* Se trata da união de todos os elementos de dois conjuntos em um terceiro conjunto.
* Elementos repetidos só aparecem uma única vez.
* Representação:
  - A ∪ B = AB
* Representação por propriedade:
  - A ∪ B = { x / x ∈ A ou x ∈ B}

Ex: A = {1, 2} e B = {3, 4} 
1. A ∪ B => AB = {1, 2, 3, 4}

#### Quantidade de elementos da união de 2 conjuntos
* Representação:
  - n(A ∪ B) = n(A) + n(B) - n(A ∩ B)

Ex: A = {1, 2, 3, 4} e B = {1, 2, 3, 4, 10, 20 , 30} quantos elementos tem (A ∪ B) ?
1. n(A ∪ B) = 4 + 7 - 4
2. n(A ∪ B) = 7

#### Quantidade de elementos da união de 3 conjuntos
* Representação:
  - n(A ∪ B ∪ C) = n(A) + n(B) + n(C) - n(A ∩ B) - n(A ∩ C) - n(B ∩ C) + n(A ∩ B ∩ C)

Ex: A = {1, 2, 3, 4}, B = {0, 1, 2, 4, 10, 20} e B = {2, 4, 9} quantos elementos tem (A ∪ B ∪ C) ?
1. n(A ∪ B ∪ C) = 4 + 6 + 3 - 2 - 2 - 2 + 2
2. n(A ∪ B ∪ C) = 9

> ### Propriedades da união entre conjuntos

#### Comutativa
* A ∪ B = B ∪ A

#### Associativa
* (A ∪ B) ∪ C = A ∪ (B ∪ C)

#### Distributiva
* A ∪(B ∩ C) = (A ∪ B) ∩ (A ∪ C)

#### Se A está contido em B
* A ∪ B = B ⇔ A ∩ B = A
* (A ∪ C) ⊂ (B ∪ C)
* (A ∩ C) ⊂ (B ∩ C)

## INTERSEÇÃO ENTRE CONJUNTOS
* Se trata do conjunto formado pelos elementos que se repetem nos dois conjuntos.
* Quando dois conjuntos não possuem elementos em comum, a interseção entre eles é um conjunto vazio.
* Representação:
  - A ∩ B = C
* Representação por propriedade:
  - A ∩ B = { x / x ∈ A e x ∈ B}

Ex: A = {1, 2} e B = {1, 2, 3, 4} 
1. A ∩ B => C = {1, 2}

Ex: A = {1, 2} e B = {3, 4} 
1. A ∩ B = {}

> ### Propriedades da interseção entre conjuntos

#### Comutativa
* A ∩ B = B ∩ A

#### Associativa
* (A ∩ B) ∩ C = A ∩ (B ∩ C)

#### Distributiva
* A ∩(B ∪ C) = (A ∩ B) ∪ (A ∩ C)

#### Se A está contido em B
* A ∪ B = B ⇔ A ∩ B = A
* (A ∪ C) ⊂ (B ∪ C)
* (A ∩ C) ⊂ (B ∩ C)

***DICA:*** A expressão *ou* indica união entre conjuntos e a expressão *e* indica interseção.

## DIFERENÇA ENTRE CONJUNTOS
* Se trata do conjunto de elementos  que estão no primeiro conjunto, e não estão no segundo conjunto.
* Representação:
  - A - B = C
* Representação por propriedade:
  - A - B = { x / x ∈ A e x ∉ B}

Ex: A = {1, 2, 10, 15} e B = {1, 2, 3, 4} 
1. A - B => C = {10, 15}

## IGUALDADE ENTRE CONJUNTOS
* É quando todos os elementos dos conjuntos são iguais.
* Representação:
  - A = B 

Ex: A = {1, 2, 3, 4} e B = {1, 2, 3, 4} 
1. A = B 

## CONJUNTO COMPLEMENTAR
* O conjunto complementar de **A** é o conjunto do qual **A** faz parte (o conjunto universo) formado pelos elementos que não pertençam a **A**
* Representação:
  - A<sup>C</sup> ou C<sup>A</sup>
  - Se B ⊂ A então A - B = B<sup>C</sup>

Ex: A = {3, 4} e B = {1, 2, 3, 4} 
1. A<sup>C</sup> = {1, 2}

> ### Leis de Morgan

#### 1ª lei
* O complementar da união é igual a interseção dos complementares
* Representação:
  - (A ∪ B)<sup>C</sup> = A<sup>C</sup> ∩ B<sup>C</sup>

#### 2ª lei
* O complementar da interseção é igual a união dos complementares.
* Representação:
  - (A ∩ B)<sup>C</sup> = A<sup>C</sup> ∪ B<sup>C</sup>