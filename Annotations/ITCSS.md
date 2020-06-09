# ITCSS

## Divisões de camada do ITCSS

1. Settings
   - São as configurações básicas da sua arquitetura;
   - Exemplos: variáveis globais, cores, espaçamentos;
   - Nada nessa camada será gerada como arquivo final.
2. Tools
   - Local onde guarda os mixins e funções;
   - Nada nessa camada será gerada como arquivo final.
3. Generic
   - Destinadas para propriedades mais genéricas;
   - Baixa especificidade;
   - Lugar para colocar os resets;
   - Gerado como css final.
4. Base
   - Local para se aplicar as estilizações básicas;
   - Última camada para se utilizar seletores de tags;
   - Gerado como css final.
5. Objects
   - Camada para adicionar os pequenos pedaços da interface;
   - Padrões que se repetem por todo o site;
   - Exemplos: botões, listas, paineis, cards;
   - Utilizar os padrões do RSCSS;
   - Gerado como css final.
6. Componentes
   - Nessa camada é adicionado os componentes criados no RCSSS;
   - Gerado como css final.
7. Trumps
   - Camada parecida com o Helpers da RSCSS;
   - A com mais especifidade de todas e com componentes com *!importante*;
   - Essa camada somente deverá ser utilizada em casos que não afete a estrutura da página;
   - Gerado como css final.  

# Material de Apoio

- [ITCSS - Apresentação](https://speakerdeck.com/dafed/managing-css-projects-with-itcss)
- [Willian Justen - ITCSS](https://willianjusten.com.br/organizando-seu-css-com-itcss/)
- [Danilo Vaz - RSCSS e ITCSS (Vídeo)](https://www.youtube.com/watch?v=xK5IrnlulaA)