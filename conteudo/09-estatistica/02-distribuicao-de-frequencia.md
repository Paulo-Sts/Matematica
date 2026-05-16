# Distribuição de Frequência

## 1. Definição
- Distribuição de Frequência é uma representação tabular dos dados estatísticos, discretos ou contínuos, sendo uma forma de resumir grandes conjuntos de dados. 
- Dados representados em uma tabela de frequência facilitam a construção de gráficos, bem como a compreensão sobre a natureza dos dados.

> ### 1.1 Representação dos Dados Discretos
- Considere a seguinte amostra de valores, relativos às disciplinas estudadas por 20 alunos X: {4, 8, 8, 6, 6, 8, 5, 5, 6, 7, 7, 7, 6, 6, 7, 5, 5, 7, 5, 5}.
- Essas variáveis são considerados variáveis discretas, pois são valores inteiros. A partir deles, é possível formar tabelas para facilitar a compreensão.

#### 1.1.1 Frequência Simples Absoluta (fi)
- A frequência simples de um elemento é o número de vezes que o elemento figura no conjunto de dados. 

Exemplo:
- X: {4, 8, 8, 6, 6, 8, 5, 5, 6, 7, 7, 7, 6, 6, 7, 5, 5, 7, 5, 5}
- A variável (Xi) é a quantidade de disciplinas cursadas pelos alunos. O "n" representa a amostra e o total do Fi. 
- O "n" é o mesmo que Σ (sigma), ou o somatório do fi, representando por Σfi.

| DISCIPLINAS (Xi) | FREQUÊNCIA (fi) | 
|:----------------:|:---------------:|
| 4                | 1               |
| 5                | 6               |
| 6                | 5               |
| 7                | 5               |
| 8                | 3               |
| Total            | n = Σfi = 20    |

#### 1.1.2 Frequência relativa (fr)
- É a razão entre a frequência absoluta da variável e o número total (n) de elementos da série.

Exemplo:
- Para compreender a Frequência relativa, basta dividir o "fi" pelo total (20). 
- E para dispor o resultado em porcentagem, é preciso apenas multiplicar o resultado por 100. 
- A frequência relativa apresenta o quanto determinado valor representa em relação ao total.

| DISCIPLINAS (Xi) | FREQUÊNCIA (fi) | FREQUÊNCIA RELATIVA (fr) |
|:----------------:|:---------------:|:------------------------:|
| 4                | 1               | 1/20 = 0.05 = 5%         |
| 5                | 6               | 6/20 = 0.3 = 30%         |
| 6                | 5               | 5/20 = 0.25 = 25%        |
| 7                | 5               | 5/20 = 0.25 = 25%        |
| 8                | 3               | 3/20 = 0.15 = 15%        |
| Total            | n = Σfi = 20    | 20/20 = 1 = 100%         |

#### 1.1.3 Frequência Acumulada (fac ou Fi)
- Frequência acumulada é o somatório da frequência simples da variável com as frequências simples dos elementos que cedem.

Exemplo:

| DISCIPLINAS (Xi) | FREQUÊNCIA (fi) | FREQUÊNCIA RELATIVA (fr) | FREQUÊNCIA ACUMULADA (fac) |
|:----------------:|:---------------:|:------------------------:|:--------------------------:|
| 4                | 1               | 1/20 = 0.05 = 5%         | 1                          |
| 5                | 6               | 6/20 = 0.3 = 30%         | 1 + 6 = 7                  |
| 6                | 5               | 5/20 = 0.25 = 25%        | 7 + 5 = 12                 |
| 7                | 5               | 5/20 = 0.25 = 25%        | 12 + 5 = 17                |
| 8                | 3               | 3/20 = 0.15 = 15%        | 17 + 3 = 20                |
| Total            | n = Σfi = 20    | 20/20 = 1 = 100%         |                            |

#### 1.1.4. Amplitude Amostral (AA)
- É a diferença entre o maior e o menor valor da amostra. Também chamada de amplitude total.
- Amplitude se remete a uma ideia de distância. 

Exemplo:
- E para empreender a Amplitude, tomando como base X: {4, 8, 8, 6, 6, 8, 5, 5, 6, 7, 7, 7, 6, 6, 7, 5, 5, 7, 5, 5}, deve-se subtrair o maior valor (8) pelo menor valor (4).
- Logo, Amplitude (A) = 8 - 4 = 4

## 2. Representação dos Dados em Classes
- É a organização de um conjunto de dados em intervalos, utilizado principalmente em grandes conjuntos de dados para facilitar a sua representação.
- São muito comuns na representação de variáveis quantitativas contínuas ou discretas em grande volume.

> ### 2.1 Classes (k)
- O número de classes de uma representação em classes define como serão subdivididos os dados em subconjuntos. 
- Ela é feita a partir da regra do quadrado. Para valores em que **n** não possui raíz exata, utiliza-se o valor mais próximo do quadrado perfeito.
- O número de classes define quantas linhas a tabela de distribuição de freqûencia terá.
- Representação:
  - K = √n
  - K = número de classes
  - n = número de elementos do conjunto

Exemplo: n = 25 pessoas com altura entre 50 kg e 100 kg.

1. K = √n
2. K = √25
3. K = 5
4. Serão formadas 5 classes.

> ### 2.2 Amplitude da Classe (h)
- É a definição do tamanhao de cada classe da representação em classes, em que valor ela começa e em que valor termina, ou seja, é a diferença entre o limite superior e inferior da classe. 
- Na definição da amplitude das classes é importante entender as possíveis definições dos valores inferior (início) e superior (final) da classe. As definições indicam se esses valores estão ou pertencem ou não ao intervalo da classe. Sua representação é feita normalmente por meio do simbolo de linhas (\|-, \-|, \|-|).
- O tamanho da amplitude da classe é feito dividindo o resultado da amplitude da amostra (ou amplitude total), pelo número de classes.
- Representação:
  - h = AA/k

Exemplo: n = 25 pessoas com altura entre 50 kg e 100 kg.

1. k = 5, AA = 50
2. h = 50/5 = 10
3. Cada classe vai ir de 10 em 10.

| PESO (Xi)  | FREQUÊNCIA (fi) |
|:----------:|:---------------:|
| 50 \|- 60  | 5               |
| 60 \|- 70  | 6               |
| 70 \|- 80  | 5               |
| 80 \|- 90  | 5               |
| 90 \|- 100 | 3               |
| Total      | n = Σfi = 25    |

> ### 2.3 Ponto Médio da Classe (Pm)
- É a média aritmética simples dos limites superior e inferior de cada classe.
- Representação:
  - Pm = (Ls + Li)/2

Exemplo:

| PESO (Xi)  | FREQUÊNCIA (fi) | PONTO MÉDIO (Pm)  |
|:----------:|:---------------:|:-----------------:|
| 50 \|- 60  | 5               | (60 + 50)/2 = 55  |
| 60 \|- 70  | 6               | (70 + 60)/2 = 65  |
| 70 \|- 80  | 5               | (80 + 70)/2 = 75  |
| 80 \|- 90  | 5               | (90 + 80)/2 = 85  |
| 90 \|- 100 | 3               | (100 + 90)/2 = 95 |
| Total      | n = Σfi = 25    |                   |