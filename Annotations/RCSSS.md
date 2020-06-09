# RSCSS

Um Padrão CSS foca em manter o html e css limpo, sua ideia principal é criar um componente pai, que irá governar os elementos internos a partir do seletor de filho direto `>`.

## Utilizando o RSCSS

1. Tudo é um componente
   1. Os componentes deverão ter pelo menos duas palavras separadas por um hífen: `.book-section`.
2. Elementos
   1. Deve possuir classes com somente uma palavra: `.action`;
   2. Utilizar o seletor de filho direto `>`: `.book-section { > .action}`;
   3. Elementos que necessitam de mais de uma palavra, concatene-o: `.firstname`;
   4. Evitar o uso de tags.
3. Variações
   1. As classes devem ser prefixadas por um traço: `.book-section { &.-active}` ;
   2. Para variações em elementos, pode-se utiliza o seletor de adjacência: `.book-section { > .heading.-large}`;
4. Componentes aninhados
   1. Evitar modificações no componente intero, através do componente principal;
   2. Utilizar o @extend para cimplificar os componentes internos.
5. Layouts
   1. Evitar aplicar propriedades de posicionamento, floats, margins e dimensões fixas nos componentes
   2. Caso seja necessário aplicar posicionamento no componente, aplique no elemento pai que irá contê-lo.
6. Helpers
   1. SEu principal objetivo é sobrescrever valores, nomeie com underscore, como possivelmente serão utilizada com *!important*, utile com sabedoria e sempre que possível, evite.
7. Estrutura
   1. Colocar um componente por arquivo.

# Material de Apoio

- [RCSSS - Documentação](https://rscss.io/)
- [Willian Justen - RSCSS](https://willianjusten.com.br/falando-sobre-rscss/)