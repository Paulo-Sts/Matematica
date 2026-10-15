# Triângulos

## 1. Definição
- Triângulo: Polígono de três lados, formado por três pontos não colineares.
- Vértices: A, B, C
- Lados: AB, BC, AC (ou a, b, c)
- Ângulos internos: A, B, C

<div style="display:inline_block">
    <img align="left" height="120" width="180" alt="TypeScript" src="./../../img/triangulo.png">
</div><br><br><br><br><br><br>

## 2. Condição de Existência (Desigualdade Triangular)
- Para três medidas a, b, c formarem um triângulo:
  - a < b + c  
  - b < a + c  
  - c < a + b

## 3. Soma dos Ângulos Internos
- Em qualquer triângulo A + B + C = 180°.

<div style="display:inline_block">
    <img align="left" height="120" width="180" alt="TypeScript" src="./../../img/soma-triangulo.png">
</div><br><br><br><br><br><br>

## 4. Teorema do Ângulo Externo
- A medida de um ângulo externo (e) é igual à soma dos ângulos internos não adjacentes.
- Fórmula:  
  - e = A + B

<div style="display:inline_block">
    <img align="left" height="120" width="180" alt="TypeScript" src="./../../img/teorema-do-angulo-externo.png">
</div><br><br><br><br><br><br>

## 5. Classificação dos Triângulos

### 5.1 Quanto aos Lados
- Escaleno: Três lados diferentes.
- Isósceles: Dois lados iguais.
- Equilátero: Três lados iguais (ângulos = 60°).

### 5.2 Quanto aos Ângulos
- Acutângulo: Três ângulos agudos (< 90°).
- Retângulo: Um ângulo reto (= 90°).
- Obtusângulo: Um ângulo obtuso (> 90°).

## 6. Elementos Notáveis do Triângulo

#### Altura (h)
- Segmento de um vértice perpendicular ao lado oposto.
- As três alturas se encontram no ortocentro.

<div style="display:inline_block">
    <img align="left" height="150" width="320" alt="TypeScript" src="./../../img/altura-triangulo.png">
</div><br><br><br><br><br><br><br>

#### Bissetriz Interna
- Segmento que divide um ângulo interno ao meio.
- As três bissetrizes se encontram no incentro.

<div style="display:inline_block">
    <img align="left" height="150" width="200" alt="TypeScript" src="./../../img/bissetriz-interna.png">
</div><br><br><br><br><br><br><br>

#### Mediana
- Segmento de um vértice ao ponto médio do lado oposto.
- As três medianas se encontram no baricentro.

<div style="display:inline_block">
    <img align="left" height="150" width="200" alt="TypeScript" src="./../../img/mediana-triangulo.png">
</div><br><br><br><br><br><br><br>

#### Mediatriz
- Reta perpendicular a um lado passando pelo seu ponto médio.
- As três mediatrizes se encontram no circuncentro.

<div style="display:inline_block">
    <img align="left" height="150" width="200" alt="TypeScript" src="./../../img/mediatriz-segmento.png">
</div><br><br><br><br><br><br><br>

#### Baricentro (Propriedade)
- O baricentro divide cada mediana na razão 2:1.
- Do vértice ao baricentro: 2 partes
- Do baricentro ao ponto médio: 1 parte
- Exemplo: 
  - mediana = 12 cm ⟶ baricentro divide em 8 cm e 4 cm.

<div style="display:inline_block">
    <img align="left" height="150" width="200" alt="TypeScript" src="./../../img/baricentro-triangulo.png">
</div><br><br><br><br><br><br><br>

## 7. Semelhança de Triângulos
- Dois triângulos são semelhantes se possuem ângulos correspondentes iguais e lados correspondentes proporcionais.

#### Casos de semelhança
- AA (Ângulo-Ângulo): Dois ângulos iguais.
- LAL (Lado-Ângulo-Lado): Dois lados proporcionais e o ângulo entre eles igual.
- LLL (Lado-Lado-Lado): Três lados proporcionais.

## 9. Triângulo Retângulo (Relações Métricas)

#### Elementos
- Hipotenusa (a): Lado oposto ao ângulo reto.
- Catetos (b e c): Lados que formam o ângulo reto.
- Altura relativa à hipotenusa (h).
- Projeções dos catetos sobre a hipotenusa (m e n).

#### Relações
- Teorema de Pitágoras: a² = b² + c²
- Cateto ao quadrado: b² = a·n ; c² = a·m
- Produto dos catetos: b·c = a·h
- Altura ao quadrado: h² = m·n

<div style="display:inline_block">
    <img align="left" height="150" width="320" alt="TypeScript" src="./../../img/triangulo-retangulo.png">
</div><br><br><br><br><br><br><br>


## 10. Teoremas Fundamentais

### 10.1 Teorema de Tales
- Definição: Se um feixe de retas paralelas é cortado por duas transversais, os segmentos correspondentes são proporcionais.
- Na prática (Triângulos): Quando uma linha corta um triângulo de forma paralela à base, ela cria um mini triângulo semelhante ao grandão.
- Fórmula:
  - A/B = C/D
- Exemplo:
~~~
       / \
      /   \
    r------------ (paralela à base)
    / A | C \
   /____|____\
  /   B | D   \
 /______|______\
~~~

Exemplo: Para medir a altura de um prédio comercial, um técnico fincou uma estaca de 1 metro de altura no chão, paralela ao prédio. Em um determinado momento do dia, o sol projetou uma sombra de 3 metros para o prédio e uma sombra de 0,5 metros para a estaca. Qual é a altura do prédio?  

Resolução (Regra de Três/Proporção):  
1.  Altura do prédio/Altura da estaca = Sombra do prédio/Sombra da estaca
2.  Altura/1 = 3/0,5
3.  Altura = 3/0,5
4.  A altura do prédio é 6 metros.

### 10.2 Teorema de Pitágoras
- Fórmula Básica: 
  - a² = b² + c² 
  - a = hipotenusa 
  - b = cateto oposto 
  - c = cateto adjacente
- Triângulos Pitagóricos: São triângulos retângulos cujos lados são números inteiros. Seus múltiplos também funcionam:
- Exemplos:
  - Triângulo 3, 4, 5 (Múltiplos comuns: 6, 8, 10 | 9, 12, 15 | 30, 40, 50)
  - Triângulo 5, 12, 13

Exemplo: Um operário precisa encostar uma escada em uma parede para consertar um refletor que está a 4 metros de altura. Para a escada ficar segura e não tombar para trás, o manual de segurança diz que a base da escada deve ficar no chão, a 3 metros de distância da parede. Qual deve ser o comprimento dessa escada?  

Resolução:  
1. Lado inclinado² = 3² + 4²
2. Lado inclinado² = 9 + 16 = 25
3. O tamanho da escada é 5 metros.

> [!TIP] DICAS: 
> - Escala em área e volume:
>   - Se a questão der uma miniatura ou mapa na escala linear 1:k.
>   - Para converter áreas, a razão será 1:k².
>   - Para converter volumes (ou capacidade em litros), a razão será 1:k³.
> - Exemlo:
>   - Escalas Superficiais: Em um plano de uma casa, a escala é 1:200, e a área de um quarto na planta é de 6 cm². Qual a área real do quarto?
>     - 1. A escala linear é 1:200, então a escala superficial será (1:200)² = 40.000
>     - 2. Logo: 6 cm² × 40.000 = 240.000 cm² = 24 m²
>     - 3. Resposta: 24 m².
> - Exemplo:
>   - Escala Volumétrica: Em uma maquete, a escala volumétrica é 1:100. Se o volume da maquete é de 8 cm³, qual é o volume real?
>     1. A escala volumétrica será (1:100)³ = 1.000.000
>     2. Logo: 8 cm³ × 1.000.000 = 8.000.000 cm³ = 8 m³
>     3. Resposta: 8 m³.