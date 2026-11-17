# Alexandre

## 1. Construção de textos e parágrafos com HTML

### A. criação de parágrafos ou frases

#### Exemplo:
```html
<p id ="p1" onclick ="mudar_cor()">Alexandre farmador de aura</p>
```
### B. Adicionando CSS aos parágrafos

#### Exemplo adicionando cores:

```css
#p1{

    color: green;
}
```
### C. Adicionando JavaScript aos parágrafos

#### Exemplo mudando cores:
```js
function mudar_cor(){

    document.getElementById("p1").style.color = "brown";
}
```
#### Observe que o mesmo p1 está sendo repetido no HTML, CSS e JavaScript!!!


## 2. Construção de titulos e subtítulos

### A. Toda página possui um único tema. Para isso, use h1.
```html
<h1 id ="h1" onclick ="mudarh1()">BUMBUM GULOSO</h1>
```
<br>

### B> Adicionando CSS ao tema

#### Exemplo adicionando um tipo de capitalização:
```css
#h1{

    text-transform: lowercase;
}
```
<br>

### C. Adicionando JavaScript ao tema

#### Exemplo mudando a capitalização padrão do CSS
```js
function mudarh1(){

    document.getElementById("h1").style.textTransform = "uppercase"
}
```
### D. Toda página pode ter subtítulos para cada pedaço de conteúdo, assim como um mercado possui um nome para cada corredor. Para isso, use h2.

<h2 id ="h2" onclick ="mudar_h2()">BUMBUM MOLE</h2>

<h2 id ="h2" onmouseenter ="mudar_h_2()">BUMBUM DURO</h2>

<br>

### E. Adicionando CSS aos subtítulos

#### Exemplo adicionando cor de fundo e alterando alinhamento:

#h2{

    background-color: cyan;
}

#h_2{

    text-align: right;
}

<br>

### F. Adicionando JavaScript ao subtítulos

#### Exemplo mudando a cor de funfo e o alinhamento padrão do CSS

function mudar_h2(){

    document.getElementById("h2").style.backgroundColor = "yellow";
}

function mudar_h_2(){

    document.getElementById("h_2").style.textAlign = "left";
}

<br>
```html
<h1>Seleções nacionais mais vencedoras da roubada copa do mundo FIFA:</h1>

<ol id ="ol1" onclick ="mudar_ol1()">
      <li>Brasil - 99</li>
      <li>Alemanha - 1</li>
      <li>Itália - 10</li>
      <li>Argentina - 0<li>
      <li>Uruguai - 1</li>
      <li>França - 1</li>
      <li>Espanha - 2</l1>
      <li>Inglaterra - 1</li>
</ol>
```
<br>
```css
#ol1{

    list-style-type: lower alpha;
}

#ol1 > li::marker{

    color: red;
}
```
<br>
```js
function mudar_ol1(){

    document.getElementById("oli").style.listStyleType = "decimal";
}
```
<br>
```html
<h1>Os assuntos mais comuns em estatistica</h1>

<ul id ="ul1" onclick ="mudar_ul1()">
      <li>Brasil - 99</li>
      <li>Alemanha - 1</li>
      <li>Itália - 10</li>
      <li>Argentina - 0<li>
      <li>Uruguai - 1</li>
      <li>França - 1</li>
      <li>Espanha - 2</l1>
      <li>Inglaterra - 1</li>
</ul>
```
<br>
```css
#ul1{

    list-style-type: square;
}

#ul1 > li::marker{

    color: coral;
}
```
<br>
```js
function mudar_ul1(){

    document.getElementById("uli").style.listStyleType = "circle";
}
```