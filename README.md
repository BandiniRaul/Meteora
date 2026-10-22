# Meteora

Página inicial fictícia de uma loja de moda, criada para praticar desenvolvimento front-end. O projeto apresenta banners, categorias, produtos em destaque, facilidades da loja e um formulário para cadastro de e-mail.

## Tecnologias

- **HTML5** para estruturar o conteúdo da página.
- **CSS3** em `styles.css` para personalizações visuais.
- **Bootstrap 5.3.8** para componentes, grid, utilitários e comportamento responsivo. O Bootstrap é carregado por CDN; seu JavaScript permite, por exemplo, o funcionamento do menu recolhível e do carrossel.
- **Bootstrap Icons 1.13.2** para os ícones da seção de facilidades.

## Sobre o Bootstrap

O layout usa o sistema de grid e as classes responsivas do Bootstrap para adaptar os conteúdos a diferentes tamanhos de tela. Também utiliza componentes prontos, como a barra de navegação, o carrossel e os cards de produtos. As regras específicas da página — como cores, posicionamento e alguns ajustes de layout — estão em `styles.css`.

As imagens possuem versões para celular, tablet e desktop, organizadas na pasta `assets/`. As classes responsivas do Bootstrap controlam qual versão aparece em cada largura de tela.

## Como visualizar

Não é necessário instalar dependências ou executar um processo de build. Abra `index.html` diretamente no navegador. Como o Bootstrap e os ícones são carregados por CDN, é necessária uma conexão com a internet para que esses recursos externos sejam exibidos.

## Estrutura

```text
meteora/
├── assets/       # Imagens e ícones do projeto
├── index.html    # Estrutura da página
├── styles.css    # Estilos personalizados
└── README.md     # Documentação do projeto
```

> Projeto fictício, sem fins comerciais. O formulário e os links são demonstrativos e não estão conectados a um serviço de cadastro ou compra.
