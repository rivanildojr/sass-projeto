# Sass

Um pré-processador CSS que servirar para simplificar, organizar e programar com CSS.

Existem duas sintaxe possiveis para escrever nessa tecnologia: .scss e .sass                                                                                                                                                                      
## Variáveis

Sintaxe: `$+nomeDavariavel`

## Arquivos Parciais

Esses arquivos são compilados pelo o sass.

Sintaxe: `_+nomeDoArquivo` e é chamado no outro arquivo como `@import "nomeDoArquivo";`

## Encadeamento

É trabalhado com a ideia de escopo. Variáveis criadas nesse escopo não serão acessadas fora dele.

Sintaxe: `div { color: blue; .title {color: white;}}`

## Mixins

Facilita a reutilização de declarações no código.

Sintaxe: `@mixins nomeDoMixin(){...}` e é chamado no dentro arquivo com `@include "nomeDoMixin()";`

## Condicionais

Sintaxe: `@if | @else if | @else`

## Estrutura de Repetição

Sintaxe: `@for $contador from valorInicial through valorFinal{ .section-#{$contador} {font-size: 16px * $contador}}`;
 `@for $contador from valorInicial to valorFinal{ .section-#{$contador} {font-size: 16px * $contador}}`;
Com o *to* não conta o o valorFinal

`@each $key,(Opcional) $valorDaColecao in $colecao{ .section-#{$contador} {font-size: 16px * $contador}}`;

## Funções

Funções existente: lighten(), darken() ...;
Sintaxe: `@function nomeDaFuncao(){@return ...}`

## Herança

Sintaxe: `@extend nomeDoSeletor`

## Referência

Sintaxe: `&nomeDoSeletor`

# Material de Apoio

- [Sass documentação](https://sass-lang.com/documentation)
- [Sass Guide - pt-BR](https://sass-guidelin.es/pt/)
- [Justin Brazeau - 10 Useful Sass Mixins for Automation (Medium)](https://sass-guidelin.es/pt/)
- [dpw - Sass (Artigo/Vídeo)](https://desenvolvimentoparaweb.com/css/o-basico-de-sass/)
- [Emerson Broga - Sass (Vídeo)](https://www.youtube.com/watch?v=C8KlabGtE8Y)
- [Rocketseat - Sass (Vídeo)](https://www.youtube.com/watch?v=BaI8dHUthLA)