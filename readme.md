## Projeto: site Museu Nacional

### Curso Desenvolvimento Web Completo 2022

Seção 6: HTML5 e CSS3 Recursos especiais

### Aula 01

Criação do topo da página.

- Aplicação dos conceitos: HTML shiv, Normalize CSS;
- Utilização das tags &lt;header&gt; e &lt;nav&gt;.

### Aula 02

Criação da barra lateral.

- Aplicação das tags &lt;aside&gt; para criação da barra lateral e &lt;section&gt; na área de conteúdos;
- Atributo "alt" pode ser utilizado para fazer uma descrição da imagem, caso a página não carregue o CSS.

### Aula 03

Criação da área de conteúdos e rodapé.

- Aplicação da tag &lt;article&gt; para exibir as postagens, e da tag &lt;footer&gt; para o rodapé;
- Ao invés de limpar o fluxo flutuante diretamente no footer, poderia criar uma div antes dele, e aplicar style "clear: both".
- Não é possível aplicar margin-top no footer, pois é o elemento que limpa o fluxo flutuante (tem por característica "colar" o conteúdo no anterior, sem aceitar o espaçamento); portanto, foram inseridar margin-bottom no "conteudo" e na "galeria", para garantir o espaçamento em relação ao rodapé.