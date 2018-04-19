# Carregando

## Introdução
Este é um plugin jQuery que simula o placeholder-content do Facebook. Use pra deixar as telas de carregamento de conteúdo mais atrativas.

## Demonstração
Em Breve.

## Como Utilizar
Apenas baixe e inclua os arquivos `carregando.min.css` e `carregando.min.js` no `<head>` do seu HTML.

Para aplicar o plugin, basta escolher a `<div>` que você quer aplicar o efeito, e chamar o plugin passando o parâmetro `true` para mostrar ou `false` para ocultar. Veja melhor no exemplo abaixo aplicando o efeito em um formulário de endereço:

Crie uma div que simulará o local onde o campo da rua ficará (você pode utilizar grid css para estruturar suas divs sem problema nenhum).

```html
<div class="campo-rua">&nbsp;</div>
```
```js
$(document).ready(function(){
  $(".campo-rua").carregando(true); // mostrará a animação de carregando na div campo-rua
});
```


Também é possível aplicar o plugin em várias `<div>` ao mesmo tempo, basta fazer como no exemplo abaixo:
```js
$(".campo-rua, .campo-cep, .campo-numero, .campo-bairro").carregando(true);
```
