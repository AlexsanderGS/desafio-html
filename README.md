# Introdução ao HTML

Este documento fornece um resumo sobre o funcionamento do **HTML (HyperText Markup Language)**, a linguagem de marcação usada para estruturar e exibir conteúdo na web.

## O que é HTML?
O HTML é a espinha dorsal de uma página da web, permitindo organizar textos, links, imagens, tabelas e outros elementos em uma estrutura compreensível e navegável pelos navegadores.

---

## Estrutura Básica do HTML
Um documento HTML utiliza **tags** para definir os elementos da página. Aqui está um exemplo básico:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Minha Página</title>
  </head>
  <body>
    <h1>Bem-vindo!</h1>
    <p>Este é um exemplo de página HTML.</p>
  </body>
</html>
```

## Componentes Principais
- ```html
  <!DOCTYPE html>: Indica o tipo de documento.
  <html>: Elemento raiz que contém todo o conteúdo da página.
  <head>: Armazena metadados (título, links para CSS, etc.).
  <body>: Contém o conteúdo visível no navegador.
  ```
## Tags e Atributos
O HTML utiliza tags para definir os elementos, que podem incluir atributos para fornecer informações adicionais.
```html
<a href="https://example.com" target="_blank">Visite o site</a>
<a>: Cria um link.
href: Define o destino do link.
target="_blank": Abre o link em uma nova aba.
```

## Estruturas e Hierarquia
As tags podem ser aninhadas para criar hierarquias de conteúdo.
Por exemplo, uma lista não ordenada:
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

Resultado:
Item 1
Item 2
```

## Elementos Semânticos
O HTML possui tags semânticas para melhorar a organização e acessibilidade. Exemplos:
```html
<header>: Cabeçalho da página ou seção.
<footer>: Rodapé.
<article>: Para conteúdo independente, como artigos de blog.
<section>: Para dividir o conteúdo em seções temáticas.
```
## Interação com CSS e JavaScript

Embora o HTML forneça a estrutura, ele frequentemente é usado em conjunto com:
 - CSS (Cascading Style Sheets): Para estilizar a página (cores, fontes, layouts).
 - JavaScript: Para adicionar interatividade e dinamismo.

## Conclusão
O HTML é essencial para criar páginas da web e funciona como a base que sustenta todos os outros elementos de design e interatividade. Aprender HTML é o primeiro passo para quem deseja explorar o desenvolvimento web.
