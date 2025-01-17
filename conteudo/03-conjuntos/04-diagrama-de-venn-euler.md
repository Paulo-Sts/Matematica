# Diagrama de Venn-Euler

<br>

## DEFINIÇÃO
* É uma representação gráfica dos elementos de um conjunto.

<div style="display:inline_block">
    <img align="left" height="200" width="400" alt="TypeScript" src="https://static.todamateria.com.br/upload/di/ag/diagrama1.jpg">
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

Ex: Foi feita uma pesquisa entre 100 estudantes de uma escola sobre o consumo de três marcas de refrigerantes: A, B e C. O resultado obtido foi: 38 estudantes consomem a marca A, 30 a marca B, 27 a marca C; 15 consomem a marca A e B, 8 as marcas B e C, 19 as marcas A e C e 4 consomem os três refrigerantes.
Considerando os dados da pesquisa, quantos estudantes consomem apenas uma dessas marcas?

1. Para resolver esse tipo de questão, vamos começar desenhando um diagrama de Venn. Cada marca de refrigerante será representada por um círculo.
2. Vamos começar colocando o número de estudantes que consomem as três marcas simultaneamente, ou seja, a intersecção da marca A,B e C. 
3. Note que o número que consome as três marcas também está embutido no número que consome duas marcas. Então, antes de colocar esses valores no diagrama devemos tirar esses estudantes em comum. 
4. Devemos fazer o mesmo para o número que consome cada marca, pois aí também está repetido as partes comuns.

<div style="display:inline_block">
    <img align="left" height="200" width="400" alt="TypeScript" src="https://static.todamateria.com.br/upload/co/nj/conjunto1.gif?auto_optimize=low">
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

5. Agora que conhecemos o número de cada parte do diagrama, podemos calcular o número de estudantes que consome apenas uma dessas marcas, somando os valores de cada conjunto. 
6. Nº de pessoas que consome apenas uma das marcas = 11 + 8 + 4 = 23