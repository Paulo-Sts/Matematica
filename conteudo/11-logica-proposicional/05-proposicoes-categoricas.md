# Proposições Categóricas

> ## 1. Definição
- Proposição Categórica é uma afirmação que relaciona dois termos (sujeito e predicado) de forma universal ou particular, afirmativa ou negativa. 
- Podem ser Universais (TODO, NENHUM) ou Particulares (ALGUM, EXISTE, PELO MENOS UM); Afirmativas ou Negativas (NÃO, NADA, NENHUM).
- Estrutura:
  - Todo A é B.
  - Nenhum A é B.
  - Algum A é B.
  - Algum A não é B.
- Exemplos:
  - Todo cão é bravo.
  - Nenhum homem é imortal.
  - Algum pássaro é azul.
  - Alguns gatos não são pretos.

> [!TIP] DICA:
> - Sinônimos de "Algum":
>   - Pelo menos um
>   - Existe
>   - Há pelo menos um

> ### 1.1 Quantidade e Qualidade
- Quantidade refere-se ao número de membros da classe de sujeito que são usados na proposição. Se a proposição se refere a todos os membros da classe de sujeito, ela é universal. Se a proposição não emprega todos os membros da classe de sujeito, é particular. 
- Qualidade é descrita como se a proposição afirma ou nega a inclusão de um sujeito dentro da classe do predicado. As duas qualidades possíveis são chamadas afirmativas e negativas. 

| DECLARAÇÃO              | QUANTIDADE  | QUALIDADE  |
|-------------------------|-------------|------------|
| (A) Todo A é B.         | Universal   | Afirmativa |
| (E) Nenhum A é B.       | Universal   | Negativa   |
| (I) Algum A é B.        | Particular  | Afirmativa |
| (O) Alguns A não são B. | Particular  | Negativa   |

> ## 2. Negação de Proposições Categóricas
- Para negar uma proposição categórica, basta lembrar que a negação deve contradizer a afirmação original. A contraditória de uma universal é uma particular, e vice-versa.
- Em resumo a negação de uma proposição universal é uma proposição particular, e a negação de uma afirmativa é uma negativa (ou vice-versa).

| PROPOSIÇÃO ORIGINAL | NEGAÇÃO CORRETA (EQUIVALENTE) | MACETE                       |
|---------------------|-------------------------------|------------------------------|
| Todo S é P (A)      | Algum S não é P (O)           | "Nem todo" = "Algum não"     |
| Nenhum S é P (E)    | Algum S é P (I)               | "Existe pelo menos um que é" |
| Algum S é P (I)     | Nenhum S é P (E)              | "Não existe S que seja P"    |
| Algum S não é P (O) | Todo S é P (A)                | "Todos são"                  |

> [!CAUTION] OBSERVAÇÃO:
> - A negação NÃO pode ser feita com "Todo não é" ou "Nenhum não é". É preciso usar os quantificadores corretos.

> #### Processo de Negação 
1. Identificar o quantificador: Verificar se é "Todo", "Nenhum" ou "Algum".
2. Identificar a qualidade: Verificar se a frase é afirmativa ou negativa.
3. Aplicar a regra do quadro:
  - A (Todo) vira O (Algum... não).
  - E (Nenhum) vira I (Algum... é).
  - I (Algum é) vira E (Nenhum... é).
  - O (Algum não é) vira A (Todo... é).

> #### Macete para Encontrar Negação
- Deve-se pegar o quantificador e encontrar o seu equivalente que realiza a negação a partir da tabela a seguir.

| PREPOSIÇÃO | NEGAÇÃO | EXPLICAÇÃO       |
|------------|---------|------------------|
| E          | T       | Existe ⟶ Todo   |
| N          | E       | Nenhum ⟶ Existe |
| E          | N       | Existe ⟶ Nenhum |
| T          | E       | Todo ⟶ Existe   |

- Exemplos:
  - "Todo concurseiro adora lógica." (T → E) = "Algum concurseiro não adora lógica."
  - "Nenhuma laranja está madura." (N → E) = "Alguma laranja está madura."
  - "Existe caneta preta." (E → T) ou (E → N) = "Toda caneta não é preta." ou "Nenhuma caneta é preta".

> ### 2.1 Equivalências Notáveis
- Todo A é não B ⇔ Nenhum A é B  
- Exemplo:
  - "Todo cientista não é estudioso" ⇔ "Nenhum cientista é estudioso"
- Nenhum A é não B ⇔ Todo A é B  
- Exemplo:
  - "Nenhum pedreiro não é operário" ⇔ "Todo pedreiro é operário"

> ### 3. Aplicações Práticas e Armadilhas Comuns

> #### Negação de "Todo"
- Muitos erram ao tentar negar "Todo" com "Nenhum". Isso está incorreto, pois "Todo S é P" e "Nenhum S é P" são contrárias (podem ser falsas simultaneamente), mas não são contraditórias.
- Exemplo: "Todo brasileiro gosta de futebol".
  - Errado: "Nenhum brasileiro gosta de futebol" (basta um que goste para a original ser verdadeira e a negação ser falsa).
  - Certo: "Algum brasileiro não gosta de futebol" (basta um contraexemplo para derrubar a universal).

> #### Negação de "Nenhum"
- Segue a mesma lógica. A existência de um único elemento que possua a característica já nega a universal negativa.
- Exemplo: "Nenhum político é honesto".
   - Negação: "Algum político é honesto".

> #### Negação de "Algum" (ou "Existe")
- Para negar que existe pelo menos um, é preciso afirmar que não existe nenhum.
- Exemplo: "Algum funcionário é competente".
  - Negação: "Nenhum funcionário é competente".

### 4. Representação por Diagramas de Venn
- Todo S é P: O conjunto S está dentro de P. A negação exige que exista pelo menos um S fora de P (Algum S não é P).
- Nenhum S é P: Os conjuntos são disjuntos (não se tocam). A negação exige que haja interseção (Algum S é P).
- Algum S é P: Existe interseção entre os conjuntos. A negação exige que não haja interseção (Nenhum S é P).
- Algum S não é P: Existe uma parte de S fora de P. A negação exige que todo S esteja dentro de P (Todo S é P).