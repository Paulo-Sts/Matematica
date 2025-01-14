# Teoria dos Conjuntos 

<br>

## DEFINIÇÃO
* É a teoria matemática que trata do agrupamento de elementos e suas relações.
* Conjuntos, são formados por elementos (qualquer coisa), podendo ser finitos ou infinitos.
* Representação de conjunto:
  - Letra = { elemento1, elemento2, elemento3, elemento4 }

> ### Relações entre conjuntos

#### Pertinência
* Indica se um elemento pertence ou não pertence a um determinado conjunto.
* Representação:
  - Elemento ∈ conjunto (pertence)
  - Elemento ∉ conjunto (não pertence)

Ex: B = {1, 2, 3, 4}  
1. 2 ∈ B  
2. 10 ∉ B  

#### Inclusão
* Indica se um conjunto é um sujconjunto de outro ou não.
* Representação:
  - **A** ⊂ **B** (**A** está contido em **B**)
  - **A** ⊄ **B** (**A** não está contido em **B**)
  - **B** ⊃ **A** (**B** contém **A**)
  - **B** ⊅ **A** (**B** não contém **A**)

Ex: A = {1, 2}; B = {1, 2, 3, 4} e C = {11, r}
1. A ⊂ B  
2. C ⊄ B
3. B ⊃ A
4. B ⊅ C

> ### Tipos de conjuntos

#### Conjunto unitário
* É um conjunto formado por um único elemento.
* Representação:
  - A = {2} (Primo par)

#### Conjunto vazio
* O conjunto vazio é um conjunto que não possui elementos.
* Representação:
  - {} ou ∅

#### Conjunto universo
* É o conjunto que possui todos os elementos de um determinado contexto, sendo representado pela letra **U**.
* Representação:
  - U = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9} (Números menores que 10)

#### Subconjuntos
* São conjuntos formados a partir de um outro conjunto.
* As partes de um conjunto A, é o conjunto formado por todos os subconjuntos de A.
* Representação:
  - A = {0, 1, 2} 
  - P(A) = {{0}, {1}, {2}, {0, 1}, {0, 2}, {1, 2}, {0, 1, 2}, ∅}
* Fórmula dos subconjuntos:
  - P = 2<sup>n</sup>
  - P = Partes do conjunto
  - n = número de elementos do conjunto

> ### Operações com Conjuntos

#### União entre conjuntos
* Se trata da união de todos os elementos de dois conjuntos em um terceiro conjunto.
* Elementos repetidos só aparecem uma única vez.
* Representação:
  - A ∪ B = AB

Ex: A = {1, 2} e B = {3, 4} 
1. A ∪ B => AB = {1, 2, 3, 4}

#### Interseção entre conjuntos
* Se trata do conjunto formado pelos elementos que se repetem nos dois conjuntos.
* Quando dois conjuntos não possuem elementos em comum, a interseção entre eles é um conjunto vazio.
* Representação:
  - A ∩ B = C

Ex: A = {1, 2} e B = {1, 2, 3, 4} 
1. A ∩ B => C = {1, 2}

Ex: A = {1, 2} e B = {3, 4} 
1. A ∩ B = {}

#### Diferença entre conjuntos
* Se trata do conjunto de elementos  que estão no primeiro conjunto, e não estão no segundo conjunto.
* Representação:
  - A - B = C

Ex: A = {1, 2, 10, 15} e B = {1, 2, 3, 4} 
1. A - B => C = {10, 15}

#### Igualdade entre conjuntos
* É quando todos os elementos dos conjuntos são iguais.
* Representação:
  - A = B 

Ex: A = {1, 2, 3, 4} e B = {1, 2, 3, 4} 
1. A = B 

#### Conjunto complementar
* O conjunto complementar de **A** é o conjunto do qual **A** faz parte (o conjunto universo) formado pelos elementos que não pertençam a **A**
* Representação:
  - A<sup>C</sup> ou C<sup>A</sup>
  - Se B ⊂ A então A - B = B<sup>C</sup>

Ex: A = {3, 4} e B = {1, 2, 3, 4} 
1. A<sup>C</sup> = {1, 2}

> ### Propriendades da união e interseção entre conjuntos

#### Comutativa
* A ∪ B = B ∪ A
* A ∩ B = B ∩ A

#### Associativa
* (A ∪ B) ∪ C = A ∪ (B ∪ C)
* (A ∩ B) ∩ C = A ∩ (B ∩ C)

#### Distributiva
* A ∩(B ∪ C) = (A ∩ B) ∪ (A ∩ C)
* A ∪(B ∩ C) = (A ∪ B) ∩ (A ∪ C)

#### Se A está contido em B
* A ∪ B = B ⇔ A ∩ B = A
* (A ∪ C) ⊂ (B ∪ C)
* (A ∩ C) ⊂ (B ∩ C)

> ### Leis de Morgan

#### 1ª lei
* O complementar da união é igual a interseção dos complementares
* Representação:
  - (A ∪ B)<sup>C</sup> = A<sup>C</sup> ∩ B<sup>C</sup>

#### 2ª lei
* O complementar da interseção é igual a união dos complementares.
* Representação:
  - (A ∩ B)<sup>C</sup> = A<sup>C</sup> ∪ B<sup>C</sup>