# Circunferência e Círculo

## 1. Definição
- Circunferência é o conjunto de pontos equidistantes de um ponto central (a "borda").
- Círculo é a circunferência mais sua região interna ("a moeda").
- Centro é o ponto central.
- Raio (r) é a distância do centro a qualquer ponto da circunferência.
- Diâmetro (d) é o segmento que passa pelo centro, ligando dois pontos da circunferência.  
- Fórmula do diâmetro:
  - d = 2r
- Corda é o segmento que liga dois pontos quaisquer da circunferência.
- Arco é a porção da circunferência entre dois pontos.

<div style="display:inline_block">
    <img align="left" height="150" width="300" alt="TypeScript" src="./../../img/circulo-e-circunferencia.png">
</div><br><br><br><br><br><br><br>

## 2. Área e Comprimento do Círculo

### 2.1 Comprimento (Perímetro)
- Fórmula:
  - C = 2πr  
  - (π ≈ 3,14 se não for dado)

### 2.2 Área do Círculo
- Fórmula:
  - A = πr²

<div style="display:inline_block">
    <img align="left" height="250" width="330" alt="TypeScript" src="./../../img/area-e-comprimento-circulo.png">
</div><br><br><br><br><br><br><br><br><br><br><br><br>

## 3. Arcos e Ângulos
- Grau (°) é acircunferência dividida em 360 partes.
- Radiano (rad) é o arco cujo comprimento é igual ao raio.
- Relação fundamental:
  - 360° = 2π rad
- Conversões comuns:
  - 30° = π/6 rad
  - 45° = π/4 rad
  - 60° = π/3 rad
  - 90° = π/2 rad

<div style="display:inline_block">
    <img align="left" height="250" width="320" alt="TypeScript" src="./../../img/arcos-e-angulos.png">
</div><br><br><br><br><br><br><br><br><br><br><br><br>

### 3.1 Comprimento de um arco (l)
- Fórmula:
  - l = α · r (α em radianos)

<div style="display:inline_block">
    <img align="left" height="220" width="280" alt="TypeScript" src="./../../img/comprimento-de-arco.png">
</div><br><br><br><br><br><br><br><br><br><br><br>

Exemplo (pêndulo):  

1. r = 15 cm, α = 15°  
2. Convertendo: 15° = π/12 rad  
3. l = (π/12) · 15 = (5π/4) cm ≈ 3,9 cm

## 4. Setor Circular
- Região entre dois raios (fatia de pizza).

### 4.1 Área do Setor
- Proporcional ao ângulo central α.  
- Usar regra de três:
  - Área total do círculo: πr² corresponde a 360° (ou 2π rad)
  - Área do setor (As) corresponde a α
- Fórmula direta (α em radianos):  
  - As = (α/2) · r²
- Exemplo (gráfico de setores)
  - d = 12 cm ⟶ r = 6 cm  
  - Sem opinião: 12% do total  
  - Área total = π·6² = 36π ≈ 113,04 cm²  
  - Área do setor = 12% de 113,04 ≈ 13,56 cm²

<div style="display:inline_block">
    <img align="left" height="200" width="400" alt="TypeScript" src="./../../img/setor-circular.png">
</div><br><br><br><br><br><br><br><br><br>

## 5. Segmento Circular
- Região entre um arco e uma corda.

### 5.1 Área do Segmento
- Aseg = Asetor − Atriângulo
- Exemplo:
  - r = 4 cm, α = 135°
  - Área do setor: regra de três ⟶ As = 6π cm²
  - Área do triângulo (com trigonometria): At = ½·4·4·sen(135°) = 4√2 cm²
  - Aseg = 6π − 4√2 = 2(3π − 2√2) cm²

<div style="display:inline_block">
    <img align="left" height="200" width="430" alt="TypeScript" src="./../../img/segmento-circular.png">
</div><br><br><br><br><br><br><br><br><br>

## 6. Coroa Circular
- Região entre dois círculos concêntricos.

### 6.1 Área
- Ac = πR² − πr² = π(R² − r²)
- Exemplo (praça com chafariz)
  - Tangente AB = 16 m ⟶ metade = 8 m  
  - Triângulo retângulo: R² = r² + 8² ⟶ R² − r² = 64  
  - Ac = π·64 = 64π m²

<div style="display:inline_block">
    <img align="left" height="250" width="300" alt="TypeScript" src="./../../img/coroa-circular.png">
</div><br><br><br><br><br><br><br><br><br><br><br><br>