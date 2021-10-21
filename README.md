# cssTreinamento-
- 01 • Grid  
- 02 • Propriedade Min e Max 
- 03 • Padding / Margin 
- 04 • Z-index  
- 05 • Flex box 
- 06 • Introdução ao SASS 

## Dia 1(01,02,03)

Bootstrap: Facilitador de frameworks.

Grid: possuei até 12 colunas e n linhas(Bootstrap reorganiza as colunas), conteúdo  multidimensional. O grid possibilita dimencionar em até 12 colunas, podendo dividir simetricamente. 

class="container" -> Conjunto de linhas 
class="row" -> linha 
class="col" -> coluna


---------------------------------------------------
### Min e Max usado apenas nas propriedades width e height.

```bash
.div{max-width:100px; min-heigth: 100px}
```

- min faz referência  ao tamanho mínimo aceito para a propriedade, assim como o max faz referência  ao tamanho máximo  aceito pela propriedade.

- Ele adapta ao dispositivo, descendo os elementos de acordo com a redução  da resolução. Oque possibilita utilização  do mesmo código  pra infitos dispositivo.


Proporção  vw vh:


---------------------------------------------------
### Padding / Margin:

Movimentação  absoluta em ambos, não se difere ao mudar o tamanho da tela, não  usar variável  de tamanho em nenhum dos dois, recomendado usar position

- Padding: A propriedade usada para gerar espaço  em trono de um elemento, dentro de quaisquer bordas definidas de forma absoluta, ou seja a partir das bordas ele empurrará o conteúdo  para dentro. Usa apenas o conteudo, nao leva em consideração  o site.

- Margin: A propriedade usada para gerar espaço por fora de um elemento. Meche nos conteudos adjacentes. Deve-se usar com cuidado, pois vai superar ou puxar os espaços e conteúdos dos elementos ao adjacentes .

## Dia 2 (04,05)

04 • z-index: usado pra posicionamento de tela, só funciona em elementos de position: absolute, position: relative, position: fixed or position sticky. Tambem em itens flexiveis.

```CSS
.z-index1{
  position: relative
  z-index: valor // quando número de z-index é maior do outro z-index é vai sobrepor. 
  backgrounde-color: blue;
  width: 100px;
  heigh: 100 px;
}

```
## 05 • Flex-box: 
é unidimensional , ou seja, linha **OU** coluna. Organiza os elementos da pagina HTML. 

**display: É o passo inicial para o flex-box (display: flex)**


- flex-direction: aplicado ao container, e define o eixo/fluxo de exibição  em que os elentos serão  organizados. Ordena a lista, muito usado para menus.

- flex-wrap: Com a propriedade  de flex-wrap funciona como quebra de linha dos container's

- flex-flow: se aplica ao container, é uma forma reduzida de escrita para ter as duas felx-direction e felx-wrape.

- justify-content: propriedade que define a justificação  dos containers, muito usado em todas as situações.

- align-content: define como as coluna são definidas ao longo do eixo horizontal. Só funciona com mais de uma coluna.

- align-items: define como as linha são distribuídas ao longos das linhas verticais.

order: a ordem de defalt pode ser alterada por meio da propriedade order:

 `.item2{order: VALOR}`

- flex-grow: define a proporção  com que o item deve crescercaso necessário. Por padrao seu valor é 0. Muito pouco usado.

- flex-shrink: define a proporção  com que o intem deve diminuir. Por padrão seu valor é 0. Muito pouco usado.

## 06 - Intro SASS ( !IMPORTANTE PARA FRONT-END -> CSS 3 ):

Uma extensão  de CSS que adciona poder e elegância  ao CSS básico.

Estudar sobre




