# Implicação Lógica

## 1. Definição
- A implicação lógica trata de um conjunto de afirmações, sejam elas proposições simples ou compostas, cujo encadeamento lógico resulta em uma conclusão a ser descoberta. 
- Esta conclusão será, normalmente, a resposta requisitada em questões desse assunto. Vale destacar que, para ser considerada a resposta correta, tal conclusão deverá ser
necessariamente verdadeira para aquele conjunto de afirmações.

## 2. Métodos de resolução
- A forma de resolução dependerá da estrutura lógica das premissas, podendo ser de 2 tipos.

### 2.1 Tipo 1
- Quando houver, nas premissas que compõe o enunciado da questão, uma proposição simples ou uma conjunção.

#### Processo
1. Considerar as premissas verdadeiras e, com o conhecimento das tabelas-verdade dos conectivos, descobrir os valores lógicos das proposições simples presentes nas premissas.
2. Substituir os valores lógicos das proposições simples em cada uma das opções de resposta. Aquela que for necessariamente verdadeira é a opção correta da questão.

Exemplo:   
P1: Mauro é vendedor e Ana é dentista.  
P2: Se Paulo é estudante, então Ana não é dentista.  
P3: Ana é dentista.  

Portanto é correto afirmar que:  
a) Mauro não é vendedor.  
b) Mauro é vendedor e Paulo não é estudante.  
c) Paulo é estudante.  
d) Mauro não é vendedor ou Paulo é estudante.  

Resolução:  
P1: p ∧ q = V    
P2: r ⟶ ~q = V     
P3: q = V  

1. Logo q = v, ~q = f, r = f, p = v
2. Resposta = b)

### 2.2 Tipo 2
- Aquelas que não são do tipo 1, ou seja, que não aparece, entre as premissas, uma proposição simples ou uma conjunção.

#### Processo
1. Nesse caso não haverá nenhuma sentença em forma de proposição simples ou de conjunção, de sorte que não estará previamente definido qual o ponto de partida da resolução. 
2. Sendo assim será necessário testar as alternativas e verificar se uma alternativa for verdade se as proposições serão verdades.
3. Também é possível procurar nas alternativas uma resposta que seja uma conclusão a partir de uma equivalência lógica.

Exemplo: 
Considere que as sentenças dadas a seguir são verdadeiras:  
S1: Se Alice é cearense, então Bianca é paraense.    
S2: Se Consuelo é piauiense, então Bianca não é paraense.    
S3: Se Alice não é cearense, então Consuelo não é piauiense.    
S4: Alice é cearense ou Consuelo é piauiense.    

Pode-se deduzir corretamente que:  
a) Alice é cearense, Bianca é paraense e Consuelo é piauiense.  
b) Alice não é cearense, Bianca é paraense e Consuelo é piauiense.  
c) Alice é cearense, Bianca é paraense e Consuelo não é piauiense.  
d) Alice é cearense, Bianca não é paraense e Consuelo não é piauiense.  

Resolução: 
Testar letra A como verdade.    
S1: Se Alice é cearense, então Bianca é paraense. p(v) ⟶ q(v) = V    
S2: Se Consuelo é piauiense, então Bianca não é paraense. r(v) ⟶ ~q(f) = F (ERRADO)   
S3: Se Alice não é cearense, então Consuelo não é piauiense. ~p(f) ⟶ ~r(f) = V    
S4: Alice é cearense ou Consuelo é piauiense. p(v) ∨ r(v) = V    

Resolução: 
Testar letra D como verdade.    
S1: Se Alice é cearense, então Bianca é paraense. p(v) ⟶ q(v) = V  
S2: Se Consuelo é piauiense, então Bianca não é paraense. r(f) ⟶ ~q(f) = V  
S3: Se Alice não é cearense, então Consuelo não é piauiense. ~p(f) ⟶ ~r(v) = V  
S4: Alice é cearense ou Consuelo é piauiense. p(v) ∨ r(f) = V  

1. Logo, resposta = d)