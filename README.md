# graduation
code made in graduation

Código paara determinação de esforços e deslocamentos nas barras de uma treliça 2D:


Devido ao código desenvolvido ser um programa que necessita de entradas para
aplicações de processamento, será desenvolvido nessa etapa, instruções para utilização
correta do programa.


Dessa maneira, após rodar o programa, algumas perguntas serão feitas para o
usuário na janela de comando, listadas e explicadas a seguir:
Dados do sistema:
1. Será uma treliça "2d" ou "3d"??
Pergunta para determinar o tipo de treliça e qual sequência de código utilizar
2. Digite a unidade de medida em cm das coordenadas:
Essa medida representará a distância entre cada ponto de coordenada no eixo x e y,
ou seja, o ponto (0,0) terá a “unidade de medida” em [cm] até o ponto (0,1) , assim
como o ponto (0,0) terá a mesma distância até o ponto (1,0)
3. Digite o Módulo de Young em [kN/cm²]:
Módulo de elasticidade do material.
4. Qual o número de barras:
Número de barras que o sistema possui.
5. Quantos nós o conjunto possui?
Número de nó total que o sistema possui no total.
6. Digite a Área da seção transversal da barra “1” em cm²:
Quantos cm² de área cada barra possui, sendo que como existem várias barras, terá
que ser feito o input para o “1”, “2”,..
7. Qual o número do primeiro nó na referência global:
Classificação do primeiro nó da barra local no sistema global, com base na quantidade
de nós existentes.
8. Digite a coordenada X desse nó na barra “1”
Valor da coordenada X no primeiro nó da barra na referência global, sendo que como
existem várias barras, terá que ser feito o input para o “1”, “2”,..
9. Digite a coordenada Y desse nó na barra “1”
Valor da coordenada Y no primeiro nó da barra na referência global, sendo que como
existem várias barras, terá que ser feito o input para o “1”, “2”,..
310. Qual o número do segundo nó na referência global?
Classificação do segundo nó da barra local no sistema global, com base na quantidade
de nós existentes.
11. Digite a coordenada X desse nó na barra “1”:
Valor da coordenada X no primeiro nó da barra na referência global, sendo que como
existem várias barras, terá que ser feito o input para o “1”, “2”,..
12. Digite a coordenada Y desse nó na barra “1”:
Valor da coordenada Y no primeiro nó da barra na referência global, sendo que como
existem várias barras, terá que ser feito o input para o “1”, “2”,..
Dados de entrada das forças:
Entrada de força no eixo X:
1. Existem forças na direção X?
Aqui deverá ser inserido “yes” ou “no” caso haja ou não forças.
2. Insira a quantidade de forças:
Digitar quantas forças o sistema tem (Ex: 1,2,3 ...)
3. Qual o valor em [kN] da “1º” força aplicada em X.
Valor de cada força do sistema, sendo que se existirem múltiplas forças, deverá ser
digitado todas conforme o sistema solicita.
4. Qual o ângulo (em relação ao eixo x) da “1º” força aplicada em X
Ângulo de cada força do sistema com referência a X, sendo que se existirem múltiplas
forças, deverá ser digitado todas conforme o sistema solicita.
5. Em que nó esta essa força na referência?
Referência do nó no sistema global
Entrada de força no eixo Y:
1. Existem forças na direção Y?
Aqui deverá ser inserido “yes” ou “no” caso haja ou não forças.
2. Insira a quantidade de forças:
Digitar quantas forças o sistema tem (Ex: 1,2,3 …)
3. Qual o valor em [kN] da “1º” força aplicada em Y:
4Valor de cada força do sistema, sendo que se existirem múltiplas forças, deverá ser
digitado todas conforme o sistema solicita.
4. Qual o ângulo (em relação ao eixo y) da “1º” força aplicada em Y
Ângulo de cada força do sistema com referência a y, sendo que se existirem múltiplas
forças, deverá ser digitado todas conforme o sistema solicita.
5. Em que nó esta essa força na referência?
Referência do nó no sistema global.
Dados de entrada dos apoios:
Entrada de apoios fixos:
1. Existem apoios fixos na estrutura?
Aqui deverá ser inserido “yes” ou “no” caso haja ou não apoios fixos.
2. Quantos Apoios fixos existem?
Digitar a quantidade de apoios fixos existentes.
3. Qual o nó que o “1º” apoio fixo esta?
Digitar o nó no sistema global que o apoio está, caso exista mais de 1, digitar todos
conforme o programa solicita.
Entrada de apoios móveis:
1. Existem apoios móveis na estrutura?
Aqui deverá ser inserido “yes” ou “no” caso haja ou não apoios móveis.
2. Quantos Apoios móveis existem?
Digitar a quantidade de apoios móveis existentes.
3. Qual o nó que o “1º” apoio móvel esta?
Digitar o nó no sistema global que o apoio está, caso exista mais de 1, digitar todos
conforme o programa solicita.
4. Esse apoio restringe em 'x' ou 'y'?
Digitar a letra ‘x’ ou ‘y’ para cada apoio móvel existente.

