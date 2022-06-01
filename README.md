# HTML-E-CSS
Alguns comandos e noções básicas sobre HTML5 e CSS3

# <h1 align="center"> 💻HTML_CSS_DIO💻 </h1>
Anotações das aulas do Bootcamp da Digital Innovation One

## 📖 Um Pouco da História

O Html foi criado pelo Tim Berners-lee, quando ele viu a necessidade de compartilhar documentos com seus colegas. O Processo de criação foi um pouco demorado, tendo seu início em 1980 mas a linguagem apenas surgiu em 1991 sendo aprimorada de lá pra cá, até chegar no que temos atualmente, o HTML 5.

- HTML 1 (1991)
- HTML 2 (1995)
- HTML 3 (1997)
- HTML 4 (2001)
- HTML 5 (2014 - )

---

### Semântica

✔️ `<section>` seção genérica de conteúdo <br>
✔️ `<article>` representa um conteúdo relevante em uma página <br>
✔️ `<footer>`  rodapé da página ou de parte da página <br>
✔️ `<h1>` ... `<h6>` representam a importância de um título dentro de uma página, só pode haver um h1 por página <br>

✔️ O elemento `<a>` tem dois atributos principais: <br>
1º Hyperlink `<a href = "https://github.com/WilliamOSantos"> GitHub </a>`
###### Obs: mailto - email/tel - telefone <br>
2º target - define como o link será aberto `target = "_blank"` o "_blank" define que o link deve ser aberto em outra guia do navegador.

---
### 🖨Como inserir imagens em seu site

✔️O elemento `<img>` possui apenas dois atributos próprios <br>
1° - src (obrigatório) - guarda o caminho da imagem <br>
2° - alt (recomendado) - mostra a descrição da foto quando ela não é carregada <br>

---
### Como organizar listas com html

✔️`<ul>` - lista não ordenada <br>
✔️`<ol>` - lista ordenada <br>
✔️`<li>` - elemento de lista <br>

---
### Introdução e conceitos básicos do CSS

#### Introdução a CSS3
- Requisitos básicos <br>
✔️Editor de texto <br>
✔️Um navegador de internet <br>
✔️Conhecimento em html <br>

- Estrutura do css <br>
✔️Seletores: elementos html <br>
✔️Declaração: propriedade + valor <br>
Exemplo: `a, h1, h2{color: green}` <br>

- Id e divs <br>
✔️`Id` (#) `div` (.) <br>
✔️O Id só pode ser usado uma vez por página <br>

---

#### Conceitos básicos do CSS

- Box model <br>
✔️Margin - espaçamento entre elementos <br>
✔️Border - circundam o padding e o conteúdo <br>
✔️Padding - espaçamento entre a borda e o conteúdo <br>
✔️Content - o que o bloco representa (texto, imagem ou vídeo) <br>

---

<h1 align="center" > Estilizando elementos, textos e listas </h1>

---

#### Estilizando elementos

- Como atribuir valores diferentes para cada lado da página <br>
✔️Padding/margin: <br>
`.post {padding: 10px 5px;}` <br>
10px - parte superior e inferior <br>
5px - lado esquerdo e direito <br>
`.post {padding: 15px 10px 5px 0;}` <br>
15px - parte superior <br>
10px - lado direito <br>
5px - parte inferior <br>
0 - lado esquerdo <br>
`.post {padding-top: 15px padding-left:10px padding-bottom:5px padding-right:0;}` <br>

- Como mudar a cor de fundo <br>
✔️Background <br>
`.post {background-color: black;}` <br>
`.post {background-color: #000;}` <br>
`.post {background: #000;}` <br>

- Como Mudar a Borda <br>
✔️Border <br>
Largunra: px, cm, ml... <br>
Cor: black. #000... <br>
Esilo: solida, pontilhada, tracejada... <br>
Radius: px e porcentagem <br>
`.post{border: 3px solid blue; border-top: 2px dotted green; border-right: 4px dashed pink;}` <br>

---

### Estilizando textos

✔️Font-family <br>
`#title {font-family: verdana;}` - adcionando apenas um tipo de fonte ao texto <br>
`#title {font-family: verdana, arial;}` - adcionando dois tipos de fonte pois assim caso a primeira não funcione, a segunda será usada <br>

✔️Font-size <br>
`#title {font-size: 10px;}` - adcionando tamanho de 10px para a font <br>

✔️Font-style <br>
`#title {font-style: italic;}` - mudando a fonte para italica <br>

✔️Font-weight <br>
`#title {font-weight: bold;}` - alterando o peso da fonte para negrito <br>

✔️Text-tranform <br>
`#title {text-tranformt: uppercase;}` - coloca todo o texto em caixa alta <br>
`#title {text-tranformt: lowercase;}` - coloca todo o texto em caixa baixa <br> 
`#title {text-tranformt: capitalize;}` - coloca todo as primeiras letras de cada palavra maiúscula <br> 

✔️Text-tdecoration <br>
`#title {text-decoration: underline;}` - coloca linha abaixo da palavra <br> 
`#title {text-decoration: overline;}` - coloca linha acima da palavra <br> 
`#title {text-decoration: line-through;}` - coloca linha ao centro da palavra <br> 

#### Estilizando listas

✔️List-style-type <br>
`ul{list-style-type: square;}` - altera o marcador da lista para um quadrado <br> 
`ol{list-style-type: uper-roman;}`- altera o marcador da lista para um algorismo romano maiusculo <br>
`ul{list-style-type: "#\1F44D";}`- altera o marcador da lista para um simbolo (nesse caso, um emogi) <br> 

✔️List-style-image <br>
`ul{list-style-image: url(rocket.com);}` - altera o marcador da lista para uma imagem <br> 

---

### Propriedades de dimensões e alinhamento

✔️Widht - ajusta a largura <br>
✔️Height - ajusta a altura <br>
✔️Max-widht - largura máxima do elemento <br>
✔️Max-height - largura mínima <br>
✔️Margin - espaçamento em elemento, o valor auto alinha o elemente automaticamente <br>
✔️Text-align - alinha o texto <br>

---

### Links Uteis

<a href="https://visualstudio.microsoft.com/pt-br/free-developer-offers/" target = "_blank" > Instale o Visual Studio </a> <br>
<a href="https://www.devmedia.com.br/comandos-e-tags-html5/23618" target = "_blank" > Códigos HTML 5 </a>
