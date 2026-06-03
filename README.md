# AluraBooks

AluraBooks e uma pagina responsiva de uma livraria online criada durante os estudos de HTML e CSS na Alura. O projeto simula uma home page com cabecalho, menu de categorias, banner de busca, carrosseis de livros, cards de destaque, topicos visitados, area de cadastro por e-mail e rodape institucional.

## Tecnologias utilizadas

- HTML5
- CSS3
- Flexbox
- Media queries
- SwiperJS para os carrosseis
- Google Fonts: Poppins e Josefin Sans

## Como visualizar o projeto

1. Clone o repositorio:

```bash
git clone https://github.com/Adrianhermes/alurabooks.git
```

2. Entre na pasta do projeto:

```bash
cd alurabooks
```

3. Abra o arquivo `index.html` no navegador.

Como o projeto e estatico, nao e necessario instalar dependencias ou iniciar servidor local.

## Layout responsivo

O AluraBooks foi desenvolvido com a abordagem mobile first. Isso significa que o CSS base atende primeiro telas menores, e depois recebe melhorias para tablet e desktop por meio de media queries.

### Mobile

Na visao mobile, a interface prioriza uma navegacao simples e compacta:

- Cabecalho com menu hamburguer.
- Logo da AluraBooks em destaque.
- Icones de favoritos, sacola e usuario.
- Menu de categorias aberto por checkbox.
- Banner com campo de busca ocupando a largura da tela.
- Carrosseis de livros adaptados para telas pequenas.
- Cards, topicos e formulario de contato empilhados verticalmente.
- Rodape simplificado, exibindo apenas o titulo principal.

Essa versao e a base do projeto e funciona bem em celulares.

### Tablet

A partir de `1024px`, o layout ganha mais espaco e passa a mostrar mais informacoes na tela:

- Titulo `AluraBooks` aparece ao lado da logo.
- Menu de navegacao horizontal com categorias, favoritos e minha estante.
- Menu hamburguer deixa de aparecer.
- Banner recebe titulo maior e campo de busca mais estreito.
- Carrosseis e cards ficam centralizados e com larguras maiores.
- Area de contato passa a ficar em duas colunas.
- Rodape exibe listas de links organizadas por categoria.

Essa visao melhora a leitura e aproveita melhor telas intermediarias, como tablets e notebooks menores.

### Desktop

A partir de `1728px`, o projeto recebe ajustes para telas grandes:

- Cabecalho com mais espacamento lateral.
- Links de sacola e perfil exibem texto junto dos icones.
- Menu principal ocupa melhor a area horizontal.
- Banner fica mais alto e com campo de busca mais proporcional.
- Secoes de carrossel e cards ficam lado a lado.
- Titulos e textos dos cards ganham mais destaque.
- Area de contato recebe maior espacamento interno.
- Rodape ganha divisorias laterais entre as listas.

Essa versao entrega uma experiencia mais completa para monitores grandes.

## Estrutura de arquivos

```text
alurabooks-main/
|-- assets/
|-- styles/
|   |-- banner.css
|   |-- carrossel.css
|   |-- contato.css
|   |-- footer.css
|   |-- header.css
|   `-- topicos.css
|-- index.html
|-- reset.css
|-- style.css
`-- README.md
```

## Aprendizados

Durante o desenvolvimento do projeto, foram praticados conceitos importantes de front-end:

- Criacao de paginas com HTML semantico.
- Organizacao de estilos em arquivos separados.
- Uso de variaveis CSS.
- Construcao de layout responsivo com media queries.
- Adaptacao de componentes para mobile, tablet e desktop.
- Integracao de biblioteca externa para carrossel.

## Status do projeto

Projeto finalizado para fins de estudo e pratica de responsividade.
