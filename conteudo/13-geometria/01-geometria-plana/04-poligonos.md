# Polígonos

## 1. Definição
- Polígono é toda figura plana formada por segmentos de reta consecutivos não colineares, fechada, sem cruzamentos.

<div style="display:inline_block">
    <img align="left" height="200" width="580" alt="TypeScript" src="./../../img/poligonos.png">
</div><br><br><br><br><br><br><br><br><br><br><br><br>

> [!CAUTION] OBSERVAÇÃO:
> - A figura 1 é um polígono simples convexo, e a figura 2 é um polígono simples não convexo, são formadas por linhas poligonais que não se cruzam. A figura 3 não é um polígono, uma vez que há um cruzamento na linha. 

### 1.1 Classificação Quanto à Convexidade
- Polígono convexo são aqueles com ângulos internos menores que 180°. Nos convexos, todos os vértices apontam para seu exterior.
- Polígono côncavo (não convexo) é uma figura geométrica fechada que possui pelo menos um ângulo interno maior que 180° e menor que 360°. Possui ao menos um "vértice voltado para dentro", criando uma reentrância, concavidade ou "buraco" na estrutura.

### 1.2 Classificação Quanto ao Número de Lados
- Triângulo: 3 lados.
- Quadrilátero: 4 lados.
- Pentágono: 5 lados.
- Hexágono: 6 lados.
- Heptágono: 7 lados.
- Octógono: 8 lados.
- Eneágono: 9 lados.
- Decágono: 10 lados.
- Dodecágono: 12 lados.

<div style="display:inline_block">
    <img align="left" height="250" width="600" alt="TypeScript" src="./../../img/tipos-de-poligonos.png">
</div><br><br><br><br><br><br><br><br><br><br><br><br>

## 2. Ângulos em Polígonos Convexos

### 2.1 Soma dos Angulos Internos
- Fórmula:
  - Si = 180° × (n − 2)

### 2.2 Soma dos Ângulos Externos
- Fórmula:
  - Se = 360° (para qualquer polígono convexo)

## 3. Polígonos Regulares
- Polígono regular são os polígonos em que todos os lados e todos os ângulos são congruentes.

<div style="display:inline_block">
    <img align="left" height="150" width="500" alt="TypeScript" src="./../../img/poligonos-regulares.png">
</div><br><br><br><br><br><br><br>

### 3.1 Medida do Ângulo Interno
- Fórmula:
  - ai = 180° × (n − 2)/n

### 3.2 Medida do Ângulo Externo
- Fórmula:
  - ae = 360°/n

### 3.3 Relação Entre Ângulos Internos e Externos
- Fórmula:
  - ai + ae = 180°

## 4. Número de Diagonais
- Diagonal é o segmento que liga dois vértices não consecutivos.
- Fórmula:
  - d = n × (n − 3)/2
