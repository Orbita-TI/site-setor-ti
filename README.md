# 📚 Referência Completa de HTML e CSS

Guia de consulta rápida com as principais **tags HTML** e **propriedades CSS**, organizadas por categoria, com uma descrição e um **exemplo de código** de cada uma.

---

## Sumário

- [Parte 1 — Tags HTML](#parte-1--tags-html)
  - [Estrutura do documento](#estrutura-do-documento)
  - [Metadados (`<head>`)](#metadados-head)
  - [Seccionamento e semântica](#seccionamento-e-semântica)
  - [Agrupamento de conteúdo](#agrupamento-de-conteúdo)
  - [Texto em linha (inline)](#texto-em-linha-inline)
  - [Links e âncoras](#links-e-âncoras)
  - [Listas](#listas)
  - [Tabelas](#tabelas)
  - [Formulários](#formulários)
  - [Mídia embutida](#mídia-embutida)
  - [Scripts e programação](#scripts-e-programação)
  - [Elementos interativos](#elementos-interativos)
  - [Web Components e templates](#web-components-e-templates)
- [Parte 2 — Propriedades CSS](#parte-2--propriedades-css)
  - [Como aplicar CSS](#como-aplicar-css)
  - [Seletores](#seletores)
  - [Box model](#box-model-modelo-de-caixa)
  - [Display e posicionamento](#display-e-posicionamento)
  - [Flexbox](#flexbox)
  - [Grid](#grid)
  - [Tipografia e texto](#tipografia-e-texto)
  - [Cores e fundo](#cores-e-fundo)
  - [Bordas e contornos](#bordas-e-contornos)
  - [Efeitos visuais](#efeitos-visuais)
  - [Transições, animações e transformações](#transições-animações-e-transformações)
  - [Listas e tabelas](#listas-e-tabelas)
  - [Outras propriedades úteis](#outras-propriedades-úteis)
  - [Unidades e funções](#unidades-e-funções)
- [Exemplo completo montado](#exemplo-completo-montado)

---

# Parte 1 — Tags HTML

## Estrutura do documento

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<!DOCTYPE html>` | Declara o documento como HTML5. Primeira linha. | `<!DOCTYPE html>` |
| `<html>` | Elemento raiz que envolve toda a página. | `<html lang="pt-br"> ... </html>` |
| `<head>` | Metadados do documento (não visíveis). | `<head> ... </head>` |
| `<body>` | Todo o conteúdo visível da página. | `<body> ... </body>` |

## Metadados (`<head>`)

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<title>` | Título exibido na aba do navegador. | `<title>Minha Página</title>` |
| `<meta>` | Charset, viewport, descrição etc. | `<meta charset="UTF-8">` |
| `<link>` | Vincula recursos externos (CSS). | `<link rel="stylesheet" href="style.css">` |
| `<style>` | CSS embutido no documento. | `<style> body { margin: 0; } </style>` |
| `<base>` | URL base para links relativos. | `<base href="https://site.com/">` |

## Seccionamento e semântica

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<header>` | Cabeçalho da página ou seção. | `<header><h1>Logo</h1></header>` |
| `<nav>` | Bloco de navegação. | `<nav><a href="#">Início</a></nav>` |
| `<main>` | Conteúdo principal e único. | `<main> ... </main>` |
| `<section>` | Seção temática. | `<section><h2>Sobre</h2></section>` |
| `<article>` | Conteúdo independente. | `<article><h2>Post</h2></article>` |
| `<aside>` | Conteúdo lateral/secundário. | `<aside>Publicidade</aside>` |
| `<footer>` | Rodapé da página ou seção. | `<footer>© 2026</footer>` |
| `<h1>`…`<h6>` | Títulos, do mais ao menos importante. | `<h1>Título</h1>` |
| `<address>` | Informações de contato. | `<address>contato@site.com</address>` |

## Agrupamento de conteúdo

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<p>` | Parágrafo de texto. | `<p>Olá, mundo!</p>` |
| `<div>` | Contêiner em bloco genérico. | `<div class="card"> ... </div>` |
| `<span>` | Contêiner em linha genérico. | `<span class="destaque">texto</span>` |
| `<hr>` | Linha separadora horizontal. | `<hr>` |
| `<br>` | Quebra de linha. | `Linha 1<br>Linha 2` |
| `<pre>` | Texto pré-formatado. | `<pre>  código  </pre>` |
| `<blockquote>` | Citação longa em bloco. | `<blockquote>Frase citada.</blockquote>` |
| `<figure>` | Agrupa mídia + legenda. | `<figure><img src="a.jpg"></figure>` |
| `<figcaption>` | Legenda de um `<figure>`. | `<figcaption>Foto 1</figcaption>` |

## Texto em linha (inline)

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<a>` | Link/âncora. | `<a href="#">Clique</a>` |
| `<strong>` | Forte importância (negrito). | `<strong>Atenção!</strong>` |
| `<b>` | Negrito visual. | `<b>negrito</b>` |
| `<em>` | Ênfase (itálico). | `<em>importante</em>` |
| `<i>` | Itálico visual. | `<i>itálico</i>` |
| `<mark>` | Texto destacado. | `<mark>grifado</mark>` |
| `<small>` | Texto de menor importância. | `<small>termos</small>` |
| `<del>` | Texto removido (tachado). | `<del>R$ 100</del>` |
| `<ins>` | Texto inserido (sublinhado). | `<ins>R$ 80</ins>` |
| `<sub>` | Subscrito. | `H<sub>2</sub>O` |
| `<sup>` | Sobrescrito. | `x<sup>2</sup>` |
| `<code>` | Código em linha. | `<code>console.log()</code>` |
| `<kbd>` | Entrada de teclado. | `<kbd>Ctrl</kbd>` |
| `<samp>` | Saída de programa. | `<samp>Erro 404</samp>` |
| `<var>` | Variável. | `<var>x</var>` |
| `<abbr>` | Abreviação com dica. | `<abbr title="HyperText">HTML</abbr>` |
| `<cite>` | Título de obra citada. | `<cite>Dom Casmurro</cite>` |
| `<q>` | Citação curta em linha. | `<q>frase curta</q>` |
| `<time>` | Data/hora legível por máquina. | `<time datetime="2026-07-14">hoje</time>` |
| `<bdo>` | Força direção do texto. | `<bdo dir="rtl">texto</bdo>` |
| `<wbr>` | Ponto opcional de quebra. | `Super<wbr>califragilistico` |
| `<dfn>` | Termo sendo definido. | `<dfn>API</dfn>` |

## Links e âncoras

| Uso | Descrição | Exemplo |
|-----|-----------|---------|
| Link externo | Vai para outra página. | `<a href="https://site.com">Site</a>` |
| Nova aba | Abre em outra aba. | `<a href="#" target="_blank" rel="noopener">Abrir</a>` |
| Âncora interna | Vai a um `id` da página. | `<a href="#contato">Contato</a>` |
| E-mail | Abre o cliente de e-mail. | `<a href="mailto:eu@site.com">E-mail</a>` |
| Telefone | Inicia uma ligação. | `<a href="tel:+5591999999999">Ligar</a>` |
| Download | Força o download. | `<a href="arq.pdf" download>Baixar</a>` |

## Listas

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<ul>` | Lista não ordenada. | `<ul><li>Item</li></ul>` |
| `<ol>` | Lista ordenada (numerada). | `<ol><li>Primeiro</li></ol>` |
| `<li>` | Item de lista. | `<li>Conteúdo</li>` |
| `<dl>` | Lista de definições. | `<dl> ... </dl>` |
| `<dt>` | Termo definido. | `<dt>HTML</dt>` |
| `<dd>` | Descrição do termo. | `<dd>Linguagem de marcação</dd>` |

## Tabelas

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<table>` | Cria a tabela. | `<table> ... </table>` |
| `<caption>` | Legenda da tabela. | `<caption>Vendas</caption>` |
| `<thead>` | Agrupa o cabeçalho. | `<thead><tr>...</tr></thead>` |
| `<tbody>` | Agrupa o corpo. | `<tbody> ... </tbody>` |
| `<tfoot>` | Agrupa o rodapé. | `<tfoot> ... </tfoot>` |
| `<tr>` | Linha da tabela. | `<tr> ... </tr>` |
| `<th>` | Célula de cabeçalho. | `<th>Nome</th>` |
| `<td>` | Célula de dados. | `<td>Ricardo</td>` |
| `colspan` | Mescla colunas. | `<td colspan="2">Total</td>` |
| `rowspan` | Mescla linhas. | `<td rowspan="2">Ano</td>` |

## Formulários

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<form>` | Contêiner do formulário. | `<form action="/enviar" method="post"> ... </form>` |
| `<input>` | Campo de entrada. | `<input type="text" name="nome">` |
| `<label>` | Rótulo do campo. | `<label for="nome">Nome</label>` |
| `<textarea>` | Texto de várias linhas. | `<textarea rows="4"></textarea>` |
| `<button>` | Botão clicável. | `<button type="submit">Enviar</button>` |
| `<select>` | Lista suspensa. | `<select><option>A</option></select>` |
| `<option>` | Opção do `<select>`. | `<option value="1">Um</option>` |
| `<optgroup>` | Agrupa opções. | `<optgroup label="Grupo"> ... </optgroup>` |
| `<fieldset>` | Agrupa campos com borda. | `<fieldset> ... </fieldset>` |
| `<legend>` | Título do `<fieldset>`. | `<legend>Dados</legend>` |
| `<datalist>` | Sugestões para um input. | `<datalist id="op"><option>SP</option></datalist>` |
| `<output>` | Resultado de cálculo. | `<output name="soma">0</output>` |
| `<progress>` | Barra de progresso. | `<progress value="70" max="100"></progress>` |
| `<meter>` | Medida em um intervalo. | `<meter value="6" max="10"></meter>` |

**Tipos de `<input>`:** `text` · `password` · `email` · `number` · `tel` · `url` · `search` · `checkbox` · `radio` · `date` · `time` · `color` · `range` · `file` · `hidden` · `submit` · `reset`

## Mídia embutida

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<img>` | Insere uma imagem. | `<img src="foto.jpg" alt="Descrição">` |
| `<picture>` | Imagens responsivas. | `<picture><source ...><img src="x.jpg"></picture>` |
| `<source>` | Fonte alternativa de mídia. | `<source src="v.webm" type="video/webm">` |
| `<audio>` | Reproduz áudio. | `<audio src="som.mp3" controls></audio>` |
| `<video>` | Reproduz vídeo. | `<video src="v.mp4" controls></video>` |
| `<track>` | Legendas para mídia. | `<track src="leg.vtt" kind="subtitles">` |
| `<iframe>` | Incorpora outra página. | `<iframe src="https://site.com"></iframe>` |
| `<canvas>` | Área de desenho via JS. | `<canvas id="tela" width="300"></canvas>` |
| `<svg>` | Gráfico vetorial. | `<svg><circle cx="50" cy="50" r="40" /></svg>` |
| `<map>`/`<area>` | Mapa de imagem clicável. | `<map name="m"><area shape="rect" coords="..."></map>` |

## Scripts e programação

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<script>` | Insere/vincula JavaScript. | `<script src="app.js"></script>` |
| `<noscript>` | Alternativa sem JS. | `<noscript>Ative o JavaScript.</noscript>` |

## Elementos interativos

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<details>` | Bloco expansível. | `<details><summary>Ver</summary>Conteúdo</details>` |
| `<summary>` | Título de um `<details>`. | `<summary>Clique aqui</summary>` |
| `<dialog>` | Caixa de diálogo/modal. | `<dialog open>Mensagem</dialog>` |

## Web Components e templates

| Tag | Descrição | Exemplo |
|-----|-----------|---------|
| `<template>` | HTML reutilizável (clonado via JS). | `<template id="t"><li></li></template>` |
| `<slot>` | Ponto de inserção em componentes. | `<slot name="titulo"></slot>` |

---

# Parte 2 — Propriedades CSS

## Como aplicar CSS

```html
<!-- 1. Inline (no próprio elemento) -->
<p style="color: red;">Texto vermelho</p>

<!-- 2. Interno (dentro do <head>) -->
<style>
  p { color: red; }
</style>

<!-- 3. Externo (arquivo separado - recomendado) -->
<link rel="stylesheet" href="style.css">
```

## Seletores

| Seletor | Descrição | Exemplo |
|---------|-----------|---------|
| `elemento` | Por tag. | `p { color: blue; }` |
| `.classe` | Por classe. | `.card { padding: 10px; }` |
| `#id` | Por id (único). | `#topo { height: 60px; }` |
| `*` | Todos os elementos. | `* { margin: 0; }` |
| `A B` | Descendente. | `nav a { color: white; }` |
| `A > B` | Filho direto. | `ul > li { list-style: none; }` |
| `A + B` | Irmão imediato. | `h1 + p { margin-top: 0; }` |
| `[attr]` | Por atributo. | `input[type="text"] { border: 1px; }` |
| `:hover` | Estado do mouse. | `a:hover { color: red; }` |
| `:nth-child(n)` | Enésimo filho. | `li:nth-child(2) { color: red; }` |
| `::before` | Pseudo-elemento. | `.item::before { content: "★"; }` |

## Box model (modelo de caixa)

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `width` / `height` | Largura e altura. | `width: 300px;` |
| `min-width` / `max-width` | Limites de largura. | `max-width: 100%;` |
| `margin` | Espaço externo. | `margin: 20px auto;` |
| `padding` | Espaço interno. | `padding: 10px 15px;` |
| `border` | Borda do elemento. | `border: 1px solid #000;` |
| `box-sizing` | Inclui borda no tamanho. | `box-sizing: border-box;` |
| `overflow` | Trata conteúdo que estoura. | `overflow: hidden;` |
| `aspect-ratio` | Mantém proporção. | `aspect-ratio: 16 / 9;` |

## Display e posicionamento

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `display` | Tipo de exibição. | `display: flex;` |
| `position` | Método de posicionamento. | `position: absolute;` |
| `top`/`right`/`bottom`/`left` | Deslocamento. | `top: 0; left: 0;` |
| `z-index` | Ordem de empilhamento. | `z-index: 10;` |
| `float` | Flutua o elemento. | `float: left;` |
| `clear` | Impede elementos ao lado. | `clear: both;` |
| `visibility` | Mostra/oculta com espaço. | `visibility: hidden;` |
| `opacity` | Transparência (0 a 1). | `opacity: 0.5;` |

## Flexbox

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `display: flex` | Ativa o flexbox. | `display: flex;` |
| `flex-direction` | Direção dos itens. | `flex-direction: column;` |
| `flex-wrap` | Quebra em várias linhas. | `flex-wrap: wrap;` |
| `justify-content` | Alinhamento horizontal. | `justify-content: center;` |
| `align-items` | Alinhamento vertical. | `align-items: center;` |
| `gap` | Espaço entre itens. | `gap: 16px;` |
| `flex-grow` | Fator de crescimento. | `flex-grow: 1;` |
| `flex-basis` | Tamanho base do item. | `flex-basis: 200px;` |
| `align-self` | Alinhamento individual. | `align-self: flex-end;` |
| `order` | Reordena itens. | `order: 2;` |

## Grid

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `display: grid` | Ativa o grid. | `display: grid;` |
| `grid-template-columns` | Define colunas. | `grid-template-columns: 1fr 1fr 1fr;` |
| `grid-template-rows` | Define linhas. | `grid-template-rows: auto 100px;` |
| `gap` | Espaço entre células. | `gap: 20px;` |
| `grid-column` | Extensão nas colunas. | `grid-column: 1 / 3;` |
| `grid-row` | Extensão nas linhas. | `grid-row: 1 / 2;` |
| `grid-area` | Posição por área. | `grid-area: header;` |
| `place-items` | Alinha itens nas células. | `place-items: center;` |

## Tipografia e texto

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `font-family` | Família da fonte. | `font-family: Arial, sans-serif;` |
| `font-size` | Tamanho da fonte. | `font-size: 1.2rem;` |
| `font-weight` | Peso da fonte. | `font-weight: bold;` |
| `font-style` | Estilo (itálico). | `font-style: italic;` |
| `line-height` | Entrelinhas. | `line-height: 1.5;` |
| `letter-spacing` | Espaço entre letras. | `letter-spacing: 2px;` |
| `text-align` | Alinhamento do texto. | `text-align: center;` |
| `text-decoration` | Sublinhado/tachado. | `text-decoration: underline;` |
| `text-transform` | Maiúsculas/minúsculas. | `text-transform: uppercase;` |
| `text-indent` | Recuo da 1ª linha. | `text-indent: 2em;` |
| `text-overflow` | Texto que estoura. | `text-overflow: ellipsis;` |
| `white-space` | Espaços e quebras. | `white-space: nowrap;` |
| `text-shadow` | Sombra no texto. | `text-shadow: 2px 2px 4px gray;` |

## Cores e fundo

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `color` | Cor do texto. | `color: #333;` |
| `background-color` | Cor de fundo. | `background-color: #f5f5f5;` |
| `background-image` | Imagem/gradiente de fundo. | `background-image: url(bg.jpg);` |
| `background-size` | Tamanho do fundo. | `background-size: cover;` |
| `background-position` | Posição do fundo. | `background-position: center;` |
| `background-repeat` | Repetição do fundo. | `background-repeat: no-repeat;` |
| `background` | Atalho de fundo. | `background: #000 url(x.jpg) center;` |

## Bordas e contornos

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `border-width` | Espessura da borda. | `border-width: 2px;` |
| `border-style` | Estilo da borda. | `border-style: dashed;` |
| `border-color` | Cor da borda. | `border-color: #0066cc;` |
| `border-radius` | Cantos arredondados. | `border-radius: 8px;` |
| `outline` | Contorno externo. | `outline: 2px solid blue;` |

## Efeitos visuais

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `box-shadow` | Sombra na caixa. | `box-shadow: 0 4px 8px rgba(0,0,0,.2);` |
| `filter` | Filtros (blur, brilho). | `filter: blur(4px);` |
| `backdrop-filter` | Filtro no fundo (vidro). | `backdrop-filter: blur(10px);` |
| `mix-blend-mode` | Mesclagem com o fundo. | `mix-blend-mode: multiply;` |
| `clip-path` | Recorta em formas. | `clip-path: circle(50%);` |
| `cursor` | Aparência do cursor. | `cursor: pointer;` |

## Transições, animações e transformações

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `transition` | Anima mudanças. | `transition: all 0.3s ease;` |
| `animation` | Aplica keyframes. | `animation: girar 2s infinite;` |
| `@keyframes` | Define os passos. | `@keyframes girar { to { transform: rotate(360deg); } }` |
| `transform` | Move/rotaciona/escala. | `transform: scale(1.1);` |
| `transform-origin` | Origem da transformação. | `transform-origin: top left;` |
| `perspective` | Profundidade 3D. | `perspective: 800px;` |
| `will-change` | Dica de otimização. | `will-change: transform;` |

## Listas e tabelas

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `list-style-type` | Tipo de marcador. | `list-style-type: none;` |
| `list-style-position` | Posição do marcador. | `list-style-position: inside;` |
| `border-collapse` | Une bordas das células. | `border-collapse: collapse;` |
| `border-spacing` | Espaço entre células. | `border-spacing: 5px;` |
| `table-layout` | Largura da tabela. | `table-layout: fixed;` |

## Outras propriedades úteis

| Propriedade | Descrição | Exemplo |
|-------------|-----------|---------|
| `content` | Insere conteúdo (before/after). | `content: "→ ";` |
| `user-select` | Seleção de texto. | `user-select: none;` |
| `pointer-events` | Eventos de mouse. | `pointer-events: none;` |
| `scroll-behavior` | Rolagem suave. | `scroll-behavior: smooth;` |
| `object-fit` | Ajuste de imagem. | `object-fit: cover;` |
| `resize` | Permite redimensionar. | `resize: vertical;` |
| `accent-color` | Cor de checkbox/radio. | `accent-color: #0066cc;` |

## Unidades e funções

| Item | Descrição | Exemplo |
|------|-----------|---------|
| `px` | Pixels (absoluto). | `font-size: 16px;` |
| `%` | Relativo ao pai. | `width: 50%;` |
| `em` | Relativo à fonte do elemento. | `padding: 1.5em;` |
| `rem` | Relativo à fonte da raiz. | `margin: 2rem;` |
| `vw` / `vh` | % da viewport. | `height: 100vh;` |
| `fr` | Fração (Grid). | `grid-template-columns: 1fr 2fr;` |
| `calc()` | Calcula misturando unidades. | `width: calc(100% - 40px);` |
| `var()` | Usa variável CSS. | `color: var(--cor-primaria);` |
| `clamp()` | Valor dinâmico com limites. | `font-size: clamp(1rem, 2vw, 2rem);` |
| `rgb()` / `rgba()` | Cor por canais RGB. | `color: rgba(0, 0, 0, 0.6);` |
| `hsl()` | Cor por matiz/saturação/luz. | `color: hsl(210, 100%, 50%);` |
| `linear-gradient()` | Gradiente linear. | `background: linear-gradient(90deg, red, blue);` |
| `@media` | Responsividade. | `@media (max-width: 600px) { ... }` |
| `@font-face` | Fonte personalizada. | `@font-face { font-family: "Minha"; src: url(f.woff2); }` |

---

# Exemplo completo montado

Um mini-exemplo juntando HTML + CSS para ver tudo funcionando:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exemplo</title>
  <style>
    :root {
      --cor-primaria: #0066cc;
    }
    * {
      margin: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: linear-gradient(135deg, #667eea, #764ba2);
    }
    .card {
      background: white;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
      text-align: center;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .botao {
      background: var(--cor-primaria);
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <h1>Olá, mundo! 👋</h1>
      <p>Um card estilizado com <strong>HTML</strong> e <strong>CSS</strong>.</p>
      <button class="botao">Clique aqui</button>
    </div>
  </div>
</body>
</html>
```

---

> 💡 **Dica:** esta é uma referência das tags e propriedades mais usadas no dia a dia. Para a especificação completa, consulte o [MDN Web Docs](https://developer.mozilla.org/pt-BR/).
